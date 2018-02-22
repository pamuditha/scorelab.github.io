---
layout: gsoc
categories: gsoc2018
divid: nodecloud-rewrite-core
title: Nodecloud- Re-write the core architecture
description: Even though the current architecture of the Nodecloud is modular, some of the components have been wired up so that the entire application has now become a monolith. The idea of decomposing the architecture is backed up by the fact that people will use only a particular provider at a given instance and load all the components related to all cloud providers will be an overkill for the application. Main tasks in this idea are to identify a modular architecture where the entire core is a separate NPM module and all the cloud providers will implement the core to develop other cloud providers such as AWS, GCP, Azure etc.
expectedresults: <ul style="list-style:inherit"><li>New Architecture for the Nodecloud Core</li><li>Separate NPM modules for core and current providers</li><li>Maintain good code quality throughout</li><li>Write proper unit tests</li><li>Integrate the build and test cases to TravisCI</li></ul>
githuburl: https://github.com/cloudlibz/clocal-gcp/
requiredknowledge: NodeJS, Google Cloud Platform, AWS
possiblementors: Rumesh Eranga Hapuarachchi, Rajika
---