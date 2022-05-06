# MALP

# Microprocessor and Assembly Language Processing

# Quick Access

- [Introduction to MicroProcessor](#introduction-to-microprocessor)

# Introduction to MicroProcessor

[Top](#quick-access)

## Table of Contents Chapter 1

1. [MicroProcessor](#microprocessor)
2. [MicroComputer](#microcomputer)
3. [MicroController](#microcontroller)
4. [Generation of Computer](#generations-of-computer)
5. [IC Fabrication Technology](#ic-fabrication-technology)
6. [History of Microprocessor](#history-of-microprocessor)
7. [I/O interfacing device](#io-interfacing-devices)
8. [Application of MicroProcessor](#application-of-microprocessor)
9. [Bus Structure of Microprocessor](#bus-organization--structure-of-a-microprocessor)
10. [Fetch Decode and Execute](#fetch-decode-execute-and-storage)

## MicroProcessor

- CPU of a digitial computer built into a single IC chip
  Introduction to Microprocessor:
- A MicroProcessor is a multipurpose, programmable, clock driven, register based electronic device that reads binary instructions from a storage device called memory, accepts binary data as input and processes data according to those instructions and provides result as output.
  ![Block Diagram](PicsReadMe/BlockDiagramOfMicroProcessor.png)

- The clock speed of a MP ranges from MHz to GHz.

## MicroComputer

: A computer having microprocessor as its CPU.

![Block Diagram](PicsReadMe/BlockDiagramOfMicroComputer.png)

## MicroController

: Entire computer built into a single IC chip.

- The advancement in the development of Semiconductor device (IC's) led to the invention of microcontroller.

- A microcontroller is a semiconductor device which is fabricated to include MPU, memory, I/O and other peripherals (USB,etc) within the same IC-Package.

- Clock Speed is in the range of MHz

- It is used for specific purpose
  ![BlockDiagram](PicsReadMe/BlockDiagramOfMicroController.png)

## Generations of computer

<table border=1>
<tr><th>Generation</th><th>Main Features</th></tr>
<tr><td>1</td><td>Vacuum Tubes</td></tr>
<tr><td>2</td><td>Transitors</td></tr>
<tr><td>3</td><td>IC Chip/ LSI </td></tr>
<tr><td>4</td><td>MP/VLSI/ULSI </td></tr>
<tr><td>5</td><td>AI/Bio-chips </td></tr>
</table>

## IC Fabrication Technology

| IC   | Full Form               | No of gates/chips |
| ---- | ----------------------- | ----------------- |
| SSI  | Smale Scale Integration | Upto 10           |
| MSI  | Medium                  | 10-100            |
| LSI  | Large                   | 100-1000          |
| VLSI | Very Large              | 1000-100000       |
| ULSI | Ultra Large             | >100000           |

## History of Microprocessor

- First one is 4004 - 4 bit.
- 8008 - 8 bit.
- 8085 - 8 bit most popular.
- 8086 - 16 bit upgraded vesrion of 8085.
- 8088 - 16 bit first used in IBM computers.

- Currently using, Intel i7 11th Gen

## I/O Interfacing Devices

- Consider the block diagram of a computer system

![Block Diagram](PicsReadMe/BlockDiagramOfComputer.png)

- The input devices maybe Electro Mechanical in nature
- The output devices also maybe Electro Mechanical in Nature.

- But the CPU and Primary Memory are Electronic in nature.
- Thus we need some sort of interface to translate and the device we use for this are called input output interfacing device.

## Application of MicroProcessor

- Re-Programmable system, microprocessor is used as a computing unit.

- Embedded System, MP is part of the final product and is not available for end user. eg. Traffic light Control system.

Some of them are:

- Microcontroller
- Industrial Controls
- Robotics
- Medical Machine
- Washing Machine
- Traffic Light control system,etc

## Bus Organization / Structure of a MicroProcessor

![Block Diagram](PicsReadMe/BusStructutreOfMicroProcessor.png)

- A bus is a path or group of wires thorough which data and information (bits) travels.
- It is an electronic path through which binary bits of data flow takes place.
- It consits of

1. Address Bus
   - Address bit travels
   - Multiple of 4
   - Total addressable memory for 'n' bits is 2<sup>n</sup>.
   - unidirectional
2. Data Bus
   - that carries data
   - indicates the data bit capacity of a MP
   - Bidirectional
   - It may be 4-bit, 8-bit, 16-bit, 32-bit, 64-bit or 128-bit.
3. Control Bus
   - That carries control signals
   - The width of a bus depends upon the types of control signals used.
   - Control signals maybe memory read, memory write, I/O read, I/O write.

## Fetch Decode Execute and Storage

![Fetch Diagram](PicsReadMe/FetchDecodeExecute.png)

1. Fetch Operations

- In this operation instruction code and data from storage is loaded into the microprocessor.

2. Decode Operations

- Once the MPU gets the required data and instruction code, it uses the CU (Control Unit) to divide the information into a set of operations.

3. Execute Operations

- The operations divided by the CU are now executed by the ALU (Arithmetic and Logic Unit) and passed to the Storage(Memory).

4. Storage

- It stores data and/or instruction code.
