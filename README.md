# Guideline: Transport Layer Security (TLS)
**Version:** 1.0.3

---

## 1. Introduction
When transmitting information over communication networks, there is a risk of unauthorized access or tampering. To protect the confidentiality and integrity of data, appropriate security measures must be implemented.
**Solution:** Use of the **Transport Layer Security (TLS) protocol**.

---

## 2. Scope
These guidelines apply to:
- Public web services, websites, and applications of the **Evangelical Church in Rhineland (EKiR)**
- Services provided by **EKiR itself or third parties**

---

## 3. Objectives
- Establish a **minimum security standard** across the organization.
- Focus on **critical aspects** with clear, actionable instructions.
- Ensure **secure TLS configurations** for all public websites and services.
- Implement **future-proof TLS settings**.

---

## 4. TLS Minimum Standards

### 4.1 Compliance
EKiR adheres to:
- **Dutch National Cyber Security Centre (NCSC) TLS Guidelines** (latest version)
- **BSI TR-02102-2** ("Cryptographic Mechanisms: Recommendations and Key Lengths – Part 2: Use of TLS")

### 4.2 General Rules
- Applies to **all standard use cases**.
- **Mandatory implementation** of technical guideline requirements.
- **Conflict resolution:** NCSC standards take precedence.
- **Exceptions:** Deviations may be permitted in **justified individual cases**.

---

## 5. Governance

### 5.1 Responsibilities
| Role | Responsibility |
|------|---------------|
| **EKiR IT Department (TLS/PKI Role)** | Approves TLS profiles & certificate requests; maintains central certificate inventory. |
| **System Owners** | Ensure compliance for their services and commissioned providers. |

### 5.2 Service Providers
**Requirements for external providers:**
✅ Use **only EKiR-approved Certificate Authorities (CAs) and certificate types**
✅ **Coordinate TLS changes & certificate usage** with EKiR in advance
✅ **Regularly test TLS configurations** and remediate findings promptly
✅ **Contractual obligation:** Include these requirements in **written agreements or security appendices**

---

## 6. Implementation & Testing

### 6.1 Testing Tools
| Service Type | Recommended Tool | Notes |
|-------------|----------------|-------|
| **Websites** | [internet.nl](https://internet.nl/), [SSL Labs Server Test](https://www.ssllabs.com/ssltest/) | Disable public publication where possible |
| **Other Public Services** | [Mozilla Observatory](https://observatory.mozilla.org/) | Disable public publication where possible |

---

## 7. Lifecycle & Audit

### 7.1 Certificate Management
- **Maximum validity period:** **12 months** for public TLS certificates.
- **Central documentation required** for all public certificates, including:
  - FQDN
  - Service name
  - Certificate Authority (CA)
  - Validity period
  - Operating party

### 7.2 Audit Requirements
- **Frequency:** **Annual testing** (or after major changes)
- **Documentation:** Results must be recorded.

#### 7.2.1 Public Websites
- Use **referenced tools** (internet.nl, SSL Labs)
- Integrate into **EKiR’s ISMS (Information Security Management System) and risk management processes**

#### 7.2.2 Other Public Internet Services
- Perform **equivalent TLS checks** using suitable tools
- **Document findings** accordingly

---
---
### Changelog
| Version | Date       | Changes                          |
|---------|------------|----------------------------------|
| 1.0.3   | [DD/MM/YYYY] | [Brief description of changes]   |

---
### Notes
- For **exceptions or clarifications**, contact the **EKiR IT Department (TLS/PKI Role)**.
