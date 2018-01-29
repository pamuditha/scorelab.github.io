---
layout: gsoc
categories: gsoc2018
divid: etherbeat3
title:  EtherBeat - Optimize block extracting mechanism in EtherBeat
description: Currently EtherBeat extract from Ethereum blockchain in parallel using different threads. However, this is not scalable due to various overheads (network calls, storage). We want to optimize the extraction process to make it more scalable. Student is expected to propose alternatives and implement it in EtherBeat.
expectedresults: Student should be able to demonstrate the performance benchmarks of the optimized solution and merge it to EtherBeat codebase.
githuburl: https://github.com/scorelab/EtherBeat
requiredknowledge: Ethereum, Graph database concepts
possiblementors: Ruwan Geeganage, Tharidu Fernando and Keshan Sodimana
---