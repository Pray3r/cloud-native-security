# container-security
Resources for container security research, such as Docker, Kubernetes, etc.

## Kernel and architecture

Namespaces in operation by Michael Kerrisk - [whitepaper](https://lwn.net/Articles/531114/)

Control groups series by Neil Brown - [whitepaper](https://lwn.net/Articles/604609/)

Resource management: Linux kernel Namespaces and cgroups by Rami Rosen - [slide](http://www.haifux.org/lectures/299/netLec7.pdf)


## Escaping

2017:"Escaping Docker container using waitid() – CVE-2017-5123" by Daniel Shapira - [article](https://www.twistlock.com/2017/12/27/escaping-docker-container-using-waitid-cve-2017-5123/)

2016:"Abusing Privileged and Unprivileged Linux Containers" by NCC Group - [whitepaper](https://www.nccgroup.trust/globalassets/our-research/us/whitepapers/2016/june/container_whitepaper.pdf)


2014:"Container escape through open_by_handle_at (shocker exploit)" - [vuln](https://lists.linuxcontainers.org/pipermail/lxc-devel/2014-June/009547.html) - [exp](https://github.com/gabrtv/shocker)


## Docker

2016, BSides:"Docker: Security Myths, Security Legends" by Rory McCune - [video](https://www.youtube.com/watch?v=uQigvjSXMLw)

2015, BlackHat:"Vulnerability Exploitation In Docker Container Environments" by Anthony Bettini - [video](https://www.youtube.com/watch?v=77-jaeUKH7c) - [slide](https://www.blackhat.com/docs/eu-15/materials/eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments.pdf) - [whitepaper](https://www.blackhat.com/docs/eu-15/materials/eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments-wp.pdf)


## Kubernetes

2018:"Hard Multi-Tenancy in Kubernetes by Jessie Frazelle" - [article](https://blog.jessfraz.com/post/hard-multi-tenancy-in-kubernetes/)


## Miscs

2018:"How one of our Kubernetes clusters got pwned Shopify" - [article](https://hackerone.com/reports/341876)
