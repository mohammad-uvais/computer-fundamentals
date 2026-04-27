# Introduction

Computers are seen everywhere around us, in all spheres of life. May it be the field of education and research, travel and tourism, weather forecasting, social networking, e- commerce or any other, computers have now become an indispensable part of our lives. The manner, in which computers have revolutionised our lives because of their accuracy and speed of performing a job, is truly remarkable. Today no organization can function without a computer. In fact various organizations are trying to become paper free owing to benefits of computers. But the computers of today have evolved over the years from a simple calculating device to the portable high speed computers that we see today.

# Computer - Data and Information

It is an electronic device that processes the input according to the set of instructions provided to it and gives the desired output at a very fast rate.

**Data:** It is the term used for raw facts and figures. For example, 134, + 9, ‘Raju’, ‘C’ are data.
**Information:** Data represented in useful and meaningful form is information. In simple words we can say that data is the raw material that is processed to give meaningful, ordered or structured information. For example Raju is 9 years old. This is information about Raju and conveys some meaning.

This conversion of data to information is called data processing.

# Functional Components of a Computer

The computer is the combination of hardware and software. Hardware are the physical components of a computer like motherboard, memory devices, monitor, keyboard etc. while software is the set of programs or instructions. Both hardware and software together make the computer system function.
Every task given to a computer follows an Input-Process-Output Cycle (IPO cycle). It needs certain input, processes that input and produces the desired output. The input unit takes the input, the central processing unit does the processing of data and the output unit produces the output. The memory unit holds the data and instructions during the processing.

## Input Unit

The input unit consists of input devices that are attached to the computer. These devices take input and convert it into binary language that the computer understands. Some of the common input devices are keyboard, mouse, joystick, scanner etc.

## Central Processing Unit (CPU)

Once the information is entered into the computer by the input device, the processor processes it. The CPU is called the brain of the computer because it is the control centre of the computer. As the CPU is located on a small chip, it is also called the microprocessor. It first fetches instructions from memory and then interprets them so as to know what is to be done. If required, data is fetched from memory or input device. Thereafter CPU executes or performs the required computation and then either stores the output or displays on the output device. The CPU has three main components which are responsible for different functions – Arithmetic Logic Unit (ALU) , Control Unit (CU) and Memory Registers.

## Arithmetic and Logic Unit

The ALU, as its name suggests performs mathematical calculations and takes logical decisions. Arithmetic calculations include addition, subtraction, multiplication and division. Logical decisions involve comparison of two data items to see which one is larger or smaller or equal.

## Control Unit

The Control unit coordinates and controls the data flow in and out of CPU and also controls all the operations of ALU, memory registers and also input/output units. It is also responsible for carrying out all the instructions stored in the program. It decodes the fetched instruction, interprets (understands) it and sends control signals to input/output devices until the required operation is done properly by ALU and memory.

## Memory Registers

A register is a temporary unit of memory in the CPU. These receive data/information and then this data/information is held in them as per the requirement. Registers can be of different sizes(16 bit , 32 bit , 64 bit and so on) and each register inside the CPU has a specific function like storing data, storing an instruction, storing address of a location in memory etc. The user registers can be used by an assembly language programmer for storing operands, intermediate results etc. Accumulator (ACC) is the main register in the ALU and contains one of the operands of an operation to be performed in the ALU.

## Memory

Memory attached to the CPU is used for storage of data and instructions and is called internal memory. During processing, it is the internal memory that holds the data. The internal memory is divided into many storage locations, each of which can store data or instructions. Each memory location is of the same size and has an address. With the help of the address, the computer can find any data easily without having to search the entire memory. The internal memory is also called the **_Primary memory_** or Main memory. When the task is performed, the CU makes the space available for storing data and instructions, thereafter the memory is cleared and the memory space is then available for the next task. The time of access of data is independent of its location in memory, therefore this memory is also called Random Access memory (RAM). Primary memory is volatile in nature. That means when the power is switched off, the data stored in this memory is permanently erased. That is why secondary memory is needed to store data and information permanently for later use. Some of the examples of secondary storage devices are hard disk, compact disks, pen drives etc.

## Output Unit

The output unit consists of output devices that are attached with the computer. It converts the binary data coming from CPU to human understandable from. The common output devices are monitor, printer, plotter etc.

# Interconnection between Functional Components

As we have seen before that a computer consists of input unit that takes input, a CPU that processes the input and an output unit that produces output. All these devices communicate with each other through a common bus. A bus is a transmission path (set of conducting wires) over which data or information in the form of electric signals, is passed from one component to another in a computer. The bus can be of three types – Address bus, Data bus and Control Bus.
The address bus carries the address location of the data or instruction. The data bus carries data from one component to another and the control bus carries the control signals. The system bus is the common communication path that carries signals to/from CPU, main memory and input/output devices. The input/output devices communicate with the system bus through the controller circuit. This controller circuit helps to manage various input/output devices attached to the computer.

# Concept of Booting

When the computer is switched on, a copy of boot program is brought from ROM into the main memory. This process is called booting. The CPU first runs a jump instruction that transfers to BIOS (Basic Input output System) and it starts executing. The BIOS conducts a series of self diagnostic tests called POST (Power On Self Test). These tests include memory tests, configuring and starting video circuitry, configuring the system’s hardware and checking other devices that help to function the computer properly. Thereafter the BIOS locates a bootable drive to load the boot sector. The execution is then transferred to the Boot Strap Loader program on the boot sector which loads and executes the operating system. If the boot sector is on the hard drive then it will have a Master Boot record (MBR) which checks the partition table for active partition. If found, the MBR loads that partition’s boot sector and executes it.

Booting Process is of two types – Warm and Cold

**Cold Booting:** When the system starts from initial state i.e. it is switched on, we call it cold booting or Hard Booting. When the user presses the Power button, the instructions are read from the ROM to initiate the booting process.

**Warm Booting:** When the system restarts or when Reset button is pressed, we call it Warm Booting or Soft Booting. The system does not start from initial state and so all diagnostic tests need not be carried out in this case. There are chances of data loss and system damage as the data might not have been stored properly.

# Classification of Computers

The computers can be classified based on the technology being used as: Digital, Analog and Hybrid.

## Digital Computers

These computers are capable of processing information in discrete form. In digital technology data which can be in the form of letters, symbols or numbers is represented in binary form i.e. 0s and 1s. Binary digits are easily expressed in a digital computer by the presence (1) or absence (0) of current or voltage. It computes by counting and adding operations. The digital computers are used in industrial, business and scientific applications. They are quite suitable for large volume data processing.

## Analog Computers

An analog computer works on continuously changeable aspects of physical phenomenon such as fluid pressure, mechanical motion and electrical quantities. These computers measure changes in continuous physical quantities say current and voltage. These computers are used to process data generated by ongoing physical processes. A thermometer is an example of an analog computer since it measures the change in mercury level continuously. Although the accuracy of an analog computer is less as compared to digital computers, yet it is used to process data generated by changing physical quantities especially when the response to change is fast. Most present day analog computers are well suited to simulating systems. A simulator helps to conduct experiments repeatedly in real time environment. Some of the common examples are simulations in aircrafts, nuclear power plants, hydraulic and electronic networks.

## Hybrid Computers

These use both analog and digital technology. It has the speed of analog computer and the accuracy of a digital computer. It may accept digital or analog signals but an extensive conversion of data from digital to analog and analog to digital has to be done. Generally the analog components provide efficient processing of differential equations while the digital part deals with logical operations of the system. Hence benefits of both analog and digital computing are readily available. Hybrid Computers are used as cost effective means for complex simulations.

# Classification of Digital Computers

The digital computers are classified according to their computing capabilities. The various types of digital computers are discussed below:

## Micro Computers

These are also known as Personal Computers. These type of digital computer uses a microprocessor (a CPU on a single chip) and include both desktops and laptops. These computers can work on small volume of data, are very versatile and can handle variety of applications. These computers are being used as work stations, CAD, multimedia and advertising applications. Small portable computers such as PDAs (Personal Digital Assistants) and tablets with wireless computing technology are increasingly becoming popular.

## Mini Computers

These computers can support multiple users working simultaneously on the same machine. These are mainly used in an organization where computers installed in various departments are interconnected. These computers are useful for small business organizations.

## Mainframe Computers

These computers are large and very powerful computers with very high memory capacity. These can process huge databases such as census at extremely fast rate. They are suitable for big organizations, banks, industries etc. and can support hundreds of users simultaneously on the network.

## Super Computers

These are fastest and very expensive computers. They can execute billions of instructions per second. These are multiprocessor, parallel systems suitable for specialized complex scientific applications involving huge amounts of mathematical applications such as weather forecasting. The main difference between a supercomputer and a mainframe is that a supercomputer executes fewer programs as fast as possible whereas a mainframe executes many programs concurrently.

# Hardware and Software

The electronic components of a computer system that we can see and touch are called hardware. Software is a general term used for computer programs that control the operations of the computer. A program is a sequence of instructions that perform a particular task. A set of programs form a software. It is the software which gives hardware its capability. Hardware is of no use without software and software cannot be used without hardware.

# Types of Software

## System Software

System Software is the software that is directly related to coordinating computer operations and performs tasks associated with controlling and utilizing computer hardware. These programs assist in running application programs and are designed to control the operation of a computer system. System software directs the computer what to do, when to do and how to do. System software can be further categorized into its memory. A user cannot communicate directly with the computer hardware, so the operating system acts as an interface between the user and the computer hardware.

### Operating System

An Operating system is the most important system software. It is a set of programs that control and supervise the hardware of a computer and also provide services to application software, programmers and users. It manages all hardware and software, input, output and processing activities within the computer system, the flow of information to and from the processor, sets priorities for handling different tasks, and so on. Without operating system a computer cannot do anything useful. When a computer is switched on, the operating system is the first program that is loaded onto its memory. A user cannot communicate directly with the computer hardware, so the operating system acts as an interface between the user and the computer hardware.
Some of the popular operating systems used in personal computers are DOS, Windows, Unix, Linux, Solaris, etc.
An operating system can be a Single User or a Multiuser operating system. A single user operating system allows only one user to work at any time but a multiuser operating system allows two or more users to use a powerful computer at the same time. For example Windows 7 is a single user operating system while Linux is a multiuser operating system.

### Need for an Operating System

Operating system provides a platform, on top of which, other programs, called application programs can run. As discussed before, it acts as an interface between the computer and the user. It is designed in such a manner that it operates, controls and executes various applications on the computer. It also allows the computer to manage its own resources such as memory, monitor, keyboard, printer etc.
Our choice of operating system, therefore, depends to a great extent on the CPU and the other attached devices and the applications we want to run. The operating system controls the various system hardware and software resources and allocates them to the users or programs as per their requirement.

### Functions of an Operating System

- Process Management: This deals with management of the Central Processing Unit (CPU). The operating system takes care of the allotment of CPU time to different processes. This is called **scheduling**. Two types of scheduling techniques are employed by an operating system:
  - **Priority Scheduling:** Each task is given CPU time according to the priority assigned to that task. The program with higher priority will be given CPU time before a program with lower priority. The CPU executes the task till it is completed or there is some interrupt request i.e. till the time operating system has to stop (interrupt) the current task due to an unavoidable job request. The major drawback of Priority scheduling is that even a small job has to wait for a long time when a long duration job with higher priority is being executed.
  - **Round Robin Scheduling:** This type of scheduling technique is also known as Time Sharing Scheduling. In this, each program or task is given a fixed amount of time to execute. The CPU continues with the execution till either the allotted time is over or there is some interrupt request or the task is completed before the allotted time. If the task is not completed at the end of the allotted time, it is put at the end of the queue. So each task gets its allotted share of CPU time. This scheduling technique improves the response time and provides an interactive environment. Hence time sharing operating system is very useful in network environment as each user is allowed to share the network resources.
- **Device Management:** The Operating System communicates with hardware and the attached devices and maintains a balance between them and the CPU. This is all the more important because the CPU processing speed is much higher than that of I/O devices. In order to optimize the CPU time, the operating system employs two techniques - Buffering and Spooling.
  - **Buffering:** In this technique the temporary storage of input and output data is done in Input Buffer and Output Buffer. Once the signal for input or output is sent to or from the CPU respectively, the operating system through the device controller moves the data from the input device to the input buffer and for the output device to the output buffer. When the signal is sent to/from the operating system to the respective device controllers, the program doesn’t wait rather it returns to its processing. In case of input, if the buffer is full, the operating system sends a signal to the program which processes the data stored in the buffer. When the buffer becomes empty, the program informs the operating system which reloads the buffer and the input operation continues. Similarly for output when the program being executed has to display some output, it fills the buffer and then informs the operating system. Thereafter the operating system empties the buffer by sending data to the output device and in the meantime the program fills another buffer. This technique is called **overlapped processing**. This is because while the operating system reloads one buffer, the executing program doesn’t stop as it is able to retrieve/fill data from/in another buffer.
  - **Spooling (Simultaneous Peripheral Operation on Line):** This is a device management technique used for processing of different tasks on the same input/output device. Say for example there are various users on a network sharing the same printer. At one point of time more than one user might give print command. The speed of the printer is very slow as compared to the CPU processing. So the operating system temporarily stores the data of every user on the hard disk of the computer to which the printer is attached. The individual users need not wait for the printing process to be complete. Instead the operating system sends the data from to hard disk to the printer one by one.
- **Memory management:** In a computer, both the CPU and the I/O devices interact with the memory. When a program needs to be executed it is loaded onto the main memory till the execution is complete. Thereafter that memory space is freed and is available for other programs. The common memory management techniques used by the operating system are Partitioning and Virtual Memory.
  - **Partitioning:** The total memory is divided into various partitions of same size or different sizes. This helps to accommodate number of programs in the memory. The partition can be fixed i.e. remains same for all the programs in the memory or variable i.e. memory is allocated when a program is loaded on to the memory. The later approach causes less wastage of memory but in due course of time, it may become fragmented.
  - **Virtual Memory:** This is a technique used by the operating system by virtue of which the user can load the programs which are larger than the main memory of the computer. In this technique the program is executed even if the complete program is not loaded on to the main memory. The operating system divides the main memory into equal sizes called pages. A part of the program resides in the main memory and is called the **active set.** The rest is in the secondary storage device in the form of tracks/sectors or blocks. With the help of **Page Map Tables (PMT)**, the operating system keeps track which page of main memory is storing which block of secondary memory. A virtual address (which is not the real physical address) is mapped either to the main memory or the secondary memory. Hence virtual memory allows more programs and even larger programs to be executed in the main memory leading to efficient memory utilization.
- **File Management:** The operating System manages the files, folders and directory systems on a computer. Any data on a computer is stored in the form of files and the operating system keeps information about all of them using **File Allocation** **Table (FAT).** The FAT stores general information about files like filename, type (text or binary), size, starting address and access mode (sequential/indexed sequential/direct/relative). The file manager of the operating system helps to create, edit, copy, allocate memory to the files and also updates the FAT. The operating system also takes care that files are opened with proper access rights to read or edit them.

### Types of Operating System

OS are classified into the following types depending on their capability of processing

##### Single User and Single Task OS

It is used on a standalone single computer for performing a single task. Operating systems for Personal Computers (PC) are single-user OS. Single user OS are simple operating system designed to manage one task at a time. MS-DOS is an example of single user OS.

##### Multiuser OS

Multiuser is used in mini computers or mainframes that allow same data and applications to be accessed by multiple users at the same time. The users can also communicate with each other. Linux and UNIX are examples of multiuser OS.

##### Multiprocessing OS

**Multiprocessing OS** have two or more processors for a single running process. Processing takes place in parallel and is also called _parallel processing_. Each processor works on different parts of the same task, or, on two or more different tasks. Since execution takes place in parallel, they are used for high speed execution, and to increase the power of computer. Linux, UNIX and Windows 7 are examples of multiprocessing OS.

##### Time sharing Operating System

It allows execution of more than one tasks or processes concurrently. For this, the processor time is divided amongst different tasks. This division of time is also called **time sharing**. The processor switches rapidly between various processes. After the stipulated time is over, the CPU shifts to next task in waiting, So this type of operating system employs **round robin** **scheduling technique.** The system switches rapidly from one user to another but still each user feels that it is getting a dedicated CPU time. Virtual Memory techniques are used in this type of operating system. For example, the user can listen to music on the computer while writing an article using a word processing software. The user can switch between the applications and also transfer data between them. Time sharing operating system can be both single user and multiuser. Windows 95 and all later versions of Windows are examples of multitasking OS.

##### Real Time Operating System

It is a multitasking operating system designed for real time applications like robotics. In this type of operating system, the tasks have to be done within a fixed deadline. System performance is good if task is finished within this deadline. If it is not done, the situation is called Deadline Overrun. Lesser the deadline over run, better is the system efficiency. Hence Real Time operating systems depend not only on the logical result of the computation but also on the time in which the results are produced.

##### Distributed Operating System

On a network data is stored and processed on multiple locations. The Distributed Operating System is used on networks as it allows shared data/files to be accessed from any machine on the network in a transparent manner. We can insert and remove the data and can even access all the input and output devices. The users feel as if all data is available on their workstation itself.

##### Interactive Operating System

This is the operating system that provides a Graphic User Interface (GUI) through which the user can easily navigate and interact. The computer responds almost immediately after an instruction has been entered, and the user can enter new instructions after seeing the results of the previous instructions.

### Commonly Used Operating Systems

1. **Windows:** Microsoft launched Windows 1.0 operating system in 1985 and since then Windows has ruled the world’s software market. It is a GUI (Graphic User Interface) and various versions of Windows have been launched like Windows 95, Windows 98, Win NT, Windows XP, Windows 7 and the latest being Windows 8.
2. **Linux:** Linux is a free and open software which means it is freely available for use and since its source code is also available so anybody can use it, modify it and redistribute it. It can be downloaded from www.linux.org. It is a very popular operating system used and supported by many companies. The defining component of this operating system is the Linux kernel.
3. **BOSS (Bharat Operating System Solutions):** This is an Indian distribution of GNU/Linux. It consists of Linux operating system kernel, office application suite, Bharateeya OO, Internet browser (Firefox), multimedia applications and file sharing.
4. **UNIX:** It is a multitasking, multiuser operating system originally developed in 1969 at Bell Labs. It was one of the first operating systems developed in a high level language, namely C. Due to its portability, flexibility and power, UNIX is widely being used in a networked environment. Today, ”UNIX” and "Single UNIX Specification" interface are owned and trademarked by The Open Group. There are many different varieties of UNIX, although they share common similarities, the most popular being GNU/Linux and Mac OS X.
5. **Solaris:** It is a free Unix based operating system introduced by Sun Microsystems in 1992. It is now also known as Oracle Solaris. Solaris is registered as compliant with Single UNIX Specification. It is quite scalable and is used on virtual machines.

### Mobile Operating Systems (Mobile OS)

It is the operating system that operates on digital mobile devices like smart phones and tablets. It extends the features of a normal operating system for personal computers so as to include touch screen, Bluetooth, WiFi, GPS mobile navigation, camera, music player and many more. The most commonly used mobile operating systems are – Android and Symbian

**Android:** It is a Linux derived Mobile OS released on 5th November 2007 and by 2011 it had more than 50% of the global Smartphone market share. It is Google’s open and free software that includes an operating system, middleware and some key applications for use on mobile devices. Android applications are quiet user friendly and even one can easily customize the Smartphone with Android OS. Various versions of Android OS have been released like 1.0, 1.5, 1.6, 2. x, 3.0 etc. Most Android phones use the 2.x release while Android 3.0 is available only for tablets. The latest Android version released is 4.2.2. The Android releases have dessert inspired codenames like Cupcake, Honeycomb, Ice Cream sandwich and Jelly Bean.

**Symbian:** This Mobile OS by Nokia (currently being maintained by Accenture) designed for smartphones. It offers high level of functional integration between communication and personal information management. It has an integrated mail box and it completely facilitates the usage of all Google applications in your smartphone easily. Symbian applications are easy to shut down as compared to Android applications. Various versions like S60 series, S80 series, S90 series, Symbian Anna etc have been released. The latest Symbian releases (Symbian Belle) can support 48 languages.

# Language Processors

We know that computer understands instructions in machine code, i.e. in the form of 0s and 1s. It is difficult for us to write computer program directly in machine code. The programs are written mostly in high-level languages, i.e. BASIC, C++, Python etc. A program written in any high-level programming language (or written in assembly language) is called the Source Program or Source Code.

The source code cannot be executed directly by the computer. The source code must be converted into machine language to be executed. The program translated into machine code is known as Object Program or Object code.

The special translator system software that is used to translate the program written in high-level language (or Assembly language) into machine code is called language processor or translator program.

The language processors can be any of the following three types - Assembler, Compiler and Interpreter.

##### Assembler

The Assembler is used to translate the program written in Assembly language into machine code. The input of Assembler is a source program that contains assembly language instructions. The output generated by assembler is the object code or machine code understandable by the computer.

##### Compiler

The language processor that translates the complete source program as a whole in one go into machine code is called compiler. Some of the examples are C and C++ compilers.
The program translated into machine code is called the object program. The source code is translated to object code successfully if it is free of errors. If there are any errors in the source code, the compiler specifies the errors at the end of compilation with line numbers. The errors must be removed before the compiler can successfully recompile the source code again.

##### Interpreter

The language processor that translates a single statement of source program into machine code and executes it immediately before moving on to the next line is called an Interpreter. If there is an error in the statement the interpreter terminates its translating process at that statement and displays an error message.
Only after removal of the error, the interpreter moves on to the next line for execution.

# Utilities

A utility software is one which provides certain tasks that help in proper maintenance of the computer. The job of utility programs is to keep the computer system running smoothly. Nowadays many utility softwares are part of the operating system itself. Even if there is no utility software on your computer, the computer works but with the right kind of utility software loaded, the computer becomes more reliable and even its processing speed increases. Some of the commonly use utility softwares are antivirus, Disk defragmenter, backup, compression etc.

## Antivirus

An antivirus is utility software which detects and removes computer viruses. If the software is not able to remove the virus, it is neutralized. The antivirus keeps a watch on the functioning of the computer system. If a virus is found it may alert the user, flag the infected program or kill the virus. Some of the common types of viruses are:

- **Boot Sector Virus:** A boot sector virus displaces the boot record and copies itself to the boot sector i.e. where the program to boot the machine is stored. So first the virus is loaded on to the main memory and then the operating system. Whenever a new disk is inserted the virus copies itself to the new disk. The antivirus overwrites the correct boot record on the infected boot sector and also cleans the bad sectors.
- **File Virus:** A file virus generally attacks executable files. They can attach to various locations of the original file, replace code, fill in open spaces in the code, or create companion files to work with an executable file. Most of the file viruses are memory resident and wait in the memory until the user runs another program. While another program is running, the virus replicates.
- **Macro Virus:** This virus infects an important file called normal.dot of MS Word. As soon as the application is opened the virus gets activated. It damages the formatting of documents and even may not allow editing or saving of documents.
- **Trojan Horse:** It is a code generally hidden in games or spreadsheets. Since they are hidden, the program seems to function as the user wants but actually it is destroying the program. A Trojan horse does not require a host program to embed itself. It is a complete program. Its main objective is to cause harm to the data. They can create bad sectors on the disk, destroy file allocation tables and cause the system to hang.
- **Worm:** Worm is a program capable of replicating itself on a computer network. A worm also does not require a host as it is a self contained program. They generally travel from one computer to another across communication links on a network. They generally disrupt routine services.

## Disk Defragmenter

The memory is used in small chunks randomly. Sometimes when a memory chunk of appropriate size is not available, the operating system breaks or fragments the files resulting in slower access to files. A disk defragmenter scans the hard disk for fragmented files and brings all the fragments together.

## Backup Utility

This utility is used to create the copy of the complete or partial data stored in a disk or CD on any other disk. In case the hard disk crashes or some other system failure occurs, the files can be restored using backup software.

## Compression Utility

This utility is used to compress large files. Compression is useful because it helps reduce resources usage and the file transmission on the network becomes easier.

## Disk Cleaner

This utility scans for file that have not been accessed/used since long. Such files might be occupying huge amount of memory space. In that case the Disk Cleaner utility prompts the user to delete such files so as to create more space on the disk. If the files are important, the user might take a backup before deleting them.

## File Management Tools

This utility helps the user in storing, indexing, searching and sorting files and folders on the system. The most commonly used tool is the Windows Explorer and Google Desktop.

# Application Software

An application software is bought by the user to perform specific applications or tasks, say for example making a document or making a presentation or handling inventory or managing the employee database. An application software can be of two types – General Purpose Application Software and Customized Application software.

## General Purpose Application Software

Some of the application software is made for the common users for day to day applications and uses. These are also referred as Office Tools. The users may use them in the manner they want. Some of the popular types of general purpose application software are discussed below:

- **Word Processor:** Word processor is a general purpose application software used to create documents. It allows us to create , edit and format documents. We can use different types of fonts of various sizes; underline or make bold a certain part of the text. We can add clipart and other graphics into the document. Popular examples of Word processing software are Writer (Open Office) and Microsoft Word. We use word processing software for various uses like writing a simple document to designing special art effects. Since we can attach images and different shapes, can use different colors, even a poster can be designed using word processing software. Features like Mail Merge, Macro has further enhanced the word processing software and made it very useful.
- **Presentation Tools:** Presentation tools is a general purpose application software that lets us create presentations on any topic. We can not only create a presentation and add slides into that but also can use different types of background, fonts, animations, audio, video, etc. We can add clipart and other graphics into our document. Even audio video files can be added on to the presentations. Popular examples of Presentation tools software are Impress (open office) and Microsoft Power Point.
- **Spreadsheet Packages:** Spreadsheet is a general purpose application software that lets us create and store data in tabular form. Both text and numerical values can be entered in that tables known as a spreadsheet. We can not only create a document and add data into that but also can create different types of charts and graphs based upon the numerical data stored in that page. All common mathematical and statistical formulae can be used on the numeric data. Popular examples of Spreadsheet software are Calc (Open Office) and Microsoft Excel.
- **Database Management System:** Database Management System is general purpose application software that lets us create computer programs that control the creation, maintenance, and the use of database for an organization and its end users. We can not only store data but can also manage data in a database. We can also import and export the data to many formats including Excel, Outlook, ASCII, dBase, FoxPro, Oracle, SQL Server, ODBC, etc. Popular examples of Database Management System are Base (Open Office) and Microsoft Access.

## Customized Software

Customized Software is one which is tailor made as per the user’s requirement. Such type of software is customer specific. It is made keeping in mind the individual needs of the user and so are also referred as Domain Specific Tools. Such software cannot be installed and used by any other user/customer since the requirements may differ. Some examples of customized software are discussed below:

- **Inventory Management System & Purchasing System:** Inventory Management System is generally used in departmental stores or other organizations to keep the record of the stock of all the physical resources. For Example, in a Computer store, it keeps record of the number of computers, printers, printing sheet, printer cartridge available. It also helps to place purchase orders, bills, invoices etc. Various reports as to position of stock, sales made in a particular period, profit earned etc. can be generated.
- **School Management System:** School Management System (sometimes called a School Information System or SIS) is a system that manages all of a school's data in a single, integrated application. Having all of the information in a single system allows schools to more easily connect data together. For example, when viewing a student’s record, the user can follow a link to the student’s class, and from there a link to the student’s teacher, and from there a link to the teacher's other classes, and so on.
- **Payroll System:** Payroll Management System software is used by all modern organizations to keep track of employees of the organization who receives wages or salary. All different payment amounts are calculated by the payroll software and the record is maintained. The software keeps track of personal records of employees viz. name, address, date of birth, qualification, date of joining etc. It also keeps track of professional record viz. allowances, perks, income tax, insurance etc. Different reports, pay slips etc can be generated through this software.
- **Financial Accounting:** Financial accounting System is used to prepare accounting information, maintain different accounts ledger, and account books. It also helps an organization to make budget.
- **Hotel Management**: Hotel management software refers to management techniques used in the hotel sector. These can include hotel administration, accounts, billing, marketing, housekeeping, front office or front desk, food and beverage management, catering and maintenance. Even advance bookings can be made through this software. Customers can have a look at the hotel and the rooms before making bookings. At any point of time the room availability, tariff for each type of room and even booking status can be checked.
- **Reservation System:** Reservation System is software used to book (reserve) air flights, railway seats, movie tickets, tables in a restaurant, etc. In the case of a booking system, the inputs are booking requests. The processing involves checking if bookings are possible, and if so making the bookings. The outputs are booking confirmations/rejections.
- **Weather Forecasting system:** This software makes it possible to forecast the weather for days and even months in advance. The detailed weather reports can also be generated.

# Open Source Concepts

Software are mainly categorized into the following categories based on their licenses:

1. Proprietary
2. Shareware
3. Freeware
4. Open Source
5. Free Software

## Proprietary

We pay a supplier for a copy of the software which these days may be supplied on physical media (disks) or downloaded from the Internet. We get the permission to use the software on one or sometimes more than one machines. Examples of this type of software include Microsoft Office and Microsoft Windows.

## Shareware

Shareware is basically a software for trial purpose that the user is allowed to try for free, for a specified period of time. It is usually downloaded from the Internet. When the trial period ends, the software must be purchased or uninstalled.

## Freeware

Freeware software is free of cost and is usually bundled up with some operating system or any other software. Examples of freeware include Microsoft Internet Explorer which comes bundled up with any Microsoft operating system. The author of the freeware software is the owner of the software, though people may use it for free. The source code is not available, so no modifications can be done. Freeware should not be mistaken with Open Source Software or Free Software.

## Open Source

Open Source Software (OSS) is the software which gives the users freedom to run/use the software for any purpose and in any manner. They can be used, modified and even redistributed. In simple terms it can be freely used but it may not be free of charge. The source code is freely available to the customer. Python, Tux Paint etc are examples of Open Source Software.

## Free Software

This type of software is freely accessible and can be freely used, modified, copied or distributed by anyone. And no license fee or any other form of payment need to be made for a free software. The source code is also accessible in case of free softwares.
