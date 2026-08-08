# OSI MODEL – COMPLETE NOTES

## Introduction

The **OSI (Open Systems Interconnection) Model** is a conceptual framework that explains how data is communicated between computers over a network.

The OSI Model has **7 layers**. Each layer performs a specific function in network communication.

---

## OSI 7 Layers

| Layer | Name         | Data Unit | Main Function                        |
| ----- | ------------ | --------- | ------------------------------------ |
| 7     | Application  | Data      | Network services                     |
| 6     | Presentation | Data      | Translation, Encryption, Compression |
| 5     | Session      | Data      | Session management                   |
| 4     | Transport    | Segment   | End-to-end delivery                  |
| 3     | Network      | Packet    | Routing and IP addressing            |
| 2     | Data Link    | Frame     | MAC addressing and framing           |
| 1     | Physical     | Bits      | Signals and transmission             |

---

# Layer 7 – Application Layer

The **Application Layer** is the 7th and highest layer of the OSI Model.

It provides network services directly to applications.

### Functions

* Provides network services to applications.
* Supports web browsing, email, file transfer, etc.
* Allows applications to communicate over a network.

### Examples

* HTTP / HTTPS
* FTP
* SMTP
* DNS
* DHCP

### Simple Meaning

**Application Layer = Provides network services to applications.**

---

# Layer 6 – Presentation Layer

The **Presentation Layer** is responsible for the format and representation of data.

### Main Functions

1. **Translation**
2. **Encryption**
3. **Decryption**
4. **Compression**
5. **Decompression**

### Translation

Translation means converting data from one format or representation into another format that the receiving system can understand.

**Simple Meaning:**
**Translation = Converting data into a compatible format.**

### Encryption

Encryption means converting readable information into an encoded form to protect it from unauthorized access.

**Simple Meaning:**
**Encryption = Converting data into a secure, unreadable form.**

### Compression

Compression means reducing the size of data so that it requires less storage space or bandwidth.

**Simple Meaning:**
**Compression = Reducing data size.**

---

# Layer 5 – Session Layer

The **Session Layer** establishes, manages, and terminates communication sessions between applications.

### Functions

* Establishes sessions.
* Maintains sessions.
* Terminates sessions.
* Provides synchronization.
* Helps manage communication between applications.

### Simple Meaning

**Session Layer = Starts, manages, and ends communication sessions.**

---

# Layer 4 – Transport Layer

The **Transport Layer** provides end-to-end communication between applications running on different devices.

### Data Units

* TCP → **Segment**
* UDP → **Datagram**

### Main Functions

* **Segmentation**
* **Reassembly**
* **Flow Control**
* **Error Control**
* **Connection Management**
* **Port Addressing**

### Segmentation

Segmentation means dividing large data into smaller pieces.

**Large Data → Segment 1 + Segment 2 + Segment 3**

### Reassembly

Reassembly means combining the smaller pieces back into the original data at the destination.

**Segment 1 + Segment 2 + Segment 3 → Original Data**

### TCP

**TCP (Transmission Control Protocol)** is:

* Connection-oriented
* Reliable
* Provides sequencing
* Uses acknowledgments
* Can retransmit lost data

### UDP

**UDP (User Datagram Protocol)** is:

* Connectionless
* Faster
* Does not guarantee delivery
* Useful when speed is important

### Simple Meaning

**Transport Layer = Provides end-to-end delivery of data.**

---

# Layer 3 – Network Layer

The **Network Layer** is responsible for delivering packets from the source network to the destination network.

### Data Unit

**Packet**

### Main Functions

* **Routing**
* **IP Addressing**
* **Packet Forwarding**
* **Fragmentation**

### Routing

Routing means selecting a path for data to travel from source to destination.

### Address Used

**IP Address**

Example:

`192.168.1.10`

### Main Protocol

**IP – Internet Protocol**

### Simple Meaning

**Network Layer = Decides where data should go and which route it should take.**

---

# Layer 2 – Data Link Layer

The **Data Link Layer** provides communication between devices on the same local network or link.

### Data Unit

**Frame**

### Main Functions

* **Framing**
* **MAC Addressing**
* **Error Detection**
* **Flow Control**
* **Media Access Control**

### Framing

Framing means converting data into frames.

**Data → Frame**

### MAC Address

A **MAC Address** is a hardware-level address used to identify a network interface.

Example:

`00:1A:2B:3C:4D:5E`

### Simple Meaning

**Data Link Layer = Sends frames to the correct device on a local network.**

---

# Layer 1 – Physical Layer

The **Physical Layer** is responsible for transmitting raw bits through a physical medium.

### Data Unit

**Bits (0s and 1s)**

### Main Functions

* Converts bits into signals.
* Transmits signals through cables, fiber, or wireless media.
* Defines physical transmission characteristics.
* Handles physical connectors and media.

### Examples

* Ethernet cable
* Fiber-optic cable
* Radio waves
* Connectors
* Electrical signals
* Optical signals

### Simple Example

Data:

`10101010`

The Physical Layer converts these bits into physical signals and transmits them.

### Simple Meaning

**Physical Layer = Sends 0s and 1s as physical signals.**

---

# Important Networking Terms

## Protocol

A **protocol** is a set of rules that defines how devices communicate and exchange data.

**Example:** HTTP defines rules for communication between web browsers and web servers.

**Simple Meaning:**
**Protocol = Rules for communication.**

---

## Encryption

Converting readable data into an encoded form for security.

**Simple Meaning:**
**Encryption = Making data unreadable to unauthorized users.**

---

## Translation

Converting data from one format or representation into another compatible format.

**Simple Meaning:**
**Translation = Changing the data format.**

---

## Compression

Reducing the size of data.

**Simple Meaning:**
**Compression = Making data smaller.**

---

## Segmentation

Dividing large data into smaller pieces at the Transport Layer.

**Large Data → Small Segments**

---

## Reassembly

Combining the smaller segments back into the original data.

**Small Segments → Original Data**

---

## Routing

Selecting the best path for packets to reach their destination.

**Routing = Choosing the path for data.**

---

## Framing

Converting data into frames at the Data Link Layer.

**Data → Frame**

---

## Encapsulation

When data moves from the Application Layer down toward the Physical Layer, each layer adds its own information.

**Data → Segment → Packet → Frame → Bits**

---

## Decapsulation

At the receiving device, the process happens in reverse.

**Bits → Frame → Packet → Segment → Data**

---

# OSI Data Flow

### Sender

**Application**
↓
**Presentation**
↓
**Session**
↓
**Transport – Segment**
↓
**Network – Packet**
↓
**Data Link – Frame**
↓
**Physical – Bits**

### Receiver

**Bits**
↓
**Frame**
↓
**Packet**
↓
**Segment**
↓
**Data**

---

# Quick Revision

| Layer | Name         | Remember                             |
| ----- | ------------ | ------------------------------------ |
| 7     | Application  | Network Services                     |
| 6     | Presentation | Translation, Encryption, Compression |
| 5     | Session      | Session Management                   |
| 4     | Transport    | Segmentation, Reassembly, TCP, UDP   |
| 3     | Network      | Routing, IP                          |
| 2     | Data Link    | Framing, MAC                         |
| 1     | Physical     | Bits, Signals                        |

---

# Conclusion

The **OSI Model** divides network communication into seven layers. 
Understanding these layers makes it easier to learn networking, troubleshoot network problems, and understand how data travels from one device to another.

