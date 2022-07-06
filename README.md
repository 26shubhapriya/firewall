# AN OVERVIEW ABOUT FIREWALL
---
## ABSTRACT

This is an era of technology and with the rapid growth of the Internet, networks are continuously growing.Since networks are responsible to transmit huge data which is often sensitive and a point of concern for hackers.Despite the sizes of the networks,all networks are subject to several threats. Companies deploy several security measures to protect their networks from unauthorized access.Firewalls are the piece of software that provides internal and external security of the network. Firewalls aim to enhance the device level as well as network-level security. This paper aims to investigate the different types of firewalls, their architecture,and vulnerabilities of the firewall. This paper improves the understanding of firewall and its various types of architecture.

---
## INTRODUCTION
A Firewall can be implemented as software or it can be a hardware that basically blocks unauthorized communication going out or coming to a network. Lots of softwares are available to provide security at system or network level. In same manner, firewall devices are also used for providing system security Firewalls are much of the time used to prevent unapproved internet users to get access to private systems connected with the Internet. All information that is coming and going outside the networks need to pass through the firewall, which analyze each and every packet and block those that don't meet the certain security policies.
![IMAGE](https://linuxkamarada.com/files/2019/11/iptables.jpg)

---
## WHAT FIREWALL DOES?

Firewalls act as a filter between a home network and the Internet. User can configure in its own way whatinformation he wants to get away and what he wants to get inside. All the other stuff is not permitted.There are various different approaches or techniques firewalls use to filter traffic, and some of them are used together. These techniques function at various levels of a network, which decides how proper the filtering options can be at each level. Firewalls can be utilized in various techniques to provide security to your home network or business.
---
## WHAT  DOES A FIREWALL NOT DO

 Although a firewall manages traffic efficiently but still it does not provide full security and can make you fully safe on the internet. It is considered to be one of the first lines of defense, but all alone it will not secure you totally. This is the reason an internet security software packages includes several other parts of software also. A portion of the things a firewall does not secure you against are mentioned as follow:
- Viruses, worms and spam messages
- Wireless Network that is not configured well.
- Installation of malware software (secures you from spyware activities, but these activities may still be available in your PC)
---
## TYPES OF FIREWALL TECHNIQUES
 - Packet Filtering Firewall
 - Application/Proxy Firewall
 - Hybrid Firewall
---
 ### 1)Packet Filtering Firewall

This technique is based on most fundamental and oldest type of firewall model. Packet-filtering firewalls essentially make a checkpoint at a traffic switch or router. The firewall directly check the information packets passing through router or switch for example, the source and destination IP address, packet number, port number, and other data without opening up the packet to investigate its information. It works on network layer of network model. This technique applies a lot of principles on every packet and dependent on the result,chooses to either transfer or dispose of the packet. For instance, a rule could determine to hinder all  approaching traffic from a specific IP address or deny all traffic that utilizes UDP protocol. In the event that there is no match with any predefined rules, it will make default move. The default activity can be to 'dispose everything’ or to 'acknowledge all packets'.
---
 ### 2)Application/Proxy Firewall
Application firewalls review network packets to check whether data is valid (at the application layer) before allow making a connection. It investigates the data encapsulated in all packets going through network and after that it provides complete connection state. These firewalls also validate other security information like user passwords and service requests. Application or proxy services are used for specific reason in order to control traffic such as FTP or HTTP. These services can provide increased access control , detailed checks needed for data validity, and they can generate summary report about the traffic to identify and track traffic It is otherwise called Proxy server.Application level firewalls can also be implemented as Caching Servers which in way increase the network performance and makes it easier to track traffic.
 ---
 ### 3)Hybrid Firewall
Hybrid firewall is the combination of packet filtering firewall and application/proxy firewall in series, to give a better and stronger level of protection and security to the user.
---
 ## FIREWALL LIMITATIONS/DISADVANTAGES

 - #### COST
Firewalls does have an investment depending on the types of it. In general hardware firewalls are more expensive than the software firewalls. Besides that hardware firewalls require installations and maintenance which can be costly. These types of configurations cannot be done without an expert IT employee. Comparing this to a software firewall, there is no much investment and it is easy enough for an average user to deploy them.

- #### User Restriction
There is no doubt that firewalls prevent unauthorized access to your system from the network. While this can be advantageous for an average user, this can actually be a problem for large organizations. The policies used by the firewall cab be strict enough to prevent employees from doing certain operations. As a result of this, the overall productivity of the company an be affected severely. Sometimes this can also prompt employees from using backdoor exploits. However this can lead to security problems since the data travelled through these backdoor exploits are not examined properly.

- #### PERFORMANCE
Firewalls especially the software based has the capability to limit your computer's overall performance. The processing power and the RAM resources are some of the factors which decides the computer's overall performance. When the software firewalls constantly run on the background they consume more the processing power and the RAM resources. This can lead to a diminished system performance. However hardware firewalls does not impact the system performance since they do not rely upon the computer resources.
- #### Malware Attacks
Even though firewalls has the capability to block the basic types of trojans, it is proved to be defenseless against other types of malwares. These types of malwares can enter your system in the form of trusted data. Therefore, even if you have firewall, it is still recommended to have an anti-malware software installed on your PC. Because the only way to remove them is through an anti-malware scan.

- #### Complex Operations

Even though for small businesses the firewall maintenance is made easy, it is definitely not for large organizations. Firewalls for large organizations require separate set of staffs for operating them. These people make sure that the firewall is safe enough to protect the network from intruders. 
## SOFTWARE FIREWALL VS HARDWARE FIREWALL
At the most basic level, a hardware firewall is a physical unit, while software firewalls operate from inside your computer via an application. They have the same general mission, but they go about it in slightly different ways, giving them their own set of advantages: 
Cost less initially: When first purchased, a software firewall is relatively cheap. Some come with a free trial, and after that, a relatively low monthly fee. In the long run, however, the subscription expense may end up being more costly than what you would have paid for a hardware solution.
Require little space: If space is a concern, software may be a better choice because, as an application, it has no footprint.
Easy to install: Many software firewalls only require a few clicks to be up and running, whereas hardware firewalls require attaching wires, connecting to power, and proper positioning.
At the same time, the protection of a software firewall also comes with limitations. They have to be installed on every computer in the network. When it comes time to update your protection, if any of the units are not prepared to receive the update, they have to be updated manually. Since they don't have their own operating systems, software firewalls can also drain crucial computing power and memory, affecting user experience and network security.


## CONCLUSION 

It plays an important role in computer system security against viruses, spyware, Trojans and other malwares attacks from outside of network. A good firewall provides full security to our network and system without making any influence on the speed of computer system and network access. In order to provide security, one should always keep some points in mind: One should never install any software from suspected sources. Always download from the respected sites available on internet. Secure your firewall firstly and then use it to monitor all information that we want to transfer over the internet. On each PC a firewall software must be installed else it will to become infected and very fast it will impact all PCs connected to that network.

## REFERENCES
-https://www.fortinet.com/resources/cyberglossary/hardware-firewalls-better-than-software
-https://www.pramanaresearch.org/gallery/prj-p690.pdf
-https://www.geeksforgeeks.org/types-of-firewall-and-possible-attacks/
-http://paper.ijcsns.org/07_book/202104/20210424.pdf
-https://www.youtube.com/watch?v=Xj654WUdDFE&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&index=4











