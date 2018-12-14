# Apigee OPDK Ansible Inventory Samples

This repository contains sample Ansible inventory templates that should be used to define an 
inventory that will work with this Apigee OPDK Ansible framework. The following inventories are defined:

* Edge 2 Node
* Edge 5 Node
* Edge 5 Node that also defines an Apigee Mirror node
* Edge 5 Node that also defines monitoring nodes for Grafana, Influxdb and Telegraf
* Edge 5 Node that also defines nodes for Apigee SSO (Currently under construction)
* Edge 10 Node that installs Routers and Message Processors on separate nodes.
* Edge 10 Node that installs Routers and Message Processors on the same node.
* Edge AIO Node 
* Edge Devportal 
* Two Regions 
* Three Regions 
* Five Regions 

## Node Roles
Inventory files are annotated to provide guidance regarding how to indicate the different roles that
the nodes will fufill.

<!-- BEGIN Google Required Disclaimer -->

# Not Google Product Clause

This is not an officially supported Google product.
<!-- END Google Required Disclaimer -->
<!-- BEGIN Google How To Contribute -->
# How to Contribute

We'd love to accept your patches and contributions to this project. Please review our 
[guidelines](CONTRIBUTING.md).
<!-- END Google How To Contribute -->