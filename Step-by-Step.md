### Step-by-Step Instructions

**Step 1: Check Your Network Configuration**

Open Command Prompt and enter:

ipconfig /all

**What this does:**

Displays detailed information about your computer's network adapters, IP address, default gateway, and DNS servers.

Screenshot 1: Save your network configuration results.

**Step 2: Test Network Connectivity**

Enter:

ping google.com

**What this does:**

Tests whether your computer can communicate with the destination.

Review the replies and response times.

Screenshot 2: Save your connectivity test results.

**Step 3: Investigate DNS**

Enter:

nslookup microsoft.com

**What this does:**

Performs a DNS lookup to find the IP address associated with a domain name.

DNS helps computers locate websites and other network services by translating domain names into IP addresses.

Screenshot 3: Save your DNS lookup results.

**Step 4: Open PowerShell**

Click the Windows Start button.

Search for PowerShell.

Open Windows PowerShell.

You can use the following commands to review your firewall configuration.

**Step 5: Review Windows Firewall Profiles**

Enter:

Get-NetFirewallProfile

**What this does:**

Displays the configuration of Windows Firewall profiles.

Look for:

Domain

Private

Public

Enabled status

These profiles apply to different types of network connections.

Screenshot 4: Save your firewall profile results.

**Step 6: Review Firewall Rules**

Enter:

Get-NetFirewallRule | Select-Object -First 10

**What this does:**

Displays the first ten firewall rules returned by Windows.

Firewall rules help determine which network traffic is allowed or blocked.

You are only reviewing the rules in this lab. Do not disable the firewall or change security settings.

Screenshot 5: Save your firewall rule results.

**Step 7: Document Your Findings**

Answer these questions:

What is the purpose of an IP address? The main purpose of an IP address is to identify devices and help data travel to the correct destination across a network. The main purpose of an IP address is to identify devices and help data travel to the correct destination across a network.

What does DNS do? DNS (Domain Name System) translates website names into IP addresses so computers can find and connect to websites. DNS converts website names into IP addresses so devices know where to go.

What does the nslookup command help you investigate? The nslookup command helps you investigate DNS by checking the IP address associated with a website or domain name. nslookup helps IT and cybersecurity professionals investigate DNS issues and find the IP addresses connected to domain names.

What is a firewall? A firewall is a security system that monitors and controls incoming and outgoing network traffic to protect computers and networks from unauthorized access. A firewall protects computers and networks by filtering traffic and blocking potentially dangerous connections.

Why is Windows Firewall important? Windows Firewall is important because it helps protect your computer from hackers, unauthorized access, and potentially harmful network connections. Windows Firewall helps keep your computer safe by monitoring network traffic and blocking unwanted connections.

How do networking and cybersecurity work together? Networking and cybersecurity work together to keep computers, devices, and networks connected while protecting them from hackers, threats, and unauthorized access. Networking connects devices, while cybersecurity protects those connections and the information traveling through them.

**Screenshots**

01-network-configuration.png

02-connectivity-test.png

03-dns-lookup.png

04-firewall-profiles.png

05-firewall-rules.png
