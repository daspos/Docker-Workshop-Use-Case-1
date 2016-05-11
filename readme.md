README

#Readme for Researcher Dashboard Breakout: DASPOS Workshop

This is a repo for Breakout 1 Umbrella a session held at the DASPOS Workshop on Container Strategies for Data & Software Preservation.  More information about the workshop is available at: https://daspos.crc.nd.edu/index.php/workshops/container-strategies-for-data-software-preservation-that-promote-open-science


More information about Umbrella is available at the Notre Dame Cooperative Computing Lab's Umbrella page at: http://ccl.cse.nd.edu/software/umbrella/

This github repository contains info, links, files for participating in the Umbrella Breakout sessions at the DASPOS Workshop Container Strategies for Data & Software Preservation that Promote Open Science held at Notre Dame University 5/19-20/2016 .

The breakout sessions are related to the 5/19/2016 Umbrella workshop talk Combining Containers and Workflow Systems for Reproducible Execution presented by Douglas Thain, Professor of Computer Science and Engineering, University of Notre Dame, DASPOS Co-PI and the subsequent talk and demonstration presented by Alex Vyushkov, Assistant Manager, Research Programmer, Center for Research Computing, University of Notre Dame.

##Technology Preview:Umbrella

Umbrella is a tool for specifying and materializing comprehensive execution environments, from the hardware all the way up to software and data. A user simply invokes Umbrella with the desired task, and Umbrella parses the specification, determines the minimum mechanism necessary to run the task, downloads missing dependencies, and executes the application through the available minimal mechanism, which may be direct execution, a system container (Parrot, Docker, chroot), a local virtual machine (i.e., VMware), or submission to a cloud environment (i.e., Amazon EC2) or grid environment (i.e., HTCondor).

Umbrella involves multiple sandboxing and virtualization techniques, however, the key idea of Umbrella is to construct a sandbox for an application during runtime by mounting all the os, software, and data dependencies into a virtual root filesystem without copying them. The usage of mounting mechanism allows multiple sandboxes share the same dependencies concurrently.

Please use the following citation for Umbrella in a scientific publication:

Haiyan Meng and Douglas Thain, Umbrella: A Portable Environment Creator for Reproducible Computing on Clusters, Clouds, and Grids, Workshop on Virtualization Technologies in Distributed Computing (VTDC) at HPDC, June, 2015. DOI: 10.1145/2755979.2755982
