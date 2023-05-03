Download Link: https://assignmentchef.com/product/solved-cs204-assignment-2-congestion-avoidance-and-control
<br>
5/5 - (1 vote)




The foundational paper on transport layer congestion control was written by Van Jacobson and Michael Karles. Their paper discusses several aspects involved in a typical congestion avoidance and control scheme. Your task is to read and understand the algorithms presented in the paper and answer the following questions:

<ol>

 <li>The author says that flow of packets in a TCP connection need to follow the “conservation principle”. Explain, what is a conservation principle and how can we ensure that for a given TCP connection, conservation principle is followed.</li>

 <li>According to the author, why it is not a good idea to estimate Time Out (TO) as twice of estimated Round Trip Time (RTT) (i.e., TO = 2*RTT) under normal load scenarios. Instead, What have the authors proposed to do to compute the TO.</li>

 <li>In the case of Retransmissions, how should the TO be calculated.? Explain your answer.</li>

 <li>Figures 3 and 4 depict the behaviour of TCP without and with implementing Slow Startrespectively. Study both the graphs and explain in your own words, why do you think that TCPslow start phase is necessary for implementing congestion control algorithms.</li>

 <li>Figures 8 and 9 depict the behaviour of multiple TCP connections when implementingcongestion avoidance algorithm</li>

 <li>Explain the combined slow start and congestion avoidance algorithm.</li>

</ol>

A Protocol for Packet Network Intercommunication

The paper on Packet Network Intercommunication discusses process level communication, addressing mechanisms, transport layer segment structures, segmentation and reassembly techniques, connection and connection free protocols, and flow control mechanisms. Your task is to read and understand the various transport layer functionalities as outlined in the paper and answer the following questions:

<ol>

 <li>What is framing and why is it needed?</li>

 <li>Why do we need TCP addressing when transmitting segments using TCP from one host toanother.</li>

 <li>What is ‘ES’ and ‘EM’ flag in the TCP segment? How does it help in reassembly and sequencing?</li>

 <li>What are Transmit and Receive Control Block (TCB and RCB), explain its purpose. What is thetypical format of a TCB.</li>

 <li>What is the difference between connection and association? Explain, what do you mean byconnection free protocol with association?</li>