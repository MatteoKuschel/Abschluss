# IT-Netzwerk
  ## Protokoll
    - TLS (Transport Layer Security)
  ## Bandbreit
    - Gesamte Bandbreit = Sum(Bandbreit A + Bandbreit B)
  ## Subnetting
    - IpAdress            : 192.168.1.0/241
    - Subnetzmaske        : 255.255.255.224
    - Anzahl der Subnetze : 224 -> 1110 0000 -> 3 -> 2^3 = 8 
    - Netzwerk            : 1100 0000 1010 1000 0000 0001 0000 0000
                            1111 1111 1111 1111 1111 1111 1110 0000
                            1100 0000 1010 1000 0000 0001 0000 0000
                            192       168       1         0
    - Anzahl der Hosts    : 1111 1111 1111 1111 1111 1111 1110 0000
                                                             0 0000
                            2^5 - 2 = 30
  ## Ip Adressklasse
    - A 0.0.0.0   bis 127.255.255.255
    - B 128.0.0.0 bis 191.255.255.255
    - C 192.0.0.0 bis 223.255.255.255
    - D 224.0.0.0 bis 239.255.255.255
  ## OSI-Schichte
    - 7 Anwendung (Application)       HTTP          Layer-7-Switch
    - 6 Darstellung (Präsentation)    TLS           Layer-6-Switch
    - 5 Sitzung (Session)             PPTP          Layer-5-Switch
    - 4 Transport (Transport)         TCP,UDP       Layer-4-Switch
    - 3 Vermittlung (Network)         IPv4,Ipsec    Layer-3-Switch
    - 2 Sicherung (Data Link)         MAC           Layer-2-Switch
    - 1 Bitübertragung (Physical)     Ethernet      Kabel,Repeater

    Hauptgruppe
    - Anwendungsshichten (7-5)
    - Transportschichten (4-3)
  ## DNS Server (Domain Name Server)
    - Umwandlung Webseite Pfad oder Name in Ip adresse.
  ## DHCP Server (Dynamic Host Configuration Protocol)
    - Verteilung und zuweisung Ip Adresse.
  ## Ipsec (Internet Protocol Secure)
    - verschlüsselt die Daten bei Übertragung
    - Transportmodus
    - Tunnelmodus
  ## Packetheader
    - Quell - ziel Ip Address
    - Quell - ziel Port
    - Protokoll
  ## Anschluss
    - ADSL (Asymmetric Digital Subscriber Line)
    - VDSL (Very High Speed Digital Subscriber Line)
    - SDSL (Symmetric Digital Subscriber Line) Download und Upload gleiche Bandbreit

  ## Demilitarisierte Zone
    - Mittelort zwischen Interne Netzwerk und Extern Netzwerk
    - 
                            