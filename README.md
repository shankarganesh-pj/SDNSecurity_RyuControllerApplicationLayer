# SDNSecurity_RyuControllerApplicationLayer
Systematic Application Layer that Allows Network Monitoring and Firewall Rules for Ryu-based SDN Environments.
DDOS Mitigation System based on Ryu SDN Controller with Port Blocking Mechanism

This is a thesis project that creates The Application Layer to complement the DDoS Mitigation System of the Ryu SDN Controller inside https://github.com/bryanoliverh/SDNSecurity_DDOSMitigationDecisionTree_PortBlocking. 

This application runs on top of the Ryu Controller. As the Ryu Controller that was made is able to do packet forwarding and DDoS detection and mitigation with a port blocking mechanism, this application layer is the website to manage the topology information and it provides actions as follows:

1. Enable/disable the port.
2. Check the packet forwarding.
3. Block specific ports from network devices by choosing the device and the specific ports. 
4. Provides monitoring graphs.
5. Create whitelist/blacklist firewall rules.
