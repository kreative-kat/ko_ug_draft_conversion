# About this repository
*Brief Description...*

## Release Notes 
*New/Changed Features, bug fixes, other important, release-specific info. NOTE: This could be a link to a separate document, which might be preferable if you want to keep this doc short!*

## Supported Linux Platforms

Kontain runs on Linux hosts that meet these minimum requirements: 

*   CPU: Intel or AMD
*   Linux kernel: Version 4.15 or higher
*   Distribution: Ubuntu 20 and Fedora 32 (or newer) are recommended
*   Hardware virtualization enabled, using either: 
    *   KVM installed and enabled (requires stock kernel module on Linux kernel 4.15 or higher), or
    *   Kontain Kernel Module (KKM) (included in the Kontain release) 

## Installing Kontain
We recommend using the pre-configured [Kontain Vagrant box](https://app.vagrantup.com/kontain/boxes/beta2-kkm). 
For details, see the [Kontain User Guide](https://github.com/kreative-kat/ko_ug_draft_conversion/blob/main/user%20guide.md). 


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
