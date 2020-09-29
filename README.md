# container-service-ui-workflow

### VMware has ended active development of this project, this repository will no longer be updated. Container Service Extension now includes a VCD UI plugin, so these vRO based workflows are not needed anymore.

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

The container-service-ui-workflow project team welcomes contributions from the community. Before you start working with container-service-ui-workflow, please read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[BSD-2](LICENSE.txt)
