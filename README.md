# Azure Secure Hub-Spoke Architecture

## Overview

This project demonstrates a secure Azure hub–spoke network architecture using Zero Trust principles.
The design focuses on private connectivity, network segmentation, and elimination of public exposure for platform services.

## Key Features

* Hub–Spoke virtual network topology
* Subnet-level security using Network Security Groups (NSGs)
* Private Endpoint for secure Storage access
* Public access disabled for PaaS resources
* Private DNS integration for internal name resolution

## Architecture Summary

* **Hub VNet:** Shared services and centralized network controls
* **Spoke VNet:** Production workloads isolated and secured
* **Private Endpoint:** Enables private access to storage over Azure backbone

## Purpose

This repository showcases real-world Azure architecture patterns focused on security, scalability, and private connectivity.
