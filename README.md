# About this repository

This is a public repository for Kontain binary releases. Kontain code is open source...

Kontain is currently in beta. Kontain release includes...
*  Code examples: https://github.com/kontainapp/km-releases/tree/master/examples

## Release Notes 
*New/Changed Features, bug fixes, known issues, and additional release-specific info. NOTE: This could be a link to a separate document, which might be preferable if you want to keep this doc short!*

*  [Known Issues](https://github.com/kreative-kat/ko_ug_draft_conversion/blob/main/Known%20Issues.md)

## Supported Linux Platforms

Kontain runs on Linux hosts that meet these minimum requirements: 

*   CPU: Intel or AMD
*   Linux kernel: Version 4.15 or higher
*   Distribution: Ubuntu 20 and Fedora 32 (or newer) are recommended
*   Hardware virtualization enabled, using either: 
    *   KVM installed and enabled (requires stock kernel module on Linux kernel 4.15 or higher), or
    *   Kontain Kernel Module (KKM) (included in the Kontain release) 

## Installing Kontain
For a quick and easy way to start exploring Kontain, we recommend using the pre-configured [Kontain Ubuntu VM available from Vagrant Cloud](https://app.vagrantup.com/kontain/boxes/beta2-kkm). The Vagrant VM brings fully functional Kontain onto your desktop or laptop and provides a stable platform for exploration and validation:

*   Ubuntu 20.10 
*   Kontain pre-installed 
*   KKM (Kontain kernel module) to support nested virtualization
*   Docker pre-installed and configured for use with Kontain
*   Compatible with Windows, Linux, and Mac OS

Prerequisite: Both [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.VirtualBox.org/) must be installed on your host machine. 

## Product Documentation
 [Kontain User Guide](https://github.com/kreative-kat/ko_ug_draft_conversion/blob/main/user%20guide.md) Provides information for developers to install Kontain and use it to run workloads. 
 
For command line help, type: `/opt/kontain/bin/km --help`

[Debugging Kontain Unikernels](https://www.google.com/url?q=https://docs.google.com/document/d/17s0QY73C_x1LEOXzkTl9MPKrNGo7PSaD-f9oZ8phkkI/edit?usp%3Dsharing&sa=D&source=editors&ust=1619070677677000&usg=AOvVaw3wDZDS-8ACFqu6ioKfKDj-) Provides information for developers about how to debug a Kontain workload (unikernel) using standard debugging tools and practices.  

[FAQs](https://github.com/kreative-kat/ko_ug_draft_conversion/blob/main/FAQ.md) Provides answers to common questions about Kontain.


## How to Find Support or File an Issue

Contact <community@kontain.app> 

## Contributing
These binaries and these instructions are open source because we want to interact with our community. If you're interested in working on Kontain or using it in your stack, please let us know! We would be more than happy to share the private code.

We also accept PRs and issues here. (LINK?) If making a large PR, please check with us first by opening an issue. Our goal is to eventually open source everything.

## Licensing
Copyright © 2021 Kontain Inc. All rights reserved.

By downloading or otherwise accessing the Kontain Beta Materials, you hereby agree to all of the terms and conditions of Kontain’s Beta License available at https://raw.githubusercontent.com/kontainapp/km-releases/master/LICENSE.
