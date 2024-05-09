# .github

A network pump is a bidirectional network appliance which allows information to flow between multilevel security networks exactly in one direction. The bidirectionality is necessary in order to feed acknowledgements so that the sender can obtain a return receipt for the transferred data which can be network packets or computer files.

The original NRL Network Pump uses statistically modulated True and False acknowledgements in order to mitigate against the manipulation of the feedback channel, which malitious actors could perform in order to send morse code signals in the reversed direction of the information flow. The statistical modulation of acknowledgement packets also introduces a random time delay in order to eliminate covert/side channels information transfer.

The BANPUMP project develops an opensource network pump using off the shelf components and libre software, empowering citizens and organizations to replicate and reproduce our solution in order to protect their networks.

Network appliances enforce hardware level security and they provide a perfect match for critical infrastructure protection. 

Use cases may vary but here are scenarios that require galvanic network isolation:
  - database replication from a high security network into a low security network;
  - files and backups transfer from a low security network into a high security network which is isolated by hardware;
  - collecting logs from a low security network into a high security network through galvanic isolation;





