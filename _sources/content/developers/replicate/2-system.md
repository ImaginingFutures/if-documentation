# System requirements

This section describes the system requirements implemented in the Imagining Futures Repository. We used two different virtual machines, one for the database and other for the application. Both virtual machines share very similar features, in those cases where they differ, the differences are described.

## Server

| Feature   |      Details      |
|----------|:-------------:|
| Operating System |  Ubuntu 20.04 (LTS) x64 |
| Memory |    4Gb   |
| Storage | 80Gb disk |
| Processor | 2 vCPUs |

## Service

We opted for Digital Ocean to host the virtual machines. Basic configuration for both virtual machines is described below.

| Feature   |      Details      |
|----------|:-------------:|
| Type |  Standard Droplet |
| Image |    Ubuntu 20.04 (LTS) x64   |
| Size | 4Gb/2vCPUs |
| Storage | 80Gb disk |
| Region | LON1 |

Storage of files is done in a Digital Ocean Space. The space is configured to be accessible only from the virtual machines.

## Core software

| Feature   |      Details      |
|----------|:-------------:|
| PHP |  8.1 |
