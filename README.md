# Proton-VPN-Setup-and-Usage

<p align="center">
<img src="https://i.imgur.com/6vpNpZX.jpeg" height="40%" width="40%" alt="Traffic Examination"/>
</p>

<h2> Objectives </h2>

- Connect to Azure VM
- IP address test 1
- IP address test 2
- Download and Install Proton VPN on the VM
- Connect to VPN
- IP address test 3

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 Pro (22H2)

<h2>Step by Step Guide</h2>

Navigate to www.whatismyipaddress.com and note the city and IP address.
1st test, Pittsburg - 50.241.148.57

<p>
<img src="https://i.imgur.com/vB583qI.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
  
Next, we will launch our Azure VM and connect to it using Remote Desktop Connection, and use enter our VMs public IP to connect and login.

</p>
<br />

<p>
<img src="https://i.imgur.com/jSFz3Ki.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/XVCp5JC.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>

Now we will open up our internet browser and navigate to and make a second note of the city and IP address.
2nd test, Quincy - 20.3.130.0

</p>
<br />

<p>
<img src="https://i.imgur.com/EdasmHw.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Now we will navigate to https://account.protonvpn.com/downloads after logging in, and download for the proper Operating System, in this case, Windows > Download Proton VPN, and run the installer.
</p>
<br />

<p>
<img src="https://i.imgur.com/yJTUEoR.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Now click OK, and click next for all, installing with default settings. Once done launch Proton VPN, and search for your desired country/location of the server to connect to. In this case Japan. Click Quick Connect, then Change Server. This should connect us to a Japanese VPN server as shown here.
</p>
<br />

<p>
<img src="https://i.imgur.com/iX6YQuN.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<br />

<p>
<img src="https://i.imgur.com/5wQjrYZ.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
For one last time, we will navigate to https://whatismyipaddress.com/ and run the last IP address test. 
3rd test, Ciseeng - 138.199.21.202
</p>
<p>
<img src="https://i.imgur.com/5kKTGgE.png" height="80%" width="80%" alt="Azure Networking Steps"/>
</p>

<br />

<h2>Lessons Learned </h2>
As expected what I learned was how simple it is to connect to use a VPN. It is an extremely fast and sharing similar steps to setting up a enterprise VPN. Connecting to an enterprise VPN may require a few extra steps, however, it isn't much more complex. Corperate VPNs only require credentials, software, configuration of the VPN, connecting, and verifying the connection to the corperate net.
