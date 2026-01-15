# DHIS2 System Settings – Appearance settings

## 1. General Application Settings

- **System default language**
  - English

- **Application title**
  - Electronic Health Management Information System

- **Application introduction**
  
```text
  नेपाल सरकार
  स्वास्थ्य तथा जनसङ्ख्या मन्त्रालय
  स्वास्थ्य सेवा विभाग
  व्यवस्थापन महाशाखा
  एकीकृत स्वास्थ्य सूचना व्यवस्थापन शाखा
```
- **Application notification**
```text
<div class="my-container">
    <div style="font-weight: bold;color: #000;margin-bottom: 5px;"></div>
    <a class="link-style" href="https://hmis-docs.hispnp.org"> Documentation</a>
    <a class="link-style" href="https://community.dhis2mis.org"> Community & Support</a>
    <a class="link-style" href="https://academy.dhis2mis.org/"> Academy (Training)</a>
    <a class="link-style" href="#"> Apps & Extensions</a>
    <a class="link-style" href="https://ocl.hmis.gov.np"> Health Information Standards (OCL) </a>
    <a class="link-style" href="#"> Releases & Roadmap </a>
    <a class="link-style" href="#"> FHIR Implementation Guide </a>
</div>
```

- **Application left-side footer**
  - Docs : <a href="https://hmis-docs.hispnp.org">https://hmis-docs.hispnp.org</a>

- **Application right-side footer**
  - System default (English)

---

## 2. Appearance & Style

- **Style (Android)**
  - Light Blue

- **Flag**
  - Nepal

- **Interface language**
  - English

- **Database language**
  - System default

---

## 3. Navigation & Start Page

- **Start page**
  - eRecord

- **Enable lightweight start page**
  - Enabled

- **Help page link**
  - Not configured (System default)

---

## 4. Security & Permissions

- **Require authority to add to view object lists**
  - Enabled

---

## 5. Branding & Logos

- **Custom login page logo**
  - Configured (FileResource-based)

- **Custom top menu logo**
  - Configured (FileResource-based)

---

## 6. Login Page Configuration

- **Login page theme**
  - Default

- **Login page template**
  - Default

---

## 7. Governance Notes

- All settings are maintained as **configuration-as-code**
- Changes must be:
  - Reviewed via Pull Request
  - Approved by HMIS / System Administrator
- No UI-only changes are allowed in production

---

## 8. Environment Scope

| Environment | Applied |
|------------|--------|
| Development | Yes |
| Staging | Yes |
| Production | Yes (after approval) |

---

## 9. References

- DHIS2 System Settings API
- National Digital Health Governance Guidelines
- HMIS Branding & Identity Policy
