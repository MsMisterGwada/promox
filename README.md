# Proxmox

## Informations:  
This repository contains somes scripts for Proxmox hypersor server, some terraform templates to deploy vm and ct using telmate\proxmox provider.

## Terraform

Terraform module that creates a cloud-init enabled VM in Proxmox.

### Requirements
Cloud Init and QEMU Guest Agent must be installed. 
iso9660 (isofs) module must be loaded for cloud-init to mount the Proxmox cloud-init drive.

### Improvements
- Expose all disk options
- Expose all network options

### Requirements

| Name | Version |
|------|---------|
| terraform | >=0.14 |
| proxmox | ~>2.9.0 |

## Providers

| Name | Version |
|------|---------|
| proxmox | ~>2.9.0 |

## Modules

No Modules.

## Resources

| Name |
|------|
| [proxmox_vm_qemu](https://registry.terraform.io/providers/Telmate/proxmox/~>2.9.0/docs/resources/vm_qemu) |
