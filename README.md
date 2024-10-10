# VPNSetup


Virtual Private Networks: Setting Up and Using VPNs

Understanding VPNs

	💡 What is a VPN?
A Virtual Private Network (VPN) is a secure technology that encrypts internet traffic and routes it through a remote server. This process masks your IP address, making it appear as though you are browsing from a different physical location. VPNs are commonly used to:

	•	Protect sensitive data
	•	Bypass geographical restrictions
	•	Enhance online security and anonymity
	•	Conceal your IP address to prevent tracking by websites and advertisers

Think of it as a secure, encrypted tunnel through which your data travels safely, away from prying eyes.

Required Software & Setup

	⚠️ Prerequisites:
You will need the following:

	•	A free version of Proton VPN
	•	An Azure Virtual Machine (VM) to practice with.

For instructions on creating an Azure VM, refer to the Azure Crash Course: Virtual Machines Section.

Common Uses for VPNs

	•	Secure connections in public areas like cafes, airports, or hotels with public Wi-Fi networks.
	•	Reduce latency and DDoS attacks while gaming online.
	•	Prevent bandwidth throttling when streaming or downloading.
	•	Conceal IP address to prevent websites and advertisers from tracking your activities.

Building an Intuition for VPNs

	1.	Visit WhatIsMyIPAddress.com and note your current IP Address.
	2.	Go to Portal.Azure.com and create a Virtual Machine using Windows 10.

	⚠️ Important:
When selecting the Region for your VM, choose a region other than where you live.

	3.	Retrieve the Public IP for your new VM and connect to it using Remote Desktop Connection.
	4.	From within your VM, visit WhatIsMyIPAddress.com again and note the IP Address displayed for your VM.

	💡 Note:
If your VM region is set to another country (e.g., Japan), you may notice that any Google searches you perform appear in Japanese. This is because the server believes the VM is physically in Japan.

VPN Setup Steps

	⚠️ Prerequisite:
If you haven’t already, set up your free Proton VPN account.

	1.	From within your VM, log into Proton VPN and download the free version. Use the default installation settings.

	💡 Note:
Installing and using the VPN may interrupt the connection to your VM.

	2.	Once installed, open the Proton VPN application and attempt to connect to a server.
	💡 Note:


	3.	Once connected to a VPN server within your VM, revisit WhatIsMyIPAddress.com and refresh the page. Compare the new IP address to the one you noted earlier to see how your VM’s “location” has changed.

	💡 Note:
Using a VPN within a Remote Desktop Connection can mimic similar effects to using a VPN, as the VM’s IP address will reflect the server’s region rather than your physical location.

