# Networking\_basics

### 🌐 OSI Model: Open Systems Interconnection

The OSI model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven distinct layers.

#### 💡 Mnemonic

> Please Do Not Throw Sausage Pizza Away _(Physical, Data Link, Network, Transport, Session, Presentation, Application)_

***

#### Layer 1: Physical

* Transmits raw bitstreams over physical mediums like cables, fiber, and connectors.
* Deals with electrical signaling and mechanical specifications rather than protocols.
* Common issues involve hardware failures like damaged wires or bad ports.

#### Layer 2: Data Link

* Provides node-to-node data transfer and manages physical MAC(media access control) addresses.
* Functions as the "Switching Layer" where frames are directed via hardware IDs.
* Acts as the foundation for communication over Ethernet and local networks.

#### Layer 3: Network

* Handles logical addressing and the routing of data packets across different networks.
* Operates primarily using the Internet Protocol (IP).
* Fragments frames to ensure they can traverse varying network infrastructures.

#### Layer 4: Transport

* Manages end-to-end communication, flow control, and error recovery between hosts.
* Utilizes TCP for reliable delivery and UDP for fast, connectionless transfer.
* Often referred to as the "Post Office" layer of the stack.

#### Layer 5: Session

* Coordinates the establishment, maintenance, and termination of connections between applications.
* Manages dialogue control to keep different data streams separate.
* Includes various control and tunneling protocols.

#### Layer 6: Presentation

* Responsible for character encoding, data compression, and application-level encryption.
* Ensures that data is in a readable format for the application layer to process.
* Is frequently integrated directly into the application layer in modern implementations.

#### Layer 7: Application

* Serves as the interface between the end-user and the network services.
* Supports protocols that enable software tasks like HTTP, FTP, and DNS.
* The only layer that interacts directly with user-facing software applications.

### Networking Devices

* **Router**\
  Connects different networks and sends data to the correct destination using IP addresses.
* **Switch**\
  Connects devices inside the same local network and sends data only to the correct device using MAC addresses.
* **Firewall**\
  A security system that allows or blocks network traffic based on rules.
* **IDS (Intrusion Detection System)**\
  Monitors network traffic and alerts when suspicious activity is detected.
* **IPS (Intrusion Prevention System)**\
  Detects and automatically blocks harmful network activity.
* **Server**\
  A computer that provides services or data to other computers (clients).
* **Proxy Server**\
  Acts as a middleman between a user and the internet. Can filter, cache, or hide requests.
* **NAS (Network Attached Storage)**\
  A storage device connected to a network so multiple users can access files.
* **SAN (Storage Area Network)**\
  A high-speed dedicated network that connects servers to storage systems.
* **Access Point (AP)**\
  A device that provides Wi-Fi access to wireless devices.

### Networking Functions

* **CDN (Content Delivery Network)**\
  A group of servers placed in different locations to deliver content faster to users.
* **VPN (Virtual Private Network)**\
  Creates a secure encrypted connection over the internet.
* **QoS (Quality of Service)**\
  Prioritizes important network traffic to improve performance.
* **TTL (Time To Live)**\
  A value in a packet that limits how many routers it can pass through before being discarded.
* **IP (Internet Protocol)**\
  The system used to identify devices and route data across networks.
* **DNS (Domain Name System)**\
  Converts domain names like `google.com` into IP addresses computers can understand.

### Types of Network

A **computer network** is a system of interconnected devices that communicate and share resources. Networks are broadly classified into several types based on their geographical scale and purpose.

* A **Personal Area Network (PAN)** is the smallest type, connecting devices within a few meters of a person, such as a smartphone paired with wireless earbuds via Bluetooth.&#x20;
* A **Local Area Network (LAN)** connects devices within a limited area like a home, office, or school building, offering high speed and low cost.&#x20;
* A **Metropolitan Area Network (MAN)** spans a city or large campus, typically used by organizations that need to connect multiple office locations across an urban area.&#x20;
* A **Wide Area Network (WAN)** covers vast geographical distances — the internet itself is the largest WAN in existence — linking cities, countries, and continents.&#x20;
* Finally, a **Wireless Local Area Network (WLAN)** is essentially a LAN that uses Wi-Fi instead of physical cables, offering mobility and flexibility within a defined space.

Each type serves a distinct purpose, and in practice, they often interconnect — for example, a home LAN connects to the broader internet (WAN) through an ISP.

### Types of Personal Data

**Personal data** refers to any information that relates to an identified or identifiable individual. It plays a central role in today's digital world, where data is constantly being collected, analyzed, and used by organizations. Personal data is generally categorized into three key types based on how it is generated or collected.

*   **Volunteered data** is information that individuals consciously and willingly provide. This includes details shared when filling out a registration form, posting on social media, writing a review, or entering personal information into an app. The individual is fully aware that they are sharing this data and does so intentionally.


*   **Observed data** is information that is passively collected by recording a person's behavior or activity, often without them actively providing it. Examples include browsing history tracked by websites, GPS location data recorded by a smartphone, purchase transactions logged by a retailer, or app usage patterns monitored in the background. The individual may be aware this data is being collected, but they do not directly hand it over.


* **Inferred data** is information that is derived or predicted about an individual based on analysis of their volunteered and observed data. For instance, a company might infer a person's income bracket from their spending habits, or predict health conditions from lifestyle patterns. This type of data is generated by the organization itself using algorithms and analytics — the individual never provided it directly.

### Bit

A **bit** is the most fundamental unit of data in computing and digital communications. Short for **binary digit**, it represents the smallest piece of information a computer can process. Everything a computer does — from displaying text to streaming video — ultimately comes down to the manipulation of bits. A bit can hold one of only two possible values, and the entire field of digital technology is built upon this simple concept.

**0 (Zero)** represents the "off" state in a binary system

**1 (One)** represents the "on" state in a binary system

Beyond a single bit, bits are grouped together to represent more complex data. Eight bits form a **byte**, which can represent 256 different values and is the standard unit used to measure file sizes and memory. Larger units such as kilobytes, megabytes, and gigabytes are all built upon this foundation.

### Common Methods of Data Transmission

After the data is transformed into a series of bits, it must be converted into signals that can be sent across the network media to its destination. Media refers to the physical medium on which the signals are transmitted. Examples of media are copper wire, fiber-optic cable, and electromagnetic waves through the air. A signal consists of electrical or optical patterns that are transmitted from one connected device to another. These patterns represent the digital bits (i.e. the data) and travel across the media from source to destination as either a series of pulses of electricity, pulses of light, or radio waves. Signals may be converted many times before ultimately reaching the destination, as corresponding media changes between source and destination.

There are three common methods of signal transmission used in networks:

* **Electrical signals -** Transmission is achieved by representing data as electrical pulses on copper wire.
* **Optical signals -** Transmission is achieved by converting the electrical signals into light pulses.
* **Wireless signals -** Transmission is achieved by using infrared, microwave, or radio waves through the air.

### Bandwidth

**Bandwidth** refers to the maximum theoretical capacity of a network connection — the highest amount of data that _can_ be transmitted over a channel in a given period of time. It is measured in bits per second (bps), megabits per second (Mbps), or gigabits per second (Gbps). Think of bandwidth as the width of a highway — a wider road has more lanes and can theoretically accommodate more traffic at once. It represents potential, not actual performance.

#### Throughput

**Throughput**, on the other hand, refers to the actual amount of data successfully transmitted over a network in a given period of time. It is what you experience in reality, and it is almost always lower than the bandwidth due to factors such as network congestion, packet loss, latency, hardware limitations, and transmission errors. Using the same highway analogy, throughput is the number of cars that actually reach their destination — accounting for traffic jams, accidents, and slowdowns along the way.

### Clients and Servers

#### Roles

#### The Client

The client is the device or application that requests information or services.

* Examples: Your web browser (Chrome, Safari), a mobile app like Instagram, or your smart TV.
* Role: It provides the user interface, takes your input (like clicking a link), sends a request across the network, and displays the response you get back.

#### The Server

The server is a powerful computer or cluster of computers that delivers data or services to the clients.

* Examples: Google’s search database, Netflix's video storage, or an email host.
* Role: It constantly listens for incoming requests from clients. When a request arrives, the server processes it, fetches the necessary data, and sends it back to the client.

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### Peer-to-Peer Networks

Unlike the client-server model, where a central computer does all the heavy lifting, a Peer-to-Peer (P2P) network is a decentralized structure where every computer on the network is an equal.

In a P2P network, there is no dedicated server. Instead, every connected computer is called a peer.

#### How P2P Works

In this setup, each peer acts as both a client and a server at the same time.

* As a Client: A peer can request files or data from other computers on the network.
* As a Server: A peer shares its own processing power, disk storage, or bandwidth, allowing other computers to download files directly from it.

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

#### Key Characteristics of P2P

* Decentralized: There is no single point of control. If one computer goes offline, the rest of the network keeps working perfectly.
* Highly Scalable: The network actually gets _stronger_ and faster as more people join, because every new user adds more resources to share.
* Common Examples: File-sharing networks (like BitTorrent), blockchain and cryptocurrencies (like Bitcoin), and certain VoIP services (like early versions of Skype).

### Network Infrastructure

Network infrastructure is the underlying hardware and software resources that enable network connectivity, communication, operations, and management of an enterprise network. Think of it as the digital highway system of the modern world—it provides the paths, signals, and rules that allow data to travel safely and quickly from point A to point B.

A typical network infrastructure is built from three main components:

#### 1. Hardware

These are the physical, tangible devices you can touch. They form the literal backbone of the network.

* Routers: The traffic cops that connect different networks together and direct data packets along the most efficient paths.
* Switches: The internal hubs that connect devices (like computers, printers, and servers) within the same local network.
* Cables and Access Points: Fiber-optic cables, Ethernet wires, and Wi-Fi routers that physically transmit data.

#### 2. Software

Without software, the hardware is just expensive metal. This layer manages and secures the data flow.

* Operating Systems: Network OS (like Cisco IOS) that run routers and switches.
* Protocols and Firewalls: Security software and rules (like TCP/IP) that protect the network from unauthorized access and ensure data is packaged correctly.

#### 3. Services

These are the background functions that make the network usable for humans.

* IP Addressing (DHCP): Automatically assigning a digital "home address" to every device that connects.
* Domain Name Resolution (DNS): The phonebook of the internet that translates human-friendly URLs (like google.com) into computer-friendly IP addresses.

### End Devices

The network devices that people are most familiar with are called end devices, or hosts. These devices form the interface between users and the underlying communication network.

Some examples of end devices are as follows:

* Computers (workstations, laptops, file servers, web servers)
* Network printers
* Telephones and teleconferencing equipment
* Security cameras
* Mobile devices (such as smart phones, tablets, PDAs, and wireless debit/credit card readers and barcode scanners)

An end device (or host) is either the source or destination of a message transmitted over the network, as shown in the animation. In order to uniquely identify hosts, addresses are used. When a host initiates communication, it uses the address of the destination host to specify where the message should be sent.

### Wireless Networks

Wireless networks are computer networks that use radio frequency (RF) connections to connect devices, eliminating the need for physical cables. They allow smartphones, laptops, and smart devices to communicate and share data over the air, providing mobility and flexibility.

Depending on their range, speed, and purpose, wireless networks are categorized into different types. Here is a breakdown of the most common ones you use every day:

#### 1. Wireless Personal Area Networks (WPAN)

These are short-range networks designed to connect personal devices within a small space, usually within arm's reach or a single room.

* Bluetooth: Best for short-range audio streaming, file sharing, and connecting peripherals (like wireless earbuds, mice, and smartwatches). It operates efficiently over short distances with low power consumption.
* NFC (Near Field Communication): An ultra-short-range technology (usually requiring devices to be within a few centimeters of each other). It is the backbone of contactless mobile payments like Apple Pay or Google Wallet, and quick data transfers between phones.

#### 2. Wireless Local Area Networks (WLAN)

These networks cover a medium distance, typically inside a home, office, or school.

* Wi-Fi: The most ubiquitous wireless technology. It connects local devices to each other and to the internet through a central wireless router or access point. It offers high data speeds but requires devices to stay within a few hundred feet of the router.

#### 3. Wireless Wide Area Networks (WWAN)

These networks cover massive geographic areas, such as entire cities, countries, or even the globe.

* Cellular Networks (4G/5G): Provided by telecommunications companies using cellular towers. This is what gives your phone internet access on the go, allowing you to stream videos or browse the web from almost anywhere.
* GPS (Global Positioning System): While technically a one-way space-based navigation system rather than a two-way communication network, GPS uses a constellation of satellites to beam signals down to your device. Your phone calculates these signals to determine your exact location anywhere on Earth.

#### Summary Table

| **Technology** | **Typical Range** | **Primary Use Case**                           |
| -------------- | ----------------- | ---------------------------------------------- |
| NFC            | Centimeters       | Contactless payments, tap-to-pair              |
| Bluetooth      | \~10 meters       | Connecting headphones, smartwatches, keyboards |
| Wi-Fi          | \~50–100 meters   | Home and office internet browsing              |
| Cellular (5G)  | Kilometers        | Mobile internet while traveling                |
| GPS            | Global            | Maps, navigation, and tracking                 |

### The Internet and Standards

With the increasing number of new devices and technologies coming online, how is it possible to manage all the changes and still reliably deliver services such as email? The answer is internet standards.

A standard is a set of rules that determines how something must be done. Networking and internet standards ensure that all devices connecting to the network implement the same set of rules or protocols in the same manner. Using standards, it is possible for different types of devices to send information to each other over the internet. For example, the way in which an email is formatted, forwarded, and received by all devices is done according to a standard. If one person sends an email via a personal computer, another person can use a mobile phone to receive and read the email as long as the mobile phone uses the same standards as the personal computer.

### Network Protocols

Think of network protocols as the digital languages and rulebooks of the internet. Without them, gadgets might be able to physically connect to each other, but they wouldn't have a clue how to actually communicate.

#### What is a Network Protocol?

A network protocol is a standardized set of rules, formats, and procedures that govern how data is transmitted and received across a network. They ensure that whether you are using an iPhone, a Windows laptop, or a smart fridge, your devices can seamlessly exchange data regardless of their manufacturer or internal software.

#### The Core Functions

Protocols work behind the scenes to handle several critical tasks:

* Data Formatting: Breaking large chunks of data (like a video file) into smaller, manageable pieces called packets.
* Routing: Ensuring these packets find the most efficient path to their destination.
* Error Recovery: Checking if any packets were lost or corrupted during transit and asking for them to be resent.

#### Common Examples You Use Every Day

| **Protocol** | **What it Stands For**                            | **What it Does**                                                                                                     |
| ------------ | ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| HTTP / HTTPS | Hypertext Transfer Protocol (Secure)              | Loads webpages. The "S" version encrypts the data for security.                                                      |
| TCP / IP     | Transmission Control Protocol / Internet Protocol | The fundamental "backbone" of the internet that connects devices and guarantees reliable data delivery.              |
| DNS          | Domain Name System                                | The internet's phonebook. It translates human-friendly URLs (like `google.com`) into computer-friendly IP addresses. |
| SMTP / IMAP  | Simple Mail Transfer / Internet Message Access    | The protocols responsible for sending and retrieving emails.                                                         |

If a network protocol is a single rulebook, a protocol stack is the entire library.

In the real world, no single protocol can handle everything required to send data across the globe. Instead, multiple protocols work together, stacked on top of each other in a specific hierarchy.

#### What is a Protocol Stack?

A protocol stack (also known as a protocol suite) is a prescribed hierarchy of software layers that work together to enable network communication. Each layer in the stack has a dedicated job and uses specific protocols to accomplish it.

When you send data, it moves down the stack, with each layer adding its own necessary information. When the data arrives at its destination, it moves up the stack, stripping that information back off.

#### The Two Main Models

Network engineers generally refer to two conceptual models to understand how these stacks are structured:

1. The TCP/IP Model (The Practical Stack): This is the actual architecture that powers the modern internet. It is typically broken down into 4 layers:
   * Application Layer: Where you interact with the network (e.g., HTTP for web browsers, SMTP for email).
   * Transport Layer: Ensures data gets from point A to point B reliably (e.g., TCP, UDP).
   * Internet Layer: Handles the routing and addressing of data packets across different networks (e.g., IP).
   * Network Access Layer: The physical hardware and data-link protocols that actually move bits over wires or Wi-Fi (e.g., Ethernet, Wi-Fi).
2. The OSI Model (The Theoretical Stack): A more detailed, 7-layer theoretical model used primarily for teaching and troubleshooting. It breaks the process down even further into Physical, Data Link, Network, Transport, Session, Presentation, and Application layers.

#### How It Works: The Assembly Line Analogy

Think of a protocol stack like a factory assembly line preparing a package for shipping:

* Application Layer: You write a letter and put it in an envelope.
* Transport Layer: The factory seals the envelope and writes a tracking number on it so it doesn't get lost.
* Internet Layer: The shipping department pastes the destination address and return address on the outside of the box.
* Network Access Layer: The box is loaded onto a delivery truck and driven down the highway.

### TCP/IP

The TCP/IP model is the foundational blueprint of the modern internet. Created in the 1970s by the U.S. Department of Defense, it is a practical, four-layer framework that dictates exactly how data is packaged, addressed, sent, and received across a global network of diverse devices.

* Application Layer: Interacts directly with user software to initiate communication via familiar protocols like HTTP for web browsing or SMTP for email.
* Transport Layer: Manages host-to-host communication by slicing data into segments and deciding whether to send them reliably (TCP) or rapidly (UDP).
* Network (or Internet) Layer: Packages segments into packets and uses IP addresses to route them across different networks to their ultimate destination.
* Network Access Layer: Converts data packets into hardware-readable frames and physically transmits them as raw bits (1s and 0s) over Wi-Fi, Ethernet, or fiber-optic cables.

### TCP/IP vs OSI

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### The Internet Protocol (IP)

Think of the Internet Protocol (IP) as the universal postal service for the digital world. Whenever you send a text, stream a video, or load a website, your data is chopped up into tiny digital envelopes called "packets." The Internet Protocol is the set of rules that ensures these packets are properly addressed, sorted, and delivered across the vast global network. Without this standard agreement, our devices would be speaking different languages, and your data would get hopelessly lost in cyberspace.

#### IPv4 Addresses

To deliver a physical letter, the post office needs your specific street address. In the digital realm, that unique identifier is called an IP address, and IPv4 (Internet Protocol version 4) is the traditional format we've used for decades. An IPv4 address looks like a string of numbers separated by periods—for example, `192.168.1.1`. Every single smartphone, laptop, and smart TV connected to the internet gets one of these unique numbers so the network knows exactly where to route the information you requested.

#### The Structure of IPv4

Behind the scenes, computers don't actually see these friendly numbers; they see binary code (a massive string of 1s and 0s). An IPv4 address is made up of exactly 32 bits, which we humans divide into four sections called octets (because each section contains 8 bits). When written out normally, each of these four sections can range from 0 to 255. Structurally, the address is split into two halves: the first part acts like a "ZIP code" identifying your specific network, while the second part acts like the "house number" identifying your specific device within that network.

### Ipv4 Unicast , Broadcast and Multicast

#### Unicast Communication

Unicast is a one-to-one transmission method where data is sent from a single source to a single, specific destination. It operates much like a targeted email or a direct phone call. When a device requests a webpage or downloads a specific file from a server, a dedicated communication channel is established between those two endpoints. Because the data packet contains a unique destination IP address, only the intended recipient processes the information, ensuring efficient network utilization and data privacy for individual transactions.

#### Broadcast Communication

Broadcast is a one-to-all transmission method where a single sender transmits data to every device within a local network segment simultaneously. This is structurally equivalent to a television station broadcasting a signal to all local antennas. In networking, broadcast is primarily utilized for essential discovery protocols, such as Address Resolution Protocol (ARP), where a device needs to find a resource but does not know its specific location. While effective for localized coordination, excessive broadcast traffic can lead to "broadcast storms," consuming significant network bandwidth and processing power as every device is forced to intercept and evaluate the packet.

#### Multicast Communication

Multicast is a one-to-many transmission method designed to deliver data from a single source to a specific, predefined group of interested recipients. Instead of flooding the entire network like a broadcast, or replicating the data dozens of times via unicast, multicast uses a specialized range of IP addresses to target a subscription group. When a device wants to receive a multicast stream—such as an enterprise video conference, a live IPTV feed, or real-time financial market data—it joins the corresponding multicast group. The underlying network switches and routers then intelligently replicate the data stream only along the paths where active subscribers exist, drastically optimizing bandwidth efficiency.

### Assignment of IP Addresses

#### Regional Internet Registries

Public IPv4 addresses are addresses which are globally routed over the internet. Public IPv4 addresses must be unique.

Both IPv4 and IPv6 addresses are managed by the Internet Assigned Numbers Authority (IANA). The IANA manages and allocates blocks of IP addresses to the Regional Internet Registries (RIRs).&#x20;

RIRs are responsible for allocating IP addresses to ISPs who provide IPv4 address blocks to organizations and smaller ISPs. Organizations can also get their addresses directly from an RIR (subject to the policies of that RIR).

### Legacy Classful Addressing: The Original Sorting System

When the internet was first created, engineers needed a way to hand out IP addresses to different organizations. They invented a system called Classful Addressing, which divided all available IP addresses into rigid categories, or "classes" (Classes A, B, and C).

* Class A was for massive entities like governments or tech giants; it gave them a giant "ZIP code" block containing over 16 million individual device addresses.
* Class B was for medium-sized organizations like universities, offering about 65,000 addresses.
* Class C was for small businesses, offering only 254 addresses.

The system is called "legacy" because it is no longer used today. It was incredibly wasteful; if a company needed 500 addresses, they were too big for Class C and had to be given a Class B block, leaving over 64,000 addresses completely unused and locked away.

### Types of IPv4 Addresses: Public vs. Private

Because of the waste caused by classful addressing, the world began running out of IPv4 addresses. To fix this, engineers split IPv4 addresses into two main types: Public and Private.

* Public IP addresses are unique worldwide. Any server, website, or router directly facing the global internet must have a public IP, much like a unique international phone number. No two devices on earth can share the same public IP at the same time.
* Private IP addresses are reusable numbers reserved for inside closed, local networks—like your home Wi-Fi or a school computer lab. Your home router likely assigns your phone an address like `192.168.1.5`. Your neighbor's router can use that exact same address for their phone because the two networks are completely isolated from each other. Private addresses cannot travel onto the global internet; they only work inside your local walls.

### NAT (Network Address Translation): The Digital Border Guard

If private IP addresses cannot travel onto the global internet, how does your phone load a website over Wi-Fi? The answer is NAT (Network Address Translation). NAT is a technology built into your home router that acts like a digital border guard or a mailroom manager for an entire apartment building.

### IPv4 Issues

The primary crisis facing IPv4 is address exhaustion. Because IPv4 uses a 32-bit addressing scheme, it is limited to about 4.3 billion unique addresses—a number easily overwhelmed by the explosion of global internet users, smartphones, and IoT devices.

To stretch this limited pool, the networking world relies heavily on Network Address Translation (NAT). While NAT allows entire private networks to share a single public IP address, it introduces significant downsides: it breaks the end-to-end routing integrity of the internet, adds processing overhead (latency) at the router level, and complicates peer-to-peer applications and security protocols. Additionally, IPv4 suffers from large routing tables due to inefficient address allocation, which strains core internet routers, and its lack of built-in security requires bolt-on solutions like IPsec.

### IPv6 Addressing

IPv6 was engineered to solve IPv4's limitations by expanding the address space to a massive 128-bit architecture. This yields $$ $2^{128}$ $$ (roughly 340 undecillion) unique addresses, ensuring the world will not run out of IPs for the foreseeable future.

#### Key Characteristics:

* Notation: IPv6 addresses are written in hexadecimal, split into eight groups of four digits separated by colons (e.g., `2001:0db8:85a3:0000:0000:8a2e:0370:7334`).
* Simplification: They can be compressed by omitting leading zeros and replacing consecutive blocks of zeros with a double colon (`::`), though this double colon can only be used once per address.
* Structure: A standard global unicast address is typically split right down the middle: the first 64 bits represent the Network Prefix (used for routing), and the last 64 bits represent the Interface Identifier (the specific host's address, often derived automatically via SLAAC or DHCPv6).
* Enhanced Features: Beyond sheer scale, IPv6 eliminates the need for NAT, native headers are simplified for faster router processing, and security (IPsec) is baked directly into the protocol specification rather than added as an afterthought.

### Static vs. Dynamic Addressing

An IP address can be assigned to a device in one of two ways:

* Static Addressing: The IP address is manually configured on the device by a network administrator and remains permanent until manually changed. This is critical for infrastructure devices that must always be found at the exact same network location, such as servers, printers, and default gateways (routers). The downside is the high administrative overhead and the risk of human error leading to duplicate IP conflicts.
* Dynamic Addressing: The IP address is automatically assigned to a device by a network protocol for a temporary period (a lease). This is ideal for end-user devices like smartphones, laptops, and IoT products that join and leave networks frequently. It maximizes IP address efficiency and eliminates manual configuration errors.

### DHCP (Dynamic Host Configuration Protocol)

DHCP is an application-layer protocol that automates the network configuration process for hosts. Instead of a technician manually entering settings on every machine, a device running DHCP automatically requests and receives an IP address, subnet mask, default gateway, and DNS server addresses upon connecting to the network.

The protocol operates using a four-step handshake known as the DORA process:

1. Discover: The client broadcasts a message looking for any available DHCP server.
2. Offer: The server responds with a unicast or broadcast offering a specific IP address and configuration.
3. Request: The client broadcasts a message accepting that specific offer and notifying any other servers that it is taken.
4. Acknowledge (ACK): The server sends a final confirmation, finalizing the temporary lease agreement.

### DHCP Servers

A DHCP Server is a network service (running on a dedicated server appliance, a domain controller, or integrated directly into a local router) that manages the centralized pool of IP addresses, known as a DHCP Scope.

The server is responsible for keeping track of IP allocations to prevent duplicate assignments, managing lease times (reclaiming IPs when devices disconnect for long periods), and handling DHCP Reservations. A reservation maps a device's permanent MAC address to a specific IP address within the pool, ensuring that a critical device (like a network printer) always receives the exact same dynamic IP every time it boots up, giving it the benefits of a static IP without the manual setup overhead.
