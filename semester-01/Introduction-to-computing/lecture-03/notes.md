# Lecture 03 – Advanced Computing Concepts

*Topics Covered:*

1. *System Calls:*  
   - System calls are the interface between user programs and the operating system.  
   - They allow programs to request services from the OS, such as reading/writing files, creating processes, or communicating with hardware.  
   - Example: open(), read(), write() in C.

2. *Application Programming Interface (API):*  
   - APIs let programs communicate with other software components or the operating system without knowing the internal implementation.  
   - Example: A web app using Google Maps API to show locations.

3. *Virtual Machines (VMs):*  
   - Software-based emulation of a physical computer.  
   - Allows multiple OS environments on a single physical machine.  
   - Example: Running Ubuntu Linux inside Windows using VirtualBox.

4. *Containers:*  
   - Lightweight, isolated environments to run applications.  
   - Unlike VMs, containers share the host OS kernel, making them faster and smaller.  
   - Example: Docker containers for deploying web applications.

5. *Cluster Computing:*  
   - Multiple computers connected to work together as a single system.  
   - Used for high-performance tasks like scientific simulations.  
   - Example: Rendering a large animation using multiple computers.

6. *Grid Computing:*  
   - Similar to clusters, but the computers may be geographically distributed.  
   - Used for large-scale computational problems.  
   - Example: Folding@Home project for protein folding research.

7. *Cloud Computing:*  
   - Using remote servers over the internet to store, manage, and process data.  
   - Provides scalable resources and services without owning physical infrastructure.  
   - Examples: AWS, Google Cloud, Microsoft Azure.

*Example to Connect Concepts:*  
When you open *Gmail* or any cloud-based application:  
- The browser requests data via *APIs*.  
- The OS handles *system calls* to access network and storage.  
- The application may run in a *container* in the cloud.  
- Multiple servers (cluster/grid) process tasks efficiently.  

*Summary:*  
Lecture 03 introduced advanced computing concepts essential for modern software development. Understanding system calls, APIs, VMs, containers, clusters, grid computing, and cloud computing is crucial for building scalable and efficient applications.
