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

### Throughput

**Throughput**, on the other hand, refers to the actual amount of data successfully transmitted over a network in a given period of time. It is what you experience in reality, and it is almost always lower than the bandwidth due to factors such as network congestion, packet loss, latency, hardware limitations, and transmission errors. Using the same highway analogy, throughput is the number of cars that actually reach their destination — accounting for traffic jams, accidents, and slowdowns along the way.

