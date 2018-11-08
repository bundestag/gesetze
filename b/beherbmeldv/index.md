---
Title: Verordnung über die elektronische Speicherung von Daten zur Einhaltung der
  besonderen Meldepflicht in Beherbergungsstätten
jurabk: BeherbMeldV
layout: default
origslug: beherbmeldv
slug: beherbmeldv

---

# Verordnung über die elektronische Speicherung von Daten zur Einhaltung der besonderen Meldepflicht in Beherbergungsstätten (BeherbMeldV)

Ausfertigungsdatum
:   2020-06-05

Fundstelle
:   BGBl I: 2020, 1218


## Eingangsformel

Auf Grund des § 56 Absatz 2 des Bundesmeldegesetzes vom 3. Mai 2013
(BGBl. I S. 1084), der durch Artikel 1 Nummer 4 Buchstabe a des
Gesetzes vom 22. November 2019 (BGBl. I S. 1746) eingefügt worden ist,
verordnet das Bundesministerium des Innern, für Bau und Heimat:


## § 1 Anwendungsbereich

Diese Verordnung regelt die Einzelheiten der elektronischen
Speicherung und Bereitstellung der Daten von beherbergten Personen in
Beherbergungsstätten nach § 29 Absatz 5 und § 30 Absatz 4 des
Bundesmeldegesetzes durch die Leiter der Beherbergungsstätten oder der
Einrichtungen nach § 29 Absatz 4 des Bundesmeldegesetzes.


## § 2 Dateispezifische Anforderungen

(1) Die in § 1 genannten Leiter der Beherbergungsstätten oder der
Einrichtungen haben zu jeder beherbergten Person nach § 29 Absatz 2
des Bundesmeldegesetzes einen Datensatz vollständig am Tag der Ankunft
zu speichern.

(2) Die Daten sind als strukturierter maschinenlesbarer Datensatz im
Dateiformat der Extensible Markup Language (XML) zu speichern. Die
Daten sind im UNICODE-Zeichensatz UTF 8 zu codieren. Das
Bundesministerium des Innern, für Bau und Heimat gibt die Struktur des
XML-Dokumentes als XML-Schema-Definition (XSD) im Bundesanzeiger
bekannt.

(3) Die Datei ist nach dem Muster „JJJJMMTT\_
BeherbMeldeschein             \_Zaehler.xml“ zu benennen. Dabei ist
einzusetzen:

1.  bei „JJJJ“ das Jahr des ersten Beherbergungstags mit vier Ziffern,


2.  bei „MM“ der Monat des ersten Beherbergungstags mit zwei Ziffern,


3.  bei „TT“ der Kalendertag des ersten Beherbergungstags mit zwei Ziffern
    und


4.  bei „Zaehler“ eine fortlaufende Nummerierung der Datensätze eines
    Tages beginnend mit der Zahl 1.




(4) Die Datensätze sind sortiert in Ordnerstrukturen nach Jahren und
Monaten wie in Absatz 3 Nummer 1 und 2 bestimmt zu speichern.

(5) In jedem Datensatz sind die zu erhebenden Daten nach der Anlage zu
dieser Verordnung zu speichern.

(6) Landesrechtliche Vorgaben zur Ausführung des Bundesmeldegesetzes
bleiben unberührt.


## § 3 Bereitstellung der Daten

Verlangt eine nach § 30 Absatz 4 Satz 3 des Bundesmeldegesetzes
berechtigte Behörde gespeicherte Dateien, so hat der Leiter der
Beherbergungsstätte oder der Einrichtung die Datensätze entsprechend
den Anforderungen des § 2 zur Einsichtnahme bereitzustellen und eine
Übertragung auf Datenträger oder Speichersysteme zu ermöglichen.


## § 4 Inkrafttreten

Diese Verordnung tritt am Tag nach der Verkündung in Kraft.

(zu § 2 Absatz 5)

## Anlage Bei der Speicherung der Daten im Datensatz zu verwendende Bezeichner

(Fundstelle: BGBl. I 2020, 1219)


*    *
    *   Bezeichner

    *   Erläuterung


*    *   1.

    *   DatumAnkunft

    *   Datum der Ankunft der beherbergten Person (JJJJMMTT)


*    *   2.

    *   DatumAbreise

    *   Datum der voraussichtlichen Abreise (JJJJMMTT)


*    *   3.

    *   Familienname

    *   vollständiger derzeitiger Familienname mit Namensbestandteilen,
        jeweils durch Leerzeichen getrennt


*    *   4.

    *   Vornamen

    *   sämtliche Vornamen, jeweils durch Leerzeichen getrennt


*    *   5.

    *   Geburtsdatum

    *   Geburtsdatum (JJJJMMTT)


*    *   6.

    *   Staatsangehoerigkeiten

    *   sämtliche Staatsangehörigkeiten


*    *   7.

    *   Anschrift

    *   bestehend aus

        a)  Staat, in dem sich der Wohnort befindet


        b)  Postleitzahl des Wohnorts


        c)  Wohnortbezeichnung


        d)  sofern vorhanden, Zusätze zum Wohnort


        e)  Straßenbezeichnung


        f)  Hausnummerziffern sowie gegebenenfalls zusätzlich Buchstaben oder
            Zusatzziffern


        g)  sofern vorhanden, Ergänzungen zur Anschrift





*    *   8.

    *   AnzahlAngehoerige

    *   Anzahl der mitreisenden Angehörigen gemäß § 29 Absatz 2 Satz 2 des
        Bundesmeldegesetzes


*    *   9.

    *   AnzahlMitreisende

    *   Anzahl der Mitreisenden bei Reisegesellschaften gemäß § 29 Absatz 2
        Satz 3 des Bundesmeldegesetzes


*    *   10.

    *   StaatsangehoerigkeitMitreisende

    *   sämtliche Staatsangehörigkeiten der Mitreisenden der
        Reisegesellschaften


*    *   11.

    *   SeriennummerPass

    *   Seriennummer des anerkannten und gültigen Passes oder
        Passersatzpapiers ausländischer Personen oder Angaben zu Abweichungen
        oder Nichtvorlage


*    *   12.

    *   Zahlungszuordnungsnummer

    *   bestehend aus der zweckgebunden Zuordnungsnummer des elektronischen
        Zahlungsvorganges (Token) und aus dem Namen des Zahlungsdienstleisters
        der Beherbergungsstätte, der den Token generiert


*    *   13.

    *   Beherbergungsstaette

    *   bestehend aus Namen und Anschrift der Beherbergungsstätte oder
        Einrichtung, die die Daten speichert




