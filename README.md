# container-service-ui-workflow

## Overview

vRealize Orchestrator based UI for vCloud Director Container Services Extension

This repository contains a workflow package for vRealize Orchestrator that can be used to publish Container Service Extension tasks into the vCloud Director Service Catalog.

![Screenshot](docs/screenshot.png?raw=true "CSE UI Workflows")

## Prerequisites

You need to have the Conatiner Service Extension https://vmware.github.io/container-service-extension/ installed and setup.
You need to have a vRealize Orchestrator instance registered in vCloud Director.

## Setup

* Import the worfklow package to vRealize Orchestrator
* (If not existing yet) Create a RestHost Inventory object for the vCloud Director Host
* Provide the environment details, credentials for CSE server, ... as values to the Configuration Element "CSE / CSE Environment"
* Run the workflow "CSE UI / Store Clusters in Cache"
* Publish the workflows in folder "CSE UI / Frontend" into the vCD Service Library

## Contributing

The container-service-ui-workflow project team welcomes contributions from the community. If you wish to contribute code and you have not
signed our contributor license agreement (CLA), our bot will update the issue when you open a Pull Request. For any
questions about the CLA process, please refer to our [FAQ](https://cla.vmware.com/faq). For more detailed information,
refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[BSD-2](LICENSE.txt)