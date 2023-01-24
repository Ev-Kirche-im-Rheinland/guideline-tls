# guideline-tls
These guidelines are intended as advice during procurement, set-up or review of confgurations of the Transport Layer Security protocol (TLS) on servers

Version: 0.1

## Einführung

Transport Layer Security (TLS), der Nachfolger von Secure Socket Layer (SSL), ist ein Netzwerkprotokoll zur Verschlüsselung der Kommunikation zwischen TLS-Servern (z. B. Websites) und TLS-Clients (z. B. Webbrowsern). Jede Kommunikation wird durch eine Chiffriersuite gesichert: eine Kombination aus mehreren Algorithmen, die zusammenwirken. Die Entscheidung über die richtige TLS-Konfguration liegt letztlich bei jeder Organisation selbst zu entscheiden. Es ist eine komplexe Aufgabe und jede Option erfordert eine Wahl zwischen den verfügbaren Alternativen, von denen es viele existieren. Die Sicherheit spielt dabei eine Rolle, aber auch die Kompatibilität mit Software der Kunden oder Endbenutzer

## Anweichungen vom Mindeststandard
Dieser Mindeststandard ist für allgemeine kirchliche Anwendungsfälle gedacht. Bei speziellen Problemen kann eine Abweichungen vom Mindeststandard sinnvoll sein.

### Ziele 
- Beschränkung auf die wichtigsten Punkte
- Nachvollziehbare Handlungsanweisungen
- Öffentlich nutzbare Kontrollmöglichkeiten
- Öffentliche Websites (z.B. www.ekir.de) sollen einen SSL-Status A+ zeigen.
- Es wird vorausgesetzt, dass die Regeln der TLS Spezifikation eingehalten werden.

#### TLS-Richtlinien Referenz
Für den Einsatz von TLS nehmen wir bei EKIR bezüglich des Mindeststandards Bezug auf die jeweilsgeltende Fassung der

- IT Security Guidelines for Transport Layer Security (TLS) des Dutch National Cyber Security Centre (https://english.ncsc.nl/publications/publications/2021/january/19/it-security-guidelines-for-transport-layer-security-2.1)

sowie ergänzend

- Technischen Richtlinie des BSI TR-02102-2 „Kryptographische Verfahren: Empfehlungen undSchlüssellängen. Teil 2 –Verwendung von Transport Layer Security (TLS)“ (TR-02102-2]https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr02102/tr02102_node.html)

#### TLS Mindeststandards - Umsetzung
Die Anforderungen der o.g. technischen Richtlinien sind umzusetzen. Bei Konflikten in der Konfiguration ist der Standard des Dutch National Cyber Security Centre zu bervorzugen.

#### TLS Referenztest Websites
Referenz-Test für Websites sollen ausgeführt werden mit 
- https://internet.nl/  („Test your Website“)
- https://www.ssllabs.com/ssltest ( bitte wählen "X Do not show the results on the boards")

#### TLS Referenztest für weitere Dienste
Folgenden Dienste können zusätzlich verwendet werden:
- https://observatory.mozilla.org ( bitte wählen "x Don't include my site in the public results")
