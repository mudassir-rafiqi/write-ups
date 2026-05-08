# Networking Basics 

This repository contains my learning from the networking basics Course from cisco.

---

# Table of Contents

- [Basics](#basics-)
- [Wireless-Networks](#wireless-networks-)

---
# Basics :
## Who Owns “The Internet”?

Internet is not owned by anybody but its connection of the all the interconnected networks , they are connected by optical-fibre cables , telephone wires , wireless transmissions and sattelite links.
everything you access online is stored somewhere on the internet.

## Types of Personal Data :

1. **Volunteered Data :** Data shared by the person itself by creating a social media profile or uploading online somewhere
2. **Observed Data :** the data captured by recording actions of individuals such as location data 
3. **Inferred Data :** The data taken by analysis of volunteered and observed data

## Signal Transmission :

1. **Electric Signals :** transmission is throuh electric pulses used in copper wires
2. **optical signal :** transmission is through light pulses used in optical fibres
3. **wireless signal :** transmission is through infrared ,microwave , radio waves through air

## Bandwidth and Throughput :

**Bandwidth :** it is the rate at which the data is transferred through a medium.
- Kbps :Thousands of Bits Per second
- Mbps :Millions of Bits Per second
- Gbps : billions of Bits Per second. 
**Throughput :** it is same as bandwidth but it is also influenced by amount of data and latency 
`latency is amount of time ,including delays`

## P2P network :

Peer to Peer network is when computers are both client and host and share different things with each other

## Cisco Packet Tracer Symbols

![Symbols](images/symbols.png)

## ISP (Internet Service Provider) :

Internet Service provider links networks with the internet , ISPs are connected with each other to form the internet , They use Fiber-optic cables

---

# Wireless Networks :

1. **Gps :** gps or global positioning system uses satellites to find our position
2. **Wi-Fi :** Wi-Fi is used to connect to the internet with help of routers or hotspots
3. **Bluetooth :** Bluetooth is a low power and short range wireless technology normally used for speakers ,headsets ,mics .Multiple devices can be connected at a time.  
When bluetooth is in discoverable mode it sends this data when another bluetooth device requests :
- Name 
- Bluetooth class
- Services device can use
- technical info ,such as features or BT specs.
1. **NFC :** Near-field communication is very short range wireless technology used for payments .it uses elctromagnetic fields to transmit data

## Wireless Standards :

The **IEE 802.11** standard gives rules for wlan environments
- wireless stands use 2.4Ghz and 5Ghz frequency bands

## wireless Settings :

- **Network Mode :** like 802.11ac,802.11b or mixed mode
- **Network Name (SSID) :** (service set identifier ) names of the wifi like home etc
- **Standard channel :** channels are specific frequency ranges , set to auto
- **SSID Broadcast :** to show our wifi name to devices in range

 ---

# Protocols and models :

Protocols are rules used by networks to communicate with each other ,They include :

- **Message Format :** it is the structure or layout of a message
- **Message Size :** rules on how much the msg size should be , if the msg is big it will have to be broken in pieces to send.
- **Timing :** it synchronises sender and receiver , when to send data and how fast to send and waitng for devices for responses
- **Encoding :** Msgs sent are converted into bits so they can be sent through electric or light signals or radio waves which are decoded by the receiver
- **Encapsulation :** it adds header to the messages transmitted . it contains source and destinatio adress etc
- **Message Pattern :** some msgs require ack (acknowledgement ) before sending another and some just send without ack.

### Commom Ethernet Protocols :

- Ethernet : for communication in lan
- ip : internet protocol handles routing and adresses
- Tcp : makes sure packets sent are received and are in order
- Http : used for web browsing for getting html data

## TCP/IP And OSI Model :

It helps in visualizing how protocols work with each other to establish a communication . it shows work of protocols occuring in each layer and shows how they work with above and below layer  
They benefit us in : 
- helps in protocol design
- helps in editing or changing anything in a layer without disturbing others
- common language to describe networking functions and capabilities

First protocol modes was made in 1970s with 4 layers called internet model and tcp/ip model uses same layout so its often called tcp/ip model 

### TCP/IP Model :

Tcp/ip model has 4 layers and it is a practical model which is used in making protocols 

1. **Application Layer :** shows data to user and does encoding ,dialog control.
2. **Transport Layer :** it ensures reliable communication between the sender and receiver
3. **Internet Layer :** finds the shortest path in the network for the communication
4. **Network Access Layer :** it handles physical transmission of media like transferring by electric signals etc and also does framing of data

### OSI Model :

osi model has 7 layers and it is not practical it shows clearly how protocol models work so its mainly used for learning purposes also its a reference model like it tells what function each layer should do but now how it should do . it is used for data network design ,troubleshooting and for operation specifications

1. **Application Layer :** provides process to process communication like when we open a webpage and http protocol shows the html data
2. **Presentation Layer :** it makes sure that both sender and receiver have the same representation,format or appearance of data which was transferred between application layer
3. **Session layer :** it starts and ends the communication session and controls communication flow like full duplex means both send at a time and half duplex means one sends at a time 
4. **Transport Layer :** it breaks data into segments and also reassembles them .it also check if data is arrived correctly 
5. **Internet Layer :** Provides service to send pieces of data over the network .It handles the ip adressing and routing . finds the best path to transfer the data 
6. **Data Link Layer :** it describes method for transferring frames to local network
7. **Physical Layer :** It is responsible for transferring raw bits through physical media by electrical or light signals or radio waves , it is responsible for all the hardware related things


![models](images/models.png)