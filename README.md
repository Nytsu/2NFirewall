# 2NFirewall
2N Firewall is an Android firewall application that 
uses an artificial neural network to filter packets. 
Instead of programming the packet filtering rules, 
the 2N firewall application learns the rules from a 
training set of packet data. The data provided to the 
neural network is retrieved from the NetGuard 
Firewall application, this data set includes: uid, IP 
version, protocol, destination IP address and 
destination port. Since the desired output is known, 
the neural network must be trained with supervised 
learning to validate the neural network’s output. 
Once the neural network is trained, all the packet 
filtering is done by the neural network and not by a 
set of filtering rules.
