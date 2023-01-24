## guideline-tls
These guidelines are intended as advice during procurement, set-up or review of confgurations of the Transport Layer Security protocol (TLS) on servers.

Transport Layer Security (TLS), the successor to Secure Socket Layer (SSL), is a network protocol for encrypting communications between TLS servers (such as websites) and TLS clients (such as web browsers). Each communication is secured by a cipher suite: a combination of several algorithms working together. The decision about the right TLS confguration is ultimately up to each organization to decide. It is a complex task and each option requires a choice among the available alternatives, of which there are many. Security plays a role, but so does compatibility with customer or end-user software.

Version: 0.1

### our goals
- Organization-wide implementation of a tls minimum standards
- Limitation to the most important points and comprehensible instructions for action
- Public websites (e.g., www.ekir.de) should show an A+ SSL status.

## tls minimum standards
For the use of TLS, we at EKIR refer to the respective applicable version of the

- IT Security Guidelines for Transport Layer Security (TLS) des Dutch National Cyber Security Centre (https://english.ncsc.nl/publications/publications/2021/january/19/it-security-guidelines-for-transport-layer-security-2.1)
and
- Technischen Richtlinie des BSI TR-02102-2 „Kryptographische Verfahren: Empfehlungen undSchlüssellängen. Teil 2 –Verwendung von Transport Layer Security (TLS)“ (TR-02102-2]https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr02102/tr02102_node.html)

### tls minimum standards - implementation
The requirements of the above technical guidelines must be implemented. In case of configuration conflicts, the Dutch National Cyber Security Centre standard shall be preferred.

## audit

#### tls audit for public websites
Reference tests for websites are to be executed respectively with 
- https://internet.nl/ ( test your website )
- https://www.ssllabs.com/ssltest ( please select "X Do not show the results on the boards")

#### tls audit for other public Internet services
The following services can be used:
- https://observatory.mozilla.org ( please select "x Don't include my site in the public results")

#### Deviations from tls minimum standard
This minimum standard is intended for general church use cases. In special individual cases, a deviation from the minimum standard may be appropriate.
