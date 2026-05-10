# Welcome! 😸

Hello!
I'm currently an IT student that likes to delve deep into the tough parts of computers, networks, and infrastructure! I enjoy the challenge of figuring out and troubleshooting issues!

## Projects

### Done ✅

#### [Proxmox VE](https://www.proxmox.com/en/)
I've worked with proxmox for well over a year now and use it constantly. I have it running my Docker vm, as well as my Kubernetes VM's as well. I've also used it to run my own HA Windows AD servers as well. I also setup [PBS (Proxmox backup server)](https://proxmox.com/en/products/proxmox-backup-server/overview) to facilitate hourly, daily, weekly, monthly, and yearly backups of all my vms.

#### [Docker](https://www.docker.com)
I use docker on a daily basis to host my Arr stack as well as a Jellyfin server that I use to store the movies/shows/music that I've downloaded. It's been one of my favorite things to learn and it's super fun once you get used to it!

#### [Ansible](https://docs.ansible.com)
I used ansible to automatically update and upgrade packages in Linux VM's to streamline the testing process. I used both SSH keys as well as password input.

### In Progress 🔄

#### Infiniband
I'm currently using 2 Mellanox ConnectX-3 VPI Cards to facilitate an Infiniband connection with my Mellanox SX6036. The Mellanox SX6036 runs the Subnet Manager and provides the routing capabilities for the cards to talk to eachother. I also implemented NVMe-oF using RDMA from my TrueNas server (NVMe Target) to my Proxmox node (NVMe Initiator). This had to be done with an extra step of using IPoIB to facilitate the necessary connection using IP addresses statically assigned to each NIC, but the underlying transport method is Infiniband. It allows for direct copy of a ZFS block from my Truenas server to my Proxmox node while bypassing the CPU entirely using Zero-Copy. Eventually, I'm going to move to a dedicated ZVOL of 4 U.2 drives, but temporarily I have it set to export from my long-term storage architecture.

#### [Kubernetes](https://kubernetes.io)
I'm still new to Kubernetes but so far I've setup a cluster of 1 Control node and 3 Worker nodes. They're all currently VM's but I'm looking towards moving them to physical devices soon. I also run a local instance of [MetalLB](https://metallb.io) to facilitate load balancing between nodes


<!--
**Boggo-Chez/Boggo-Chez** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
