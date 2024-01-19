# Hashing_NIC_clusters

We are given a sensor network with a large number of MAC addresses, one for each sensor,
and we would like to group the sensors to form a cluster of sensors based on their MAC address. We
assume that the sensors are from the same manufacturer, so we consider only the NIC numbers are
of importance for the problem. Our project is about reading a fairly small number of distinct Network
Interface Controllers (NICs), each being a 6-digit number in hexadecimal, and deciding which digit
among the six gives the best-balanced distribution of the NICs. Based on the lowest cluster load
difference, the most balanced hash table is selected. The MAC addresses are considered as a
6-alphanumeric string from the set {0,1,2….9,A,B,C,D,E,F}. Any other alphanumeric character or
upper-case characters are treated as an invalid output.
