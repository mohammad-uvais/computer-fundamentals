# [[Input Unit]]

# [[Central Processing Unit (CPU)]]

# [[Memory Unit]]

# [[Output Unit]]

# Data Transfer between Functional Components

All the components of a computer — CPU, memory, and input/output devices — communicate with each other through a common pathway called a **bus**. A bus is a set of conducting wires over which data, addresses, or control signals are passed as electric signals from one component to another.

There are three types of buses:

1. The Address Bus carries the address of the memory location that the CPU wants to read from or write to.
2. The Data Bus carries data from one component to another.
3. The Control Bus carries control signals that coordinate and manage the operations of all components. Through the control bus, the CPU specifies whether a read or write operation is to be performed.
 
 All these three buses collectively make the system bus. The system bus is the common communication path that carries signals to/from CPU, main memory and input/output devices.

As the CPU interacts directly with main memory, any data entered from input device or the data to be accessed from hard disk needs to be placed in the main memory for further processing. The data is then transferred between CPU and main memory using bus.

The CPU places on the address bus, the address of the main memory location from which it wants to read data or to write data. While executing the instructions, the CPU specifies the read or write control signal through the control bus.

As the CPU may require to read data from main memory or write data to main memory, a data bus is bidirectional. But the control bus and address bus are unidirectional. To write data into memory, the CPU places the data on the data bus, which is then written to the specific address provided through the address bus. In case of read operation, the CPU specifies the address, and the data is placed on the data bus by a dedicated hardware, called memory controller. The memory controller manages the flow of data into and out of the computer's main memory. Input/output devices communicate with the system bus through a controller circuit, which helps manage the various devices attached to the computer.