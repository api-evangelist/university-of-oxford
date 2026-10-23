---
title: "Connecting VS Code to a Cluster"
url: "/blog/connecting-vs-code-to-a-cluster/"
date: "2026-06-17"
feed_url: "https://blog.oxrse.uk/index.xml"
---
Introduction If you use the ARC clusters at Oxford and want to use your local editor (such as Visual Studio Code) for editing and debugging code on the cluster, you’ll quickly find that you can’t just connect to the login node and launch VS Code’s Remote-SSH as you might on a regular remote server. In this post I’ll explain why you can’t launch VS Code directly on the login node , then walk you through the workflow: starting an interactive job, configuring SSH proxy-jump, and connecting VS Code to the interactive node. Note that while I’m talking about Oxford’s ARC cluster here, the general pr
