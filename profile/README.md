# Project Lavender

## An Experimental Modern Operating System

### What the heck is this?

Project Lavender is an experimental attempt to create a much more modern operating system than those that are in common use today. It seeks to achieve this by incorporating several features that have been described
in the operating systems research literature but thus far not used in mainstream operating system despite providing clear advantages over their equivalents in the mainstream systems. Among these features are the following:

- Capability based access control
- A strongly typed system namespace used to enumerate and interact with all system resources from the filesystem to the registry and beyond as well as the same features on other hosts
- A low level OS API that allows developers to aggressively optimize their applications and libraries when they so choose and also allows for the layering of their preferred abstractions atop it
- URIs as namespace paths allowing access to system resources both locally and on the network without mounting or unmounting anything
- A highly modular kernel that internally abstracts almost all of its components to common interfacces allowing for implementations to be replaced or added relatively easily
- Graceful failure mechanisms that avoid total system failure to the extent possible by simply allowing any kernel function that can fail to return a Result
- Intuitive and easy to use text based and graphical interfaces
- Atomic update and installation transactions for all software including OS components with easy rollback
- others to be determined in the course of development

### How can I get involved?

Just clone any of the repositories in this organization, make a new branch and make your desired changes, then make a pull request and a maintainer will review your changes and either merge them or make a request for changes. You can also
feel free to open issues in any of our repositories or participate in the disussion sections.

### Is there documentation or a wiki?

Not yet but it would be ideal to create a centralized repository of developer knowledge some point soon to avoid the issues that come with relying on so called tribal knowledge.

### History

This project is the successor to the now defunct CharlotteOS project and is run by some of the same people. We decided to start from scratch with the knowledge we gained from the prior attempt since it was the path of least resistance
compared to attempting to refactor a proejct whose code was not organized well from the start and which was not designed with sufficient modularity and interface-implementation separation.

### Licenseing

All executables within this project are licensed under the GNU General Public License version 3 or later while libraries are licensed under the GNU Lesser General Public License version 3 or later. If you do not wish to license your
contributions under these terms then please do not contribute. We consider the strong copyleft license to be a feature of our project as much as anything else that its software components can do and will not ever consider changing or weakening the
license requirements for any reason.
