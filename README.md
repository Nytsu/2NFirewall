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

![Screenshot_1620941116](https://user-images.githubusercontent.com/47388246/125693062-6e407c30-f788-4575-92aa-f3776def3602.png)
![Screenshot_1620941122](https://user-images.githubusercontent.com/47388246/125693124-b55ca56f-dbc3-45e1-bc2f-2b75daf30853.png)
![button on](https://user-images.githubusercontent.com/47388246/125693144-5813fdae-6130-4355-9c96-d6f533fc93cc.JPG)
![Screenshot_1620941279](https://user-images.githubusercontent.com/47388246/125693169-92b59410-f9a7-47a5-bcab-7794168e7b46.png)
