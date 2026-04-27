The electronic components of a computer system that we can see and touch are called hardware.

## Functional Components of a Computer

Every task given to a computer follows an Input-Process-Output Cycle (IPO cycle). It needs certain input, processes that input and produces the desired output. The input unit takes the input, the central processing unit does the processing of data and the output unit produces the output. The memory unit holds the data and instructions during the processing.

### Input Unit

The input unit consists of input devices that are attached to the computer. Input devices send control signals to a computer. These devices take input and convert it into binary language that the computer understands. Some examples of input devices include keyboard, mouse, scanner, touch screen, etc. Besides, we can now enter data through voice, for example, we can use Google voice search to search the web where we can input the search string through our voice.

Data entered through input device is temporarily stored in the main memory (also called RAM) of the computer system. For permanent storage and future use, the data as well as instructions are stored permanently in additional storage locations called secondary memory.

### Central Processing Unit (CPU)

It is the electronic circuitry of a computer that carries out the actual processing and usually referred as the brain of the computer. Physically, a CPU can be placed on one or more microchips called integrated circuits (IC). The ICs comprise semiconductor materials. As the CPU is located on a small chip, it is also called the microprocessor and commonly called processor.

Once the information is entered into the computer by the input device, the processor processes it. It first fetches instructions from memory and then interprets them so as to know what is to be done. If required, data is fetched from memory or input device. Thereafter CPU executes or performs the required computation and then either stores the output or displays on the output device. The CPU has three main components which are responsible for different functions – Arithmetic Logic Unit (ALU), Control Unit (CU) and Memory Registers.

#### Arithmetic Logic Unit

The ALU, as its name suggests performs mathematical calculations and takes logical decisions as per the instruction in a program. Arithmetic calculations include addition, subtraction, multiplication and division. Logical decisions involve comparison of two data items to see which one is larger or smaller or equal.

#### Control Unit

The Control unit coordinates and controls the data flow in and out of CPU and also controls all the operations of ALU, memory registers and also input/output units. It is also responsible for carrying out all the instructions stored in the program. It decodes the fetched instruction, interprets (understands) it and sends control signals to input/output devices until the required operation is done properly by ALU and memory.

#### Memory Registers

A register is a temporary unit of memory in the CPU. These receive data/information and then this data/information is held in them as per the requirement. Registers can be of different sizes (16 bit, 32 bit, 64 bit and so on) and each register inside the CPU has a specific function like storing data, storing an instruction, storing address of a location in memory etc. The user registers can be used by an assembly language programmer for storing operands, intermediate results etc. Accumulator (ACC) is the main register in the ALU and contains one of the operands of an operation to be performed in the ALU.

### Memory Unit

A computer system needs memory to store the data and instructions for processing. Whenever we talk about the 'memory' of a computer system, we usually talk about the main or primary memory. The secondary memory (also called storage device) is used to store data, instructions and results permanently for future use.

#### Types of Memory

##### (A) Primary Memory

The CPU interacts directly with the primary memory to perform read or write operation. It is of two types viz. (i) Random Access Memory (RAM) and (ii) Read Only Memory (ROM).

RAM is divided into many storage locations, each of which can store data or instructions. Each memory location is of the same size and has an address. With the help of the address, the computer can find any data easily without having to search the entire memory. The time of access of data is independent of its location in memory, that is why this memory is called Random Access Memory (RAM). RAM is volatile in nature. That means when the power is switched off, the data stored in this memory is permanently erased. Whenever the computer is started or a software application is launched, the required program and data are loaded into RAM for processing. When the task is performed, the CU makes the space available for storing data and instructions, thereafter the memory is cleared and the memory space is then available for the next task. It is used to store data temporarily while the computer is working. That is why secondary memory is needed to store data and information permanently for later use. RAM is usually referred to as main memory and it is faster than the secondary memory or storage devices.

ROM is non-volatile, which means its contents are not lost even when the power is turned off. It is used as a small but faster permanent storage for the contents which are rarely changed. For example, the startup program (boot loader) that loads the operating system into primary memory, is stored in ROM.

##### (B) Cache Memory

RAM is faster than secondary storage, but not as fast as a computer processor. So, because of RAM, a CPU may have to slow down. To speed up the operations of the CPU, a very high speed memory is placed between the CPU and the primary memory known as _cache_. It stores the copies of the data from frequently accessed primary memory locations, thus, reducing the average time required to access data from primary memory. When the CPU needs some data, it first examines the cache. In case the requirement is met, it is read from the cache, otherwise the primary memory is accessed.

##### (C) Secondary Memory

Primary memory has limited storage capacity and is either volatile (RAM) or read-only (ROM). Thus, a computer system needs auxiliary or secondary memory to permanently store the data or instructions for future use. The secondary memory is non-volatile and has larger storage capacity than primary memory. It is slower and cheaper than the main memory. But, it cannot be accessed directly by the CPU. Contents of secondary storage need to be first brought into the main memory for the CPU to access. Examples of secondary memory devices include Hard Disk Drive (HDD), Memory Card, etc. However, these days, there are secondary storage devices like SSD which support very fast data transfer speed as compared to earlier HDDs. Also, data transfer between computers have become easier and simple due to the availability of small-sized and portable flash or pen drives.

#### Units of Memory

A computer system uses binary numbers to store and process data. The binary digits 0 and 1, which are the basic units of memory, are called bits. Further, these bits are grouped together to form words. A 4-bit word is called a Nibble. Examples of nibble are 1001, 1010, 0010, etc. A two nibble word, i.e., 8-bit word is called a byte, for example, 01000110, 01111100, 10000001, etc.

### Output Unit

The output unit consists of output devices that are attached with the computer. Output device receives data from a computer system for display, physical production, etc. It converts the binary data coming from CPU to human understandable form. The common output devices are monitor, printer, projector, headphone, speaker, etc.

### Data Transfer between Functional Components

As we have seen before that a computer consists of input unit that takes input, a CPU that processes the input and an output unit that produces output. All these devices communicate with each other through a common bus. A bus is a transmission path (set of physical conducting wires) over which data or information in the form of electric signals, is passed from one component to another in a computer. The bus can be of three types – Address bus, Data bus and Control Bus.

The address bus carries the address location of the data or instruction between CPU and main memory. The address of the memory location that the CPU wants to read or write from is specified in the address bus. The data bus carries data from one component to another, and the control bus communicates control signals between different components of a computer. All these three buses collectively make the system bus. The system bus is the common communication path that carries signals to/from CPU, main memory and input/output devices.

As the CPU interacts directly with main memory, any data entered from input device or the data to be accessed from hard disk needs to be placed in the main memory for further processing. The data is then transferred between CPU and main memory using bus. The CPU places on the address bus, the address of the main memory location from which it wants to read data or to write data. While executing the instructions, the CPU specifies the read or write control signal through the control bus.

As the CPU may require to read data from main memory or write data to main memory, a data bus is bidirectional. But the control bus and address bus are unidirectional. To write data into memory, the CPU places the data on the data bus, which is then written to the specific address provided through the address bus. In case of read operation, the CPU specifies the address, and the data is placed on the data bus by a dedicated hardware, called memory controller or controller circuit. The memory controller manages the flow of data into and out of the computer's main memory.