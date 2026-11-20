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

What is the purpose of an IP address?

What does DNS do?

What does the nslookup command help you investigate?

What is a firewall?

Why is Windows Firewall important?

How do networking and cybersecurity work together?

Screenshots

Save your screenshots inside the screenshots folder.

**Recommended filenames:**

01-network-configuration.png

02-connectivity-test.png

03-dns-lookup.png

04-firewall-profiles.png

05-firewall-rules.png
