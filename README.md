# linux-kernel
document linux

# linux-kernel
document linux
Linux Kernel is the heart of Linux operating systems. It is an open-source (source code that can be used by anyone freely) software that is most popular and widely used in the industry as well as on a personal use basis. Who created Linux and why? Linux was created by Linus Torvalds in 1991 as a hobby project. Since then, many of the users have contributed to its growth and development of it. Before Jumping directly to the main topic “Linux Kernel” one must know a few concepts (prerequisites) to better understand the Linux Kernel.

What is Linux Operating System and Kernel?
An operating system (OS) is a software system that manages the computer that provides some services for computer programs and manages computer hardware and software. Basically, it is a communication or resource allocation between computer hardware and applications. It provides some services like managing input and output devices, managing file systems, providing UI (User Interface) and also managing computer memory. It also governs and executes all the programs. 

Linux operating System also consists of various components for example system libraries, user-space utilities, Linux kernel, and applications. The kernel is the core component of an operating system. This provides a platform for programs and various services to run on top of it. The Linux kernel is modifiable according to the user’s needs. Overall, the Linux Operating System and Linux kernel together provide a strong and user-friendly platform.  

In a General-Purpose Computer running many processes simultaneously, we need a middle layer to manage the distribution of the computer’s hardware resources efficiently and fairly among all the various processes running on the computer. This middle layer is referred to as the kernel. The kernel virtualizes the computer’s common hardware resources to provide each process with its own virtual resources. This makes the process seem as if it is the sole process running on the machine. The kernel is also responsible for preventing and mitigating conflicts between different processes. This is schematically represented below: 


Schematical representation of Kernel working
Schematical representation of Kernel working

Figure: Virtual Resources for each Process

The Core Subsystems of the Linux Kernel are as follows:

The Process Scheduler
The Memory Management Unit (MMU)
The Virtual File System (VFS)
The Networking Unit
Inter-Process Communication Unit
 Core Subsystems of the Linux Kernel 
 Core Subsystems of the Linux Kernel 

Figure: The Linux Kernel for the purpose of this article we will only be focusing on the 1st three important subsystems of the Linux Kernel. The basic functioning of each of the 1st three subsystems is elaborated below:

The Process Scheduler: This kernel subsystem is responsible for fairly distributing the CPU time among all the processes running on the system simultaneously.
The Memory Management Unit: This kernel sub-unit is responsible for proper distribution of the memory resources among the various processes running on the system. The MMU does more than just simply provide separate virtual address spaces for each of the processes.
The Virtual File System: This subsystem is responsible for providing a unified interface to access stored data across different filesystems and physical storage media.
Some Basic Commands:
Some Basic Commands we need to know while working on Linux Kernel. 

`ls` : Use to list all the files and directories in a particular location specified by us.
Syntax: 

ls
Example:

In this example we are going to list all the file and directories in our current location , we have one directory name `snap`.

 Here in second time we use `a` option (to see all the hidden files).

 In third time we specified a `snap` directory.

`ls` command
ls command

`mkdir` : In this we will create a new directory.
Syntax:  

mkdir

Example:

In this we will make a directory name `test` and to check it we can use command `ls`.

`mkdir` command
mkdir command

`cat` : In this we will print the context inside a text file on terminal.
Syntax: 

cat
Example: 

Printing a content inside a text file name `example`.

`cat` command
cat command

`pwd` : In this we will get to know the name and path of the current working directory.
Syntax: 

pwd
Example:

`pwd` command

