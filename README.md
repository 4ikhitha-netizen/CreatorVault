# CreatorVault

## Demo Video


https://github.com/user-attachments/assets/ea79490d-98d0-4c2f-9824-c204741e163e




Teammates: Hoang Anh Tran (San Jose State University)  and Likhitha Ramayanam (San Jose State University)

Project and Track: CreatorVault Network and Track#4: DIY Software 


Project Description:

CreatorVault Network is a segmented, secured local area network built in Cisco Packet Tracer for independent creators and small creative teams. The network isolates internal collaborators from external clients using four virtual LANs: Creators (VLAN 10) isolating traffic of designers and editors working with sensitive files, Guests/Clients (VLAN 20) used for isolating outside visitors requiring minimum access, a dedicated Server VLAN (VLAN 30) that carries portfolio server or file server traffic, and a Management VLAN (VLAN 99) providing secure administrative access.

How it works: 
The router and switch are configured with inter-VLAN routing, DHCP pools for automatic IP assignment per VLAN, and Access Control Lists (ACLs) that enforce strict traffic rules like guest devices can reach the server but are blocked from ever communicating with creator machines. SSH replaces Telnet for all remote management, and both the router and switch are protected with console and enable passwords.

Problem it solves: 
Independent creators: freelance designers, video editors, musicians, photographers — often send files over insecure public Wi-Fi, cloud infrastructure with unknown data usage policies, or flat home networks where everyone's device can talk to everyone else's. However, the risks are real like for example, unauthorized file access, IP theft, control loss of unreleased music, designs or videos.
We solve these issues for our customers by giving creators their own private network infrastructure that is low-cost and that they fully own and control. No subscription fees. No third-party cloud middlemen. We make enterprise-grade network security accessible to individual creators who don't have the budget or IT resources of a big studio. Because we’ve perfected a Cisco Packet Tracer template for building your very own private segmented network to secure your creations and avoid expensive managed services . It’s so easy in fact that even if you’re just one guy or small indie team you can now build your awesome stylish studio across multilevel virtual isolation zones.


Ethical AI Statement: 
This project does not use AI in its core implementation. The Network was designed, configured and tested by our team using Cisco Packet Tracer solely. All the routing logics, VLANs segmentation, ACL rules and configurations made regarding the security are applied from our own understanding about Networking.
If any AI tools were used during the development of this project it is just for consulting only. Like we all consult documentation and online resources to check syntaxes or verify if the configuration is logically correct or not. All creative and technical decisions, including the network topology, IP addressing scheme, and security policy were made by the team. The AI did not generate any Packet Tracer configurations or replace any hands-on problem solving.




