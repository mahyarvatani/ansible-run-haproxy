# ansible-run-haproxy
# Ansible HAProxy and Nginx Project

## Overview

This Ansible project automates the setup of a simple web application environment with three machines:

1. A CentOS machine running HAProxy.
2. An Ubuntu machine running Nginx (Node 1).
3. Another Ubuntu machine running Nginx (Node 2).

The goal of this project is to configure HAProxy to load balance requests between the two Nginx machines.

## Prerequisites

Before running this Ansible project, make sure you have the following prerequisites:

1. Ansible installed on the machine from which you'll run the playbook.
2. SSH access to the CentOS and Ubuntu machines.
3. Inventory file (`inventory.ini`) with the IP addresses or hostnames of the machines.
