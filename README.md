# soc-environment
### Cyber Security Operation Center (CSOC) Environment Project
**Technologies Used**: VirtualBox, pfSense, Splunk, Ubuntu, Windows

#### Project Details
- **Firewall Configuration**: Implemented a pfSense firewall to secure the network environment and manage traffic flow.
- **Virtual Machines**: Set up and configured two virtual machines:
  - **Splunk Forwarder on Ubuntu**: Deployed the Splunk forwarder on an Ubuntu machine to collect and forward log data.
  - **Splunk Indexer on Windows**: Configured the Splunk indexer server on a Windows machine to index and store log data for real-time analysis.
- **Log Management**: Established a comprehensive log management system, enhancing the ability to monitor and analyze security events.

#### Key Achievements
- Successfully created a virtual CSOC environment focused on efficient log management and security monitoring.
- Improved threat detection and response capabilities through real-time log indexing and analysis.
- Demonstrated expertise in using Splunk for log management and cybersecurity operations.

--
#Netwwork architecture diagram
![Screenshot (43)](https://github.com/user-attachments/assets/8c6fcb4f-a729-4f58-8e28-808374c6af9a)
--
#created a virtual machine environment for a Security Operations Center
![Screenshot (44)](https://github.com/user-attachments/assets/269ee8de-eaef-4756-82cf-5141f40db113)

#intalled a firewall OS that is pfsense on the virtual machine 
configured a network settings on virrtual box for lan comunication 
![Screenshot (50)](https://github.com/user-attachments/assets/da4c3a55-24e1-40b0-836d-cf809525d182)
![Screenshot (48)](https://github.com/user-attachments/assets/67f3cc79-5901-407f-aacd-5890b5a03f76)

#after completing a firewall configuration , its time to configure a other vms that is devices which aare connected to same lan, ip address is assign by dhcp pool
![Screenshot (51)](https://github.com/user-attachments/assets/4cd8d2dd-c56a-4007-9396-d426df757908)

#afte setting up all the vms, we can see that our network is routing via fire wall , as i used trace route command for inspecting network routes , you can see , pfsense firewall in the network flow
![Screenshot (46)](https://github.com/user-attachments/assets/db1de51f-4cd0-4398-86be-45eaf4ebd913)

#same for ubuntu 
![Screenshot (47)](https://github.com/user-attachments/assets/a0107895-cd84-4866-81c6-3290803bc5a1)

#even i can access the firewall web page , only devices which is presnt in lan can access this firewall page
![Screenshot (49)](https://github.com/user-attachments/assets/9857c3b5-afb2-4c9d-ba60-05a90ad00425)

--
--
## remaining documentation will Update soon


