# ◊ FallEstateOnboard

**Sovereign UK estate & letting agent client onboarding.** AML CDD, Right-to-Rent, tenant referencing, deposit protection. Single HTML file. Data never leaves the device. Prime 887.

Part of the **estate agent bundle**: [fallestate](https://github.com/sjgant80-hub/fallestate) (883) · **fallestateonboard** (887) · [fallestatepaper](https://github.com/sjgant80-hub/fallestatepaper) (907) · [fallestatepractice](https://github.com/sjgant80-hub/fallestatepractice) (911).

Live: <https://sjgant80-hub.github.io/fallestateonboard/>

---

## For the end user

Onboard tenants, buyers, sellers, and landlords with a wizard that adapts by client type. Tenants get Right-to-Rent checks, referencing, guarantor capture, and deposit protection. Buyers get source-of-funds AML. All clients get sanctions screening, PEP checks, and vulnerability assessment.

### Wizard steps (tenant path)

| Step | What it captures |
|---|---|
| Type | Tenant / buyer / seller / landlord |
| Details | Name, DOB, nationality, employer, income |
| Contact | Phone, email, address |
| Tenancy | Property, rent, dates, AST type |
| AML | MLR 2017 CDD — ID, address, source of funds, sanctions, PEP |
| RTR | Immigration Act 2014 — document type, share code, confirmation |
| Referencing | Credit, employer ref, landlord ref, affordability, guarantor |
| Vulnerable | Category, details, adjustments |
| Deposit | Amount, scheme (DPS/MyDeposits/TDS), protection date |
| Documents | Upload with SHA-256 hashing and expiry tracking |

### Key rules

- **AML**: MLR 2017 — CDD for property transactions ≥€10k rent/year
- **RTR**: Immigration Act 2014 — civil penalty up to TBAk per occupier
- **Deposit**: Housing Act 2004 — protect within 30 days, 1-3x penalty
- **Tenant Fees Act 2019**: deposit capped at 5 weeks rent
- **Redress**: PRS or TPOS membership required, TBAk penalty

---

## Licence

MIT · Simon Gant · prime 887 · ◊·κ=1.
