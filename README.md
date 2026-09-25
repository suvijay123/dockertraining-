# docker training
Repository prepared as part of giving training to student who are keen to learn docker from basic to advanced.
This repository covers all the topics which can help every individual to become pro in learning docker from basic level

**Let us start journey........**

**Please note:
if you found this repo useful, kindly help me with STAR .. feel free to fork it.**

first question before starting to learn about docker 
let us start with containers   

**What is a container?**
  
A container is a lightweight, portable, and isolated environment for running an application with its dependencies while sharing the host operating system kernel.

below image helps in understanding what a container is...

<img width="500" height="600" alt="image" src="https://github.com/user-attachments/assets/1841c913-f654-4c8d-b6eb-5c215c5caadb" />

let us also understand why containers are lightweight by nature

Containers are lightweight mainly because they do not carry a complete operating system with them.

A container packages only the application + required libraries + dependencies + configuration. It shares the host machine’s OS kernel with other containers.

**Technically:
Containers are lightweight because they isolate applications using OS-level features such as namespaces and cgroups while sharing the host operating system kernel instead of running a separate guest OS for every application.**

Container = Application + Dependencies, sharing the Host OS Kernel.

**Containers Vs Virtual Machines**
