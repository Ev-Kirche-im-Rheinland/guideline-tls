## guideline-tls
- these guidelines outline the mandatory minimum standards for obtaining, establishing, and verifying Transport Layer Security (TLS) configurations.

Version: 1.0.2

#### introduction
When transmitting information over communication networks, there is a risk of unauthorized access or tampering. To protect the confidentiality and integrity of this information, appropriate security measures must be taken.
- One effective solution is the use of the Transport Layer Security (TLS) protocol.

#### scope
These guidelines apply to public web services, websites, and applications of the Evangelical Church in Rhineland (EKiR), whether provided by the church itself or by third parties.

### our objectives include
- Implementing a minimum standard across the organization.
- Focusing on crucial aspects and providing clear, easy-to-follow instructions.
- Ensuring that public websites and services have a secure TLS configuration.
- Adopting future-proof TLS configurations.

### tls minimum standards
- For the use of TLS, EKiR complies with the relevant and up-to-date version of the IT Security Guidelines for Transport Layer Security (TLS) of the Dutch National Cyber Security Centre and the BSI Technical Guideline TR-02102-2 “Cryptographic Mechanisms: Recommendations and Key Lengths – Part 2: Use of Transport Layer Security (TLS)”.
- This minimum standard applies to general use cases.
- The requirements outlined in the technical guidelines must be implemented.
- In the event of conflicting configurations, the standard set by the Dutch National Cyber Security Centre should be prioritized.
- In exceptional individual cases, deviations from the minimum standard may be acceptable.

### governance
- The EKiR IT department, acting in the TLS/PKI role, approves TLS profiles and certificate requests for public EKiR services and maintains a central certificate inventory.
- System owners are responsible for ensuring that their services and commissioned service providers comply with this guideline.

### service providers
- Public EKiR services operated by external service providers must comply with this guideline.
- Service providers must use only certificate authorities and certificate types approved by EKiR, coordinate TLS changes and certificate usage with EKiR in advance, test TLS regularly, and remediate findings in a timely manner.
- These requirements should be reflected in written contracts or security appendices with service providers.

#### tls minimum standards - implementation
- Tests for websites can be performed using [internet.nl](https://internet.nl/) and [SSL Labs Server Test](https://www.ssllabs.com/ssltest/), with public publication disabled where possible.
- Tests for other public internet services can be conducted using [Mozilla Observatory](https://observatory.mozilla.org/), with public publication disabled where possible.

### lifecycle and audit
- Public TLS certificates should not have a validity period longer than 12 months.
- All public certificates must be documented centrally with at least the FQDN, service name, certificate authority, validity period, and operating party.
- TLS configurations should be tested at least annually and after major changes, and the results should be documented.

#### tls audit for public websites
- Regular verification should use the tools referenced above and be integrated into EKiR's information security management and risk management processes.

#### tls audit for other public internet services
- Where websites are not in scope, equivalent TLS checks should be performed using suitable public testing tools and documented accordingly.
