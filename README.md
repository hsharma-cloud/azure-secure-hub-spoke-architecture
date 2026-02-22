# Azure Secure Hub-Spoke Architecture

## Overview

This project demonstrates a secure Azure hub–spoke network architecture designed using Zero Trust principles.
The implementation focuses on private connectivity, network segmentation, and eliminating public exposure for platform services.

## Key Features

* Hub–Spoke virtual network topology
* Subnet-level security using Network Security Groups (NSGs)
* Private Endpoint for secure Storage access
* Public network access disabled for PaaS resources
* Private DNS integration for internal name resolution

## Architecture Summary

* **Hub VNet**: Hosts shared services and centralized network controls
* **Spoke VNet**: Isolates production workloads with subnet-level security
* **Private Endpoint**: Enables private access to storage over the Azure backbone

## Purpose

This repository showcases real-world Azure architecture patterns focused on security, scalability, and private connectivity.
