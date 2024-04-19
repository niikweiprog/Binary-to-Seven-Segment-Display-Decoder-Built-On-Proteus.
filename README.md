# Binary-to-Seven-Segment-Display-Decoder-Built-On-Proteus.
A decoder for seven segment display output built considering the individual inputs for each instance to display from 0 through 9.

These are achieved through the various equations that encodes the output of every pin. That is from pin  A to G.
Giving each bit a name P,Q,R,S where P is the MSB.
The equations:
A = P + R + QS + Q*S*
B = P + R*S* + P*Q* + P*RS
C =PQ* +P*Q + P*R* + P*RS 
D = P + RS* + P*Q*R + Q*S* + QR*S
E = RS* + Q*R*S* + P*Q*S*
F = P + R*S* QR* + QS*
G = P + RS* + QR* + P*Q*R

NOTE THAT... A compliment of an each bit is indicated by a *. That is Q* is the compliment of Q.

