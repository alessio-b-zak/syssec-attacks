
Public Key Infrastructure & Certificate Authorities
  - DigiNotar 2011: Dutch Certificate Authority. Fraudently issued certificates
    for google allowing 300,000 iranian gmail users to be man-in-the middled

  - Comodo 2011: fraudently created create nine certificates for unknown
    addresses.

  - Morris Worm: 1998 Cornell Student took advantage of a buffer overflow in the
    unix fingerd program to spread a worm which downloaded and copied itself.
    estimated costs $100,000-10,000,000 infected 10% of computers at the time.

  - Spectre

  - Meltdown

  - Mirai Botnet: 2016, malware that scanned IP addresses for IoT
    devices. Uses table of 60 common factory default usernames and passwords.
    attempts to establish a telnet connection. If established listens to a server
    telling it to direct traffic causing a DDOS. Used to attack Github, twitter,
    Reddit. Attacked Dyn DNS provider and Liberia. Originally made to ddos minecraft
    servers. Recruited 500,000 IoT devices.

Data Breaches

  - Yahoo: breach of hashed passwords by state sponsored actor. 3 billion user accounts compromised

  - Heartland Payment Systems: SQL injection of card transaction sytem

  - Adult Friend Finder: SHA-1 hashed passwords meaning 99% had been cracked.

Replay Attack:
  - KRACK (Key Reinstallation Attack): all WPA2 devices are vulnerable. WPA2
    uses a four way handshake and allows a disconnection part way through. The
    same third handshake from another device can be used to reset the WPA2
    encryption key.


Tor deanonymysation
  - Sabu from lulzsec. Hacker group in 2011. accessed an IRC chat from original
    IP.
  - Timing correlation attacks. student at harvard university sent fake bomb
    threat. Used guerilla mail which puts IP of tor exit node in header. FBI
    looked at who used TOR from a given network at any time. One can check if
    they connect to directory authorities who give out relay information

VPN breaches
  - HideMyAss leaked session logs for Sabu mentioned above
  - PureVPN collaborating with the FBI


Rootkits
  - Sony BMG: 2005. DRM software on CDs installed rootkits which prevented access to CD.
    Hid from user all files starting with $sys$.
  - Stuxnet: 2010, targetted the programmable logic controllers in centrifuges
    that controlled Iran's Nuclear Program. Made the spin themselves apart.
    Installed usng USB and then installed infected rootkit.


Race Conditions
  - Dirty Cow


Ransomware
  - Wannacry:

Shellshock

Heartbleed
