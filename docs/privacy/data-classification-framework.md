# DesertTech Solutions – Data Classification Framework

## Purpose

Data classification helps DesertTech determine how information should be protected based on sensitivity, business value, privacy impact, and risk.

The four classification levels are:

1. Public
2. Internal
3. Confidential
4. Restricted

---

# 1. Public

### Definition

Information approved for unrestricted public disclosure.

### Examples

- Public website content
- Approved marketing brochure
- Public job advertisements

### Storage Requirements

May be stored on approved public or internal systems.

### Access Requirements

No special access restriction is required for information intended for public release.

### Sharing Restrictions

May be publicly shared once approved for publication.

### Disposal Requirements

Normal disposal is generally sufficient.

### Example Security Controls

- Content approval
- Change management
- Website security

---

# 2. Internal

### Definition

Information intended for use within DesertTech but not intended for public disclosure.

### Examples

- Internal procedures
- Internal meeting notes
- Internal operational documentation

### Storage Requirements

Store on approved company systems.

### Access Requirements

Access should be limited to authorized employees and approved third parties.

### Sharing Restrictions

Do not publicly disclose without authorization.

### Disposal Requirements

Use appropriate organizational disposal procedures.

### Example Security Controls

- Authentication
- Access control
- Internal sharing restrictions

---

# 3. Confidential

### Definition

Information that could cause significant business, financial, operational, or reputational impact if improperly disclosed.

### Examples

- Customer name/email database
- Security incident report
- Business strategy
- Supplier security assessment

### Storage Requirements

Store only on approved systems with appropriate security controls.

### Access Requirements

Need-to-know access and least privilege should apply.

### Sharing Restrictions

Sharing requires authorization and appropriate security protections.

### Disposal Requirements

Secure disposal should be used.

### Example Security Controls

- MFA
- Encryption
- Access reviews
- DLP
- Logging

---

# 4. Restricted

### Definition

Highly sensitive information requiring the strongest protection because unauthorized disclosure could create significant harm or security risk.

### Examples

- Employee payroll
- Passport copy
- Password database

### Storage Requirements

Store only in specifically approved secure systems.

### Access Requirements

Strict least-privilege and need-to-know access.

### Sharing Restrictions

Highly restricted and only shared when explicitly authorized and appropriately protected.

### Disposal Requirements

Secure destruction or verified secure deletion.

### Example Security Controls

- Strong MFA
- Encryption
- Privileged access management
- Detailed logging
- DLP
- Access reviews

---

# Data Classification Examples

| Information | Classification | Reason |
|---|---|---|
| Marketing brochure | Public | Intended for external distribution |
| Employee payroll | Restricted | Highly sensitive employee information |
| Customer name/email | Confidential | Personal data requiring protection |
| Passport copy | Restricted | Highly sensitive identity information |
| Password database | Restricted | Compromise could enable unauthorized access |
| Public website | Public | Intended for public access |
| Security incident report | Confidential | Contains sensitive security information |

---

# Classification Workflow

Identify Data
↓
Determine Sensitivity
↓
Assign Classification
↓
Apply Security Controls
↓
Control Access
↓
Review Periodically
↓
Retain According to Requirements
↓
Securely Dispose
