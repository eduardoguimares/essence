---
topic:
  - Technology
aliases:
  - E2E encryption
---
This type of end to end encryption (RSA) was made by Ron **R**ivest, Adi **S**hamir and Leonard **A**dleman[^1]

When the sender of a message sends a message to the receiver, the message is encrypted and only the receiver has the necessary key to decipher the message. The server (where the message gets through) can not decipher the message because it does not have the key. The catch is that a new key needs to be created every time the sender wants to encrypt the message in a new way and the sender needs to send the key directly to the receiver (kab exchange) in order for the server to not be able to decipher the message[^1]

The key is not really exchanged directly. What in fact happens is the exchange of variables and then they are combined with some private variables that were hidden, so the key is created. The key created by the receiver needs to be the same as the key creator by the sender of the message[^2]

The sender creates an unique variable (s). No one knows the variable except him. The receiver does the same thing but with another variable (r). Both variables (s and r) are unknown to the public.

Then there is a third variable (g) that both will get. This third variable (g) is known to the public, but that is not a problem because that variable will be mixed with the variable of the receiver (r) and he will send that mixed variable (rg) to the sender. The sender will do the same thing with this variable (sg). The public will know the mixed variables (rg and sg), but it is incredibly difficult to extrapolate the individual variables.
Then the sender mixes the mixed variable (rg) with his variable (s) to create the final mixed variable (srg) which will be the same as the mixed variable of the receiver (srg)

In the end, the public might know (g), (rg) and (sg). But the public will never know (s), (r) and (srg)

[^1]: Title: *How Quantum Computers Break The Internet... Starting Now* 
Director: Veritasium 
Scriptwriters: Casper Mebius | Derek Muller | 
Producers: Trenton Oliver | Raquel Nuno | Ivy Tello | Mike Radjabov |
Date: 2023
[Source web page](https://www.youtube.com/watch?v=-UrdExQW0cs)
[^2]: Title: *Secret Key Exchange* 
Director: Computerphile 
Producers: Sean Riley | Diffie Hellman |
Date: 2017
[Source web page](https://www.youtube.com/watch?v=NmM9HA2MQGI)