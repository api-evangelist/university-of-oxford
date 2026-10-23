---
title: "Debug Python on HPC Compute Nodes"
url: "/blog/debug-python-on-hpc-compute-nodes/"
date: "2025-10-29"
feed_url: "https://blog.oxrse.uk/index.xml"
---
Overview When working on a high-performance computing (HPC) cluster, debugging code using an IDE such as VSCode can be complicated by network restrictions on compute nodes. This article demonstrates a workaround of starting an interactive session and launching code via debugpy in a ‘wait for client’ state on an open port. VSCode can then be connected to the debugger through the port rather than SSH.
