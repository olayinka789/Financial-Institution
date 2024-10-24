Technologies Implemented
* Design Tool- Use Cisco Packet Tracer to design and implement the network solution.
* Hierarchical Design- Use a hierarchical model providing redundancy at every layer.
* ISPs- The network is also expected to connect to at least two ISPs to provide redundancy and each router is connected to the two ISPs.
* WIFI- Each department is required to have a wireless network for the users.
* VoIP- Each department should have IP phones and users in the department should be able to call each other.
* VLAN- Each department should be in a different VLAN and a different subnetwork. The voice VLAN ID number will remain at VID 120 for the entire network.
* Subnetting- Provided the networks above, carry out subnetting to allocate the correct number of IP addresses to each department.
* Basic settings- Configure basic device settings such as hostnames, and console passwords, enable passwords, and banner messages, encrypt all passwords and disable IP domain lookup.
* Inter-VLAN Routing- Devices in all the departments are required to communicate with each other with the respective multilayer switch configured for inter-VLAN routing.
* Core Switches- The Multilayer  switches are expected to carry out both routing and switching functionalities and thus will be assigned IP addresses.
* DHCP Server- All devices in the network (except IP phones) are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server-side site.
* Cisco 2811 Router- Ensure to have a router that can support telephony service i.e Cisco Catalyst 2811(the VoIP router should be connected to any of the l3-switches at HQ).
* Static Addressing- Devices in the  server room are to be allocated IP addresses statically.
* Telephony Service- Configure VoIP on the voice gateway router and allocate dial numbers in format (4..).
* Routing Protocol- Use OSPF as the routing protocol to advertise routes both on the routers and multilayer switches.
* Switchport security- Configure port security for the server site department switch to allow only one device to connect to a switch port, and use the sticky method to obtain mac-address and violation mode shutdown.
* SSH- Configure SSH in all the routers and layer three switches for remote login.
* Standard ACL for SSH- configure a simple standard ACL on the line VTY to allow only the ICT department to carry out all remote administrative tasks using SSH.
* NAT + ACL- Configure PAT to use the respective outbound router interface IPv4 address, and implement the necessary ACL rule.
* IPsec VPN + ACL- Configure site-to-site IPsec VPN between the HQ router and the Server-side router, and implement the necessary ACL rule.
