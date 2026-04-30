# Networking\_basics

## 🌐 OSI Model: Open Systems Interconnection

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

