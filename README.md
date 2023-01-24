## guideline-tls
these guidelines describe minimum standards for obtaining, setting up, or verifying transport layer security protocol (TLS) configurations

Version: 0.1

### our goals
- organization-wide implementation of the minimum standard
- limitation to the most important points and comprehensible instructions for action
- our public websites and services shall have a clean tls configuration
- future-proof tls configurations

## tls minimum standards
For the use of TLS, we @ekir refer to the respective applicable version of the

- IT Security Guidelines for Transport Layer Security (TLS) des Dutch National Cyber Security Centre (https://english.ncsc.nl/publications/publications/2021/january/19/it-security-guidelines-for-transport-layer-security-2.1)
and
- Technischen Richtlinie des BSI TR-02102-2 „Kryptographische Verfahren: Empfehlungen undSchlüssellängen. Teil 2 –Verwendung von Transport Layer Security (TLS)“ (TR-02102-2]https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr02102/tr02102_node.html)

#### tls minimum standards - implementation
- this minimum standard is intended for general use cases
- the requirements of the above technical guidelines must be implemented
- in case of configuration conflicts, the standard of the dutch national cyber security centre shall be preferred.
- in special individual cases, a deviation from the minimum standard may be appropriate.

## audit

#### tls audit for public websites
tests for websites can be carried out with
- https://internet.nl/ ( test your website ) and
- https://www.ssllabs.com/ssltest ( please select "X Do not show the results on the boards")

#### tls audit for other public Internet services
tests for public internet services can be carried out with
- https://observatory.mozilla.org ( please select "x Don't include my site in the public results")
