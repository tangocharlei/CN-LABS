Experiment 2A: Demonstration of Peer-to-Peer (P2P) Network using Copper Cross-over Cable
🎯 Objective
To demonstrate the copper cross-over cabling by designing a Peer-to-Peer (P2P) network.

🧰 Components Required
Device	Quantity
PCs	2
Copper Cross-over Cable	1
🗂️ Addressing Table
Device	Interface	IP Address	Subnet Mask
PC0	Fa0/0	192.168.10.1	255.255.255.0
PC1	Fa0/0	192.168.10.2	255.255.255.0
🛠️ Steps
Drag and drop 2 PCs in the simulation window.

Select Connectivity > choose Copper Cross-over Cable.

Connect PC0 to PC1 using the cross-over cable.

On PC0:

Go to Desktop > IP Configuration
Set IP address: 192.168.10.1
Subnet mask: 255.255.255.0
On PC1:

Set IP address: 192.168.10.2
Subnet mask: 255.255.255.0
To verify connectivity:

Open Command Prompt on PC0
Type ping 192.168.10.2

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/f777eac7-5ecb-4252-a22d-d6bbd15a1d4f" />
