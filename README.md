# DHIS2 Configuration Repository

This repository is the **official source of truth** for DHIS2 configuration used in the government health information system.

It follows **configuration-as-code** principles to ensure:
- Auditability
- Reproducibility
- Security
- Neutrality

---

## Repository Scope

This repository manages **only configuration artifacts**:

- System Settings
- Logos and branding assets
- DHIS2 metadata (reviewed and approved)
- No credentials
- No personal or patient data

---

## 1. System Settings


### Description
Contains DHIS2 **System Settings** exported and maintained as code.

Examples:
- Application title
- Language and locale
- Start page
- Branding references (logos)
- Security-related system flags

### Rules
- System settings **must not** be changed directly in production UI
- Any change requires:
  - Git commit
  - Pull Request
  - HMIS / System Owner approval

---

## 2. Logos & Branding


### Description
Official and approved logos used in DHIS2, including:
- Login page logo
- Top menu logo
- Government / Ministry identity assets
- Favicon

### Key Principles
- GitHub is the **only source of truth**
- DHIS2 stores only **FileResource references**
- Logos are applied via scripts, not manual upload

### Naming Convention
- Lowercase
- No spaces
- Descriptive names


---

## 3. Metadata


### Description
Contains **approved DHIS2 metadata** such as:
- Data elements
- Indicators
- Programs
- Dashboards
- Organisation units

### Governance Rules
- Metadata changes follow the workflow:
- Production metadata **must not** be edited manually
- Each metadata change requires:
- One Pull Request
- Technical review
- Program/HMIS approval

---

## 4. Environments

This repository supports multiple environments:

- Development
- Staging
- Production

Environment-specific values (URLs, credentials) are **never committed**.
They are managed using:
- `.env` files
- Secure secrets storage

---

## 5. Security & Compliance

- No secrets in GitHub
- No credentials in scripts
- Full audit trail via Git history
- Compliant with government IT and donor requirements

---

## 6. Change Management

All changes must include:
- Clear commit message
- Purpose of change
- Approval reference (if applicable)

Example commit types:
- `branding`
- `config`
- `metadata`
- `docs`

---

## 7. Ownership

- Repository Owner: Government / HMIS Authority
- Maintainers: National IT / DHIS2 Team
- Contributors: Approved vendors and partners

---

## 8. Disclaimer

This repository contains **configuration only**.  
It does not include:
- Databases
- User accounts
- Health data

---

## 9. References

- DHIS2 Official Documentation
- National Digital Health Strategy
- HMIS Governance Guidelines