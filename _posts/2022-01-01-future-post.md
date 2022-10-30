---
title: 'Current Projects'
permalink: /posts/2022/01/future-post/
tags:
  - cool posts
  - category1
  - category2
---
All these current projects are funded by the **Office of Naval Research**.

Geographically Distributed Management of Enterprise Network Security Policy
====
This work extends a single, globally-defined and managed, enterprise network security policy to many geographically distributed sites. Each site operates independently and enforces a least-information policy slice that is dynamically parameterized with user location as employees roam between sites. We build a prototype of MSNetViews and analyze performance. As such, we demonstrate the utility of SDN towards achieving zero trust for on-premises network resources, even for organizations with many geographically distributed sites.

Security Analysis of Next Generation Access Control
=====
To analyze NIST Next Generation Access Control, we follow the application-independent approach; later, we will expand it for particular application scenarios (like MSNetViews, and NetViews). We want to verify that the interplay among the policy classes is more restrictive than the individual policy class. We want to ensure that the dynamic policy update using obligation does not violate the access control policy’s security properties. Furthermore, we envision formalizing the multi-tenant or multi-administration policy definition of NGAC. 

Device to Device Least Privilege Access Control in 5G User Plane
======= 
As enterprises move from the wired network to 5G cellular, there is a need to migrate the access control enforcement from the wired network to the 5G network. To achieve this, we define policies between enterprise end-hosts using the NGAC policy language. And develop a custom policy network function in 5G core that takes the NGAC policy, transforms the access control rules to a 5G specified format, and feeds those rule into the Network Repository Function (NRF).
