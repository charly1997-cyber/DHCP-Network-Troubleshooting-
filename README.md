# DHCP-Network-Troubleshooting-
A user complains he/she can’t access to the company’ s resources 
After disabling the adapter, the client lost:
	•	IPv4 Address
	•	DHCP assignment
	•	DNS communication
	•	Network connectivity

⸻

Troubleshooting Steps

1. Checked Network Configuration
Result:
	•	No active Ethernet adapter detected
	•	No DHCP information available

⸻

2. Re-enabled Network Adapter
	•	Opened Network Connections
	•	Enabled Ethernet0 adapter

3. Renewed DHCP Lease
   Result:
	•	Client received a valid IPv4 address
	•	DHCP server assigned network settings successfully

4. Verified Connectivity
   Result:
	•	Successful communication with Domain Controller
5. Verified DNS Resolution
Result:
	•	Domain name resolved successfully to the Domain Controller IP address

# Resolution

The issue was resolved by:
	•	Re-enabling the disabled network adapter
	•	Renewing the DHCP lease
	•	Verifying DNS and network communication
# Skills Practiced
	•	DHCP troubleshooting
	•	Network adapter troubleshooting
	•	DNS verification
	•	Windows networking
	•	Help Desk troubleshooting methodology
	•	Command-line diagnostics

  # Key Commands Used
  ipconfig /all
ipconfig /renew
ping 192.168.134.10
nslookup charlycyber.local

# screenshots <img width="4032" height="3024" alt="IMG_78FCBE64-2186-4174-8F80-E16A66A5339E" src="https://github.com/user-attachments/assets/2a0aa195-587e-4130-9431-f68e6fddc9a6" />


  
