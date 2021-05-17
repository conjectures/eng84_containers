# Containerisation


## What are containers
Containers sit on top of a physical server and its host Operating System. Each container shares the host OS kernel and uses its binaries and libraires.
The shared components are only read by the container and can't be changed by it. The container then will install only the libraries that are not included 

In that way they reduce the overhead required to run them, and they can 'simulate' an operating system with fewer resources, and much less space.


## Why use containers
Due to their reduced overhead, containers are very fast and lightweight.
They can therefore offer the same functionality with VM much more easily.

## Difference between Containers and Virtual Machines 
As mentioned

![Containers vs VMs](docker-containerized-and-vm-transparent-bg.png)
## Most popular Containerisation tools
- docker
- rkt
- containerd
- Microsoft Containers

