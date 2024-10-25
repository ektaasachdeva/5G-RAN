# 5G-RAN
Let's get to know about how actually the 5G works and transfers date from one device to another. 

**5G Technology** 

This repository contains comprehensive information about 5G technology, including its architecture, components, and processes. The content is organized into several sections, each focusing on a specific aspect of 5G.

**Table of Contents**

 Introduction to 5G
 
5G Radio Access Network (RAN)
  
User Equipment (UE)
 
Application Server (AS)
 
5G Core Network
 
Data Transfer Process
 
Reference Points and Service-Based Architecture
  
Control Plane and User Plane
  
Machine-Type Communication (MTC)
 
Key Network Areas and Functions
	
Wireless Connectivity
	
Massive MIMO and Beamforming

**Introduction to 5G** 

5G is the fifth generation of cellular network technology designed to fulfill and establish higher data and connectivity requirements from modern society. It gives far superior capabilities compared with previous generations in terms of speed, capacity, latency, and flexibility.The 3 factors of 5G we have already done in the previous repository, Now let's explore the procedure 5G follows.

![image alt](![image 1](https://github.com/user-attachments/assets/0a44c432-1e67-4d5a-ac43-37ab3f4fbf1a)



**5G Radio Access Network (RAN)**

The 5G radio access network, or RAN, is the part of the 5G network connecting users' equipment to the core network. It is classified into some kinds of base stations: gNodeB in 5G.

**Key components of 5G RAN:**

•  gNodeB (gNB): Base station in 5G

•  Distributed Unit (DU): Manages real-time functions

•  Centralized Unit (CU): Manages non-real-time functions

•  Radio Unit (RU): Conducts radio frequency processing

![image alt]![image 2](https://github.com/user-attachments/assets/f6a4c6a8-6519-4a73-970a-68f83ba66605)


**User Equipment (UE**)

Any equipment, used by the UE for communication over a 5G network, is called UE. This includes smartphones, tablets, IoT devices, and all connected ones.

Main characteristics of UE over 5G:

•Improve capabilities so that high data rates are achieved

•Multi-frequency bands support

•Power consumption is enhanced

•Provide advanced antenna systems for beamforming

 
![image alt]![image 3 1](https://github.com/user-attachments/assets/28cabae1-4156-4547-a633-75a743badcf7)


**Application Server (AS)**

The Application Server (AS) is the functional layer of the 5G protocol stack that performs all functions relevant to the radio interface between the UE and RAN.

Main functions of AS:
•RRC
•PDCP
•RLC
•MAC
•PHY


![image alt]![image 4 1](https://github.com/user-attachments/assets/6e5cc154-f8f7-4a17-9382-2fc76cbcc46e)


**5G Core Network**

5G Core Network is the central element of a 5G system. It provides fundamental features, consisting of authentication, mobility management, and session management.

The key elements of the 5G Core are:

_•Access and Mobility Management Function (AMF)_

It is responsible for managing user registration, authentication, and mobility across the network, ensuring that devices maintain connectivity as users move between different network cells.

_•Session Management Function (SMF)_

It manages data session setup and modification, including IP address assignment and handling PDU sessions for efficient data communication.

_•User Plane Function (UPF)_

The UPF routes user data between the RAN and external networks, ensuring efficient data transmission and traffic management.

_•Network Slice Selection Function (NSSF)_

It is a key component responsible for selecting the appropriate network slice for a device or service. A network slice  is a virtual segment of a network dedicated to a specific type of service or application, allowing the network to meet diverse requirements for different use cases, such as enhanced mobile broadband, URLLC, or massive IoT.


_•Policy Control Function (PCF)_

The PCF applies and enforces network policies, such as QoS management, based on user profiles and service requirements.

_•Unified Data Management (UDM)_

UDM stores and manages subscriber data, including user profiles, authentication information, and  subsription details, ensuring secure access to services.


![image alt]![image 5 2](https://github.com/user-attachments/assets/27273f95-249f-44b7-9add-91c72f8cb13c)


**Data Transfer Process**

Data transfer from the UE to the external network in 5G follows a series of steps: (Overall at high level)

 -The UE establishes a connection to gNodeB
 
 -The gNodeB authenticates the UE with the support of AMF
 
 -SMF has established a data session
 
 -UPF routes the actual data
 
 -gNodeB transfers data back to the UE
 

![image alt]![image 6 4](https://github.com/user-attachments/assets/7461c49d-37d1-4f57-bc07-6218984d0103)


**Essential Points and Service-Based Architecture**

The core part of the 5G network uses a service-based architecture (SBA) unlike the previous generations, which had been utilizing reference point architecture.

**Points to note**

• The network functions are interconnected by service-based interfaces

• Enhances network configuration to be flexible and scalable

• Has introduced network slicing and edge computing


![image alt]![image 7](https://github.com/user-attachments/assets/61eca495-5403-4934-ac3a-f1220ea37a38)


**Control Plane and User Plane**

In 5G networks, the control plane and user plane are separated. Thus, the function increases flexibility and scalability
Control Plane

• Signaling and control functions

• It controls connections, mobility and sessions

**User Plane:**

• It is involved in the actual data transmission

•It controls forwarding and quality of service enforcement


![image alt]![image 8](https://github.com/user-attachments/assets/123f96ae-12e8-4bba-99e1-8cfa3ae32df7)


**Machine-Type Communication (MTC)**

MTC is a form of data communication between machines that does not need any human involvement. 5G has strengthened MTC or eMTC in order to provide more IoT connectivity.

**Key features of MTC in 5G**

•Millions of devices support

•Power consumption is low

•Extended coverage

•Latency for mission-critical applications


![image alt]![images 9 5](https://github.com/user-attachments/assets/83325aa9-48aa-4db0-b045-83140203856b)


**Important Network Areas and Functions**

There are some key areas and functions which are built into 5G networks to support use cases with advanced capabilities.

•  Network Slicing allows multiple virtual networks to exist on a single piece of physical infrastructure

•  Edge Computing moves computing resources closer to the end-user to reduce latency

•  NFV enables flexible deployment of network functions

•  SDN enables programmable network control


![image alt]![image 10 2](https://github.com/user-attachments/assets/7baf50aa-4ecc-46ea-96ad-ce5495bc2111)


**Wireless Connectivity**

5G brings advanced wireless connectivity by means of:

-Higher frequency bands (mmWave) with a wider bandwidth

-Increased spectral efficiency

-More advanced modulation and coding schemes

-Aggregated carriers in order to yield a high data rate

**Massive MIMO and Beamforming**
Massive MIMO and beamforming are two of the important technologies in 5G:

_**Massive MIMO**_: Using a large number of antennas increases capacity and energy efficiency.

**• Beamforming:** Focuses the radio wave on one of the users to have good quality and low interference



