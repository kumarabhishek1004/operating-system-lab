Overview
This repository contains modifications made to the xv6 operating system as part of a course project at IIT Guwahati. The project, guided by Dr. Phrangboklang Lyngton Thangkhiew, focused on enhancing xv6's core functionality in scheduling and memory management.

Key Features
This project includes the following key implementations:

Advanced Process Scheduling: Implemented two new scheduling algorithms, Lottery Scheduling and Shortest Job First (SJF), by modifying the scheduler and process control structures to manage new scheduling parameters.

System Call Enhancements: Developed new system calls to allow for dynamic interaction with the kernel. These calls enable users to:

Retrieve process metadata.

Manage and configure scheduling parameters.

Set burst times for processes.

Efficient Memory Management: Built a lazy memory allocation and paging mechanism with a Least Recently Used (LRU) policy. This system uses kernel processes to optimize memory utilization and improve overall system performance.
