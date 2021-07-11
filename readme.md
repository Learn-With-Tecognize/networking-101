## Learn networking 101 with Tecognize

Welcome to networking 101. This repo will containe documents regarding networking fundamentals. This is sort of like a digital class notebook.

Topics to be covered

- Access Networks
- Types of Computer Networks
- OSI Model
  - Application Layer
  - Transport layer
  - Network layer
  - Link layer

**Protocol** A protocol is a set of rules governing the exchange or transmission of data between devices. 

**Packet** In telecommunications and computer networking, a network packet is a formatted unit of data carried by a packet-switched network. - [Wikipedia](https://en.wikipedia.org/wiki/Network_packet)

Why use packets: Smaller packets faster and easier to transmit and more manageable interm of a disaster. Imaging when you are downling from torrent, if your internet connection disrupts for some reason at 90%, when net connection is back, your download will start from 90% where a direct download will initiate a redownload of package, starting from 0%.

**IP** IP stands for Internet Protocol. Every device on the network is assigned an IP address. IPv4 are 32 bit numbers, separated by 4 dots. Each number can be a minimum of 0 and a maximum of 255. Eg: `102.33.21.231` or `103.42.32.21`. 
To get your own IP you can type `curl ifcofnig.me -s`

**PORT** A computer system can be connected to mulitple applications on the network. Each application will likely have a different port allowing its communication. Port is like a gate/door to the system. Just like a shipping port.

IP addresses a system and a port addresses an application. IP with port are written like `$IP:$PORT`. eg : `103.42.32.21:3306` . Here 3306 is the port.

- Every application has a 16-bit port number. So the port number could range from `0 to 2^16 = 65535`
- The ports `1024−49152` are known as registered. They are used by specific applications. But not system defined. Eg: mysql uses `3306`. Port mapping can be change by specific config for each application.
- The ports `49152–65535` can be used by user applications.

**TCP** TCP stands for Transmission Control Protocol. A set of rules and standards for networking.
TCP is the protocol that ensures reliability in a transmission. Specifically, TCP guarantees:

- No packets are lost.
- The packets are in the right order.
- The delay is at an acceptable level.
- There is no duplication of packets.

**Network Interface Adapter** NIA allows our devices to connect to a network. They usually have an address attached to them. These are physical gateways to the network.


**Note** More to come.
