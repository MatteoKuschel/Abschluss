# IT-Sicherheit
  ## Test
    - Anweisungsüberdeckung
      - Testverfahren, gibt an, wie viel Anweisungen bei Test ausgeführt wurden. Ziel davon ist, dass alle Code einmal durchlaufen wird.
    - Modultest => Integrationstest => Systemtest => Abnahmetest
    - Modultest
      - Bei den wird jeder Modulen oder Komponenten getest
      - Testen durch Entwickler
      - Durch Frameworks
      - White-Box-Tests
    - Integrationstest
      - Bei den wird von Modultest getesten einzelnen Modulen zusammengetest.
    - Systemtest
      - Bei den wird komplette Software nach Anforderungen getest.
    - Abnahmetest
      - Bei den wird Auftraggeber die geforderten Funktionalitäten getest.
      - Black-Box-Test 
  ## Verschlüsselung
    - Symmetrische Verschlüsselung
      - Sender und Empfänger benutzen selben Schlüssel
      - Sicher, Sobald die Schlüssel beideseitg bekannt ist.
      - Resourcenschonend, leicht und schnell, geeignet für kleine Software.
    - Asymmetrische Verschlüsselung
      - eine öffentlichen und privaten Schlüssel
      - öffentlichen Schlüssel ist frei verfügbar, privaten nicht
      - Verschlüsselung nur mit öffentlichen Schlüssel, EntSchlüssel nur mit privaten
    - Digitale Signalisierung
      - Datei historie verfolgen
      - Vertraulichkeit, Integrität einhalten
      - Kompliziert
    - Hybride Verschlüsselung

  ## Vertraulichkeit Integrität Verfügbarkeit
    - Vertraulichkeit
      - Die Daten darf nur von autorisierte Person zugreifen.
    - Integrität
      - Die Daten sollte korrekt und vollständig sind und nicht durch anderem verändert
    - Verfügbarkeit
      - Die Daten sollte jeder zeit von autorisierte person zugreifen können und nicht durch technische Störung beeinträchtigt.

  ## Fälle der Sicherheit
    - Höhere Gewalt
    - Phishing Mail (Mithilfe von fake Webseite und E-mail wird daten ermittelt.)
    - Vishing Anrufe
    - Pharming (Damit wird die DNS angeriffen und auf fake Webseite umgeleitet.)
    - Distributed Denial of Service (Überlastung server durch menge Abfragen Angriffe)
  ## Backup
    - VollDatensicherung
      - Allen Daten werden gespeichert werden
    Vorteile:
      - Prozess einfach
      - Einfach Wiederherstellen
    Nachteile:
      - Große Zeitlich Aufwand
  
    - Differentiellensicherung
      - Zunächst Vollsichrung und dann wurde alle Daten, die seit letzte Vollsicherung geänderte wurden, gespeichert.
    Vorteile:
      - Schneller als Vollbackup
    Nachteile:
      - nicht effizient, sobald eine änderungen besteht, muss Sicherung durchführen
      - Brauch mehr speicherplatz
  
    - Inkrementellensichrung
      - Zunächst Vollsichrung und dann wurde der Daten, die seit letzten Sicherung geänderte wurden, gespeichert.
    Vorteile:
      - Effizient, jedes mal muss kleine Änderungen speichern
      - schnell erlediglich
    Nachteile:
      - langsame wiederherstellung

  ## Zwei Faktor Authtifizierung
    - durch zwei unterscheidliche und unhängige Komponenten authtifizieren (Bankkarte mit Pin, Password mit Fingerprint)

  