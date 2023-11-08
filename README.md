# DEVWKS-2176 
## Overview

This Repository is to be used in the DEVWKS-2176 workshop. The code is a set of example use cases and is not considered a whole solution. This Repository is only to show the art of the possible.

The repository will include scripts and examples with the following:

1. Jinja2 Scripting
2. DNA Center Templates
3. YAML files for settings
4. CSV files for settings
5. Python Examples 
6. Ansible Examples

## Cisco Catalyst (DNA) Center Jenkins Automations

This repo includes the files for two Cisco DNA Center Jenkins automations pipelines.

- Pull from GitHub CLI templates and the devices that we need to configure in the lab and production - "jenkinsfile_templates"
Automate the process of deploying CLI templates to devices. This build may run every evening during maintenance hours or on-demand.

- Collect the device inventory and push to GitHub - "jenkinsfile_inventory"
The always up-to-date inventory may be used by other automations tools and platforms

- Create a new fabric with a Border, Control-plane and Edge node device - "jenkinsfile_fabric"
Automate the process to create new fabrics using GitHub repos with the fabric configuration saved as YAML files
