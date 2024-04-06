# Software
  ## Drei-Schichten-Architektur
    - Client
    - Backend
    - Datenbank
  ## Open-Source Software
    - Quelletext öffentlich einsehbar
    - Manche doch mit Lizenz verwaltet, kann doch nicht so viel erweitern und ändern
    - Jeder kann nachvollziehen, was die Code macht.
    - Mache Stelle gibt es Schwachstelle.
  ## Programmierungssprach
    - Imperative Programmierung (命令式编程)
      - Prozedurale Programmierung (面向过程) => C
        - Dabei wird Befehlen nacheinander gearbeitet. Anders als Funktionale Programmierung gibt Prozedurale Programmierung kein Ausgabewert zurück.
      - Objektorientierte Programmierung (面向对象) => Java C#
      - Strukturierte Programmierung (面向结构) => C++ Fortran
    - Deklarative Programmierung (声明式编程)
      - Funktionale Programmierung (函数式编程) => ECMAScript
        - Dabei wird Gesamtcode in vielen kleinen Funktion verteilt. Jeder Funktion arbeiten allein.
        - Eignet für einfache und modulare AUfgaben
      - Logische Programmierung (逻辑编程) => SQL
   ## Art der Software
    - Standardsoftware
      - für einen klar definierten Zweck eingesetzt.
      - Vorfertigesproduckt
      - in unterscheidlichen Bereichen einsetzbar
    - Individualsoftware
      - speziell für Wunsch von Kunden
    - Branchensoftware
      - eine Art von Standardsoftware, aber nur für speziellen Markt und Branchen
  ## Libraries und Frameworks
    - Libraries
      - Vorfertiges Produkt
      - sofort benutzbar
      - kein speziellen Regel zu halten
    - Frameworks
      - Halbfertiges Produkt
      - nur Grundgerüst, muss erst konfigurieren
      - muss auf speziellen Regel zu halten
  ## Ergonomische Prinzipien
    - Aufgabenangemessenheit (geeignete Funktionalität, minimierung unnötiger Interaktion)
    - Selbstbeschreibungsfähigkeit (Verständlichenkeit durch Rückmeldung)
    - Fehlertoleranz (unbekannte Fehler verhindern)
  ## Barrierenfreiheit am Arbeitsplatz
    - Maßnahmen Sehvermögen (Schriftart und Farbegebung)
    - Maßnahmen Hörvermögen
    - Maßnahmen motorische Fähigkeiten
  ## Softwarelebenszyklus
    - 1. Anforderungsanalyse
    - 2. Planung
    - 3. Umsetzung
    - 4. Test
    - 5. Veröffentlichung (Rollout)
    - 6. Instandhaltung
  ## Complier und Skriptssprachen
    - Compliersprach
      - Vorteile:
        - Schnell Ausführung von komplierte Maschinencodes
        - meist Plattformübergreifend
        - meist Typsicherheit
    - Skriptssprachen
      - Vorteile:
        - Änderung sofort ausführbar
        - kein Entwicklungsumgebung nötig
        - Schnell und einfach lernbar
  ## Interpreter und Compiler  
    - Unterschied
      - Zeitpunkt der Quellcode Übersetzung
      - Interpreter Sprachen erfolgt Übersetzung im lauf des Programm Zeilen zu Zeilen
      - Compiler sprachen erfolgt vor Ausführung des gesamte Code von Programm
  ## Linker
    - Führt alle Kompilierte Objectdatei mit anderen lauffähigen Datei oder Bibliothek zusammen. Hierdurch wird Zugriff zwischen Objectdateien verbunden, Wenn alle zugriffe aufgelöst wurden, wird Binärdatei erzeugen.
  ## Variable und Konstanten
    - Variable ist Platzhalter, wo veränderbare Werte speichert.
    - Dadurch wird ein Speicherplatz erschließen
  ## Schulungsarten
    - Ohline-Seminar
      - Über Internet
    - Inhouse-Schulung
      - Mehreren Teilnehmen
    - Individual-Schulung
      - An einem einzeln Person
  ## Debugging, Fehlersuche
    - Breakpunkt setzen
    - Zeilen für Zeilen ausführen
    - Werte von Varibale auslesen im Laufen des Programm
  ## Usability (EN ISO 9241)
    - Benutzerfreundlichkeit einer Oberfläche
    - Gute Usability kann Kundenzufriedenheit erhöhen
  ## User Experience
    - Erweitert Usablity
    - Angenehmen Interaktion mit Oberfläche
  ## Grafische Oberfläche
    - Vorteile:
      - einfach bedienen
      - Weniger Lernzeit
    - Nachteile:
      - Langsamer Bearbeitung
      - Mehr Ressourcen
      - Einschränkung durch Programm ohne UI
  ## Kommandozeilen
    - Vorteile:
      - schnell Bearbeitung
      - Weniger Ressourcen
    - Nachteile:
      - Mehr Lernzeit
      - Ergebnisausgabe in Text
  ## XML (Extensible Markup Language)
    - Die Daten der Textdatei werden in einer hierarchischen Struktur gespeichert. 
    - Die Elemente dieser Struktur werden durch Schlüsselworte (Tags) voneinander abgegrenzt
    - DTD
    - Eigenschaft
  ## CSV (Comma Seperat Values)
    - Textdatei ohne Steuerzeichen, in der die Daten in der Regel von einem Komma getrennt werden.
  ## Datenbank
    besteht aus datenbank und datenbankmanagementsystem
    - Datatype
      - Decimal (3,2)
      - Timestamp (Zeitpunkt)
      - Varchar(16)
    - Casecad
    - Referentielle Integrität
      - sichert die Dateninterität durch Anlegen einer Fremde Schlüssel in eine Tabelle, der auf einen anderen Tabelle verweist. Dadurch wird die Löschen und Update Operation beschränkt.
      - Mit On delete cascade / On Update cascade wird die Beschränkung igonorieren.
    - Transaktion
      - eine Menge von SQL, die als eine logische Einheit betrachtet. die werden entweder vollständig und fehlerfrei oder gar nicht ausgeführt und zurückgerollt.
    - Begin Transcation
    - Commit (Beendet Transcation, führt die Befehl endgültig aus)
    - Rollback (Beendet Transcation, Rollt die Zustand zurück auf vor der Starten der Transaktion)
  ### datenbankmanagementsysten (MYSQL, SQL SERVER)
    - Rollen, Recht und Benutzerverwaltung
    - Gewährleistung der Datenintegrität
    - Speichern, Löschen, Updaten Daten
    - Umsetzung des Mehrbenutzerbetriebs
    - Realisierung von Trigger und Procedures

  
  ## OOP
    - Klasse
      -  Definiert eine Kategorie von Objekten mit gleichen Attributen und Methoden. 
      -  Sie stellt einen Bauplan für Objekte dar.
    - Object
      - Ein Instanz einer Klasse
  
  ## UML
  ### Klassediagramm
    - Beziehung
      - Aggregation : Teil-Ganze-Beziehung, bei der die Teile unabhängig vom Ganzen existieren können
      - Komposition : Teil-Ganze-Beziehung, bei der die Teile abhängig vom Ganzen existieren können
    