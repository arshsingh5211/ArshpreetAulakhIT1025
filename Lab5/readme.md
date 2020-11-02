## Executive Summary ##

Unit 5 revolved around learning how to effectively use Lucidchart to organize your projects before you start to code, providing an introduction to basic networking concepts, and learning how to use encryption to properly secure your information. I was able to practice encrypting and decrypting messages, using UML, and understanding core cybersecurity concepts.

### Lucidchart ###

This is an amazing resource that I definitely could have used when starting my coding projects. I would try to keep all the different parent classes, child classes, interfaces, methods, and any other parts of my code organized, but I would inevitably have to change things up as I eventually realized that there was a cleaner and more efficient way to organize my project. Being able to use a flowchart would have allowed me to clearly see how each class, attribute, and method impacts each other and how to properly carry out basic OOP principles such as encapsulation, inheritence, and polymorphism. It also allows others in your project to refer to the UML diagram to understand the thinking behind your code.

I tried handwriting diagrams or using other sites, but Lucidchart is definitely the most user-friendly and simplest one I have used so far. The different shapes are easily explained and creating the diagram is made to be as effortless as possible. I will definitely be using Lucidchart to plan my code in my future projects.

### Introduction to Networking ###

#### Data Transmission ####

1. **Protocol:** Set of rules to allow devices to communicate *(determines how data is transmitted between different devices in the same network)*

2. **Packet:** Unit of data routed between an origin and a destination on the internet or any other packet-switched network *(carried out by a packet-switching network)*

3. **IP address:** Unique identifying number that identifies each computer using the Internet Protocol to communicate over a network

4. **Packet-Switching:** Technology that allows packets of data to be routed based on destination address *(includes the origin IP address, the destination IP address, the number of packets in the entire data file, and the sequence number)*

5. **DNS (Domain Name System):** Directory of IP address common names.

#### Network Hardware ####

Whenever you need to connect multiple network devices, you can use either a hub, a switch, or a router. A switch is more advantageous to use than a hub, but a router is what most people use as it has many advantages over both switches and hubs.

While a hub and a switch both connect multiple devices together, there are some key advantages of using a switch over a hub. A hub does not separate traffic between different devices, so a hub connects multiple devices together as a single segment. A switch, on the other hand, can join multiple devices within a network, so it seen as more intelligent than a hub. It allows you to connect multiple devices together while keeping track of individual "network conversations" and intelligently separates the traffic. A switch also maximizes security and efficiency of the network, as each networked device connected to a switch can be identified using a MAC address.

While a hub and a switch deal with transmitting frames, a router is a small computer that can be programmed to handle and route the network traffic. It usually connects at least two networks together, and uses a protocol to calculate the best route for sending data. A router will also allow you to share a single IP address among multiple network devices. A switch can only be used for a wired network, but a router can also work wirelessly. Although routers cost significantly more than switches, they are able to do everything both switches and hubs can do and so much more.

#### Network Topologies ####

A single point of failure (SPOF) is a part of a system that, if it fails, will stop the entire system from working. It is antithetical to the goal of high availability in a computing system or network, a software program, or any business practice. A **star topology**, a topology for a LAN in which all nodes are individually connected to a central connection point (such as a hub or a switch), represents a SPOF. If that central hub fails, any device connected to it will not be able to access the network. A **bus topology**, where each node is connected to a single cable, also represents a SPOF because it consists of only one wire that, if it fails, will also prevent all devices from connecting to the network. A **ring topology** is set up in a circular fashion in which data travels around the ring in one direction and each device on the ring acts as a repeater to to keep the signal strong as it travels, requiring a device sending data to travel through each device on the ring until it reaches its destination. Therefore, as all nodes work as a server and repeat the signal, every node represents a SPOF. 

An infrastructure topology, although it allows for both wired and wireless networks, is very similar to a star topology in that it also has its devices communicate with a central base station. This base station, called an AP, acts as a bridge between wired and wireless LANS or WLANs. It is used to extend a wired LAN to include wireless devices as well. In a wireless mesh topology, however, several APs are interconnected to one another (similar to a wired mesh topology) where each node is connected to every single node in the network. While an infrastructure topology is most useful for wireless networking, it also represents a single point of failure because the nodes are connected to a central hub. 

I think a mesh topology would be more advantageous than an infrastructure topology because messages can be received more quickly if the recepient is short, and multiple connections mean that no node should be isolated and that each node can transmit to and recieve more than one node at at ime.Therefore, I think the wireless mesh is best because there are multiple access points and they all communicate with each other to create a seamless internet connection for wireless devices to connect to.


#### Network Design ####

I chose to diagram a wireless mesh topology, where the computers and printers are interconnected to each other using an access point, which  then connects to the router. This allows for most transmissions to be distributed even if one of the connections goes down.

#### NSA/CSS ####

The NSA works with other agencies and commercial partnerships to recognize cyber threats, develop solutions, and protect information storage and transmission. They not only respond to threats as they happen, but they also work to proactively defend against cybersecurity attacks against the nation.

### Cybersecurity and Encryption ###

#### Information Systems Security ####

If I was part of the Amazon online chat, each component of the security triad would significantly impact my job. Confidentiality would be of utmost importance, as only the people that need to know encrypted information should be allowed access to it. This especially applies to customers' private information such as address and date of birth, but also for the company's data as well. Integrity, the second component of CIA, is the assurance that the information being accessed has not been altered in any way and is an accurate representation of what is intended. At Amazon, maintaining integrity despite both attacks of malicious intent and unintentional issues would involve not making a change to the site that is outside of your scope, not using your access in a way that goes against company policy or your job title, or making sure you take the necessary precautions to protect against file corruption or accidental file deletion. Finally, the last component of the security triad is availability -- making sure the information can be accessed and modified by anyone authorized to do so in the appropriate timeframe. In this context, it means making sure the chat is accessible to the users in a reasonable time without servers failing and without an unreasonably long wait time.

Three examples of a daily task that requires authentication is using face or fingerprint recognition to unlock your phone, using your car keys to start your car, and using Kronos to clock in at work. Multi-factor authentication helps to secure these processes as it makes it much more difficult for someone to misrepresent themselves. For example, your phone could ask for a passcode in addition to facial recognition. When you use your car keys to unlock your car, it could also ask for your fingerprint as an anti-theft precaution. Kronos or most devices to clock in at work already use multi-factor authentication, as you have to enter your employee ID or swipe your ID while you are on camera. So if someone else punches you in to work, it would likely be easily detectable.

An access control list (ACL) and Role-Based Access Control (RBAC) are two of the more common access control models. ACL contains rules that grant or deny access to certain digital environments, and it is better suited for implementing security at the individual user level (and for low-level data). While ACLs are simple to understand and maintain, they are much harder to maintain within a company with hundreds of employees. Since each resource is managed separately, it would be tedious to keep adding or deleting a user from access to resources. On the other hand, RBAC assigns users to roles and then those roles are given specific access, so it is better for company-wide encryption with a system administrator overseeing security. The main disadvantage of RBAC is when roles change, it can become a complex affair to properly encapsulate their access. When my current position at my employer was newly created, it was a long and strenous process to properly set up the proper access for all the employees who would be transitioning to that position.

When sending a message over the internet or using a flash drive, the users employ cipher text to encode the message in case an unauthorized person comes across the information. To send an encrypted message with public key encryption, a user would obtain the public key, encode the message, and then send it. The recepient would then use their private key to decode it. So each user would require both a public and private key in order to decode secure cipher text messages.

As malicious attack attempts are inevitable, especially in higher leverage situations such as the Cold War or other national cybersecurity vulnerabilities, public key cryptography allows for the ability to encrypt data even if an attacker is able to gain access to it. As many precautions that are taken, it is always possible there are still vulnerabilities, so using cryptography is another defense against data falling into the wrong hands.

#### Cryptography ####

In the Caesar Cipher Exploration box, my message was encrypted by shifting each letter three places to the right. In the Frequency Fingerprint Exploration" box, it analyzes how many times each letter is used, after which you can decode the message based on the frequency of each letter. Changing the language would only change the method if the alphabet did not use the same letters as English. Punjabi or Arabic letters are not in any way similar to the English alphabet, so you would have to alter the method to use this cipher. Otherwise, everything would remain the same as you are basically just counting how often each letter shows up in the message. A polyalphabetic cipher is any cipher based on substitution, using multiple substitution alphabets. In the Polyalphabetic Exploration box, the shift word determines how many letters to shift the original message by using the number of each letter in the word.

#### Brute-Force ####

A brute-force attack is when an attacker just tries to guess a password or key by trying as many possibilities as possible with the hope of eventually getting it right. Kerckhoff's principle states that a cryptosystem should be secure even if everything about the system, except the key, is public knowledge. So according to Kerckoff's principle, as long as no one knows how the key works, a brute-force attack should be unsuccessful.



## Conclusion ##

Throughout this unit, I was able to learn about how to best use UML diagrams, how all the different components of a network fit together, and how encryption affects both everyday life as well as higher-level security issues, particularly of the NSA's role in national cybersecurity. While I do not anticipate a career in system administration, cyber security, or networking, I will definitely use what I learned on Lucidchart to plan out my coding projects in a more efficient manner in the future.
