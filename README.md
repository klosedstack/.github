# KlosedStack
<p align="center">
  <img width="30%"src="https://github.com/isu-kim/klosedstack/assets/49092508/f7d3c2df-4673-4d28-987f-1ae29af2e6d4" />  
</p>

KlosedStack is an open source project designed to facilitate VM management across multiple hosts. It offers essential functionalities for deploying and maintaining each VM efficiently.

## Motivation
As the name suggests, KlosedStack draws heavy inspiration from the renowned open-source program OpenStack. OpenStack offers a wide range of features; however, installing it can be challenging, especially for beginners. 

To address this, KlosedStack was introduced as a simplified yet powerful alternative to OpenStack. KlosedStack incorporates key concepts from OpenStack and presents them in a more user-friendly and streamlined manner, reducing the overall complexity of the program.

## Dependencies
KlosedStack relies on the following well-known open-source programs as dependencies for its proper functioning:

-  [Vagrant](https://www.vagrantup.com/): Used for creating and deleting [libvirt](https://libvirt.org/) based VMs. 
-  [OpenvSwitch](https://www.openvswitch.org/): Used for creating a virtual network that connects the VMs.
-  [Ceph](https://ceph.com/en/): Used for storing the block storages of the VMs.

Special thanks to the following open-source contributors whose invaluable work has made KlosedStack possible!

## Services
In order for KloseStack to operate, there are following services required to operate. 

- [Nebula](https://github.com/klosedstack/nebula): Nebula is the core component of KloseStack responsible for scheduling and managing virtual machines (VMs) across multiple hosts. Corresponds to *Nova* in Openstack.
- [Plasma](https://github.com/klosedstack/plasma): Plasma is the networking service in KloseStack that enables seamless communication and connectivity between VMs across nodes in the infrastructure. Corresponds to *Neutron* in Openstack.
- [Panorama](https://github.com/klosedstack/panorama): Panorama is the user-friendly web interface of KloseStack, providing a graphical user interface (GUI) for users to easily manage and interact with their virtualized environment. Corresponds to *Panorama* in Openstack.

## Contributing
To contribute, please follow these guidelines:

-   Fork the repository.
-   Make your desired changes.
-   Submit a pull request with a clear explanation of your changes.

Please ensure that your contributions align with the project's coding standards and follow our code of conduct.

## Issues
If you have encountered any bugs or would like to suggest a new feature, please visit Issue pages of each services and create a new issue using the provided templates. 

## Further Informations
KlosedStack is currently undergoing extensive construction, and as a result, additional information about KlosedStack is pending. Stay tuned as we will soon unveil more details!
