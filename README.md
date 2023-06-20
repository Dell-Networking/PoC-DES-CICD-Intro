# Proof-of-COncept - Automating Configuration of Dell Enterprise SONiC with CI/CD Pipelines


[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](#-how-to-contribute)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Dell-Networking/PoC-DES-CICD-Intro/blob/main/LICENSE.md)
[![GitHub issues](https://img.shields.io/github/issues/Dell-Networking/PoC-DES-CICD-Intro)](https://github.com/Dell-Networking/PoC-DES-CICD-Intro/issues)

Built and maintained by [Ben Goldstone](https://github.com/benjamingoldstone/) and [Contributors](https://github.com/Dell-Networking/PoC-DES-CICD-Intro/graphs/contributors)

------------------

Welcome to our guide on how to get started with using a CI/CD tooling for automating configuration of Dell Enterprise SONiC network switches!

## Contents

- [Description and Objective](#-description-and-objective)
- [Requirements](#-requirements)
- [How to Contribute](#-how-to-contribute)


## 🚀 Description and Objective

Use this space to provide clarity around what the objective of the PoC is and what the end result of successfully running through the exercise should look like.

This repo should enable you to get started with a basic CD pipeline for deploying network configuration to Dell Enterprise SONiC switches. We will be using the following components:

  * Drone.ci
  * Ansible
  * GNS3

We will be modifying the configuration of a VXLAN/BGP/EVPN network by adding a VLAN, a VLAN to VNI mapping, a VRF for a tenant and then placing the VNI into the new VRF. This simple example should get you started to build more complex infrastructure with CI/CD tooling.  


## 📋 Requirements

  * GNS3 virtual environment or physical hardware
  * Drone CI server and runners
  * Dell Enterprise SONiC 4.1 (virtual image for GNS3 or Enterprise image for hardware)


## 👏 How to Contribute

We welcome contributions to the project. Please reference the [CONTRIBUTING](https://github.com/Dell-Networking/PoC-Index/blob/main/CONTRIBUTING.md) guide in the PoC-Index repo for more details (this guide is common across Dell Networking PoC projects).



