## Notes on networking

###  Contents of Networking:

#### Chapter 1 : Introduction to Networking Fundamentals   
#### Chapter 2 : OSI Model  
#### Chapter 3 : DNS   
#### Chapter 4 : Routing   
#### Chapter 5 : Subnetting   
#### Chapter 6 : Network Troubleshooting   
#### Chapter 7 : Cloud-Native Networking   
#### Chapter 8 : Hands-on Networking

---

## Chapter 1 : Introduction to Networking Fundamentals  
A. Overview of computer networks and their importance in modern infrastructure & DevOps  
B. Network Basics/Types of Networks: LAN, WAN etc  
C. Key networking components: Routers, switches, firewalls  
D. IP addressing (IPv4 & IPv6)  
E. MAC addresses  
F. Ports and Protocols (TCP, UDP)

## Overview of Computer Networks {#overview-of-computer-networks}

A computer network is a group of devices connected with each other allowing them to share information and resources. Think about your home setup. You might have a phone, a laptop, and a smart TV, all connected to the same Wi-Fi. That connection between them forms a small network where they can share the internet and, in some cases, even files.

### **Types of Networks** {#types-of-networks}

There are more than 10 different types of networks, but here are the two main ones:

1. **Local Area Network (LAN):**  
   * **Example:** Your home Wi-Fi network or an office network. It covers a small area, like one building or even a single room.  
   * **Purpose:** Connects devices within a close range, allowing them to share resources like a printer or files. For example, if you have a printer at home, everyone on the same Wi-Fi can print from it without needing to plug in directly.  
2. **Wide Area Network (WAN):**  
   * **Example:** The internet itself is a giant WAN. It’s what connects networks in homes, offices, schools, and more all around the world.  
   * **Purpose:** Allows different LANs to connect over large distances. For instance, a company with offices in New York, London, and Tokyo could use a WAN to connect all their networks so they can share data securely across locations.

### **Purpose of Networks** {#purpose-of-networks}

Networks are essential for **communication and resource sharing** between devices. Here’s why they’re so important:

* **Communication:** Networks let us browse the internet, stream videos, and talk to people from anywhere.  
  * **Example:** Video calling with a friend in another country is only possible because your devices are connected over a network that links your location to theirs.  
* **Resource Sharing:** Networks allow devices to share resources like printers, files, or even the internet connection itself.  
  * **Example:** In an office, employees can all access a shared drive on their computers. Instead of saving a document on each computer separately, it’s stored on the network, so everyone can access it in real time.

### **Networks and the Internet** {#networks-and-the-internet}

When you use the internet—browsing, streaming, or using an app—you’re actually relying on networks behind the scenes:

* **How It Works:** When you open an app or website, your device sends a request over the network to a server (a computer that stores the website’s data). The server then sends the information back to your device, and the app or site appears on your screen.  
  * **Example:** When you scroll through social media, each time you refresh, new posts load because your device is continuously sending and receiving information from the platform’s server.

### **Networks in DevOps and Cloud Computing** {#networks-in-devops-and-cloud-computing}

In DevOps (development and operations) and cloud computing, networks are essential for many tasks:

* **Inter-Server Communication:** Allows different servers to “talk” to each other.  
  * **Example:** Imagine you’re working on a project stored on your laptop. Your teammate in another city uses the same project on a cloud server (like an Amazon EC2 server). Networking allows both of you to access and work on the project from different locations as if it were local to each of you.  
* **Deployment Management:** Networking helps manage and deploy applications on multiple servers, making it possible for many people to use an app at the same time.  
  * **Example:** Think of a large website with millions of users, like a streaming service. Network management allows the service to deploy the app on many servers worldwide, so no matter where you are, you can access the content smoothly.  
* **Infrastructure Management:** Allows IT teams to monitor and troubleshoot systems.  
  * **Example:** If a business’s network starts having issues, the IT team can quickly detect where the problem is, whether it’s with a specific device, server, or application, and fix it to prevent downtime.  
* **Optimization and Performance:** Well-managed networks ensure that data moves quickly and smoothly between devices and servers, improving the performance of applications.  
  * **Example:** If a gaming app has slow or unreliable network connections, it can cause lag (slow response times) or interruptions. But with good networking, games load faster, and the experience is much smoother.

### **Final Thoughts** {#final-thoughts}

Learning about networks may seem challenging, but it’s like learning how your city or neighbourhood is laid out. Over time, you’ll get to know the main “roads” and connections, and it will become second nature. Networks are the backbone of all digital communication, from the internet to file sharing, and they’re a critical part of our everyday tech use.

# Introduction to LAN and WAN {#introduction-to-lan-and-wan}

LAN and WAN are two essential types of networks that help devices communicate in both small and large environments. Let’s break down what they do and why they’re important.

### **Local Area Network (LAN)** {#local-area-network-(lan)}

* **What It Is:** A LAN, or Local Area Network, connects devices within a limited area like a home, office, or school.  
* **Purpose:** LANs enable devices within a close range to communicate and share resources easily.  
* **Examples of How LANs Are Used:**  
  * **Home Setup:** Imagine your home Wi-Fi network. Your phone, laptop, and smart TV are all connected to the same router, forming a LAN. Because they’re on the same network, they can share resources, like the internet, without needing separate connections.  
  * **Office Environment:** In an office, LANs connect computers, printers, and servers, so employees can share files, send documents to printers, or access shared drives all from the same network.  
  * **Printing at Home:** When you print a document from your laptop to your wireless printer, you’re using a LAN. Both devices are connected to the same Wi-Fi, allowing them to “talk” to each other and send the print job without needing cables.  
* **Primary Uses of LANs:**  
  * Connecting devices in a single area, like a home or office.  
  * Sharing resources locally, such as files, printers, or internet access within a confined space.

### **Wide Area Network (WAN)** {#wide-area-network-(wan)}

* **What It Is:** A WAN, or Wide Area Network, covers a much larger area than a LAN, even spanning cities, countries, or continents.  
* **Purpose:** WANs connect multiple LANs over large distances, allowing data to travel far beyond a single location.  
* **Examples of How WANs Are Used:**  
  * **The Internet:** The internet is the largest WAN. It links millions of LANs worldwide, allowing computers and devices in different countries to communicate. For example, when you send an email to someone overseas, it travels through various networks across cities and continents, all thanks to the WAN structure of the internet.  
  * **Connecting Company Branches:** A company with offices in multiple cities might use a WAN to connect its local networks (LANs) in each office. This way, employees in New York, London, and Tokyo can access the same shared files, databases, and applications as if they were in the same building.  
  * **Banking Networks:** ATMs are part of a bank’s WAN. When you use an ATM, the machine communicates with the bank’s network, no matter where you are. This is possible because the bank’s LANs at each branch are connected through a larger WAN.  
* **Primary Uses of WANs:**  
  * Connecting LANs across large geographical areas.  
  * Allowing data transfer and communication over long distances, essential for global communication and services like the internet.

### **Key Differences Between LAN and WAN** {#key-differences-between-lan-and-wan}

* **Range:** LANs cover a small area (like a home or building), while WANs cover large areas (like cities or even the whole world).  
* **Purpose:** LANs connect devices in close proximity for local resource sharing, while WANs link multiple LANs to allow long-distance communication and data sharing.

In summary, **LANs** are used to connect devices in a limited space, enabling local communication and sharing, while **WANs** connect these local networks over much larger distances, making global communication and internet functionality possible. Understanding LAN and WAN is key to grasping how networks of all sizes work.

# Switches, Routers and Firewalls {#switches,-routers-and-firewalls}

Switches, routers, and firewalls are essential devices in any network. Each plays a unique role to ensure smooth, efficient, and secure communication.

![][image1]

---

### **Switches** {#switches}

* **What It Is:** A switch is like a manager within a Local Area Network (LAN). It connects multiple devices in the same network, like computers, printers, and other devices within a home or office.  
* **Purpose:** Switches ensure that data flows smoothly between devices within a LAN, avoiding congestion and managing the communication between connected devices.  
* **Examples of How Switches Work:**  
  * **Home Network:** In a home setup with several devices connected to Wi-Fi, a switch manages and directs data between these devices. This allows your computer and smart TV to “talk” to each other seamlessly, whether they’re sharing data or accessing the same resources, like the internet.  
  * **Office Network:** In an office, a switch might connect dozens of computers, printers, and servers. When an employee sends a print job, the switch ensures that only the printer receives that specific data, preventing network congestion and speeding up operations.  
* **Primary Uses of Switches:**  
  * Connecting devices within the same network.  
  * Managing data flow within a LAN to ensure smooth communication.

---

### **Routers** {#routers}

* **What It Is:** A router acts like a traffic cop, directing data between different networks. Its main job is to manage the flow of information from one network to another.  
* **Purpose:** Routers connect your network to other networks, like the internet, and make sure data reaches its correct destination, whether that’s a webpage you’re loading or a video you’re streaming.  
* **Examples of How Routers Work:**  
  * **Home Internet Connection:** When you connect to the internet at home, your router directs information between your home network (your Wi-Fi) and the wider internet. For instance, when you visit a website, the router ensures the data from that site reaches your device while keeping other data (like updates from other devices) organised.  
  * **Public Networks:** In a coffee shop with free Wi-Fi, a router connects all customers’ devices to the internet. It directs each device’s requests to the right places without mixing them up, ensuring each person’s browsing remains private and separate.  
* **Primary Uses of Routers:**  
  * Directing traffic between different networks.  
  * Connecting local networks (like your home network) to larger networks like the internet.

---

### **Firewalls** {#firewalls}

* **What It Is:** A firewall is a security guard for your network. It monitors incoming and outgoing network traffic and decides what data is safe to allow through based on security rules.  
* **Purpose:** Firewalls protect your network by blocking unauthorised access and controlling the flow of data according to security settings.  
* **Examples of How Firewalls Work:**  
  * **Home Network Security:** Many home routers have built-in firewalls to prevent outside access. For instance, if a malicious program tries to enter your network, the firewall will detect it and block it, protecting your devices.  
  * **Business Network Protection:** In a company, a firewall monitors data traffic to ensure only authorised devices and users can access sensitive files. If someone tries to access restricted areas without permission, the firewall can block their access.  
* **Primary Uses of Firewalls:**  
  * Protecting networks from unauthorised access.  
  * Monitoring and controlling data flow to ensure network security.

---

### **Summary** {#summary}

Together, **switches**, **routers**, and **firewalls** are the backbone of any network:

* **Switches** keep data flowing smoothly within a single network (like a LAN).  
* **Routers** connect different networks and direct data to the right places.  
* **Firewalls** protect the network by monitoring and controlling access.

Each device has a unique role, but they work together to create a network that is efficient, organised, and secure.

# IP address & MAC address

---

### **IP Address** {#ip-address}

* **What It Is:** An IP address (Internet Protocol address) is a unique identifier assigned to each device on a network, helping devices locate and communicate with each other.  
* **Purpose:** IP addresses allow devices to send and receive information across networks, including the internet.  
* **Types of IP Addresses:**  
  * **IPv4 (Internet Protocol version 4):**  
    * **Format:** IPv4 addresses are 32-bit numbers and look like this: `192.168.0.5`. They’re written in a decimal format with four groups of numbers separated by dots, where each group ranges from 0 to 255\.  
    * **Example:** An IP address in IPv4 might be `192.168.1.1`, which could represent a device like a home router on a local network.  
    * **Address Pool:** IPv4 can provide around 4.3 billion unique addresses. However, with so many devices connected today, these addresses are becoming limited.  
  * **IPv6 (Internet Protocol version 6):**  
    * **Format:** IPv6 addresses are 128-bit numbers and look like this: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`. They’re written in hexadecimal format with groups separated by colons.  
    * **Example:** An IPv6 address for a device might be `2001:db8:85a3::8a2e:370:7334`. The additional address space supports the expansion of connected devices.  
    * **Address Pool:** IPv6 provides approximately 340 undecillion addresses, which is enough to support the internet's growth for a very long time.  
* **Why IP Addresses Are Important:**  
  * **Device Identification:** They allow devices to recognize each other on a network, so data can be sent to the correct destination.  
  * **Internet Communication:** Without IP addresses, the internet wouldn’t function as devices wouldn’t know where to send or receive data.

---

### **MAC Address** {#mac-address}

* **What It Is:** A MAC address (Media Access Control address) is a unique identifier assigned to a device’s network interface, similar to a fingerprint for network devices. *They operate at the data link level*.  
* **Purpose:** MAC addresses operate at a more local level, specifically on the data link layer, to help devices communicate within the same local network.  
* **Format of MAC Address:**  
  * **Structure:** A MAC address is a 48-bit number written in hexadecimal format, looking something like `00:18:2B:34:56:78`.  
  * **Example:** A MAC address for a laptop’s Wi-Fi card might look like `00:1A:2B:3C:4D:5E`.  
  * **Hexadecimal Use:** Like IPv6, MAC addresses use numbers (0–9) and letters (A–F), creating a unique identifier for each network device.  
* **Why MAC Addresses Are Important:**  
  * **Local Network Identification:** They help devices recognize each other on the same network, ensuring data packets reach the right device. For example, they allow your laptop to connect specifically to your home router instead of a neighbor’s.  
  * **Network Communication & Security:** MAC addresses control access to networks, ensuring that only approved devices can connect. This is essential for managing and securing network traffic.

---

### **Summary** {#summary-1}

* **IP Addresses** help devices communicate over the internet and wide networks, allowing them to find each other across long distances.  
* **MAC Addresses** operate on local networks, providing unique identifiers for each device to help manage local communication and ensure that data reaches the right destination.

Together, IP addresses and MAC addresses are essential for both local and global network communication, helping devices connect securely and efficiently.

# Ports & Protocols: TCP, UDP {#ports-&-protocols:-tcp,-udp}

---

### **Ports** {#ports}

* **What They Are:** Ports act as virtual “doors” on a device, each assigned a unique number that helps data reach the correct application.  
* **Example of Ports in Use:**  
  * **Web Browsing:** When you type a website address in your browser, your computer communicates over **Port 80** for HTTP or **Port 443** for secure HTTPS.  
  * **Email:** Email applications use ports too, like **Port 25** for sending emails via SMTP (Simple Mail Transfer Protocol).  
* **Importance:** Ports make sure data reaches the right application on your device, much like how apartment numbers ensure mail reaches the correct recipient in a building.

---

### **Protocols** {#protocols}

* **What They Are:** Protocols are sets of rules that define how data is formatted, sent, and received across networks. Think of protocols as “languages” that devices use to communicate effectively.  
* **Examples of Protocols:**  
  * **HTTP (HyperText Transfer Protocol):** Used for web browsing; makes sure webpages load correctly by following a specific set of rules.  
  * **FTP (File Transfer Protocol):** Used to transfer files between computers, such as when uploading a document to cloud storage.  
* **Importance:** Protocols ensure devices “speak the same language,” allowing them to understand and properly handle data.

---

### **Key Protocols: TCP and UDP** {#key-protocols:-tcp-and-udp}

#### **TCP (Transmission Control Protocol)** {#tcp-(transmission-control-protocol)}

* **Overview:** TCP is like a reliable “postal service” for the internet. It makes sure data is accurately delivered from one device to another in the correct order.  
* **Key Characteristics of TCP:**  
  * **Connection-Oriented:** TCP establishes a connection before data transfer starts, similar to making a phone call where both parties confirm they’re ready.  
  * **Handshake Process:** TCP initiates a “handshake” where both devices agree to communicate, ensuring they’re in sync.  
  * **Reliable Data Transfer:** TCP checks for errors and resends any lost data, ensuring everything is received correctly.  
* **Use Cases of TCP:**  
  * **Web Browsing:** When you load a website, TCP ensures the data reaches you accurately and in order so the page displays correctly.  
  * **Email:** Emails use TCP to make sure messages are delivered in full, without missing content.  
  * **File Transfers:** When sending or receiving files, TCP ensures every piece of the file arrives, making it crucial for accuracy.

#### **UDP (User Datagram Protocol)** {#udp-(user-datagram-protocol)}

* **Overview:** UDP is a faster, simpler protocol that doesn’t establish a connection first. It’s like “sending a postcard” where you hope it arrives, but don’t know for sure.  
* **Key Characteristics of UDP:**  
  * **Connectionless:** No setup is needed—data is sent right away, without waiting for the receiver to confirm.  
  * **Fast but Less Reliable:** UDP doesn’t check if data arrived successfully, making it faster but less reliable than TCP.  
  * **Independent Packets:** Each packet of data is sent individually, so packets may arrive out of order or not at all.  
* **Use Cases of UDP:**  
  * **Video Streaming:** When watching a live stream, UDP’s speed is essential, as minor data losses are often unnoticed in video playback.  
  * **Online Gaming:** In gaming, speed is key to maintaining smooth gameplay, and minor data loss (like a slight lag) is preferable to delays.  
  * **DNS Lookups:** Domain Name System (DNS) uses UDP for quick name-to-IP address resolutions, allowing web pages to load faster.

---

### **TCP vs. UDP: Quick Comparison** {#tcp-vs.-udp:-quick-comparison}

1. **Connection Setup:**  
   * **TCP:** Connection-oriented (requires a handshake)  
   * **UDP:** Connectionless (no setup required)  
2. **Reliability:**  
   * **TCP:** Highly reliable; data is checked for errors and resent if lost.  
   * **UDP:** Less reliable; there’s no guarantee data will arrive.  
3. **Speed:**  
   * **TCP:** Slower due to error-checking and connection setup.  
   * **UDP:** Faster as it skips error-checking and connection setup.  
4. **Use Cases:**  
   * **TCP:** Web browsing, emails, file transfers where reliability matters.  
   * **UDP:** Video streaming, gaming, DNS, and VPNs where speed is prioritised.

---

In summary:

* **Ports** direct data to the right applications on your device.  
* **Protocols** like TCP and UDP control how data is sent and received.  
* **TCP** is reliable and ordered, used for applications needing accurate delivery, while **UDP** is fast but less reliable, suited for real-time applications.

# Introduction to the OSI Model {#introduction-to-the-osi-model}

OSI \- Open Systems Interconnection Model. We will look at:

A. Overview of the OSI Model (Layers 1-7)  
B. Overview of the TCP/IP Model (Layers)  
C. Comparing OSI and TCP/IP Models  
D. Importance of These Models in Understanding Networking

# The 7 Layers of the OSI Model {#the-7-layers-of-the-osi-model}

The OSI Model, or **Open Systems Interconnection Model**, breaks down network communication into **seven layers**, each with a specific function. This structured model standardised communication so all devices and applications can "speak the same language" across any network technology. This makes it easier to develop, manage, and upgrade network applications and equipment.

---

### **Why Use a Communication Model?** {#why-use-a-communication-model?}

* **Application Independence**: Without a standardised model, each application would need custom solutions for different networks (Wi-Fi, Ethernet, etc.), making development complicated and time-consuming.  
* **Easier Network Management**: With standardised layers, managing and upgrading network equipment is simpler since everything follows a common framework.  
* **Decoupled Innovation**: Each layer can be independently improved without disrupting the entire network, enabling faster and more flexible innovation.

---

### **Layer 1: Physical Layer** {#layer-1:-physical-layer}

* **Role**: Deals with the actual physical connection, transmitting raw data (bitstreams) over physical media.  
* **Examples**: Cables (Ethernet, fibre), switches, and Wi-Fi signals.  
* **Real-Life Example**: Think of this as shouting in a room—everyone hears it, but it’s not directed at anyone specific. The next layer provides a solution for this.

### **Layer 2: Data Link Layer** {#layer-2:-data-link-layer}

* **Role**: Manages data transfer between nodes on networks, framing data and ensuring it reaches the correct device.  
* **Examples**: MAC addresses, Ethernet frames, switches, and bridges.  
* **Real-Life Example**: Frames work like addressed envelopes, ensuring data is organised and sent to the correct recipient within the network.

### **Layer 3: Network Layer** {#layer-3:-network-layer}

* **Role**: Determines the best path for data packets to travel across networks to reach the correct destination.  
* **Examples**: IP addresses and routers.  
* **Real-Life Example**: This layer acts like a mail service, with routers as post offices directing packets (data parcels) using IP addresses to reach the correct "destination address."

### **Layer 4: Transport Layer** {#layer-4:-transport-layer}

* **Role**: Manages end-to-end communication, data integrity, and reliability.  
* **Examples**: TCP and UDP protocols.  
* **Real-Life Example**: TCP functions like a recorded mail service, confirming receipt, while UDP is more like a postcard—faster but without confirmation of delivery.

### **Layer 5: Session Layer** {#layer-5:-session-layer}

* **Role**: Establishes, manages (maintains) and terminates sessions or connections between applications.  
* **Examples**: Session management protocols like RPC and NetBIOS.  
* **Real-Life Example**: Logging into a website is like opening a session, and logging out is closing it. This layer keeps the connection active as long as it’s needed.

### **Layer 6: Presentation Layer** {#layer-6:-presentation-layer}

* **Role**: Formats data for the application layer and handles encryption/decryption.  
* **Examples**: SSL/TLS, data encoding (e.g., JPEG, PNG).  
* **Real-Life Example**: This layer works like a translator, converting data to a readable format for applications and securing it through encryption.

### **Layer 7: Application Layer** {#layer-7:-application-layer}

* **Role**: Provides network services directly to end-user applications.  
* **Examples**: HTTP (web browsing), FTP (file transfers), SMTP (email).  
* **Real-Life Example**: Everything you interact with—such as websites, file transfers, and emails—happens here. This is the "user" layer where data reaches its final destination.

---

### **Quick Summary of Layers and Their Functions** {#quick-summary-of-layers-and-their-functions}

1. **Physical Layer**: Transmits raw data via physical media (cables, Wi-Fi).  
2. **Data Link Layer**: Organises data into frames and manages local addressing.  
3. **Network Layer**: Routes data to the correct destination across networks.  
4. **Transport Layer**: Ensures data integrity and manages data flow (TCP/UDP).  
5. **Session Layer**: Manages sessions between applications.  
6. **Presentation Layer**: Translates and secures data for applications.  
7. **Application Layer**: Provides services to user applications (e.g., web browsing, email).

---

By understanding these seven layers, you gain a structured view of how network communication works, from the physical connections to the end-user applications. Each layer plays a unique and essential role in ensuring smooth, reliable, and efficient data transmission across networks.

# TCP/IP Model: A Commonly Used Model {#tcp/ip-model:-a-commonly-used-model}

The **TCP/IP model** is an essential framework for understanding how data travels across the internet. Unlike the OSI model’s seven layers, the TCP/IP model condenses networking tasks into **four layers**. This streamlined approach is what powers most internet communication.

Here’s a breakdown of the TCP/IP model and its layers:

---

#### **1\. Application Layer** {#1.-application-layer}

* **Role**: This is where network applications operate, managing everything users interact with directly.  
* **Functions**: This layer handles things like web browsing, email, file transfers, and domain name lookups.  
* **Protocols**: Common protocols include **HTTP** (for websites), **TLS** (for security/encryption), and **DNS** (for translating domain names to IP addresses).  
* **Real-Life Example**: When you type a URL into a web browser, the request to load that page occurs in the Application Layer via HTTP.

#### **2\. Transport Layer** {#2.-transport-layer}

* **Role**: The Transport Layer manages the data transfer process between devices, ensuring that information gets from point A to point B reliably.  
* **Key Protocols**:  
  * **TCP** (Transmission Control Protocol): Guarantees reliable data transfer by ensuring data packets are received in order and re-sent if lost.  
  * **UDP** (User Datagram Protocol): Provides faster, less reliable communication without error-checking, useful in streaming or gaming where speed is critical.  
* **Real-Life Example**: Imagine sending a message through a chat app (TCP), where every message should be received completely and in order. Conversely, when you watch a live stream (UDP), some data might be dropped, but the stream continues smoothly.

#### **3\. Internet Layer** {#3.-internet-layer}

* **Role**: The Internet Layer determines the logical address (IP) for each device, helping data packets find their way across networks to their final destination.  
* **Primary Protocol**: **IP** (Internet Protocol) is responsible for routing data, ensuring it reaches the correct destination address.  
* **Real-Life Example**: Think of IP as a postal service; it assigns addresses to packets and chooses the best route to deliver them, like a letter traveling between cities through a series of mail hubs.

#### **4\. Network Access Layer** {#4.-network-access-layer}

* **Role**: This layer combines aspects of the OSI model’s Physical and Data Link layers, handling the hardware and low-level tasks needed for data transmission over a network.  
* **Functions**: This includes the physical connection between devices (like cables or Wi-Fi) and the management of data frames sent across these connections.  
* **Components**: **Ethernet** is a common protocol here, ensuring that data moves reliably across physical media like cables or wireless signals.  
* **Real-Life Example**: Picture plugging an Ethernet cable into a computer; this layer deals with the nuts and bolts of making sure the connection actually works, carrying data between devices on the same network.

---

### **How It Compares to the OSI Model** {#how-it-compares-to-the-osi-model}

* The **TCP/IP model** is simpler and groups related functions from the OSI model into broader layers.  
* The **Application layer** in TCP/IP combines several OSI layers (Application, Presentation, and Session).  
* **Network Access Layer** merges OSI’s Data Link and Physical layers, making the TCP/IP model more streamlined and easier to work with.

In summary, the **TCP/IP model** is like a condensed, practical version of the OSI model, tailored for the real-world needs of the internet. With just four layers, it focuses on getting data efficiently from point A to point B.

# OSI Layers: Sender & Receiver Perspective in Action {#osi-layers:-sender-&-receiver-perspective-in-action}

To make the OSI model more practical, let’s follow the journey of a **POST request** sent to an HTTPS webpage through the OSI layers, first from the **sender’s** side and then from the **receiver’s**.

---

#### **Sender's Point of View** {#sender's-point-of-view}

Imagine a user on a client device sends a **POST request** to submit data to a webpage over HTTPS. Here’s how this request travels through each OSI layer:

1. **Application Layer (Layer 7\)**  
   * **Function**: The request is created in the application layer where the POST request originates.  
   * **Process**: In this layer, the user’s web browser (or app) sends a POST request with JSON data to an HTTPS server.  
   * **Real-Life Example**: Think of the application layer as typing a message in a chat app—this is where the content is created.  
2. **Presentation Layer (Layer 6\)**  
   * **Function**: This layer prepares data for transmission, often by encoding or serialising it.  
   * **Process**: The JSON data is serialised, meaning it’s converted into a string of bits suitable for transmission.  
   * **Real-Life Example**: Imagine translating a message into a code—only the recipient with the codebook can read it.  
3. **Session Layer (Layer 5\)**  
   * **Function**: Manages sessions by establishing, maintaining, and terminating connections.  
   * **Process**: For HTTPS communication, a **TCP connection** is established, often secured with **TLS** (Transport Layer Security) for encryption.  
   * **Real-Life Example**: The session layer is like setting up a secure phone line, ensuring only the intended participants are on the call.  
4. **Transport Layer (Layer 4\)**  
   * **Function**: Ensures reliable delivery across networks, managing data flow and error checking.  
   * **Process**: The client initiates a **TCP handshake** (SYN, SYN-ACK, ACK) to establish a reliable connection over port **443** (commonly used for HTTPS).  
   * **Real-Life Example**: Think of this layer as a postal service confirming your package has been shipped, received, and recorded in order.  
5. **Network Layer (Layer 3\)**  
   * **Function**: Adds logical addressing and manages data routing.  
   * **Process**: The request is placed into an **IP packet**, which includes both the sender’s and recipient’s IP addresses to identify the origin and destination.  
   * **Real-Life Example**: The network layer is like a post office sorting mail based on the destination address.  
6. **Data Link Layer (Layer 2\)**  
   * **Function**: Adds physical addresses (MAC addresses) and prepares data for local transmission.  
   * **Process**: The IP packet from Layer 3 is wrapped into a **frame** containing the MAC address of the client and the MAC address of the nearest router.  
   * **Real-Life Example**: It’s like adding an address label to a parcel, allowing the postal worker to deliver it directly to your door.  
7. **Physical Layer (Layer 1\)**  
   * **Function**: Converts data into physical signals, such as electrical signals or light pulses.  
   * **Process**: The frame is converted into a physical signal, sent via an Ethernet cable, Wi-Fi signal, or fibre optic connection.  
   * **Real-Life Example**: This is the act of the postal truck carrying the package from one place to another.

---

#### **Receiver's Point of View** {#receiver's-point-of-view}

Now let’s look at what happens when the **POST request** reaches the server, moving back up the OSI layers from the **receiver’s perspective**.

1. **Physical Layer (Layer 1\)**  
   * **Function**: Receives physical signals and converts them back into digital data.  
   * **Process**: The incoming signal, whether electric, radio, or light, is transformed into bits for the server to interpret.  
   * **Real-Life Example**: Like hearing someone’s voice over a radio and converting the sound into meaningful words.  
2. **Data Link Layer (Layer 2\)**  
   * **Function**: Packages bits into frames and ensures data integrity over local connections.  
   * **Process**: The bits are reassembled into a frame, allowing the server’s network card to verify the data.  
   * **Real-Life Example**: Like opening an envelope to see the letter inside and confirming it’s intact.  
3. **Network Layer (Layer 3\)**  
   * **Function**: Handles logical addressing and routes data to the correct location.  
   * **Process**: The frame from Layer 2 is stripped, leaving an IP packet with source and destination IP addresses for routing to the right application.  
   * **Real-Life Example**: This step is like checking the sender’s address on a parcel to ensure the origin is legitimate.  
4. **Transport Layer (Layer 4\)**  
   * **Function**: Reassembles data segments and manages error correction.  
   * **Process**: The packet is converted back into **TCP segments**. The server completes the TCP handshake if required, ensuring data integrity.  
   * **Real-Life Example**: This is like confirming a package’s content order—if everything’s in place, you acknowledge receipt.  
5. **Session Layer (Layer 5\)**  
   * **Function**: Manages session continuity or closure.  
   * **Process**: Here, any session establishment or management requests are finalised. If required, the session is maintained as long as the data flow continues.  
   * **Real-Life Example**: It’s like maintaining a conversation over the phone; once the message is received, the session can end.  
6. **Presentation Layer (Layer 6\)**  
   * **Function**: Prepares data for the application by decrypting or decoding it.  
   * **Process**: The encrypted HTTPS data is decrypted, transforming it into a readable format such as JSON for the application.  
   * **Real-Life Example**: Imagine unlocking a coded letter with a key, revealing its actual contents.  
7. **Application Layer (Layer 7\)**  
   * **Function**: The final destination where data is processed and the request is handled.  
   * **Process**: The web application receives the POST request and processes it according to its content (e.g., storing data, sending a response).  
   * **Real-Life Example**: Like a post office opening the package and using the enclosed information—this is where the message is finally understood and acted upon.  
     ![][image2]

---

### **Summary** {#summary-2}

By viewing the OSI model from both sender and receiver perspectives, you get a clearer understanding of how data flows from creation to delivery. Each layer plays a specific role, and together they enable seamless communication, whether it’s loading a webpage, sending a message, or retrieving data from a remote server.

**–NOW  RECAP Ports & Protocols\! –**

# 

# Introduction to DNS (Domain Name System)

Have you ever wondered how typing a website name into your browser suddenly loads the site? **DNS**, or Domain Name System, is the essential system working behind the scenes to make this happen.

A. What is DNS and its role in networking  
B. DNS components  
C. DNS Records  
D. How DNS works: DNS Process  
E. DNS tools  
F. Using /etc/hosts on our local machine

### **What is DNS (Domain Name System)?** {#what-is-dns-(domain-name-system)?}

DNS, or the **Domain Name System**, is the key system that allows us to use human-friendly website names instead of memorising long IP addresses. Let’s dive into why DNS is essential and how it simplifies networking for us.

---

#### **1\. Defining DNS** {#1.-defining-dns}

* **What it Does**: DNS translates domain names (like [www.example.com](http://www.example.com)) into IP addresses (like 192.78.12.4) that computers use to identify each other. Without DNS, we’d have to remember the numerical IP address of every website we want to visit.  
* **Real-Life Comparison**: Think of DNS as the internet’s **contacts list**. Just like you look up a friend’s name to find their phone number, DNS allows your computer to look up the “name” of a website (like google.com) and find its IP address.

#### **2\. Why DNS is Crucial for Networking** {#2.-why-dns-is-crucial-for-networking}

* **Simplifies Internet Use**: Imagine having to type in a complex IP address each time you wanted to search on Google. For example, instead of typing “www.google.com,” you’d have to enter something like `192.78.12.4` or another sequence of numbers. DNS allows us to access websites using names we can remember and recognise.  
* **Human-Friendly**: DNS bridges the gap between human-readable names and the machine-readable IP addresses. So, when you type in a domain like “amazon.com,” DNS converts it behind the scenes to something that the internet infrastructure can understand.  
* **Real-Life Example**: Just like knowing someone’s name instead of having to memorise their phone number, DNS makes it easy for us to access any website without dealing with the technical side of IP addresses.

#### **3\. How DNS Works in Practice** {#3.-how-dns-works-in-practice}

* **Step-by-Step Process**:  
  * When you type a domain name into your browser, your computer sends a query to a DNS server to find out the IP address associated with that name.  
  * The DNS server responds with the IP address, allowing your computer to connect to the correct web server and load the site.  
* **Behind the Scenes**: Although you only type the domain name, your machine relies on DNS to communicate with the actual IP address of the server hosting the website.

---

### **Summary** {#summary-3}

DNS is a foundational part of networking that allows us to use simple, memorable names for websites rather than complex IP addresses. It’s like an address book for the internet, making it much easier to navigate the vast number of websites we use every day. Without DNS, browsing would be cumbersome and confusing, as we’d be forced to remember a sequence of numbers for each site.

# DNS Components: Name Servers & Zone Files {#dns-components:-name-servers-&-zone-files}

In this lesson, we’ll break down two critical DNS components—**name servers** and **zone files**—which play a key role in ensuring DNS operates smoothly.

---

#### **1\. Name Servers** {#1.-name-servers}

* **Role**: Name servers are essential for DNS to work properly. They load DNS settings and configurations and respond to queries from clients or other servers about domain names.  
* **Types of Name Servers**:  
  * **Authoritative Name Servers**: These servers hold the actual DNS records and provide the definitive answer for a domain. For instance, when a device requests the IP address of a specific domain, the authoritative server has the direct answer.  
  * **Recursive Name Servers**: These servers don’t store the final DNS records. Instead, they act like an assistant, querying authoritative servers on behalf of the client. Recursive servers also **cache** (temporarily store) the information they retrieve, which speeds up future queries.  
* **Real-World Example**: If you ask for directions at a help desk, the person there might know the answer (like an authoritative server) or they might need to call someone else to check (like a recursive server). Recursive servers do this lookup work for the user, then store the answer so they don’t have to ask again the next time someone needs it.

#### **2\. Example of Finding a Name Server Using the `dig` Tool** {#2.-example-of-finding-a-name-server-using-the-dig-tool}

* To see name servers in action, you can use a tool called **`dig`**. Here’s how it works:  
  * **Step 1**: Type `dig ns domainname.com` (e.g., `dig ns google.com`).  
  * **Step 2**: Hit enter, and the output will show name servers related to the domain you entered.  
  * **Note**: You can also use a shorter version with `dig +short ns domainname.com` for a simpler output.  
* **What You’ll See**: The output will list the name servers hosting that domain. Each name server entry (often labelled as “NS”) is like a directory showing where the domain information is stored.


#### **3\. Zone Files** {#3.-zone-files}

* **Definition**: Zone files are stored on name servers and contain detailed DNS information about a domain. They help the name server answer queries, particularly when it doesn’t immediately have the answer.  
* **Purpose**: Zone files organise DNS information in a readable and manageable way, listing records (like IP addresses, mail servers, and other data types) so the DNS system can quickly find the information it needs.  
* **Real-Life Analogy**: Think of a zone file as a mini-directory or spreadsheet within the name server. It lists the important details about each domain so that the server can quickly refer to them when needed.  
* **Example of a Zone File**:  
  * A typical zone file will have entries showing:  
    * The domain name  
    * Type of DNS record (e.g., A record for IP address, MX record for mail server)  
    * The name server that manages the domain

---

### **Summary** {#summary-4}

In DNS, **name servers** and **zone files** are critical for directing traffic. Name servers handle client requests, either directly (if they’re authoritative) or by seeking out the answer (if they’re recursive). Zone files organise all this information, like a set of directions that help name servers know where to point users, making internet navigation efficient and organised.

# DNS Components: Records {#dns-components:-records}

In this lesson, we’ll cover **DNS resource records**, which are essential components stored within a **zone file**. Each resource record carries specific details that DNS servers use to understand and process queries for domain names, IP addresses, mail servers, and other resources. Let’s break down the key components and types of records commonly used in DNS.

---

#### **1\. Key Components of Resource Records:** {#1.-key-components-of-resource-records:}

* **Record Name**: The domain name or label being queried (e.g., google.com).  
* **TTL (Time to Live)**: The duration (in seconds) that a record remains valid before needing a refresh. For example, a TTL of 3600 means the record is valid for one hour.  
* **Class**: Typically set to **IN** for "Internet," indicating the record is for internet resources.  
* **Type**: Defines the function of the record (e.g., A, AAAA, MX, CNAME, TXT).’  
* **NS**: Name server record  
* **Data**: The specific information corresponding to the record type. For example, an A record will store an IPv4 address as its data, while an AAAA record will hold an IPv6 address.

#### **2\. Common Types of DNS Records** {#2.-common-types-of-dns-records}

Let’s look at the different types of DNS records and their purposes:

* **A Record (Address Record)**:  
  * **Purpose**: Maps a domain name to an IPv4 address.  
  * **Example**: The A record for google.com might map to `216.58.204.79`.  
  * **Use**: This is the most common DNS record type and is critical for directing traffic to the correct IP address.  
* **AAAA Record (Quad A Record)**:  
  * **Purpose**: Maps a domain name to an IPv6 address, which is the newer IP address format.  
  * **Example**: The AAAA record for google.com might map to `2607:f8b0:4005:805::200e`.  
  * **Use**: Essential as IPv6 becomes more widely used, allowing DNS to accommodate both IPv4 and IPv6 traffic.  
* **CNAME Record (Canonical Name Record)**:  
  * **Purpose**: Creates an alias for a domain name, allowing multiple domain names to point to the same IP address.  
  * **Example**: `www.google.com` might be an alias (CNAME) for `google.com`.  
  * **Use**: Simplifies DNS management by allowing multiple domain names to be directed to a single address, which is especially helpful for larger websites.  
* **MX Record (Mail Exchange Record)**:  
  * **Purpose**: Specifies the mail server responsible for receiving emails for a domain.  
  * **Example**: The MX record for google.com might point to `mailserver.google.com`.  
  * **Priority**: MX records often include a priority value; lower values have higher priority, meaning those servers are attempted first.  
  * **Use**: Essential for ensuring emails are routed to the correct mail server, supporting reliable email delivery.  
* **TXT Record**:  
  * **Purpose**: Stores arbitrary text information within DNS.  
  * **Example**: TXT records are often used for verification purposes, such as proving ownership of a domain for email providers or web services.  
  * **Use**: Allows network engineers or domain administrators to add information such as SPF records (for email authentication) or domain verification codes.

---

#### **3\. Practical Example Using `dig`** {#3.-practical-example-using-dig}

To view DNS records for a domain, you can use the command-line tool `dig`:

* **Example Command**: Type `dig A domainname.com` to find the IPv4 address for a domain.  
* **Output**: The output will show various details, including the domain's IP address if an A record exists.  
* **Using `dig` for Different Records**: You can also use `dig MX domainname.com` to check mail servers or `dig TXT domainname.com` to see text records.

---

### **Summary** {#summary-5}

DNS records are at the core of the DNS system, enabling it to handle different types of data effectively. By understanding these records, including **A, AAAA, CNAME, MX,** and **TXT** records, you can appreciate how DNS handles everything from website access to email routing. Each record type serves a distinct purpose, ensuring that the right information is available for both users and services on the internet.

# How Does DNS Work? {#how-does-dns-work?}

Let's dive deeper into how DNS works using examples at each stage to make the concepts more tangible. We’ll go through domain resolution, DNS hierarchy, and the process of querying a domain name to get its IP address.

---

#### **1\. DNS Resolution – The Basics** {#1.-dns-resolution-–-the-basics}

DNS resolution is the process of converting a domain name (like `google.com`) into an IP address that a computer can understand. Here’s why it’s needed: imagine remembering `216.58.217.14` every time you wanted to visit Google\! DNS simplifies this by letting us use memorable names instead of numbers.

---

#### **2\. DNS Hierarchy – The DNS Tree** {#2.-dns-hierarchy-–-the-dns-tree}

The DNS system has a hierarchical structure, with several levels that work together. Let’s go step by step, using an example: finding the IP for `google.com`.

1. **Root Servers**:  
   * These servers sit at the top of the hierarchy, or "the boss," as you might say. They don’t know the exact IP address of `google.com`, but they know where to direct your query.  
   * **Example**: If you’re searching for `google.com`, the root server will say, “I don’t know `google.com` specifically, but check the `.com` TLD server.” There are 13 root server systems, labelled `A` through `M`, distributed globally.  
2. **Top-Level Domains (TLDs)**:  
   * Each **Top-Level Domain (TLD)** server (like `.com`, `.org`, `.net`) knows about all domains with that extension.  
   * **Example**: The `.com` TLD server knows about domains ending in `.com`. It will point the query towards an authoritative name server that can provide more information about `google.com`.  
3. **Authoritative Name Servers**:  
   * These are the servers that know everything about a specific domain, including its IP address, mail servers, and other records.  
   * **Example**: For `google.com`, the authoritative name server will contain the IP address (`216.58.217.14`) for the domain. When asked, it provides the exact IP address needed to connect to `google.com`.  
4. **Domains and Zone Files**:  
   * Each domain (like `google.com`) has a **zone file** that stores its DNS records, detailing information like IP addresses, email servers, and other essential data.  
   * **Example**: In Google’s zone file, an **A record** maps `google.com` to `216.58.217.14`, and **MX records** might map email functions to `mail.google.com`.

---

#### **3\. Step-by-Step: DNS Resolution Process (With an Example of `google.com`)** {#3.-step-by-step:-dns-resolution-process-(with-an-example-of-google.com)}

Let’s go through what happens when you type `google.com` in your browser.

1. **Browser to Resolver**:  
   * Your browser sends a request to a **local DNS resolver** (usually provided by your ISP).  
   * **Example**: If you type `google.com` in your browser, the resolver (like `8.8.8.8` for Google’s public DNS) will look up the IP address for `google.com`.  
2. **Resolver to Root Server**:  
   * If the IP address for `google.com` isn’t cached locally, the resolver queries the root server.  
   * **Example**: The root server says, “I don’t know `google.com`, but here’s where to find the `.com` TLD server.”  
3. **TLD Server**:  
   * The resolver then queries the `.com` TLD server, which directs the resolver to Google’s authoritative name server.  
   * **Example**: The `.com` TLD server points the resolver to the authoritative name server for `google.com`.  
4. **Authoritative Name Server**:  
   * The resolver queries Google’s authoritative name server, which responds with the IP address (`216.58.217.14`).  
   * **Example**: Google’s authoritative name server provides the IP for `google.com`, allowing the resolver to know exactly where to go.  
5. **Returning the IP**:  
   * The resolver sends the IP address back to your browser, and your browser connects directly to `216.58.217.14`, loading Google’s webpage.  
   * **Example**: Now, you see `google.com` in your browser without ever needing to know the IP.

---

#### **4\. Registrars vs. DNS Hosting Providers** {#4.-registrars-vs.-dns-hosting-providers}

It’s important to know the difference between a domain registrar and a DNS hosting provider.

### **Domain Registrar** {#domain-registrar}

* **Definition**: A company that allows you to **register** and **purchase** a domain name (like `example.com`).  
* **Functions**:  
  * Registers domain names.  
  * Manages domain settings (e.g., renewals, contact info).  
  * Works directly with TLD registries.  
* **Examples**: GoDaddy, Namecheap, Google Domains.  
* **Use Case**: You use a registrar to secure ownership of a domain name.

  ### **DNS Hosting Provider** {#dns-hosting-provider}

* **Definition**: A service that manages the **DNS records** for your domain, directing traffic to the correct server.  
* **Functions**:  
  * Hosts and manages DNS records (like A records, MX records).  
  * Ensures users reach the correct server when typing your domain.  
  * Offers features for performance and reliability.  
* **Examples**: Cloudflare, AWS Route 53, DNS Made Easy.  
* **Use Case**: You use a DNS hosting provider to set up DNS records for your domain.

  ### **Key Differences** {#key-differences}

* **Primary Function**: Registrars handle domain registration, while DNS providers manage DNS records.  
* **Integration**: After registering a domain with a registrar, you often point it to a DNS provider for record management.

In essence, you first register a domain name through a registrar and then use a DNS hosting provider to manage how that domain connects to your website or services.

---

#### **5\. Example DNS Query Process** {#5.-example-dns-query-process}

Let’s see an example of a **DNS query process** from your computer:

#### **Step 1: Your Browser Asks the DNS Resolver** {#step-1:-your-browser-asks-the-dns-resolver}

* **What Happens**: Your browser needs to find `google.com`’s IP address, it checks the local cache amd the host file /etc/hosts file to see if it can find it there. If it is not there it sends a query to your **local DNS resolver**. This resolver is typically managed by your Internet Service Provider (ISP), or it could be a public resolver like Google’s `8.8.8.8`.  
* **Example**: You type `google.com` in the browser. The browser sends a query to the local DNS resolver, asking, "What’s the IP address for `google.com`?"  
  ---

  #### **Step 2: Resolver Checks Local Cache** {#step-2:-resolver-checks-local-cache}

* **What Happens**: The resolver checks if it has recently looked up `google.com` and cached the IP address. If it finds it, the process stops here, and it sends the cached IP address back to your browser, making the query very fast.  
* **Example**: If the resolver had recently looked up `google.com`, it might still have `142.250.180.14` saved in its memory. It would quickly return this IP to your browser, skipping the rest of the process.  
* **If Not Cached**: If `google.com` isn’t cached, the resolver starts a journey to find the IP address.

  #### **Step 3: Resolver Queries a Root Server** {#step-3:-resolver-queries-a-root-server}

* **What Happens**: The DNS resolver now reaches out to one of the 13 DNS **Root Servers** around the world, which are the top-level servers in the DNS system. These root servers don’t have the specific IP for `google.com`, but they know where to find information about `.com` domains.  
* **Example**: The resolver asks the root server, "Where can I find information on `google.com`?" The root server responds, "I don’t know the IP for `google.com`, but try the `.com` TLD server."

  #### **Step 4: Resolver Queries the .com TLD Server** {#step-4:-resolver-queries-the-.com-tld-server}

* **What Happens**: The resolver follows the root server’s advice and contacts the **Top-Level Domain (TLD) server** for `.com`. This server manages all `.com` domains and can point the resolver to the specific DNS servers that handle `google.com`.  
* **Example**: The resolver asks the `.com` TLD server, "Do you know where `google.com` is?" The `.com` TLD server responds, "I don’t have the exact IP, but you can ask Google’s authoritative DNS server. Here’s where to find it."

  #### **Step 5: Resolver Queries the Authoritative Name Server for `google.com`** {#step-5:-resolver-queries-the-authoritative-name-server-for-google.com}

* **What Happens**: Now that the resolver knows where Google’s **authoritative DNS server** is, it queries this server directly. The authoritative name server has the exact DNS records for `google.com`, including the IP address.  
* **Example**: The resolver asks Google’s authoritative server, "What is the IP address for `google.com`?" The authoritative server responds, "The IP address you’re looking for is `142.250.180.14`."

  #### **Step 6: Resolver Sends the IP Address Back to Your Browser** {#step-6:-resolver-sends-the-ip-address-back-to-your-browser}

* **What Happens**: Now that the resolver has the IP address, it returns it to your browser. Your browser uses this IP to connect to Google’s web server and load the webpage.  
* **Example**: The resolver sends `142.250.180.14` back to your browser. Your browser connects to this IP, and Google’s homepage appears on your screen.


  #### **Step 7: Caching for Next Time** {#step-7:-caching-for-next-time}

* **What Happens**: The DNS resolver caches the IP address for `google.com` for a short time (according to its Time To Live or TTL setting) so that future requests for `google.com` can be answered more quickly without going through the entire query process again.  
* **Example**: Next time you or someone else requests `google.com`, the resolver can return `142.250.180.14` immediately from its cache, making it much faster.

---

### **Recap with Example Flow** {#recap-with-example-flow}

When you type `google.com`:

1. Your browser queries the **local DNS resolver**.  
2. The resolver checks **root servers**, then the **.com TLD server**, then **Google’s authoritative server**.  
3. The resolver gets the IP address and sends it back to your browser, connecting you to Google.

This layered approach ensures quick, reliable DNS resolution so websites load efficiently no matter where they’re hosted.

## 

# Network Debugging Tools: 'nslookup' and 'dig' {#network-debugging-tools:-'nslookup'-and-'dig'}

### **1\. Introduction to DNS Query Tools** {#1.-introduction-to-dns-query-tools}

* **`nslookup`**: A command-line utility for querying the Domain Name System (DNS) to obtain domain name or IP address mapping.  
* **`dig`**: (domain information groper) A more advanced DNS query tool that provides detailed DNS information, useful for troubleshooting and analysis.

### **2\. Using `nslookup`** {#2.-using-nslookup}

#### **Step-by-Step Guide** {#step-by-step-guide}

* **Open Your Terminal**:  
  * **Windows**: Search for "cmd" to open Command Prompt.  
  * **macOS/Linux**: Open the Terminal application.

**Run the Command**:  
bash  
Copy code  
`nslookup youtube.com`

#### **Example Output** {#example-output}

yaml  
Copy code  
`![][image3]`

#### **Understanding the Output** {#understanding-the-output}

* **Server**: The DNS server used to resolve the query.  
* **Address**: The IP address of the DNS server.  
* **Non-authoritative answer**: Indicates that the response is cached and not directly from the authoritative DNS server.  
* **Name**: The domain name queried.  
* **Addresses**: The IP addresses associated with the domain. Multiple addresses may be listed for load balancing.

#### **Real-Life Example** {#real-life-example}

* When visiting `youtube.com`, your computer queries a DNS server to find the IP address associated with it. Instead of remembering the numeric IP (e.g., 142.250.72.206), you just type the domain name.

### **3\. Using `dig`** {#3.-using-dig}

#### **Step-by-Step Guide** {#step-by-step-guide-1}

* **Open Your Terminal Again**:  
  * Same as above.

**Run the Command**:  
bash  
Copy code  
`dig youtube.com`

#### **Example Output** {#example-output-1}

![][image4]  
**Understanding the Output**

* **HEADER**: Contains metadata about the query, including the opcode (type of query) and status (like NOERROR).  
* **QUESTION SECTION**: Displays the original question asked (e.g., IP address of `youtube.com`).  
* **ANSWER SECTION**: Lists the response from the DNS server, including IP addresses.  
* **Query time**: Time taken to receive a response.  
* **SERVER**: The DNS server that answered the query.  
* **WHEN**: The date and time of the query.  
* **MSG SIZE**: The size of the message received.

#### **Real-Life Example** {#real-life-example-1}

* When you use `dig`, you get detailed information about the DNS resolution process for `youtube.com`, including multiple IP addresses associated with it, which can be useful for network troubleshooting or configuration.

---

### **Summary** {#summary-6}

* **`nslookup`** is straightforward and good for quick queries, showing basic DNS information.  
* **`dig`** offers detailed information and is more useful for debugging or complex DNS scenarios.  
* Both tools provide insights into how domain names are resolved to IP addresses, making it easier to understand how the Internet works.

### **Practical Usage** {#practical-usage}

* These tools are essential for network engineers and IT professionals to diagnose and fix DNS-related issues, ensuring smooth connectivity and web browsing.

# /etc/hosts File {#/etc/hosts-file}

### **1\. Introduction to the `/etc/hosts` File** {#1.-introduction-to-the-/etc/hosts-file}

* The `/etc/hosts` file is a local configuration file on your computer used to map domain names to IP addresses.  
* It allows you to override DNS settings for specific domains, providing an alternative IP address.  
* This can be particularly useful for:  
  * **Development**: Testing websites or applications locally.  
  * **Troubleshooting**: Quickly redirecting traffic without changing DNS records.

### **2\. How the `/etc/hosts` File Works** {#2.-how-the-/etc/hosts-file-works}

* When you enter a domain name into your web browser, your computer first checks the `/etc/hosts` file.  
* If the domain is listed there, it uses the corresponding IP address instead of querying a DNS server.  
* This process helps speed up access to local resources and can assist in development environments.

### **3\. Editing the `/etc/hosts` File** {#3.-editing-the-/etc/hosts-file}

#### **Step-by-Step Guide** {#step-by-step-guide-2}

* **Open a Terminal**:  
  * **macOS/Linux**: Use the Terminal app.  
  * **Windows**: Open Command Prompt or PowerShell (the equivalent file is `C:\Windows\System32\drivers\etc\hosts`).  
* **Edit the File**:  
  * You need administrative privileges to edit the `/etc/hosts` file.  
  * Use a text editor to open the file:

For example:  
Copy code  
`sudo vim /etc/hosts`

or

`sudo nano /etc/hosts`

* The `sudo` command gives you temporary administrative rights to edit the file.

#### **Format of the Entry** {#format-of-the-entry}

Each line should contain:  
Copy code  
`<IP Address> <Domain Name>`

**Example**: Mapping `example.com` to the local IP address `127.0.0.1`:  
Copy code  
`127.0.0.1 example.com`

### **4\. Practical Examples** {#4.-practical-examples}

#### **Example 1: Map `example.com` to Localhost** {#example-1:-map-example.com-to-localhost}

* **Mapping**: To redirect `example.com` to your local machine:  
  * Open the `/etc/hosts` file.

Add the following line:  
Copy code  
`127.0.0.1 example.com`

* **Test**: After saving the file, type `http://example.com` in your browser. It should redirect to your local server (localhost).

#### **Example 2: Map `dev.local` to a Local Server IP** {#example-2:-map-dev.local-to-a-local-server-ip}

**Find Local Server IP**: Use `nslookup` to find an IP address. For instance:

Copy code  
`nslookup google.com`

* This might return a result like `142.250.72.206`.

**Mapping**: Open the `/etc/hosts` file and add the line:

Copy code  
`142.250.72.206 dev.local`

* **Test**: Open your browser and go to `http://dev.local`. It should direct you to the IP you mapped.

### **5\. Important Considerations** {#5.-important-considerations}

* **Remove Entries After Testing**: After you finish testing, always remember to remove any entries you added to the `/etc/hosts` file. Otherwise, you might experience unexpected behaviour when trying to access the original domains, like Google.  
* **Why Remove Entries?**: If you don’t remove the entries, your browser will continue to use the IP addresses from the `/etc/hosts` file instead of resolving through DNS, which can lead to confusion and connectivity issues.

### **6\. Real-Life Scenarios** {#6.-real-life-scenarios}

* **Local Development**: Developers often use the `/etc/hosts` file to test websites locally before deploying them. By mapping domain names to local IPs, they can view changes in real time.  
* **Temporary Redirects**: If a website is down or being migrated, you can temporarily map the old domain to a different server IP for testing purposes.

### **Conclusion** {#conclusion}

* The `/etc/hosts` file is a powerful tool for developers and network engineers, enabling quick domain-to-IP mappings and facilitating local testing.  
* Understanding how to use this file can help streamline development processes and troubleshoot network issues effectively.

# 

# What is Routing? {#what-is-routing?}

A. What is Routing and why it matters?  
B. Static vs Dynamic Routing  
C. Common routing protocols (BGP, OSPF etc)

### **1\. Definition of Routing** {#1.-definition-of-routing}

* **Routing** is the process of determining the best path for data to travel across different networks.  
* Think of it as a GPS for data, finding the most efficient route from point A to point B.  
* **Importance of Routing**:  
  * Ensures that data packets are sent efficiently and without issues.  
  * Prevents data loss and minimises delays in data transmission.  
  * Essential for the internet to function smoothly, facilitating seamless communication and data exchange.

### **2\. Routing Process** {#2.-routing-process}

* **Routing Tables**:  
  * Routers use routing tables to make decisions about where to send data.  
  * These tables serve as maps, indicating the best routes available.

#### **Example of Routing:** {#example-of-routing:}

1. **Data Transmission**:  
   * Imagine you want to send a message from your computer (Computer A) to a friend's computer (Computer B).  
2. **Data Path**:  
   * Your data first travels to your **router**.  
   * The router checks its **routing table** to determine the best path for the data.  
3. **Routing Path**:  
   * The data might travel through multiple networks (Network 1, Network 2, etc.) before reaching its final destination.  
   * For instance, data might hop through:  
     * **Network 1** → **Network 3** → **Network 2** → **Computer B**.

![][image5]

### **3\. Importance of Routing for Network Professionals** {#3.-importance-of-routing-for-network-professionals}

* **Network Performance Optimization**:  
  * Good routing ensures that data packets take the most efficient path, reducing latency and improving overall network performance.  
* **Reliable Application Delivery**:  
  * Proper routing is vital for delivering applications and services, especially in complex cloud environments.  
* **Managing Complex Infrastructures**:  
  * As a DevOps engineer, understanding routing and route tables is crucial for managing and troubleshooting complex network environments.

**4\. Static vs. Dynamic Routing**

#### **Static Routing:** {#static-routing:}

* **Definition**:  
  * Static routing involves manually configuring routes in a router's routing table.  
* **Characteristics**:  
  * More straightforward and predictable.  
  * Suitable for smaller networks where changes are infrequent.  
* **Example**:  
  * If a small office network has a fixed number of devices, a network engineer might manually set the routes between these devices to ensure traffic flows correctly.

#### **Dynamic Routing:** {#dynamic-routing:}

* **Definition**:  
  * Dynamic routing automatically adjusts the routing table based on current network conditions using routing protocols.  
* **Characteristics**:  
  * More flexible and efficient for larger, more complex networks.  
  * Adapts to changes, such as network failures or congestion.  
  * Scalable and adaptable.  
* **Example**:  
  * In a large organisation with multiple branch offices, routers can automatically update their routing tables to find the best path as the network topology changes.

### **5\. Common Routing Protocols** {#5.-common-routing-protocols}

Routing protocols uses algorithms to figure out the best paths for data to travel from one place to another. They automate route updates which improves network resilience.

* **BGP (Border Gateway Protocol)**:  
  * Used to exchange routing information between different autonomous systems on the internet.  
* **OSPF (Open Shortest Path First)**:  
  * A dynamic routing protocol used within a single autonomous system, suitable for larger networks.  
* **RIP (Routing Information Protocol)**:  
  * An older dynamic routing protocol that uses hop count as its routing metric, mainly suitable for smaller networks.

### **Summary** {#summary-7}

* **Routing** is crucial for determining efficient paths for data across networks, ensuring reliable communication and optimal performance.  
* Understanding both **static** and **dynamic routing** is essential for network engineers to manage and troubleshoot network infrastructures effectively.  
* Familiarity with routing protocols like **BGP** and **OSPF** enhances a network professional's ability to maintain efficient and resilient networks.

# 

# Static vs. Dynamic Routing {#static-vs.-dynamic-routing}

### **Overview** {#overview}

Routing, which we’ve discussed before, is essential to determining the best paths for data across networks. Here, we focus on two main types of routing: **Static Routing** and **Dynamic Routing**. Each approach has its own advantages and is suited to different types of networks.

---

### **1\. Static Routing** {#1.-static-routing}

* **Definition**:  
  * Static routing involves manually configuring routes within a network. A network admin sets up specific, fixed paths for data to follow.  
  * Static routes remain unchanged unless they are manually updated by the admin.  
* **Characteristics**:  
  * **Reliability**: Static routing is straightforward and predictable, making it a good choice for smaller, stable networks.  
  * **Lack of Adaptability**: If network changes occur (e.g., a device goes offline, or a new device is added), the route will not adjust on its own. The admin must manually update it.  
  * **Not Scalable**: As networks grow larger, managing static routes becomes challenging and prone to errors.

#### **Real-Life Example of Static Routing:** {#real-life-example-of-static-routing:}

* **Fixed Driving Directions**: Imagine you have printed driving directions from your home to a friend’s house, following a specific set of roads. If there’s construction or a traffic jam on one of these roads, you’re stuck on this path unless you manually reconfigure a new route.  
* **Example Network Setup**: A small business office network might use static routing for routing data to a single, central server in their building. The admin sets this route manually, ensuring data reaches the server reliably. However, if the network expands, static routing may become too rigid and inefficient.

---

### **2\. Dynamic Routing** {#2.-dynamic-routing}

* **Definition**:  
  * Dynamic routing automatically adjusts routes using specific routing protocols. It finds the best path based on the current network conditions, adapting as changes occur.  
* **Characteristics**:  
  * **Flexibility**: Dynamic routing can adjust to new devices, network issues, or traffic loads in real-time.  
  * **Scalability**: Dynamic routing is well-suited to larger, more complex networks, as it minimises the need for constant manual updating.  
  * **Efficiency**: Like a GPS that recalculates directions when it detects a traffic jam, dynamic routing adapts to ensure data takes the most efficient route.

#### **Real-Life Example of Dynamic Routing:** {#real-life-example-of-dynamic-routing:}

* **GPS Navigation**: Imagine using a GPS app for driving. If the app detects traffic on your planned route, it automatically finds an alternative path to get you to your destination faster.  
* **Corporate Network Example**: A large corporation with multiple branch offices would use dynamic routing to ensure data flows smoothly across all its locations. If one network path fails or experiences heavy traffic, dynamic routing protocols adjust the routes accordingly, without any manual intervention.

---

### **3\. Comparison of Static vs. Dynamic Routing** {#3.-comparison-of-static-vs.-dynamic-routing}

### ![][image6]

---

### **4\. Common Dynamic Routing Protocols** {#4.-common-dynamic-routing-protocols}

#### **a. OSPF (Open Shortest Path First):** {#a.-ospf-(open-shortest-path-first):}

* **Purpose**: Finds the shortest path in a network, optimising data travel time.  
* **Use**: Ideal for networks within a single organisation or a local network area.

#### **b. BGP (Border Gateway Protocol):** {#b.-bgp-(border-gateway-protocol):}

* **Purpose**: Exchanges routing information between large networks or “autonomous systems” (e.g., different internet service providers).  
* **Use**: Essential for routing across the internet, helping to manage traffic between vast network zones.

---

### **Summary** {#summary-8}

* **Static Routing**:  
  * Reliable and simple, but lacks flexibility and scalability, making it better for smaller networks.  
* **Dynamic Routing**:  
  * Flexible and scalable, adjusting routes in real-time, making it ideal for large, complex, or changing networks.

Understanding these types of routing is crucial for network engineers and IT professionals, who often need to balance the reliability of static routes with the adaptability of dynamic routing to manage effective data flow across networks.

# Common Routing Protocols {#common-routing-protocols}

### **Overview** {#overview-1}

Routing protocols are essential tools in networking that determine the best path for data to travel across networks. Instead of setting up routes manually, routing protocols use algorithms to automate the process, improving network efficiency, reliability, and performance.

---

### **What are Routing Protocols?** {#what-are-routing-protocols?}

* **Purpose**: Routing protocols help find the most efficient path for data to travel from one network location to another.  
* **Function**: They act like a "smart assistant" that constantly updates and optimises routes, adapting in real-time to changes in the network.  
* **Benefits**:  
  * **Enhanced Efficiency**: Routing protocols help reduce network congestion by selecting the optimal path for data.  
  * **Automated Routing**: They update routes without requiring manual intervention, reducing the risk of errors and the need for constant updates.  
  * **Network Resilience**: If a network path fails, routing protocols can quickly find an alternative path, maintaining connectivity.

---

### **Two Key Routing Protocols: OSPF and BGP** {#two-key-routing-protocols:-ospf-and-bgp}

#### **1\. OSPF (Open Shortest Path First)** {#1.-ospf-(open-shortest-path-first)}

* **Purpose**: OSPF is a protocol used within large organisations to determine the shortest path for data within a single network or autonomous system (AS).  
* **Functionality**:  
  * OSPF uses something called **link-state information**. This is a complex system that evaluates the status (or “state”) of network links and the cost of using them, making efficient routing decisions.  
  * **Fast Convergence**: OSPF is known for quickly recalculating routes if there are changes in the network, like a link going down, ensuring that data keeps moving efficiently.  
* **Best Use**: Primarily used in **internal, large-scale networks**, such as an enterprise’s internal network.  
* **Example**:  
  * Imagine OSPF as a company’s internal mail system. Suppose you’re sending a message from the New York office to the San Francisco office. OSPF would find the shortest, least congested route within the company’s network, using existing paths and bypassing any internal issues to ensure fast delivery.

---

#### **2\. BGP (Border Gateway Protocol)** {#2.-bgp-(border-gateway-protocol)}

* **Purpose**: BGP routes data between different networks or “autonomous systems” (AS) managed by different organisations, making it essential for communication across the internet.  
* **Functionality**:  
  * BGP uses a **path vector mechanism** to maintain path information between networks. This means that it doesn’t only look for the shortest path but also considers the entire route, including various attributes or preferences defined by network administrators.  
  * **Routing Policies**: BGP allows network admins to set policies, offering control over how traffic flows through the network. For instance, a company might route its data through specific networks to improve performance, reduce costs, or enhance security.  
* **Best Use**: Primarily used for **internet-level routing**, managing data between large, separate networks across different locations and organisations.  
* **Example**:  
  * BGP is like an international courier service that handles packages between different postal systems across countries. Suppose you send a package from the U.S. to Europe. BGP will determine the best path across multiple countries’ postal systems, considering policies (like customs requirements or preferred transport partners) to ensure the most reliable delivery route.

---

### 

### 

### **Summary of OSPF vs BGP** {#summary-of-ospf-vs-bgp}

![][image7]

### ---

### **Key Takeaways** {#key-takeaways}

1. **Routing Protocols**:  
   * Routing protocols, like OSPF and BGP, use algorithms to automate and optimise routes for data within and between networks.  
2. **OSPF**:  
   * Suited for internal, large-scale networks; it finds the shortest and least congested path for data using link-state information.  
3. **BGP**:  
   * Essential for internet routing; it manages data between large networks, considering policies for reliable, efficient delivery.

Understanding routing protocols like OSPF and BGP is crucial for network professionals to design resilient, high-performance networks that can adapt to traffic changes, network expansions, and global data exchanges.

## 

# Subnetting and CIDR {#subnetting-and-cidr}

### **Overview** {#overview-2}

Subnetting and CIDR (Classless Inter-Domain Routing) are fundamental concepts in networking that allow large networks to be divided into smaller, more manageable networks, called subnets. This not only improves network organisation but also increases efficiency, especially as networks grow in complexity and size.

---

### **What is Subnetting?** {#what-is-subnetting?}

* **Definition**: Subnetting is the process of dividing a large network into smaller, more manageable subnetworks (subnets).  
* **Purpose**:  
  * **Improved Management**: Subnetting organizes IP address space more effectively, making it easier to manage devices on different networks.  
  * **Efficiency**: By splitting a network into subnets, you reduce the amount of unnecessary data (or “traffic”) that flows across the entire network. This means faster speeds and less congestion.  
* **Example**:  
  * Imagine a large office building with multiple departments (e.g., Finance, HR, and Marketing). Each department has its own subnet to ensure their data flows independently without crossing into other departments’ networks. This segmentation means that Finance doesn’t slow down HR’s network traffic and vice versa.

---

### **CIDR (Classless Inter-Domain Routing)** {#cidr-(classless-inter-domain-routing)}

* **Definition**: CIDR is a method for allocating IP addresses and routing IP packets efficiently, especially in large networks or the internet.  
* **CIDR Notation**:  
  * The format is straightforward: an IP address is followed by a **slash (/)** and a number indicating the prefix length, which specifies how many bits are used for the network part of the address.  
  * **Example**: `192.168.1.0/24`  
    * The **IP Address** (`192.168.1.0`) represents the network address.  
    * The **/24** (CIDR prefix) indicates that the first 24 bits are reserved for the network, leaving the remaining bits to designate individual host addresses within that network.

---

### **Understanding CIDR Notation and Subnet Masks** {#understanding-cidr-notation-and-subnet-masks}

* **Subnet Mask**: A subnet mask defines which portion of an IP address is designated for the network and which is for hosts (devices) within that network.  
  * For example, `/24` means the first 24 bits of the subnet mask are set to "1" (for the network portion), and the remaining bits are "0" (for the host portion).  
  * **Example**: In a subnet mask, `255.255.255.0` represents `/24` in CIDR notation.

#### **Step-by-Step Breakdown of CIDR Example** {#step-by-step-breakdown-of-cidr-example}

* **Example**: `192.168.1.0/24`  
  * **Network Part**: The first 24 bits (192.168.1) define the network.  
  * **Host Part**: The remaining bits (last 8 bits, as `0`) are for host addresses within that network.  
  * **Address Range**: This notation allows up to 256 addresses (0 to 255), where 192.168.1.0 is the network address and 192.168.1.255 is the broadcast address, leaving 254 usable addresses for devices.

---

### **Binary Basics in Subnetting** {#binary-basics-in-subnetting}

* **Binary Representation**: IP addresses and subnet masks are often represented in binary (a series of 0s and 1s) to simplify calculations.  
  * **Example**: `192.168.1.0` in binary is `11000000.10101000.00000001.00000000`.  
  * Using binary, the subnet mask `/24` becomes `11111111.11111111.11111111.00000000` (255.255.255.0 in decimal).

#### **Calculating Host Ranges in Subnets** {#calculating-host-ranges-in-subnets}

1. **Determine the Subnet Size**: For a `/24` subnet, the last 8 bits are available for host addresses (2^8 \= 256 addresses).  
2. **Host Range**: With 256 addresses, 2 are reserved (1 for the network address and 1 for the broadcast address), leaving 254 usable addresses.

---

### **Key Takeaways** {#key-takeaways-1}

1. **Subnetting**: Breaking down a larger network into smaller subnets for better management and efficiency.  
2. **CIDR Notation**: Used to define the network and host portions of an IP address, with a format like `192.168.1.0/24`.  
3. **Subnet Masks**: Work alongside CIDR notation to indicate which parts of the IP address are for the network and which are for hosts.  
4. **Binary Representation**: Essential in understanding subnetting, as binary helps in calculating network and host addresses within subnets.

---

### **Practical Applications of Subnetting and CIDR** {#practical-applications-of-subnetting-and-cidr}

Subnetting and CIDR are widely used by network engineers to:

* **Allocate IP Ranges**: For different departments or teams in an organisation, such as giving Finance and HR separate IP ranges.  
* **Limit Network Traffic**: By segmenting networks, devices on one subnet don’t flood another subnet with unnecessary traffic.  
* **Enhance Security**: Subnetting can improve security by isolating network segments and controlling access.

Mastering subnetting and CIDR is essential for network design and management, as they provide structure and efficiency to both small and large networks.

# Binary: Yep 1s and 0s {#binary:-yep-1s-and-0s}

### **Overview** {#overview-3}

Binary is the foundational language in computer science and networking, as it enables all data processing by computers and digital networks. In networking, binary is particularly crucial for understanding how **IP addresses** and **subnetting** work.

### **What is Binary?** {#what-is-binary?}

* **Definition**: Binary is a **base-2 number system** that uses only two digits: **0 and 1**.  
* **Importance in Networking**: Binary is the language that computers and networking devices “speak,” and it’s also how IP addresses are understood and managed by routers and devices across a network.

---

### **How Binary Works** {#how-binary-works}

* **Binary Representation**:  
  * Each binary digit (1 or 0\) is called a **bit**.  
  * In binary, each bit represents an increasing power of 2, starting from the rightmost bit (2^0) and moving left.  
* **Example**:  
  * For binary `101010`, each bit corresponds to:  
    * 252^525, 242^424, 232^323, 222^222, 212^121, and 202^020.  
  * Converting `101010` to decimal involves calculating each power and adding them up.

#### **Step-by-Step Conversion from Binary to Decimal** {#step-by-step-conversion-from-binary-to-decimal}

1. Write out the binary number (e.g., `101010`).  
2. Start from the rightmost bit, moving left:  
   * **Bit 1 (far right)**: 20×0=02^0 \\times 0 \= 020×0=0  
   * **Bit 2**: 21×1=22^1 \\times 1 \= 221×1=2  
   * **Bit 3**: 22×0=02^2 \\times 0 \= 022×0=0  
   * **Bit 4**: 23×1=82^3 \\times 1 \= 823×1=8  
   * **Bit 5**: 24×0=02^4 \\times 0 \= 024×0=0  
   * **Bit 6**: 25×1=322^5 \\times 1 \= 3225×1=32  
3. Add up these values: 0+2+0+8+0+32=420 \+ 2 \+ 0 \+ 8 \+ 0 \+ 32 \= 420+2+0+8+0+32=42.  
   * **Result**: `101010` in binary equals **42** in decimal.

---

### **Converting IP Addresses to Binary** {#converting-ip-addresses-to-binary}

IP addresses are structured in **four octets** (e.g., `192.168.1.1`), where each octet represents a separate binary number. Each octet is converted into binary individually.

#### **Step-by-Step Conversion of `192.168.1.1` to Binary** {#step-by-step-conversion-of-192.168.1.1-to-binary}

1. **Convert 192**:  
   * Divide 192 by 2 repeatedly, noting the remainders:  
     * 192 ÷ 2 \= 96, remainder 0  
     * 96 ÷ 2 \= 48, remainder 0  
     * 48 ÷ 2 \= 24, remainder 0  
     * 24 ÷ 2 \= 12, remainder 0  
     * 12 ÷ 2 \= 6, remainder 0  
     * 6 ÷ 2 \= 3, remainder 0  
     * 3 ÷ 2 \= 1, remainder 1  
     * 1 ÷ 2 \= 0, remainder 1  
   * **Binary for 192**: By reading the remainders from bottom to top, we get `11000000`.  
2. **Convert 168**:  
   * Follow the same process:  
     * 168 ÷ 2 \= 84, remainder 0  
     * 84 ÷ 2 \= 42, remainder 0  
     * 42 ÷ 2 \= 21, remainder 0  
     * 21 ÷ 2 \= 10, remainder 1  
     * 10 ÷ 2 \= 5, remainder 0  
     * 5 ÷ 2 \= 2, remainder 1  
     * 2 ÷ 2 \= 1, remainder 0  
     * 1 ÷ 2 \= 0, remainder 1  
   * **Binary for 168**: Reading from bottom to top, `10101000`.  
3. **Convert 1**:  
   * Converting `1` is straightforward in binary: it’s `00000001`.  
4. **Final Binary Representation for `192.168.1.1`**:

The full binary representation becomes:  
Copy code  
`192.168.1.1 = 11000000.10101000.00000001.00000001`

* 

---

### **Practice Exercise** {#practice-exercise}

* **Convert the IP address `10.0.0.1` and the subnet mask `255.0.0.0` to binary**:  
  * **Solution**:  
    * `10.0.0.1` in binary is `00001010.00000000.00000000.00000001`.  
    * `255.0.0.0` in binary is `11111111.00000000.00000000.00000000`.

### **Key Takeaways** {#key-takeaways-2}

1. **Binary Basics**: Binary uses only 0s and 1s, with each bit representing an increasing power of 2 from right to left.  
2. **Conversion Importance**: Converting IP addresses to binary allows for easier subnetting and IP address management.  
3. **Practical Application**: Network engineers often work with binary to set up, manage, and troubleshoot network addresses and subnet masks.

---

By mastering binary and IP conversion, you’ll have a solid foundation to tackle more advanced networking concepts like subnetting, routing, and CIDR.

# **Calculating Subnets** {#calculating-subnets}

### **Quick Recap on Subnetting** {#quick-recap-on-subnetting}

Subnetting is the practice of dividing a large network into smaller, more manageable **subnetworks** or **subnets**. Subnetting provides two main benefits:

1. **Efficient Management of IP Addresses** by organizing them logically within a network.  
2. **Improved Network Performance** by isolating sections of the network.

### **Understanding the Role of Subnet Masks** {#understanding-the-role-of-subnet-masks}

A **subnet mask** defines which part of an IP address belongs to the network and which part is designated for hosts. By reading the subnet mask, routers can determine where a network ends and hosts begin.

#### **Example of a Subnet Mask** {#example-of-a-subnet-mask}

* **Subnet Mask**: `255.255.255.0`  
  * This subnet mask indicates that the **first 24 bits** of the IP address are reserved for the network, and the **last 8 bits** are for host addresses.  
  * This can be represented in **CIDR notation** as `/24`, meaning 24 bits are reserved for the network.

---

### **Calculating Subnets and Host Ranges** {#calculating-subnets-and-host-ranges}

#### **Key Concepts for Subnet Calculations** {#key-concepts-for-subnet-calculations}

1. **Network Address**: The first address in a subnet, representing the network itself.  
2. **Broadcast Address**: The last address in a subnet, used to communicate with all hosts within that subnet.  
3. **Usable IP Range**: The IP addresses between the network and broadcast addresses, available for assigning to devices.

#### **Example: Subnetting with `192.168.10.0/26`** {#example:-subnetting-with-192.168.10.0/26}

Let’s go through how to calculate the **network address**, **broadcast address**, and **usable IP range** for `192.168.10.0/26`.

1. **CIDR Notation Insight**:  
   * `/26` indicates that **26 bits** are for the network portion.  
   * Since IPv4 addresses are 32 bits, this leaves **6 bits** for host addresses.  
2. **Calculate Subnet Size**:  
   * Since there are 6 bits for hosts, the number of IP addresses in this subnet is 26=642^6 \= 6426=64.  
   * **Usable IP Addresses**: Excluding the network and broadcast addresses, usable addresses are 64−2=6264 \- 2 \= 6264−2=62.  
3. **Subnet Range Calculation**:  
   * The subnet for `192.168.10.0/26` spans 64 addresses.  
   * **Network Address**: `192.168.10.0`  
   * **Broadcast Address**: `192.168.10.63`  
   * **Usable IP Range**: `192.168.10.1` to `192.168.10.62`

---

### **Practice Exercise** {#practice-exercise-1}

Using the same approach:

* **Determine the Network Address, Broadcast Address, and Usable Range** for an IP in the subnet `10.0.0.0/28`.

**Solution**:

* **CIDR /28**: 28 bits for the network, leaving 4 bits for host addresses.  
* **Subnet Size**: 24=162^4 \= 1624=16 total addresses in this subnet.  
* **Usable IP Addresses**: 16 \- 2 \= 14 usable IPs.  
* **Network Address**: `10.0.0.0`  
* **Broadcast Address**: `10.0.0.15`  
* **Usable IP Range**: `10.0.0.1` to `10.0.0.14`

---

### **Key Takeaways** {#key-takeaways-3}

1. **Subnet Masks**: Define network and host portions of an IP address.  
2. **CIDR Notation**: Indicates the number of bits reserved for the network in an address.  
3. **Subnet Calculation**: Knowing the subnet mask or CIDR allows you to determine network structure, including network, broadcast, and usable IPs.

This foundation will help you to calculate subnet addresses quickly, plan IP allocation, and optimise network configurations.

# NAT (Network Address Translation) {#nat-(network-address-translation)}

### **What is NAT?** {#what-is-nat?}

NAT, or **Network Address Translation**, is a method that enables a device on a private network to communicate on the internet using a **shared public IP address**. It translates each device’s private IP (e.g., those on a home or office network) into a single public IP when they access external networks like the internet.

#### **Example:** {#example:}

In a home network, devices like your phone, laptop, and smart fridge each have private IP addresses. NAT translates these private IPs to a single public IP so they can connect to the internet. This way, your entire network only needs one public IP.

---

### **Why Use NAT?** {#why-use-nat?}

1. **Conservation of Public IPs**: IPv4 addresses are limited, so NAT helps avoid the need for every device to have its own unique public IP.  
2. **Simplifies Internet Access**: Instead of requiring each device to be directly connected with a public IP, NAT handles the translation, making network management easier.  
3. **Network Security**: By keeping internal private IPs hidden, NAT adds a layer of security, preventing direct external access to individual devices.

---

### **How Does NAT Work?** {#how-does-nat-work?}

1. **Private IP to Public IP Translation**: NAT occurs on your router, which translates a device’s private IP (e.g., `192.168.1.10`) to a public IP when it sends data to an external network.  
2. **Public IP to Private IP Translation**: When data returns to the router, NAT translates the public IP back to the original private IP, so the data reaches the correct device.

#### **Example Walkthrough:** {#example-walkthrough:}

1. **Internal Device Request**: A device with IP `192.168.1.10` requests data from a website.  
2. **Router Translation**: The router translates `192.168.1.10` to the network’s public IP (e.g., `98.117.53.254`) and forwards the request.  
3. **Response from Website**: The website sends data back to the public IP `98.117.53.254`.  
4. **NAT Translation Back**: The router translates this response back to `192.168.1.10`, delivering it to the correct device.

---

### **Types of NAT** {#types-of-nat}

There are three common types of NAT, each suited to different networking needs:

1. **Static NAT**  
   * **One-to-One Mapping**: Maps a private IP to a fixed public IP.  
   * **Use Case**: Ideal for a device that needs a consistent public IP, such as a web server.  
   * **Example**: `192.168.0.10` is always mapped to `203.0.113.1`.  
2. **Dynamic NAT**  
   * **One-to-Many Mapping from a Pool of Public IPs**: Assigns a public IP to a private IP from a pool, only when needed.  
   * **Use Case**: Useful when there are multiple devices, but only a few need to be online at the same time.  
   * **Example**: A pool of public IPs `203.0.113.1` to `203.0.113.10` is used as needed for different devices.  
3. **PAT (Port Address Translation), or NAT Overload**  
   * **One-to-Many with Port Numbers**: Allows multiple devices to share a single public IP by assigning unique port numbers to each device’s traffic.  
   * **Use Case**: Used by most home routers to allow many devices to access the internet simultaneously.  
   * **Example**: Devices `192.168.1.10` and `192.168.1.11` both share the public IP `203.0.113.1`, with different port numbers to distinguish them.

---

### **Real-Life Example of NAT in Action** {#real-life-example-of-nat-in-action}

Let’s say Adam wants to connect to Google. Here’s how NAT helps:

1. **Adam’s Device Request**: Adam’s device, with a private IP (e.g., `192.168.1.20`), sends a request to Google.  
2. **Router Translates IP**: The router translates `192.168.1.20` to a public IP (e.g., `203.0.113.1`).  
3. **Request Reaches Google**: Google receives the request from `203.0.113.1`.  
4. **Google’s Response**: The response from Google is sent back to `203.0.113.1`.  
5. **Router Translates Back**: The router translates the response to `192.168.1.20` and sends it to Adam’s device.

This keeps Adam’s private IP hidden, conserving public IPs and ensuring that Adam’s request reaches the right destination.

---

### **Why NAT is Essential in Network Management** {#why-nat-is-essential-in-network-management}

1. **Conserves Public IPs**: NAT lets multiple devices share a single public IP, preserving the limited pool of IPv4 addresses.  
2. **Enhances Security**: By hiding private IPs, NAT adds a layer of security against direct external threats.  
3. **Simplifies Network Design**: Private IPs can be used internally while only exposing essential public IPs, making network management more flexible and secure.

In short, NAT is like a two-way translator for IP addresses, helping to maintain efficiency, security, and structure in modern networking environments.

# Troubleshoot Like a PRO\! {#troubleshoot-like-a-pro!}

### **Why Troubleshoot?** {#why-troubleshoot?}

Troubleshooting keeps networks **running smoothly**, **identifies issues**, and **minimises downtime**. Here’s why:

1. **Ensures Smooth Operations**: Just as regular car maintenance keeps it running smoothly, routine network troubleshooting helps prevent small issues from becoming big problems.  
2. **Identifies Problems Quickly**: When something is wrong, like slow internet or a server going offline, troubleshooting helps locate and fix the root cause.  
3. **Minimises Downtime**: Downtime disrupts productivity and can even impact business. Effective troubleshooting resolves issues faster, keeping services available.

---

### **Common Network Issues** {#common-network-issues}

There are several frequent culprits in network troubleshooting. Let’s look at four common issues:

1. **Connectivity Loss**: This happens when you suddenly lose your internet connection, like a dropped phone call. It could be due to hardware issues, cable disconnections, or network problems.  
2. **Slow Network Performance**: Lagging load times for webpages or files can often signal a network issue.  
3. **IP Address Conflicts**: This happens when two devices share the same IP address, causing network confusion, like having two houses with the same street address.  
4. **DNS Resolution Failures**: DNS converts domain names into IP addresses. When this fails, it can be complex to resolve but is often at the root of connectivity issues.

---

### **Key Steps for Effective Troubleshooting** {#key-steps-for-effective-troubleshooting}

When troubleshooting network issues, think of it as debugging—observe, gather information, and use the right tools. Here’s a step-by-step approach:

1. **Observe the Problem**:  
   * Identify what’s going wrong. Is the network slow? Is a specific server down?  
   * Check the simplest causes first, like ensuring cables are plugged in and there’s no visible damage.  
2. **Verify Network Configurations**:  
   * Review router and device settings. For example, a device might be set with the wrong IP address.  
   * Check if there have been any recent changes to the network settings or configurations that might have introduced issues.  
3. **Use Diagnostic Commands**:  
   * **Ping**: Open a command-line interface (CLI) or terminal and use the `ping` command to test connectivity. For example, `ping google.com` will show if the device can reach the internet.  
   * If there’s no response, it points to a network or device issue.

---

### **Example Troubleshooting Walkthrough** {#example-troubleshooting-walkthrough}

Let’s break down a typical troubleshooting scenario:

1. **Problem Identification**:  
   * You notice slow internet across several devices. Is it a network-wide problem or just affecting certain users?  
   * Determine if other services are down or if it’s just internet connectivity.  
2. **Check Physical Connections**:  
   * Inspect cables and connections to make sure everything is properly connected and in good condition.  
   * Power-cycle the router and any affected devices to see if a restart resolves the issue.  
3. **Verify IP and DNS Configurations**:  
   * On each device, check for IP address conflicts. Ensure each device has a unique IP.  
   * Check DNS settings—sometimes, simply updating to a more reliable DNS server (like Google’s DNS `8.8.8.8`) can resolve connection issues.  
4. **Ping External Sites**:  
   * Open a terminal and `ping` a public site (like `google.com`). If you get a response, it confirms that external connectivity is working.  
   * If there’s no response, this could indicate a DNS issue or a more extensive network problem.

---

### **Summary Tips** {#summary-tips}

* **Always Check the Basics First**: Loose cables or power issues are some of the simplest, most common issues.  
* **Verify Settings Regularly**: Regularly verify that network configurations are consistent and accurate.  
* **Use the Right Tools**: Tools like `ping`, `traceroute`, and network logs are essential for identifying and resolving issues efficiently.

Effective troubleshooting means catching small issues before they become larger ones, reducing downtime, and keeping network performance smooth and reliable. With these steps, you can troubleshoot like a pro\!

# Troubleshoot with Ping, Traceroute, and NSLookup\! {#troubleshoot-with-ping,-traceroute,-and-nslookup!}

### **The Core Troubleshooting Tools** {#the-core-troubleshooting-tools}

In network troubleshooting, these three commands are invaluable:

1. **Ping**: This command tests the connectivity between devices.  
2. **Traceroute**: Tracks the exact path that data takes to reach its destination.  
3. **NSLookup**: Queries DNS to retrieve the IP address of a given domain.

---

### **How to Use Each Tool** {#how-to-use-each-tool}

1. **Ping Command**:  
   * **Purpose**: Ping checks if a device is reachable by sending packets to a target IP address or domain. It shows if data packets can make a round trip.  
   * **How to Use**:  
     * Type `ping google.com` in your command-line interface (CLI).  
     * You’ll get a response time if the connection is successful, showing that the network between your device and Google’s servers is working.  
2. **Traceroute Command**:  
   * **Purpose**: Traceroute maps the entire route that packets travel to reach a destination. It’s useful for finding where delays or issues occur along the network path.  
   * **How to Use**:  
     * Enter `traceroute google.com` (or `tracert google.com` on Windows).  
     * The output shows each "hop" (stop) on the path from your device to Google. If there’s a delay or issue, you’ll see where along the route it occurs.  
3. **NSLookup Command**:  
   * **Purpose**: NSLookup is used to check the IP address associated with a domain name, helping to identify DNS issues.  
   * **How to Use**:  
     * Type `nslookup google.com`.  
     * It will show you Google’s IP address, indicating that DNS is correctly resolving the domain name.

![][image8]![][image9]![][image10]

---

### **Example Troubleshooting Scenario: "I Can't Reach a Website"** {#example-troubleshooting-scenario:-"i-can't-reach-a-website"}

If you’re having trouble accessing a website, here’s a step-by-step approach to troubleshooting it with these tools:

1. **Check Network Connectivity with Ping**:  
   * Start by testing your general connectivity. Type `ping google.com`.  
   * If you get a response, it confirms that your internet connection is active. If there’s no response, your device may not be connected to the network.  
2. **Check DNS with NSLookup**:  
   * If Ping works but you still can’t reach the website, DNS might be the issue. Run `nslookup google.com` to verify the domain’s IP address.  
   * If NSLookup can’t resolve the domain, it’s likely a DNS issue. Try switching to a different DNS server (like Google’s at `8.8.8.8`) to resolve it.  
3. **Use Traceroute to Check the Network Path**:  
   * If Ping and DNS seem fine but the website is still unreachable, use `traceroute` to see the full route. Run `traceroute google.com`.  
   * Traceroute will reveal any points where data might be delayed or blocked, showing you if and where the connection is interrupted.  
4. **Additional Checks**:  
   * **Firewall Settings**: Make sure a firewall isn’t blocking the connection.  
   * **DNS Cache**: Clear your DNS cache, as outdated DNS entries can sometimes prevent access.  
   * **Browser Issues**: Restart your browser or try a different one to rule out a browser-specific issue.  
   * **System Logs**: Check your system logs for network errors, which can provide more clues.

---

### **Summary Tips** {#summary-tips-1}

* **Ping for Connectivity**: Quick way to confirm if devices are reachable.  
* **Traceroute for Path Tracking**: Identifies where delays or failures happen along a network path.  
* **NSLookup for DNS Checks**: Confirms if DNS is correctly resolving domain names to IPs.

Mastering these commands equips you with reliable methods to identify and troubleshoot network issues quickly, helping you keep your network running smoothly and minimize downtime.

# Cloud Networking Essentials\! {#cloud-networking-essentials!}

### **Why Cloud Networking Matters** {#why-cloud-networking-matters}

Cloud networking is all about managing and configuring networks in cloud environments. This is critical for **DevOps engineers** because it ensures that applications and services can communicate effectively and securely in the cloud. Unlike traditional networks, which use physical hardware, cloud networks use **virtual components**. This approach brings greater flexibility and scalability for deploying and managing infrastructure.

---

### **Key Components of Cloud Networking** {#key-components-of-cloud-networking}

1. **VPCs (Virtual Private Clouds)**:  
   * Think of a **VPC** as your own private network within the cloud. It’s like a virtual data center where you define your **IP address range** and can create different **subnets, route tables, and gateways** to manage how data flows within and outside your network.  
   * **Purpose**: VPCs help keep your resources isolated and secure while allowing controlled access to the internet or other VPCs.  
2. **Subnets**:  
   * A **subnet** is a smaller part of a VPC, dividing it into sections to better manage network traffic. You can use subnets to organise resources by function, such as having separate subnets for web servers, application servers, and databases.  
   * **Purpose**: Subnets help you control the flow of traffic and improve security by restricting which resources can communicate with one another.  
3. **Gateways**:  
   * A **gateway** connects your VPC to external networks, like the internet. It handles both incoming and outgoing traffic, so resources in your VPC can communicate outside.  
   * **Types of Gateways**:  
     * **Internet Gateway**: Allows VPC resources to access the internet.  
     * **NAT Gateway**: Enables private resources in a subnet to access the internet while keeping their IP addresses private.

---

### **DNS in the Cloud: AWS Route 53** {#dns-in-the-cloud:-aws-route-53}

* **Route 53** is Amazon’s cloud-based DNS service. Like traditional DNS, it translates domain names (like example.com) into IP addresses so users can reach your services.  
* **Unique Features**: Route 53 also provides **traffic routing** capabilities to ensure requests are directed to the best possible endpoint, often based on factors like location and latency.

---

### **Cloud-Based Routing: AWS Route Tables** {#cloud-based-routing:-aws-route-tables}

* **AWS Route Tables** manage how traffic is routed within a VPC, directing it between subnets and to external networks.  
* **Static vs. Dynamic Routing**:  
  * **Static Routing**: Manually defined routes that don’t change.  
  * **Dynamic Routing**: Automatically updated based on network conditions (often used in more complex configurations).

---

### **Container Networking (Intro)** {#container-networking-(intro)}

* Containers often require specific networking configurations to allow efficient, secure communication between them and with external networks.  
* **Purpose**: Although not covered in detail, understanding container networking basics is essential for configuring cloud environments that involve **containerized applications** (e.g., Docker, Kubernetes).

---

### **Firewalls: Security Groups and NACLs** {#firewalls:-security-groups-and-nacls}

1. **Security Groups** (Stateful Firewalls):  
   * Control **inbound and outbound traffic** for resources. Stateful means they remember the status of network traffic, so when traffic is allowed in, the response is automatically allowed out.  
2. **NACLs (Network Access Control Lists)** (Stateless Firewalls):  
   * Applied at the **subnet level** to control traffic in and out. NACLs don’t remember the traffic state, so rules must be defined for both inbound and outbound directions.

---

### **Summary** {#summary-9}

* **Cloud Networking** enables secure, flexible infrastructure management using virtualized networking components.  
* **VPCs** and **subnets** allow you to create isolated network environments.  
* **Gateways** connect your VPC to the internet, while **Route 53** handles DNS, and **AWS Route Tables** manage traffic flow.  
* **Firewalls** (Security Groups and NACLs) provide essential security layers by controlling traffic based on predefined rules.

This foundation prepares you for building scalable, secure cloud networks that support your applications and services effectively\!
