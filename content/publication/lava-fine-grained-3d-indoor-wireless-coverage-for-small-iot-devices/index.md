---
title: "LAVA: Fine-Grained 3D Indoor Wireless Coverage for Small IoT Devices"
publication_types:
  - "1"
authors:
  - R. Ivan Zelaya
  - William Sussman
  - Jeremy Gummeson
  - Kyle Jamieson
  - Wenjun Hu
author_notes: []
doi: 10.1145/3452296.3472890
publication: Proceedings of the 2021 ACM SIGCOMM 2021 Conference
abstract: Small IoT devices deployed in challenging locations suffer from uneven
  3D coverage in complex environments. This work optimizes indoor coverage with
  LAVA, a Large Array of Vanilla Amplifiers. LAVA is a standard-agnostic
  cooperative mesh of elements, i.e., RF devices each consisting of several
  switched input and output antennas connected to fixed-gain amplifiers. Each
  LAVA element is further equipped with rudimentary power sensing to detect
  nearby transmissions. The elements report power readings to the LAVA control
  plane, which then infers active link sessions without explicitly interacting
  with the endpoint transmitter or receiver. With simple on-off control of
  amplifiers and antenna switching, LAVA boosts passing signals via multi hop
  amplify-and-forward. LAVA explores a middle ground between smart surfaces and
  physical-layer relays. Multi-hopping over short inter-hop distances exerts
  more control over the end-to-end trajectory, supporting fine-grained coverage
  and spatial reuse. Ceiling testbed results show throughput improvements to
  individual Wi-Fi links by 50% on average and up to 100% at 15 dBm transmit
  power (193% on average, up to 8x at 0 dBm). ZigBee links see up to 17 dB power
  gain. For pairs of co-channel concurrent links, LAVA provides average per-link
  throughput improvements of 517% at 0 dBm and 80% at 15 dBm.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-12-18T20:57:20.659Z
---
