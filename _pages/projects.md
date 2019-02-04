---
title:  "Projects"
layout: single
permalink: /projects/
author_profile: true
comments: false
---

# Ongoing projects

## 5GTANGO: 5G Development and validation platform for global industry-specific network services and apps

[5GTANGO](https://5gtango.eu/) is a European H2020 project focusing on flexible programmability of 5G networks by offering an NFV SDK for development support, a verification and validation platform, and a service platform for deployment. The project outcomes are demonstrated using three vertical pilots (smart manufacturing, immersive media, real-time communication).

In 5GTANGO, I work on evolving the SDK by developing new tools like the service [descriptor generator](https://github.com/sonata-nfv/tng-sdk-descriptorgen) as well as refactoring and extending existing ones like the [project management tool](https://github.com/sonata-nfv/tng-sdk-project), which support service developers in quickly creating suitable descriptors that are required for deployment. I also help designing and developing the [smart manufacturing pilot](https://github.com/sonata-nfv/tng-industrial-pilot) use cases and corresponding network functions.

**Technologies used**: Python (+ Flask and Flask extensions), Docker, Kubernetes, JavaScript, Travis/Jenkins, Ansible, Angular, Jupyter notebooks, JSON/YAML schema

## RealVNF: Improved coordination of chained VNFs under realistic conditions (Software Campus)

 "[Software Campus](https://www.softwarecampus.de/en/) trains and professionally develops tomorrow's senior IT executives while opening up excellent career prospects to young IT experts in Germany. Software Campus combines scientific leading-edge research with hands-on management practice into an entirely new and innovative concept."

In collaboration with Huawei, the project "RealVNF" investigates means to improve coordination (i.e., scaling, placement, resource allocation, scheduling, routing) of chained virtual network functions (VNFs) under realistic conditions. RealVNF addresses real-world challenges such as scalability issues, failures, etc. using a modern, agile approach and leveraging state-of-the-art techniques such as deep reinforcement learning.

**Technologies used:** Python (+ Numpy, Pandas),  (deep) machine learning with sklearn and keras

# Previous projects

## OpenC2X: An Open Source Experimental and Prototyping Platform Supporting ETSI ITS-G5 (Vehicular Networking)

Website: [http://www.ccs-labs.org/software/openc2x/](http://www.ccs-labs.org/software/openc2x/)

Vehicular networking is at the corner from early research to final  deployment. This phase requires more field testing and real-world  experimentation. Most Field Operational Tests (FOTs) are based on  proprietary commercial hardware that only allows for marginal  modifications of the protocol stack. Furthermore, the roll-out of  updated implementations for new or changing protocol standards often  takes a prohibitively long time.

We developed one of the first  complete Open Source experimental and prototyping platform for vehicular  networking solutions. Our system supports most of the ETSI ITS-G5  features and runs on standard Linux. New protocol features and updates  could now easily be done by and shared with the vehicular networking  R&D community.   

**Technologies used:** C++, ZeroMQ, Google Protobuf