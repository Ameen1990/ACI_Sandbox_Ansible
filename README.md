# coding_challenge
This is a coding challenge to build an Ansible-Playbook that goes inside APIC and build the whole topology (Tenant, VRF, Bridge Domain, EPG, Application policy, COntracts, etc.) and some extra features.

Note: 2 images are attached in Issues section.


Topology: -
-	One tenant (am_tn)
-	One application profile (am_ap)
-	3 bridge domains
•	Web_server
•	App_Server
•	Data_Base

-	All running inside one VRF

 
-	Every bridge domain is associated with a subnet

-	Three EPGs 
-	Every EPG is associated with a bridge domain
-	Two contracts were created: 


  Cont_1: filters traffic between Web_servre & App_Server

  Cont_2: filters traffic between App_Server & Data_Base
 
