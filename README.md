# NTP-amplification

If NTP server receives 'monlist' command, NTP server normally reply back to the source with the server list which is using NTP server. Attacker normally manipulates source as a victim's IP and NTP server replies back to Victim. As a resul, he can attack the target machine by using legitimate NTP servers. The reply packet is much bigger than the request packet as it has the whole server list. 

Characteristics
1. UDP tacket, generating UDP packet is so simple and the target doesn't need to communicate with target. This is the same as other DDoS
2. Attacker can generate large volume of traffic by using legit NTP server.
