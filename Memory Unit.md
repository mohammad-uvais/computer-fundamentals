Memory is one of the most important components of a computer system. It is used to store data and instructions — both during and after processing. Without memory, the computer would have nowhere to hold the data it is working with or the results it has produced.

The computer memories can be divided into three categories:

- Primary Memory
- Secondary Memory
- Cache Memory

But before we get into the types of memory, it is important to understand the units in which memory is measured.

## Units of Memory

The smallest unit of memory is a **bit**, which stands for binary digit. A bit can hold only one of two values — either 0 or 1. A collection of 4 bits is called a **nibble**. Eight bits combined together form a single **byte**, which can represent a single character such as a letter, a digit, or a symbol.

All higher units of memory are based on powers of 2 — specifically, every higher unit is 2¹⁰ (which equals 1024) times the previous unit.

|Unit|Symbol|Equivalent|
|---|---|---|
|Kilobyte|KB|1024 Bytes|
|Megabyte|MB|1024 KB|
|Gigabyte|GB|1024 MB|
|Terabyte|TB|1024 GB|
|Petabyte|PB|1024 TB|
|Exabyte|EB|1024 PB|
|Zettabyte|ZB|1024 EB|
|Yottabyte|YB|1024 ZB|

## Primary Memory

**Primary memory**, also called **main memory**, is a Metal Oxide Semiconductor (MOS) memory that stores the program and data currently being executed. It is directly accessible to the CPU — meaning the CPU can read from and write to it without any intermediate step.

Primary memory is organized into a large number of small storage locations called **words**. All words in a given memory are of the same fixed length. This length — measured in bits — is called the **word length**. Computers with word lengths of 8, 16, 24, 32, and 64 bits are available, and the higher the word length, the more powerful the computer.

Each word is assigned a unique **address**, starting from 0 up to the largest number that the computer can support. When the CPU needs a particular piece of data or instruction, it directly goes to that address without having to search through the entire memory. The total number of memory locations that can be addressed depends on how many address lines are present in the address bus. If there are n address lines, then 2ⁿ memory locations can be addressed.

Primary memory can be of two types — **RAM** (Random Access Memory) and **ROM** (Read Only Memory).

### RAM — Random Access Memory

In RAM, any memory location can be accessed directly and in the same amount of time, regardless of where it is located. This is what "random access" means — the CPU does not need to go through the memory in a sequence to find what it needs.

RAM is a **read/write memory**, which means data can both be read from it and written to it. It is also **volatile**, which means all its contents are lost the moment the power is switched off or interrupted. Nowadays, RAMs are available in gigabytes and have a normal memory access time of 20 to 80 nanoseconds.

RAM is broadly classified into two types — **DRAM** and **SRAM**.

**Dynamic RAM (DRAM)** stores each bit using a transistor and a capacitor that holds an electric charge. However, a capacitor tends to lose its charge over time, so the data stored in DRAM needs to be continuously refreshed. Each refresh operation takes several CPU cycles to complete, which makes DRAM slower. Despite being slower, DRAMs are physically smaller and cheaper to produce, which is why they are widely used as primary storage. DRAM is available in various forms such as EDORAM (Extended Data Output RAM), SDRAM (Synchronous DRAM), and DDR SDRAM.

**Static RAM (SRAM)** stores each bit using a circuit called a **flip-flop**, which holds its state without needing any refreshing as long as power is supplied. This makes SRAM significantly faster than DRAM. However, SRAM is physically larger and considerably more expensive. It is therefore used only in specialized applications where speed is critical — most notably in cache memory, which we will read about shortly. Like DRAM, SRAM is also volatile.

### ROM — Read Only Memory

As the name suggests, a **ROM** is a type of memory from which data can only be read — it cannot be written to during normal operation. The contents of a ROM are written by the manufacturer at the time of production and cannot be changed thereafter. Unlike RAM, ROM is **non-volatile**, which means its contents remain intact even when the power is switched off.

ROMs are used in applications where the stored information does not need to be changed. They hold essential instructions such as those needed to start the computer. Because they cannot be written to accidentally, they are safe for storing critical system instructions.

ROM is available in several types that offer progressively more flexibility:

**PROM (Programmable Read Only Memory)** can be programmed even after it has been manufactured, using a special device called a PROM programmer circuit. However, once a PROM has been programmed, it behaves exactly like a regular ROM — its contents are fixed and cannot be changed again.

**EPROM (Erasable Programmable Read Only Memory)** goes one step further — its contents can be erased and the memory can then be reprogrammed. To erase the data, an EPROM chip is exposed to ultraviolet (UV) light, after which it can be reprogrammed using a PROM programmer circuit. While in normal use, an EPROM behaves just like a ROM and its data can only be read.

**EEPROM (Electrically Erasable Programmable Read Only Memory)** allows its contents to be erased and reprogrammed using ordinary electric signals, without needing UV light or any special device. This makes it very practical. One important use of EEPROM is as a backup for RAM — since RAM loses all its contents when power is cut, the EEPROM can hold a copy of that data. When power is restored, the contents of the EEPROM are copied back into RAM and the computer continues working without any data loss. Nowadays, RAMs and EEPROMs are sometimes integrated together on a single chip.

## Cache Memory

We know that the processing speed of the CPU is much faster than the speed at which it can access data from the main memory (RAM). This speed mismatch means the CPU often ends up waiting for data to arrive from RAM, wasting valuable processing time.

To solve this problem, a special high-speed memory called **cache memory** is placed between the CPU and the main memory. Cache memory is made up of **high-speed SRAM** — which is why it is much faster than the DRAM-based main memory, but also smaller and more expensive.

The CPU first looks for required data in the cache memory. If the data is found there, it is called a **cache hit** and the data is transferred to the CPU immediately. If the data is not found in cache, it is called a **cache miss**, and the CPU then goes to the main memory to fetch it.

Cache memory proves to be very effective because most programs tend to repeatedly access the same data and instructions. Once that data is stored in cache, subsequent accesses become very fast.

Cache memory is of three types:

- **L1 Cache** — It is the smallest and the fastest cache. It is built directly inside the CPU chip and is the first place the CPU looks for data.
- **L2 Cache** — It is larger in size but slightly slower than L1. It is mounted on the motherboard, outside the CPU, and acts as a second level of lookup if the data is not found in L1.
- **L3 Cache** — It is even larger in size but slower than L2. It is shared among all the cores of a CPU and serves as a common pool of fast memory that all cores can access. It acts as the last level of cache before the CPU has to go all the way to the main memory (RAM).

## Secondary Memory

The main limitation of primary memory is that it has limited storage capacity and is volatile — all data is lost when power is turned off. **Secondary memory** exists to overcome both of these limitations.

Secondary memory, also called **external memory**, refers to the various storage media on which a computer can store data and programs permanently. It is not a part of the main computer and is not directly accessible to the CPU — data from secondary memory must first be brought into primary memory (RAM) before the CPU can process it.

Secondary storage media can be of two kinds. **Fixed storage media** is an internal storage medium like a hard disk that is fixed inside the computer. **Removable storage media** is portable and can be taken outside the computer — for example, CDs, DVDs, and pen drives.

### Why Do We Need Secondary Memory?

Secondary memory is needed for two main reasons:

**For permanence** — Since RAM is volatile and loses all data when power is switched off, secondary storage devices serve the purpose of storing data permanently. They do not lose data when electricity is turned off.

**For portability** — Secondary storage devices like CDs and flash drives can be used to carry data from one computer to another.

### Types of Secondary Storage Media

Secondary storage media are of three main types — Magnetic, Optical, and Solid State.

#### Magnetic Storage Media

Magnetic storage media store data by magnetizing a magnetic sensitive layer on their surface. This layer is magnetized in either a clockwise or counterclockwise direction, which is then read and interpreted as binary 1 or binary 0.

**Floppy Disk** is a flexible disk made of mylar with a magnetic coating, packaged inside a protective plastic envelope. It was one of the earliest portable storage devices and could store up to 1.44 MB of data. Floppy disks are no longer in use.

**Hard Disk** consists of one or more circular disks called **platters** mounted on a common spindle. Each surface of a platter is coated with a magnetic material. Both surfaces of each platter are capable of storing data, except the outermost top and bottom surfaces. Data is recorded on the rotating platters by magnetic **read/write heads** that are attached to a common arm called the **access arm**, which moves over the surface of the disks. Information is stored on each platter in the form of concentric circles called **tracks**, which are further divided into smaller sections called **sectors**. Hard disks are not easily portable and are primarily used internally inside the computer, though external hard disks are also available. Today, hard disks have storage capacities of several gigabytes to terabytes.

#### Optical Storage Media

On optical storage media, information is stored and read using a **laser beam**. Data is stored as a spiral pattern of **pits** (small indentations) and **ridges** (raised areas) on the surface of the disk, where pits denote binary 0 and ridges denote binary 1.

**Compact Disk (CD)** can store approximately 650 to 700 MB of data. The data is encoded as transitions between pits and ridges in a spiral pattern on a polycarbonate disc. To read the data, an infrared laser beam is directed at the disc — pits scatter the light while ridges reflect it, and these differences in the reflected beam are translated back into 0s and 1s. CDs are available in three types:

- **CD-ROM (Compact Disk — Read Only Memory)** — Data is written at the time of manufacture and cannot be changed. It can only be read. Used for distributing software, games, encyclopedias, audio and video.
- **CD-R (Compact Disk — Recordable)** — Data can be recorded on it, but only once. After that, the data cannot be erased or modified.
- **CD-RW (Compact Disk — Rewritable)** — Data can be read and written multiple times. A CD-RW drive must be installed on the computer.

**DVD (Digital Versatile Disk or Digital Video Disk)** looks similar to a CD and works on the same technology but uses a shorter-wavelength red laser that allows tracks to be spaced more closely together. This enables it to store more than six times the capacity of a CD. A DVD holds 4.7 GB to 17 GB of data. DVDs consist of two half-thickness (0.6 mm) CD-like discs glued back-to-back, which protects the reflective coating and also makes double-sided DVDs possible — where data can be stored on both halves. Like CDs, DVDs also come in three varieties — DVD-ROM, DVD-R, and DVD-RW.

**Blu-ray Disk (BD)** is the most advanced optical storage media currently available, designed for storing high-definition audio and video. It looks like a CD or DVD but uses a **blue laser** instead of a red one. Because the blue laser has a shorter wavelength, the beam can be focused with greater precision, allowing data to be packed more tightly on the disc. A single-layer Blu-ray disc can store up to 27 GB of data, while a dual-layer disc can store up to 54 GB.

#### Solid State Memories

Solid-state storage devices have **no moving parts** — no spinning discs, no reels of tape, no laser beams. They store data using a special type of memory called **flash memory**.

**Pen Drives**, also known as thumb drives or flash drives, are portable storage devices based on **EEPROM-based flash memory**, which can be repeatedly erased and rewritten using electric signals. A USB connector is built into the pen drive through which it can be plugged directly into a computer. Pen drives are smaller in capacity than a hard disk but larger than a CD, and they are the most widely used removable portable storage today.