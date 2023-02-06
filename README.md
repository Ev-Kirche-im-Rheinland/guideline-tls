## guideline-tls
- these guidelines outline the mandatory minimum standards for obtaining, establishing, and verifying Transport Layer Security (TLS) configurations.

Version: 0.2

#### introduction
- when transmitting information over communication networks, there is a risk of unauthorized access or tampering. To protect the confidentiality and integrity of this information, appropriate security measures must be taken.
- One effective solution is the use of the Transport Layer Security (TLS) protocol.

#### scope
- public web services, websites, and applications of the Evangelical Church in Rhineland (EKiR), whether provided by the church itself or by third parties.

### our objectives include:
- implementing a minimum standard across the organization.
- focusing on crucial aspects and providing clear, easy-to-follow instructions.
- ensuring that our public websites and services have a secure TLS configuration.
- adopting future-proof TLS configurations.

## tls minimum standards:
- for the use of TLS, we at EKiR comply with the relevant and up-to-date version of the
- IT Security Guidelines for Transport Layer Security (TLS) des Dutch National Cyber Security Centre (https://english.ncsc.nl/publications/publications/2021/january/19/it-security-guidelines-for-transport-layer-security-2.1)
and
- Technischen Richtlinie des BSI TR-02102-2 „Kryptographische Verfahren: Empfehlungen undSchlüssellängen. Teil 2 –Verwendung von Transport Layer Security (TLS)“ (TR-02102-2]https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr02102/tr02102_node.html)

#### tls minimum standards - implementation:
- this minimum standard applies to general use cases.
- the requirements outlined in the technical guidelines must be implemented.
- in the event of conflicting configurations, the standard set by the Dutch National Cyber Security Centre should be prioritized.
- in exceptional individual cases, deviations from the minimum standard may be acceptable.

## audit

#### tls audit for public websites
tests for websites can be performed using...
- https://internet.nl/ ( test your website ) and
- https://www.ssllabs.com/ssltest ( please select "X Do not show the results on the boards")

#### tls audit for other public Internet services
tests for public internet services can be conducted using...
- https://observatory.mozilla.org ( please select "x Don't include my site in the public results")
