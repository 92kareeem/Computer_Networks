# Computer_Networks

1. *server.c*
   
   Program to implement connection oriented and connectionless client for well known service standard ports
   
![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/576c7331-a3ab-47be-a143-f64f4f0a467a)

2. *client.c*


   ![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/641d74bc-3e81-4830-8847-3f1d0f84f931)

# What is Computer Network?

**A computer network** is a set of devices connected through links. **A node** can be a computer, printer, or any other device capable of sending or receiving data. The links connecting the nodes are known as communication channels.

**Computer networks** use distributed processing in which tasks are divided among several computers. Instead of a single computer handling an entire task, each separate computer handles a subset.


# Introduction to Computer Networks

**Computer Network** is a group of computers connected with each other through wires, optical fibers, or optical links so that various devices can interact with each other through a network. The aim of the computer network is the sharing of resources among various devices.

In the case of computer network technology, there are several types of networks that vary from simple to complex levels.

## Components of Computer Network:

   ![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/42141c86-b5ef-4417-906a-517e24b37ae4)


### NIC (Network Interface Card)

**NIC** is a device that helps the computer to communicate with another device. The network interface card contains the hardware addresses; the data-link layer protocol uses this address to identify the system on the network so that it transfers the data to the correct destination.

There are two types of NIC: wireless NIC and wired NIC.

- **Wireless NIC:** All the modern laptops use the wireless NIC. In Wireless NIC, a connection is made using the antenna that employs radio wave technology.
- **Wired NIC:** Cables use the wired NIC to transfer the data over the medium.

### Hub

**Hub** is a central device that splits the network connection into multiple devices. When a computer requests information from a computer, it sends the request to the Hub. Hub distributes this request to all the interconnected computers.

### Switches

**Switch** is a networking device that groups all the devices over the network to transfer the data to another device. A switch is better than Hub as it does not broadcast the message over the network; it sends the message to the device for which it belongs to. Therefore, we can say that the switch sends the message directly from source to the destination.

### Cables and Connectors

**Cable** is a transmission media that transmits the communication signals. There are three types of cables:

- **Twisted pair cable:** It is a high-speed cable that transmits the data over 1Gbps or more.
- **Coaxial cable:** Coaxial cable resembles like a TV installation cable. Coaxial cable is more expensive than twisted pair cable, but it provides high data transmission speed.
- **Fiber optic cable:** Fiber optic cable is a high-speed cable that transmits the data using light beams. It provides high data transmission speed as compared to other cables. It is more expensive as compared to other cables, so it is installed at the government level.

### Router

**Router** is a device that connects the LAN to the internet. The router is mainly used to connect the distinct networks or connect the internet to multiple computers.

### Modem

**Modem** connects the computer to the internet over the existing telephone line. A modem is not integrated with the computer motherboard. A modem is a separate part on the PC slot found on the motherboard.

## Uses of Computer Network

- **Resource sharing:** Resource sharing is the sharing of resources such as programs, printers, and data among the users on the network without the requirement of the physical location of the resource and user.
- **Server-Client model:** Computer networking is used in the server-client model. A server is a central computer used to store the information and maintained by the system administrator. Clients are the machines used to access the information stored on the server remotely.
- **Communication medium:** Computer network behaves as a communication medium among the users. For example, a company contains more than one computer has an email system which the employees use for daily communication.
- **E-commerce:** Computer network is also important in businesses. We can do the business over the internet. For example, amazon.com is doing their business over the internet, i.e., they are doing their business over the internet.

Features Of Computer network

A list Of Computer network features is given below.

![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/7c2781a5-e08c-4adb-aafb-2575a33c1cff)

# Additional Benefits of Computer Networks

## Communication Speed

**Networks** provide us with the ability to communicate over the network in a fast and efficient manner. For example, we can do video conferencing, email messaging, etc., over the internet. Therefore, the computer network is a great way to share our knowledge and ideas.

## File Sharing

**File sharing** is one of the major advantages of computer networks. Computer networks provide us with the ability to share files with each other.

## Easy Backup and Rollback

Since the files are stored on the main server, which is centrally located, it is easy to take backup from the main server.

## Software and Hardware Sharing

We can install applications on the main server, therefore, users can access the applications centrally. So, we do not need to install the software on every machine. Similarly, hardware can also be shared.

## Security

Networks allow security by ensuring that the user has the right to access certain files and applications.

## Scalability

**Scalability** means that we can add new components to the network. The network must be scalable so that we can extend the network by adding new devices. However, it decreases the speed of the connection and data transmission speed also decreases, increasing the chances of errors occurring. This problem can be overcome by using routing or switching devices.

## Reliability

Computer networks can use alternative sources for data communication in case of any hardware failure.


# Computer Network Architecture

**Computer Network Architecture** is defined as the physical and logical design of the software, hardware, protocols, and media of the transmission of data. Simply put, it refers to how computers are organized and how tasks are allocated to them.

## Types of Network Architectures:

![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/7b24e2bb-7209-427d-8e88-e66d486830d0)


### Peer-To-Peer Network

**Peer-To-Peer network** is a network in which all computers are linked together with equal privilege and responsibilities for processing the data. It is useful for small environments, usually up to 10 computers.

![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/b17dc705-5c5a-4cae-9d84-7af1bd3be79e)


#### Advantages Of Peer-To-Peer Network:

- It is less costly as it does not require a dedicated server.
- If one computer stops working, other computers will not be affected.
- It is easy to set up and maintain as each computer manages itself.

#### Disadvantages Of Peer-To-Peer Network:

- It lacks a centralized system, making data backup difficult.
- Security can be an issue as each device manages itself.

### Client/Server Network

**Client/Server network** is a network model designed for end-users called clients to access resources such as songs, videos, etc., from a central computer known as the Server.

![image](https://github.com/92kareeem/Computer_Networks/assets/110279232/9012eabb-0444-40e6-b286-8c302c83217d)


- The central controller is known as a server, while all other computers in the network are called clients.
- A server performs all major operations such as security and network management.
- A server is responsible for managing all resources such as files, directories, printers, etc.
- All clients communicate with each other through the server. For example, if client1 wants to send some data to client 2, it first sends the request to the server for permission. The server then initiates communication between client1 and client 2.

#### Advantages Of Client/Server Network:

- Contains a centralized system, making data backup easy.
- Has a dedicated server that improves overall system performance.
- Security is better as a single server administers shared resources.
- Increases the speed of sharing resources.

#### Disadvantages Of Client/Server Network:

- Expensive as it requires a server with large memory.
- Network Operating System (NOS) for servers can be costly.
- Requires a dedicated network administrator to manage all resources.

# Computer Network Components

**Computer network components** are the major parts needed to install the software. Some important network components include NIC, switch, cable, hub, router, and modem. Depending on the type of network needed to install, some network components can also be omitted. For example, a wireless network does not require a cable.

## Major Components Required to Install a Network:

### NIC (Network Interface Card)

- **NIC** stands for network interface card.
- It is a hardware component used to connect a computer with another computer onto a network.
- NIC can support a transfer rate of 10,100 to 1000 Mb/s.
- The MAC address or physical address is encoded on the network card chip, assigned by the IEEE to identify a network card uniquely.
- There are two types of NIC:
  - **Wired NIC:** Present inside the motherboard, used with cables and connectors to transfer data.
  - **Wireless NIC:** Contains an antenna for wireless connections, commonly found in laptops.

### Hub

- **Hub** is a hardware device that divides the network connection among multiple devices.
- It broadcasts requests to the entire network, consuming more bandwidth and limiting communication.
- Nowadays, hubs are obsolete, replaced by more advanced components like switches and routers.

### Switch

- **Switch** connects multiple devices on a network.
- It contains an updated table to decide where data is transmitted.
- Switch delivers messages directly to the correct destination, increasing network speed.

### Router

- **Router** connects a LAN with an internet connection.
- It works in the Layer 3 (Network layer) of the OSI Reference model.
- A router forwards packets based on the routing table, determining the best path for transmission.
  
#### Advantages Of Router:

- **Security:** Data transmitted on the network is only readable by the specified addressed device.
- **Reliability:** If a server stops functioning, the network served by the router remains unaffected.
- **Performance:** Router enhances network performance by splitting the network into smaller segments.

### Modem

- **Modem** allows the computer to connect to the internet over existing telephone lines.
- It converts digital data into an analog signal over telephone lines.
- Modem types include Standard PC modem or Dial-up modem, Cellular Modem, and Cable modem.

### Cables and Connectors

- **Cable** is a transmission media used for signal transmission.
- Types of cables used:
  - **Twisted pair cable**
  - **Coaxial cable**
  - **Fibre-optic cable**




