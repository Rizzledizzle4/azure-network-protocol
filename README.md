<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04



<h2>Actions and Observations</h2>


![image](https://github.com/Rizzledizzle4/azure-network-protocol/assets/135624545/08bd4aac-5757-44a1-a490-4c0541961a88)


Create 2 Virtual Machines within Azure.VM1(Microsoft 10) VM2(Ubuntu).
</p>
<br />

![image](https://github.com/Rizzledizzle4/azure-network-protocol/assets/135624545/b7a323b2-089f-4191-9645-ad37bfcac34d)



Within VM1 Install Wireshark.
</p>
<br />

![image](https://github.com/Rizzledizzle4/azure-network-protocol/assets/135624545/53150ccd-5248-41bc-abea-926c2015a3bc)


This is an example of monitoring ICMP traffic through pinging VM2's private ip address.
</p>
<br />
