# IT-System
  ## Bild-berechnung
    - (Bereite / 2.54) * Pixel * (Höhe / 2.54) * Pixel * Farbtiefes
  ## Datenvolumen Einheiten
    - 1 Bit = 8 Byte
    - 1000 Byte     = 1 KiloByte
    - 1000 KiloByte = 1 MegaByte
    - 1000 MegaByte = 1 GigaByte
    - 1000 GigaByte = 1 TeraByte
    - 1000 TeraByte = 1 PetaByte

    - 1000 Byte     = 1 Kibibyte
    - 1000 Kibibyte = 1 Mebibyte
    - 1000 Mebibyte = 1 Gibibyte
    - 1000 Tebibyte = 1 Pebibyte
  ## Raid-System
    - Datenspeichrung auf verschiedenen Festplatte verteilen
      - Software-Raid
        - von Betriebsystem gesteuert.
        - CPU Belastet
      - Hardware-Raid
        - von Controller unhängig von Betriebssystem gesteuert.
        - unhängig von CPU
      - Level 0
        - gleichmäßig auf die einzelen verteilen
        - kein Redudanz, schneller Zugriff, Große Speicherplatz
        - Mindest 2 Platte
      - Level 1
        - allen Daten kopiert in allen Platte
        - voll Redudanz, normaler Zugriff, Kleine Speicherplatz
        - Mindest 2 Platte
      - Level 5
        - allen Daten wird mit eine zusätzliche Parity-Information auf die einzelen Platte verteilen
        - voll Redudanz, normaler Zugriff, besser Speicherplatz
        - Mindest 3 Platte
  ## USV
    - Ununterberechungsstromversorgung
    - Schützt vor potenziellen unerwartete Ausfall von Strom.
    - die Stromversorgung von allen Geräten ausgleichen. So hat man noch Zeit um Daten zu retten.

  ## ERP, CRM, SCM, DMS, CMS
    - ERP (Warenwirtschaftsystem)
    - CRM (Kundenziehung verwalten und kunden historie darstellen und markting)
    - SCM (lieferkette management, matrial und informationfluss und resourcen)
    - DMS (elektronischer dokumente verwalten)
    - CMS (Content Management System) digitale Inhalte (Text,Grafiken, Fotos, Vedios) erstellen und verwalten kann.
    - CMA (Content Management Application) ohne HTML Kenntnisse Webseite zu erstellen.
  
  ## Virtualisierung
    - ist eine Simulation von physischer Hardware. Dabei wird virtuelle Betriebssystem, Speicher und Netzwerk Ressourcen erzeugen.
      
      - Server-Virtualisierung (Prozessor, Festplatte, RAM, Netzwerkkarte)
        - Ein Physischer Server in mehrere virtuelle Server logisch veteilt
        - durch eine Virtualisierungssoftware erfolgt.
        - dadurch die Hardware von der Software entkoppelt.
      
      - Speicher-Virtualisierung
        - Mehrere Physischer Speicherkomponenten zusammenbinden, um eine Speicherpool zu erzeugen

      - virtuelle Arbeitsplatzrechner (alle Elemente eines physischen Arbeitsbereichs auf einem Server)
        - weniger Speicherplatz für Client
        - Einfache Verwaltung der PCs
        - Einfache installation
        - Einfache Lizenzverwaltung
  
      - Vorteile:
        - Geringe Anschaffungskosten
        - Physischer Host ausnutzen
        - Konsolidierung von Systemresourcen
      - Nachteile:
        - Ausfall alle Virtuelle Server, wenn Host ausfall
        - Schlecht für Host
  ## Zentrale und Dezentrale Server
    - Zentrale
      - weniger Anschaffungskosten
      - weniger Verwaltungskosten
    - Dezentrale
      - Individuale Anpassung auf einzelen Server möglich
      - Ausfallsicherheit
  ## Level-Support
    - Vorteile: 
      - Systematische Bearbeitung von Anfragen
      - Einhaltung von Service-Level-Agreements
      - Nachvollziebarkeit aller Anfragen
    - First Level
      - erste Anlaufstelle, vollständig Erfassung, bei Gelegenheit an zweite weitergeben.
    - Second Level
      - Unterstürtzen first level, verfassen die Erfahrung für die first Level
    - Third-Level
      - besteht aus Fachspezialisten
  ## Neue Technik
    - Internet of Things besteht aus
      - Sensoren
      - Netzwerk
      - Software
  ## VPN Arten
    - site-to-site (the whole network connection)
    - client-to-site (single-connection)
  ## Hosting
    - Externe Hosting
      - Kein Lastung eigener Internet oder Rechner Resourcen
      - Besseres Know-how durch Spezialisierung
    - Interne Hosting
      - Kostengünstiger
      - Datenschutz
  
  ## Cloud computing
    - Vorteile:
      - Dadurch weniger Adminstrator brauchen
      - kein Hardwareanschaffungskosten
      - Hohe zeitliche Datenverfügbarkeit
      - unbeschränkte Skalierbarkeit
    - Nachteile:
      - Sehr Internetabhängig
      - Problem Schutz vor Daten
    - Public Cloud
      von Cloud Provider anbieten (Azure, AWS)
      Kein Kontroll auf physischer Server
      weniger Datensicherung
    - Private Cloud
      Server liegt bei Unternehmen
      Kontroll auf physischer Server
      mehr Datensichrung
    - Hybrid Cloud
      eine Kombination von Public und private Cloud
  ## IAAS PAAS SAAS
    - Plattform as a service (SAP Cloud, AWS Lambda)
        - nur Hardware und Plattform anbieten. Inhaltlichen Anwendungen App muss kunden selbst entwicklen
        - Datenbank, Entwicklungsumgebung
    - Software as a service (Office 365)
        - wird ein Software Produkt ausliefern, seinem IT-Infrastruktur und Plattform liegt aber bei externen IT-Dienst. Kunden errecht über Internet
        - Business Central Saas
    - Infrastructur as a service (AWS, Azure)
        - nur Hardware anbieten auch als Cloud genannt. Plattform und App muss kunden selber verwalten und entwicklen.
        - Netzwerk, Speicher, Betriebssystem


  