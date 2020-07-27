# SOC2 Guide

SOC 2 is a security standard written by the American Institute of Certified Public Accountants (AICPA).

## Reading Material

Overview: [SOC 2 compliance guide for startup](https://blog.sqreen.com/soc-2-compliance-guide-for-startups/?ref=Welcome.AI)

In depth: [The Ultimate Guide to SOC 2 Compliance](https://www.blissfully.com/guides/soc-2-compliance/)

## Budget & Costs

Expect to spend $30-$50 CAD first year getting started.

## Timeline

- 1-3 Months prep
- 1-2 Months Report Prep after Audit/Observation Period

### Type 1
- Pick a point in time

### Type 2
- 3 month observation period possible first year
- 6 months observation period

## Decisions

### Type 1 or Type 2.

"In a SOC 2 Type 1 audit, a startup defines its best practices. Type 1 essentially presents a snapshot of security controls at a certain point in time. It collects evidence that shows the security controls that have been put in place and how the company is fulfilling them."

"In a SOC 2 Type 2 audit, a startup produces a sample set of evidence that proves its security controls have been followed over time. Type 2 is a six-month to a year longitudinal audit that evaluates the constancy of controls through the lens of security."

### Scope of Audit

What parts of the company will be SOC 2 compliant? Maybe exclude your marketing efforts.

## Tools

✅ = We used them.

### Audit Prep: [Vanta](https://vanta.com/) ✅

### Background checks:
- [Certn](https://certn.co/)
  - Vanta integration

### Password Manager:
 - [1Password](https://1password.com/) ✅
   - $12 CAD/month/user paid monthly
   - Need to go with the Business (not teams plan) in order to get access to the team wide password/security tools we needed
   - Use 1password.ca for data storage in Canada 🇨🇦
 - [LastPass](https://1password.com/)

### Vendor Assessment:
- [Vanta](https://vanta.com/) ✅
- Blissfully

### Single Sign On:
- GSuite ✅
  - Vanta integration
- Okta
- OneLogin

### Pentesting:
- HackerOne
- Cobalt

### Security Monitoring:
- Detectify ✅
- [sqreen](https://www.sqreen.com/)

### Security Training:
- [Hutsix](https://www.hutsix.io/)

### Auditors:


### Auditable Infrastructure:
- Terraform
- AWS
  - Vanta integration
- [Heroku](https://heroku.com)
  - Vanta integration
  - Use Database Standard-0 at least for encryption at rest. $50/m USD
  - Use [Papertrail]https://elements.heroku.com/addons/papertrail) Fixa plan for 365 day log retention. $8/m USD
- Google Cloud

### MFA/2FA:
- Google Aunthenticator App
- Yubico Key

### Staff Security Training:
- [Cybrary](https://app.cybrary.it/browse/skill-certification-course/end-user-security-fundamentals-certification-training-course)
  - Recommended by Vanta
  - Free if self registered

### Vulnerability Scanning - Internal
Scanning packages and dependencies for vulnerabilities.
- GitHub Security ✅
- [Ruby Advisory Database](https://github.com/rubysec/ruby-advisory-db) via Bundler Audit ✅
- Vanta ✅
- Yarn Audit ✅

## Plan & Notes

- Migrating from Public & Private Heroku spaces -> AWS
  - Working with contractors to accelorate migration to disrupt interna lfocuses and roadmap as little as possible
-

## Vendor Security Locations/Links

### GSuite
- Their SOC2 report likely sufficient
- self service download page
- https://cloud.google.com/security/compliance/compliance-reports-manager

### Freshworks
- email support request
- https://www.freshworks.com/security/resources/
