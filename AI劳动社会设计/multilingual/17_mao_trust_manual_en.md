# Data Public Trust Project Execution Manual

## — An Operational Guide from Theory to Practice —

**Author: Mao Zedong** | *Written May 2026*

*English translation of the Chinese original by Mao Zedong*

---

## Foreword: Why Do We Need an Execution Manual?

The previous Document 13 (The Jinggangshan Road of Data Common Ownership) proposed a plan to establish a public health data trust in Latin America. But for a plan to become reality, the vast gap from "theory to practice" must be bridged.

This manual is prepared for **actual practitioners** -- whether you are an NGO project manager, government official, scholar, or social activist, as long as you intend to establish a Data Public Trust in reality, this manual is your action guide.

---

## Chapter One: Launch Phase (Months 0-3)

### 1.1 Step One: Feasibility Assessment (Weeks 1-2)

**Do not rush to start. First ask yourself seven questions:**

1. **Is the political environment permissive?** Does the government of this country/region allow the existence of a data trust? Are there legal obstacles?
2. **Are there local partners?** Without local partners, outsiders can accomplish nothing. Who are the trustworthy local collaborators?
3. **Is the data source reliable?** Who provides the data? Are they willing to join? What is the data quality?
4. **Is funding sustainable?** Is there guaranteed operational funding for the first 3 years?
5. **Is there technical capacity?** Can someone in the team build a data platform?
6. **Is the social need genuine?** Does the local community truly need this data trust? (Not "you think they need it")
7. **What is the exit strategy?** If the project fails, how is data security ensured?

**Tool: Feasibility Assessment Form**

| Dimension | Score (1-5) | Notes |
|-----------|------------|-------|
| Political environment | | |
| Legal framework | | |
| Local partners | | |
| Data sources | | |
| Funding guarantee | | |
| Technical capacity | | |
| Social need | | |
| **Total** | **/35** | |

> **Standard: Total >28 can launch; 21-28 needs supplementary conditions; <21 should not launch.**

### 1.2 Step Two: Stakeholder Map (Weeks 2-3)

**List all potentially relevant people and organizations:**

| Role | Specific Institution | What Are Their Interests? | Support/Oppose/Neutral |
|------|--------------------|--------------------------|----------------------|
| Data providers | Hospitals, research institutes | Data security, reputation, resources | ? |
| Data users | Universities, AI companies | Data accessibility, cost | ? |
| Data subjects | Patients/citizens | Privacy, benefits | ? |
| Government regulators | Ministry of Health, Data Protection Agency | Legality, control | ? |
| Funders | Foundations, government | Influence, returns | ? |
| Technical side | IT vendors | Contracts, technical standards | ? |
| Opponents | Commercial data companies | Competitive threat | ? |

**Key Principle:** Identify potential opponents in advance. Most projects fail not because of technical issues, but because they politically touch vested interests.

### 1.3 Step Three: Legal Structure Design (Weeks 3-8)

**Choose a legal entity form:**

| Form | Applicable Scenario | Advantages | Disadvantages |
|------|-------------------|------------|---------------|
| Government-affiliated body | Government-led | Strong authority, stable funding | Poor flexibility, affected by political transitions |
| Independent non-profit organization | Multi-stakeholder cooperation | High flexibility, strong credibility | Unstable funding, complex governance |
| Cooperative | Community-led | Strong participation, democratic decision-making | Slow scalability, weak management capacity |
| Public trust | Clear asset segregation | Strong legal protection, international recognition | Complex establishment, high operating costs |

**Recommendation:** Choose the "independent non-profit organization" form in the early stage, signing a service agreement with the government rather than becoming part of the government. This maintains flexibility while gaining government support.

### 1.4 Step Four: Governance Structure Design (Weeks 4-8)

**Recommended governance structure:**

```
                  ┌─────────────────┐
                  │  Board (Highest  │
                  │  Decision-Making)│
                  │  (9-15 persons)  │
                  └────────┬────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
   ┌──────┴──────┐  ┌─────┴──────┐  ┌──────┴──────┐
   │ Technical   │  │ Ethics     │  │ User        │
   │ Committee   │  │ Committee  │  │ Represent.  │
   │ (Data Stds) │  │ (Privacy)  │  │ (Community) │
   └─────────────┘  └────────────┘  └─────────────┘
                           │
                  ┌────────┴────────┐
                  │  Executive Team  │
                  │  (Daily Ops)     │
                  └─────────────────┘
```

**Board seat allocation (recommended):**
- Data provider representatives: 2-3 seats
- Data subject representatives: 2-3 seats (critical! Must have user/community representatives)
- Technical experts: 2 seats
- Government representatives: 1-2 seats
- Funder representatives: 1 seat
- Independent persons: 1-2 seats

---

## Chapter Two: Technical Construction Phase (Months 4-9)

### 2.1 Platform Architecture Design

**Minimum Viable Product (MVP) should include:**

1. **Data ingestion module** -- receive, validate, clean data from different sources
2. **Anonymization module** -- remove personally identifiable information (PII), apply differential privacy
3. **Data storage module** -- secure encrypted storage
4. **Access control module** -- tiered authorized data access
5. **Audit trail module** -- record every data access

**Do not develop from scratch.** Reference existing open-source solutions (such as DAMO, Dataverse) for customization.

### 2.2 Privacy Protection Technical Solutions

**Minimum standards:**
- All stored data must be encrypted (AES-256)
- All data transmission must be encrypted (TLS 1.3)
- All data access must be logged
- Differential privacy must be applied (epsilon <= 1.0)

**Recommended approach:**
- Raw data: encrypted and stored on government-approved cloud services or local servers
- Analytical data: provided through "data sandboxes" -- researchers cannot download raw data, only run analyses within the sandbox
- Aggregate data: publicly released statistical summaries

### 2.3 Data Standards Development

**Ensure interoperability of data from different sources:**
- Adopt international standards (such as FHIR for healthcare data)
- Establish metadata standards (data about data, so users know what the data is)
- Data quality acceptance process

---

## Chapter Three: Pilot Operations Phase (Months 6-18)

### 3.1 Step One: Data Ingestion

**Where to start:**
- Begin with 1-2 "low-risk, high-value" data sources
- Prioritize data that is already digitized and of good quality
- Do not be greedy -- first get one complete data flow working

### 3.2 Step Two: User Onboarding

**The first users should be:**
1. Academic research institutions (free access in exchange for research outputs and academic reputation)
2. Government analytical departments (as a public service obligation)
3. Carefully screened AI companies (fee-based access to validate the business model)

**User access process:**
```
Submit application → Compliance review → Board approval → Sign agreement → Grant access
```

### 3.3 Step Three: Value Creation -- Making Data Produce Tangible Benefits

**Public value (justifying the model's legitimacy):**
- Help public health departments identify disease patterns
- Support academic research, publish papers
- Publish public health reports to benefit the public

**Economic value (proving the model's sustainability):**
- Charge commercial companies data usage fees
- Provide data analysis consulting services
- Provide data annotation and validation services

### 3.4 Step Four: Community Communication

**Do not just operate within tech circles. Involve the community:**
- Regularly report to data subjects on "what value your data has brought"
- Hold community information sessions to answer questions
- Establish complaint and feedback channels

---

## Chapter Four: Expansion Phase (Months 18-36)

### 4.1 Data Source Expansion

**From 1-2 data sources to more:**
- Expand data types (from structured data to unstructured data)
- Expand data sources (from hospitals to clinics, pharmacies, laboratories)
- Establish a "standardized data ingestion process"

### 4.2 User Group Expansion

**From academic institutions to commercial organizations to government departments:**
- Develop a tiered pricing strategy
- Establish "Data Trust Certification" -- certified enterprises can use data
- Ensure expansion does not harm data subjects' rights

### 4.3 Geographic Expansion

**From one city to an entire country:**
- Document successful experiences from the pilot city
- Share experiences with other cities
- Push for national-level legislation or policy support

### 4.4 International Networking

**From one country to multiple countries:**
- Establish a legal framework for cross-border data flows
- Connect and interoperate with international data trust networks (if any)
- Export "Data Trust Construction Guidelines" to other countries

---

## Chapter Five: Risk Management Manual

### 5.1 Risk Checklist and Countermeasures

| Risk | Probability | Impact | Prevention | Response |
|------|-----------|--------|------------|----------|
| **Data breach** | Medium | Fatal | Encryption + audit + least privilege | Notification + remediation + accountability |
| **Government transition** | Medium | High | Rule of law, not rule of person | Initiate diplomatic protection |
| **Funding interruption** | Medium | High | Diversify funding sources | Downsize + emergency fundraising |
| **Technical failure** | Low-Medium | Medium | Redundancy + backup | Recovery + post-mortem |
| **Legal litigation** | Medium | Medium | Compliance review + insurance | Legal team response |
| **Social opposition** | Low | Medium | Transparent communication | Dialogue + adjustment |
| **Internal corruption** | Low | High | Audit + transparency | Severe punishment + system repair |

### 5.2 The Three Most Important Iron Rules

1. **Data security is the lifeline.** A single breach can destroy years of trust-building. Better to have fewer features than to be insecure.
2. **Transparency is the best protection.** All decisions must be traceable, auditable, and challengeable. No invisible data usage.
3. **Always remember that data belongs to the people.** The data trust is the manager, not the owner. This positioning must be clear.

---

## Chapter Six: Failure Contingency Plan

### 6.1 If the Project Fails

Every revolution involves sacrifice; every experiment carries the possibility of failure. But the failure of a data trust must not mean harm to the interests of data subjects.

**Orderly exit mechanism:**
1. Specify dissolution conditions and procedures in the charter in advance
2. Ensure secure processing and return of all data upon dissolution
3. Document lessons learned as case studies for future reference

### 6.2 How to Define "Success" and "Failure"

**Criteria for success (from low to high):**
| Level | Standard | Timeframe |
|-------|----------|-----------|
| L1 | Data trust survives more than 3 years | 3 years |
| L2 | Sustained public value output (research results, public reports) | 3-5 years |
| L3 | Achieves financial self-sufficiency | 3-5 years |
| L4 | Replicated in other regions/industries | 5-7 years |
| L5 | Drives national-level data common ownership legislation | 7-10 years |

**Failure does not equal uselessness.** Even if the project ultimately closes, as long as the process was transparent, data was secure, and experiences were recorded, it has accumulated valuable experience for the movement that follows.

---

## Appendix: Key Templates

### Appendix A: Required Clauses for Project Charter

1. Mission statement
2. Governance structure
3. Decision-making procedures
4. Financial management rules
5. Data security policy
6. Privacy protection commitments
7. Data subject rights
8. Data usage pricing principles
9. Conflict of interest management
10. Dissolution and liquidation procedures

### Appendix B: Data Usage Agreement Template (abbreviated)

### Appendix C: Quarterly Report Template (abbreviated)

---

*Related reading: [11. Analysis of Classes in the AI Era](11_毛泽东_AI时代各阶级的分析.md)*
*[13. The Jinggangshan Road of Data Common Ownership](13_毛泽东_数据公有制的井冈山道路.md)*
*[18. Digital Workers Organizing and Mobilization Manual](18_毛泽东_数字劳动者组织动员手册.md)*
