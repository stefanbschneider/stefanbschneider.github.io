---
title:  "Research"
layout: single
permalink: /
author_profile: true
comments: false
---

*Page under construction*

I'm a PhD researcher at the computer networks group at Paderborn University. My research focus is on network softwarization and cloud computing, but I am also interested in machine learning and applying it to the networking domain.

I enjoy tackling and solving challenging problems and am always looking to learn something new. If you are interested in collaborating, feel free to contact me: stefan.schneider@upb.de

**TODO**: More details, ongoing projects (Tango, RealVNF), add figures and links to github repos and papers, ...

## Projects

### 5GTANGO: 5G Development and validation platform for global industry-specific network services and apps

[5GTANGO](https://5gtango.eu/) is a European H2020 project focusing on flexible programmability of 5G networks by offering an NFV SDK for development support, a verification and validation platform, and a service platform for deployment. The project outcomes are demonstrated using three vertical pilots (smart manufacturing, immersive media, real-time communication).

In 5GTANGO, I work on evolving the SDK by developing new tools like the service [descriptor generator](https://github.com/sonata-nfv/tng-sdk-descriptorgen) as well as refactoring and extending existing ones like the [project management tool](https://github.com/sonata-nfv/tng-sdk-project), which support service developers in quickly creating suitable descriptors that are required for deployment. I also help designing and developing the [smart manufacturing pilot](https://github.com/sonata-nfv/tng-industrial-pilot) use cases and corresponding network functions.

My work in 5GTANGO involves (among others) the following technologies and languages: Python, JavaScript, OpenAPI/Swagger, Docker, Kubernetes, YAML/JSON schemas.

### Software Campus: RealVNF

 "Software Campus trains and professionally develops tomorrow's senior IT executives while opening up excellent career prospects to young IT experts in Germany. Software Campus combines scientific leading-edge research with hands-on management practice into an entirely new and innovative concept."

In collaboration with Huawei, the project "RealVNF" investigates means to improve coordination (i.e., scaling, placement, resource allocation, scheduling, routing) of chained virtual network functions (VNFs) under realistic conditions. RealVNF addresses real-world challenges such as scalability issues, failures, etc. using a modern, agile approach and leveraging state-of-the-art techniques such as deep reinforcement learning.

## Research topics

### B-JointSP

B-JointSP is an optimization problem focusing on the *joint scaling and placement* of NFV network services, consisting of interconnected virtual network functions (VNFs), as well as routing of flows from sources through these VNFs. The exceptional about B-JointSP is its consideration of *realistic, bidirectional network services*, in which flows return to their sources and may have a non-linear service structure. It even supports *stateful VNFs* that need to be traversed by the same flows in both upstream and downstream direction. Furthermore, B-JointSP allows the reuse of VNFs across different network services and supports physical, legacy network functions.

To solve B-JointSP, we formalized it as mixed integer linear program (MILP), which can be used to find optimal solutions, but is NP-hard (see proof in paper). Hence, we also designed an efficient heuristic algorithm that finds close-to-optimal solutions even for large problem instances within seconds.

* Paper: https://ieeexplore.ieee.org/document/8459915
* Source code on GitHub: https://github.com/CN-UPB/B-JointSP

### Specification and analysis of network services using Petri nets

### Abstraction layer and emulation platform for VNF placement algorithms
