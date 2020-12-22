---
layout:     post
comments: true
title:      "Setting up a homelab: Intel NUC on ESXi hypervisor"
description: "Like many I needed a homelab for study and learning outside my work environment. I have previously spun up VMs in azure but even when turning off resources after use it has become a fairly expensive project. Before that i used my gaming machine with HyperV, worked okay but i think it was time to get something better."
date:       2020-08-18 18:00:00
author:     "Jasmeet Gill"
header-img: assets/img/nuc.jpeg

categories:
  - Personal
---

Like many I needed a homelab for study and learning outside my work environment. I have previously spun up VMs in azure but even when turning off resources after use it has become a fairly expensive project. Before that i used my gaming machine with HyperV, worked okay but i think it was time to get something better. My requirements were fairly simple: silent, low power consumption and good enough to run a multiple VMs. Landed a on a Intel NUC with the following specs:

i7 8650U
DDR4 32GB ram
500GB SSD
Officially ESXi isnt supported on NUCs, but wasnt too hard to set up.