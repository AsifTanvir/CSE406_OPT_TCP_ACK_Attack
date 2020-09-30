# Optimistic TCP ACK Attack
Optimistic TCP-Ack acknowledges a packet before it is even received. In effect, the connection’s round trip time is reduced and the total throughput increased. An attack can be initiated on this technique where attacker keeps acknowledging the sender without getting the information to make the system flooded with packets.
	 	 	 	
For TCP ack attack, upon receiving the first data packet, the receiver sends a stream of ACKs to the sender for data which it has not yet received. The sender, confused by these ACKs, will put more data into the network before the previous data has left the network. This will force the network to increase its bandwidth. 
Eventually after a certain time the network will run out of bandwidth and it will create a Denial of Service. It means that other clients will not be able to get access to that server.

The details of the attack can be found on CSE406 Report.
