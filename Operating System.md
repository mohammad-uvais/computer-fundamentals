An Operating System is the most important system software. As the name implies, it is a system software that operates the computer and without it other software cannot work. When a computer is switched on, the operating system is the first program that is loaded onto its memory.

It is a set of programs that control and supervise the hardware of a computer and also provide services to application software, programmers and users. An operating system (OS) can be considered to be a resource manager which manages all the resources of a computer, i.e., its hardware including CPU, RAM, Disk, Network and other input-output devices. It manages all hardware and software, input, output and processing activities within the computer system, the flow of information to and from the processor, and sets priorities for handling different tasks. It also controls various application software and device drivers, manages system security and handles access by different users.

A user cannot communicate directly with the computer hardware, so the operating system acts as an interface between the user and the computer hardware. The primary objectives of an operating system are two-fold. The first objective is to provide services for building and running application programs. When an application program needs to be run, it is the operating system which loads that program into memory and allocates it to the CPU for execution. When multiple application programs need to be run, the operating system decides the order of the execution. The second objective is to provide an interface to the user through which the user can interact with the computer. A user interface is a software component which is a part of the operating system and whose job is to take commands or inputs from a user for the operating system to process.

An operating system can be a Single User or a Multiuser operating system. A single user operating system allows only one user to work at any time but a multiuser operating system allows two or more users to use a powerful computer at the same time. For example Windows 7 is a single user operating system while Linux is a multiuser operating system.

Some of the popular operating systems are Windows, Linux, Macintosh, Ubuntu, Fedora, Android, iOS, etc.

##### Need for an Operating System

Operating system provides a platform, on top of which, other programs, called application programs can run. As discussed before, it acts as an interface between the computer and the user. It is designed in such a manner that it operates, controls and executes various applications on the computer. It also allows the computer to manage its own resources such as memory, monitor, keyboard, printer etc.
Our choice of operating system, therefore, depends to a great extent on the CPU and the other attached devices and the applications we want to run. The operating system controls the various system hardware and software resources and allocates them to the users or programs as per their requirement.

##### OS User Interface

(A) Command Line Interface (CLI)
Command Line Interface requires a user to enter the commands to perform different tasks like creating, opening, editing or deleting a file, etc. The user has to remember the names of all such programs or specific commands which the operating system supports.
The primary input device used by the user for command based interface is the keyboard. Command based interface is often less interactive and usually allows a user to run a single program at a time.
Examples of operating systems with command-based interface include MS-DOS and Unix.

(B) Graphical User Interface (GUI)
Graphical User Interface (GUI) lets users run programs or give instructions to the computer in the form of icons, menus and other visual options. Icons usually represent files and programs stored on the computer and windows represent running programs that the user has launched through the operating system.
The input devices used to interact with the GUI commonly include the mouse and the keyboard. Examples of operating systems with GUI interfaces include Microsoft Windows, Ubuntu, Fedora and Macintosh, among others.

(C) Touch Based Interface
Today smartphones, tablets and PCs allow users to interact with the system simply using the touch input. Using the touchscreen, a user provides inputs to the operating system, which are interpreted by the OS as commands like opening an app, closing an app, dialing a number, scrolling across apps, etc.
Examples of popular operating systems with touch- based interfaces are Android and iOS. Windows 8.1 and 10 also support touch-based interfaces on touchscreen devices.

(D) Voice Based Interface
Modern computers have been designed to address the needs of all types of users including people with special needs and people who want to interact with computers or smartphones while doing some other task. For users who cannot use the input devices like the mouse, keyboard, and touchscreens, modern operating systems provide other means of human-computer interaction. Users today can use voice-based commands to make a computer work in the desired way.

(E) Gesture Based Interface
Some smartphones based on Android and iOS as well as laptops let users interact with the devices using gestures like waving, tilting, eye motion and shaking. This technology is evolving faster and it has promising potential for application in gaming, medicine and other areas.

##### Functions of an Operating System

- Process Management:
  While a computer system is operational, different tasks are running simultaneously. A program is intended to carry out various tasks. A task in execution is known as a **process**. We can activate a system monitor program that provides information about the processes being executed on a computer. In some systems it can be activated using Ctrl+Alt+Delete.

  It is the responsibility of operating system to manage these processes and get multiple tasks completed in minimum time. As CPU is the main resource of computer system, its allocation among processes is the most important service of the operating system. Hence **process management** concerns the management of multiple processes, allocation of required resources, and exchange of information among processes.

  The operating system takes care of the allotment of CPU time to different processes. This is called **scheduling**. Two types of scheduling techniques are employed by an operating system:
  - **Priority Scheduling:** Each task is given CPU time according to the priority assigned to that task. The program with higher priority will be given CPU time before a program with lower priority. The CPU executes the task till it is completed or there is some interrupt request i.e. till the time operating system has to stop (interrupt) the current task due to an unavoidable job request. The major drawback of Priority scheduling is that even a small job has to wait for a long time when a long duration job with higher priority is being executed.
  - **Round Robin Scheduling:** This type of scheduling technique is also known as Time Sharing Scheduling. In this, each program or task is given a fixed amount of time to execute. The CPU continues with the execution till either the allotted time is over or there is some interrupt request or the task is completed before the allotted time. If the task is not completed at the end of the allotted time, it is put at the end of the queue. So each task gets its allotted share of CPU time. This scheduling technique improves the response time and provides an interactive environment. Hence time sharing operating system is very useful in network environment as each user is allowed to share the network resources.

- **Device Management:**
  A computer system has many I/O devices and hardware connected to it. Operating system manages these heterogeneous devices that are interdependent. The operating system interacts with the device driver and the related software for a particular device. The operating system must also provide the options for configuring a particular device, so that it may be used by an end user or some other device. Just like files, devices also need security measures and their access must be restricted by the operating system to the authorized users, software and other hardware only.

  The Operating System maintains a balance between the CPU and the attached devices. This is all the more important because the CPU processing speed is much higher than that of I/O devices. In order to optimize the CPU time, the operating system employs two techniques - Buffering and Spooling.
  - **Buffering:** In this technique the temporary storage of input and output data is done in Input Buffer and Output Buffer. Once the signal for input or output is sent to or from the CPU respectively, the operating system through the device controller moves the data from the input device to the input buffer and for the output device to the output buffer. When the signal is sent to/from the operating system to the respective device controllers, the program doesn't wait rather it returns to its processing. In case of input, if the buffer is full, the operating system sends a signal to the program which processes the data stored in the buffer. When the buffer becomes empty, the program informs the operating system which reloads the buffer and the input operation continues. Similarly for output when the program being executed has to display some output, it fills the buffer and then informs the operating system. Thereafter the operating system empties the buffer by sending data to the output device and in the meantime the program fills another buffer. This technique is called **overlapped processing**. This is because while the operating system reloads one buffer, the executing program doesn't stop as it is able to retrieve/fill data from/in another buffer.

  - **Spooling (Simultaneous Peripheral Operation on Line):** This is a device management technique used for processing of different tasks on the same input/output device. Say for example there are various users on a network sharing the same printer. At one point of time more than one user might give a print command. The speed of the printer is very slow as compared to the CPU processing. So the operating system temporarily stores the data of every user on the hard disk of the computer to which the printer is attached. The individual users need not wait for the printing process to be complete. Instead the operating system sends the data from the hard disk to the printer one by one.

- **Memory management:**
  Primary or main memory of a computer system is usually limited. The main task of memory management is to dynamically (on-the-go) allocate and free memory to the running processes. Operating system should do it without affecting other processes that are already residing in the memory and once the process is finished, it is again the responsibility of the operating system to take the memory space back for re-utilization. Hence, memory management concerns with management of main memory so that maximum memory is occupied or utilized by large number of processes while keeping track of each and every location within the memory as free or occupied.

  When a program needs to be executed it is loaded onto the main memory till the execution is complete. Thereafter that memory space is freed and is available for other programs. The common memory management techniques used by the operating system are Partitioning and Virtual Memory.
  - **Partitioning:** The total memory is divided into various partitions of same size or different sizes. This helps to accommodate number of programs in the memory. The partition can be fixed i.e. remains same for all the programs in the memory or variable i.e. memory is allocated when a program is loaded onto the memory. The latter approach causes less wastage of memory but in due course of time, it may become fragmented.

  - **Virtual Memory:** This is a technique used by the operating system by virtue of which the user can load the programs which are larger than the main memory of the computer. In this technique the program is executed even if the complete program is not loaded onto the main memory. The operating system divides the main memory into equal sizes called **pages**. A part of the program resides in the main memory and is called the **active set**. The rest is in the secondary storage device in the form of tracks/sectors or blocks. With the help of **Page Map Tables (PMT)**, the operating system keeps track which page of main memory is storing which block of secondary memory. A virtual address (which is not the real physical address) is mapped either to the main memory or the secondary memory. Hence virtual memory allows more programs and even larger programs to be executed in the main memory leading to efficient memory utilization.

- **File Management:**
  Data and programs are stored as files in the secondary storage of a computer system. File management involves the creation, updation, deletion and protection of these files in the secondary memory. Protection is a crucial function of an operating system, as multiple users can access and use a computer system. There must be a mechanism in place that will stop users from accessing files that belong to some other user and have not been shared with them.

  The operating system manages the files, folders and directory systems on a computer. Any data on a computer is stored in the form of files and the operating system keeps information about all of them using **File Allocation Table (FAT)**. The FAT stores general information about files like filename, type (text or binary), size, starting address and access mode (sequential/indexed sequential/direct/relative). The file manager of the operating system helps to create, edit, copy, allocate memory to the files and also updates the FAT. The operating system also takes care that files are opened with proper access rights to read or edit them.

##### Types of Operating System

OS are classified into the following types depending on their capability of processing

1. Single User and Single Task OS
   It is used on a standalone single computer for performing a single task. Operating systems for Personal Computers (PC) are single-user OS. Single user OS are simple operating system designed to manage one task at a time. MS-DOS is an example of single user OS.

2. Multiuser OS
   Multiuser is used in mini computers or mainframes that allow same data and applications to be accessed by multiple users at the same time. The users can also communicate with each other. Linux and UNIX are examples of multiuser OS.

3. Multiprocessing OS
   **Multiprocessing OS** have two or more processors for a single running process. Processing takes place in parallel and is also called _parallel processing_. Each processor works on different parts of the same task, or, on two or more different tasks. Since execution takes place in parallel, they are used for high speed execution, and to increase the power of computer. Linux, UNIX and Windows 7 are examples of multiprocessing OS.

4. Time sharing Operating System
   It allows execution of more than one tasks or processes concurrently. For this, the processor time is divided amongst different tasks. This division of time is also called **time sharing**. The processor switches rapidly between various processes. After the stipulated time is over, the CPU shifts to next task in waiting, So this type of operating system employs **round robin** **scheduling technique.** The system switches rapidly from one user to another but still each user feels that it is getting a dedicated CPU time. Virtual Memory techniques are used in this type of operating system. For example, the user can listen to music on the computer while writing an article using a word processing software. The user can switch between the applications and also transfer data between them. Time sharing operating system can be both single user and multiuser. Windows 95 and all later versions of Windows are examples of multitasking OS.

5. Real Time Operating System
   It is a multitasking operating system designed for real time applications like robotics. In this type of operating system, the tasks have to be done within a fixed deadline. System performance is good if task is finished within this deadline. If it is not done, the situation is called Deadline Overrun. Lesser the deadline over run, better is the system efficiency. Hence Real Time operating systems depend not only on the logical result of the computation but also on the time in which the results are produced.

6. Distributed Operating System
   On a network data is stored and processed on multiple locations. The Distributed Operating System is used on networks as it allows shared data/files to be accessed from any machine on the network in a transparent manner. We can insert and remove the data and can even access all the input and output devices. The users feel as if all data is available on their workstation itself.

7. Interactive Operating System
   This is the operating system that provides a Graphic User Interface (GUI) through which the user can easily navigate and interact. The computer responds almost immediately after an instruction has been entered, and the user can enter new instructions after seeing the results of the previous instructions.

##### Commonly Used Operating Systems

1. **Windows:** Microsoft launched Windows 1.0 operating system in 1985 and since then Windows has ruled the world’s software market. It is a GUI (Graphic User Interface) and various versions of Windows have been launched like Windows 95, Windows 98, Win NT, Windows XP, Windows 7 and the latest being Windows 8.
2. **Linux:** Linux is a free and open software which means it is freely available for use and since its source code is also available so anybody can use it, modify it and redistribute it. It can be downloaded from www.linux.org. It is a very popular operating system used and supported by many companies. The defining component of this operating system is the Linux kernel.
3. **BOSS (Bharat Operating System Solutions):** This is an Indian distribution of GNU/Linux. It consists of Linux operating system kernel, office application suite, Bharateeya OO, Internet browser (Firefox), multimedia applications and file sharing.
4. **UNIX:** It is a multitasking, multiuser operating system originally developed in 1969 at Bell Labs. It was one of the first operating systems developed in a high level language, namely C. Due to its portability, flexibility and power, UNIX is widely being used in a networked environment. Today, ”UNIX” and "Single UNIX Specification" interface are owned and trademarked by The Open Group. There are many different varieties of UNIX, although they share common similarities, the most popular being GNU/Linux and Mac OS X.

##### Mobile Operating Systems (Mobile OS)

It is the operating system that operates on digital mobile devices like smart phones and tablets. It extends the features of a normal operating system for personal computers so as to include touch screen, Bluetooth, WiFi, GPS mobile navigation, camera, music player and many more. The most commonly used mobile operating systems are – Android and Symbian

**Android:** It is a Linux derived Mobile OS released on 5th November 2007 and by 2011 it had more than 50% of the global Smartphone market share. It is Google’s open and free software that includes an operating system, middleware and some key applications for use on mobile devices. Android applications are quiet user friendly and even one can easily customize the Smartphone with Android OS. Various versions of Android OS have been released like 1.0, 1.5, 1.6, 2. x, 3.0 etc. Most Android phones use the 2.x release while Android 3.0 is available only for tablets. The latest Android version released is 4.2.2. The Android releases have dessert inspired codenames like Cupcake, Honeycomb, Ice Cream sandwich and Jelly Bean.

##### Concept of Booting

When the computer is switched on, a copy of boot program is brought from ROM into the main memory. This process is called booting. The CPU first runs a jump instruction that transfers to BIOS (Basic Input output System) and it starts executing. The BIOS conducts a series of self diagnostic tests called POST (Power On Self Test). These tests include memory tests, configuring and starting video circuitry, configuring the system’s hardware and checking other devices that help to function the computer properly. Thereafter the BIOS locates a bootable drive to load the boot sector. The execution is then transferred to the Boot Strap Loader program on the boot sector which loads and executes the operating system. If the boot sector is on the hard drive then it will have a Master Boot record (MBR) which checks the partition table for active partition. If found, the MBR loads that partition’s boot sector and executes it.

Booting Process is of two types – Warm and Cold

**Cold Booting:** When the system starts from initial state i.e. it is switched on, we call it cold booting or Hard Booting. When the user presses the Power button, the instructions are read from the ROM to initiate the booting process.

**Warm Booting:** When the system restarts or when Reset button is pressed, we call it Warm Booting or Soft Booting. The system does not start from initial state and so all diagnostic tests need not be carried out in this case. There are chances of data loss and system damage as the data might not have been stored properly.
