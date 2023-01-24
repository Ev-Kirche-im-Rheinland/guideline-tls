# guideline-tls
These guidelines are intended as advice during procurement, set-up or review of confgurations of the Transport Layer Security protocol (TLS) on servers

Version: 0.1

# Einführung

Transport Layer Security (TLS), der Nachfolger von Secure Socket Layer (SSL), ist ein Netzwerkprotokoll zur Verschlüsselung der Kommunikation zwischen TLS-Servern (z. B. Websites) und TLS-Clients (z. B. Webbrowsern). Jede Kommunikation wird durch eine Chiffriersuite gesichert: eine Kombination aus mehreren Algorithmen, die zusammenwirken. Die Entscheidung über die richtige TLS-Konfguration liegt letztlich bei jeder Organisation selbst zu entscheiden. Es ist eine komplexe Aufgabe und jede Option erfordert eine Wahl zwischen den verfügbaren Alternativen, von denen es viele existieren. Die Sicherheit spielt dabei eine Rolle, aber auch die Kompatibilität mit Software der Kunden oder Endbenutzer

## Ziele 

- Beschränkung auf die wichtigsten Punkte
- Nachvollziehbare Handlungsanweisungen
- Öffentlich nutzbare Kontrollmöglichkeiten
- Es wird vorausgesetzt, dass die Regeln der TLS Spezifikation eingehalten werden.

### TLS Mindeststandards - Richtlinien

Für den Einsatz von TLS nehmen wir bei EKIR bezüglich des Mindeststandards Bezug auf die jeweilsgeltende Fassung der

1) IT Security Guidelines for Transport Layer Security (TLS) des Dutch National Cyber Security Centre 

https://english.ncsc.nl/publications/publications/2021/january/19/it-security-guidelines-for-transport-layer-security-2.1

sowie der

2) Technischen Richtlinie des BSI TR-02102-2 „Kryptographische Verfahren: Empfehlungen undSchlüssellängen. Teil 2 –Verwendung von Transport Layer Security (TLS)“ 

[TR-02102-2]https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr02102/tr02102_node.html


### TLS Mindeststandards - Umsetzung

Die Anforderungen dieser technischen Richtlinien sind bei allen TLS-Konfigurationen einzuhalten. Der den niederländischen Standard wird bevorzugt.

### TLS Test Referenz

Tests sind auszuführen mit der Website https://internet.nl/  („Test your Website“)

### TLS Test weitere Dienste

Folgenden Dienste können zusätzlich verwendet werden:

https://observatory.mozilla.org

https://www.ssllabs.com/ssltest ( X Do not show the results on the boards)

Zusätzlich ist wichtig, dass öffentlich bekannten Websites wie www.ekir.de bei Qualys einenStatus A+ zeigen.

# Anweichungen vom Mindeststandard

Dieser Mindeststandard ist für allgemeine geschäftliche Anwendungsfälle gedacht. Bei speziellen Problemen kann eine Abweichungen vom Mindeststandard sinnvoll sein.
