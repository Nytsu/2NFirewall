# 2NFirewall
2N Firewall is an Android firewall application that uses an artificial neural network to filter packets. 
Instead of programming the packet filtering rules, the 2N firewall application learns the rules from a 
training set of packet data. The data provided to the neural network is retrieved from the NetGuard 
Firewall application, this data set includes: uid, IP version, protocol, destination IP address and 
destination port. Since the desired output is known, the neural network must be trained with supervised 
learning to validate the neural network’s output. Once the neural network is trained, all the packet 
filtering is done by the neural network and not by a set of filtering rules.

Based on the existing NetGuard Firewall, our proyect is to create a new alternative for filtering packets with a more precise approach. The implemented Neural Network is first train by the existing network activity and then enables the firewall packet filtering by the current train CSV file that was included while in training. 

**Whats new with the 2NFirewall?**

- Neural Network Packet Filtering
- New Simple UI approach

**Screenshots**





