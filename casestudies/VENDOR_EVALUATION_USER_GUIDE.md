# Vendor Evaluation Process - User Guide# Vendor RFQ Evaluation Process - User Guide



**Complete Step-by-Step Instructions for Healthcare IT Vendor Selection**## Overview

This comprehensive Excel workbook provides a complete framework for evaluating and selecting vendors for mission-critical healthcare IT systems, specifically designed for HL7/FHIR integration platforms.

---

**File:** `Vendor_RFQ_Evaluation_Process_Comprehensive.xlsx`  

## Table of Contents**Created:** November 30, 2025  

1. [Getting Started](#getting-started)**Version:** 1.0

2. [Sheet-by-Sheet Instructions](#sheet-by-sheet-instructions)

3. [Scoring Guidelines](#scoring-guidelines)---

4. [Decision Gates](#decision-gates)

5. [Best Practices](#best-practices)## 📋 Workbook Structure

6. [Troubleshooting](#troubleshooting)

The Excel file contains **11 worksheets** that guide you through the entire vendor evaluation lifecycle, including real-world examples:

---

### Example Vendors Included:

## Getting Started- **Mirth Connect** (Open Source / BUILD option) - Free platform with customization

- **InterSystems HealthShare** (Enterprise / BUY option) - Premium commercial solution

### Prerequisites- **Rhapsody Integration Engine** (Mid-Market / BUY option) - Balanced commercial option

- Microsoft Excel 2016 or later (or compatible spreadsheet software)

- Basic understanding of your organization's integration requirements---

- Stakeholder team assembled (Clinical, IT, Security, Procurement)

### 1️⃣ **Process Overview**

### Initial Setup- **Purpose:** High-level view of the 6-phase evaluation process

1. **Open the Excel file**: `Vendor_RFQ_Evaluation_Process_Comprehensive.xlsx`- **Contents:** 

2. **Save a working copy**: Keep the original as a template  - Complete process flow from RFQ receipt to contract signing

3. **Review all sheets**: Familiarize yourself with the 11 worksheets  - Decision gates and branching logic

4. **Customize vendor names**: Replace example vendors with your actual candidates  - Timeline estimates for each phase

  - Key deliverables

---- **How to Use:** Start here to understand the overall process. Reference this sheet throughout your evaluation to track progress.



## Sheet-by-Sheet Instructions### 2️⃣ **Compliance Checklist** 

- **Purpose:** Phase 1 - Initial screening of vendor responses

### Sheet 1: Process Overview- **Contents:**

  - Mandatory vs. optional requirements

**Purpose**: Understand the 6-phase evaluation framework  - Submission requirements validation

  - Documentation completeness check

**What to Review**:  - Certifications verification (HIPAA, SOC 2, HITRUST)

- **Phase 1**: Initial Screening - Filter out non-viable vendors  - Technical requirements confirmation

- **Phase 2**: Detailed Evaluation - Score against weighted criteria  - Automated PASS/FAIL calculation

- **Phase 3**: Vendor Demonstrations - Assess real-world capabilities- **How to Use:**

- **Phase 4**: Reference Checks - Validate vendor claims  1. Enter "Yes", "No", or "N/A" for each vendor in columns D, E, F

- **Phase 5**: BAFO & Negotiation - Finalize commercial terms  2. Add notes in column G about discrepancies

- **Phase 6**: Final Recommendation - Make the selection  3. Review the automatic PASS/FAIL decision at the bottom

  4. Only proceed with vendors who PASS

**Action Items**:

1. Review timeline estimates (typically 8-12 weeks total)### 3️⃣ **Evaluation Matrix**

2. Identify your project stakeholders for each phase- **Purpose:** Phase 2 - Detailed weighted scoring across 5 categories

3. Note the decision gates (GO/NO-GO checkpoints)- **Contents:**

4. Plan your evaluation schedule  - **Functional Requirements (35%)**: HL7 v2, FHIR R4, transformations, error handling

  - **Technical Capabilities (30%)**: Architecture, performance, APIs, DevOps support

**Decision Gates**:  - **Security & Compliance (20%)**: Encryption, audit logs, certifications, privacy controls

- ✅ After Phase 1: Proceed only with 3-5 qualified vendors  - **Vendor Viability (10%)**: Financial stability, market presence, support quality

- ✅ After Phase 2: Shortlist to 2-3 vendors for demos  - **Commercial Terms (5%)**: Pricing model, TCO, contract flexibility

- ✅ After Phase 4: Select 1-2 vendors for BAFO  - Automated weighted score calculation

  - Automatic ranking and recommendation

---- **How to Use:**

  1. Enter vendor names in cells B3, D3, F3

### Sheet 2: Compliance Checklist  2. Score each criterion in the "V1/V2/V3 Score" columns (use max score as reference)

  3. Weighted scores calculate automatically

**Purpose**: Verify mandatory requirements before detailed evaluation  4. Review category subtotals and total weighted score

  5. The system will identify the top choice with 🏆

**How to Use**:

1. **List Requirements** (Column B): Already populated with 24 standard items### 4️⃣ **Demo Evaluation**

2. **Add Custom Requirements**: Insert rows for organization-specific needs- **Purpose:** Phase 4 - Assess live technical demonstrations

3. **Vendor Response** (Columns D, F, H):- **Contents:**

   - Enter "Yes" if vendor meets the requirement  - Demo scenarios: HL7 processing, FHIR operations, transformations, error handling

   - Enter "No" if they don't  - Performance and monitoring assessment

   - Enter "Partial" with explanation if partially met  - Red flags checklist (critical issues to watch for)

4. **Overall Result** (Row 27): Manually enter "PASS" or "FAIL"  - Overall pass/fail recommendation

- **How to Use:**

**Scoring Rules**:  1. Schedule 2-3 hour demos with each vendor

- ⚠️ **ANY "No" = FAIL** - This is a strict compliance check  2. Request they use YOUR actual (anonymized) data

- All mandatory items must be "Yes" or acceptable "Partial"  3. Score each scenario on a 1-5 scale

- Document any "Partial" responses with details  4. Document observations in the Notes columns

  5. Check any observed red flags

**Example Requirements**:  6. Use this to validate vendor claims from their proposals

- ✅ HIPAA Compliance Certification

- ✅ SOC 2 Type II Audit Report### 5️⃣ **Reference Checks**

- ✅ HL7 v2.x Support (minimum v2.3)- **Purpose:** Phase 4 - Validate vendor claims through customer interviews

- ✅ FHIR R4 Compatibility- **Contents:**

- ✅ 24/7 Production Support  - Structured interview template

  - Key questions across: Implementation, Performance, Support, Cost, Relationship

**Pro Tips**:  - Red flags section

- Request proof documentation for each "Yes"  - Overall reference rating

- Use vendor questionnaires to gather this data- **How to Use:**

- Reject vendors early if they fail compliance  1. Contact at least 3 customers per vendor

- Add industry-specific requirements (HITRUST, PCI-DSS, etc.)  2. Mix vendor-provided references with independently sourced ones

  3. Ask probing questions about what went wrong (not just success stories)

---  4. Document verbatim responses

  5. Rate each reference interaction

### Sheet 3: Evaluation Matrix - WEIGHTED SCORING  6. Look for patterns across multiple references



**Purpose**: Score vendors against 52 detailed criteria across 5 categories### 6️⃣ **BAFO Template**

- **Purpose:** Phase 5 - Request improved offers when top vendors are too close

**Understanding the Scoring System**:- **Contents:**

  - Professional request letter template

#### Category Weights:  - Checklist of areas for improvement:

| Category | Weight | Max Points |    - Pricing & commercial terms

|----------|--------|------------|    - Additional value-adds

| Functional Requirements | 35% | 35 points |    - Improved SLAs

| Technical Capabilities | 30% | 30 points |    - Implementation timeline

| Security & Compliance | 20% | 20 points |    - Contract flexibility

| Vendor Viability | 10% | 10 points |- **How to Use:**

| Commercial Terms | 5% | 5 points |  1. Use this when 2-3 vendors are within 5-10 points of each other

| **TOTAL** | **100%** | **100 points** |  2. Customize the letter with your specific requirements

  3. Send to shortlisted vendors simultaneously

#### Scoring Scales:  4. Set a clear deadline (typically 1-2 weeks)

- **Functional Requirements**: 1-10 scale (1=Poor, 10=Excellent)  5. Re-score vendors with new information

- **Technical Capabilities**: 1-5 scale (1=Weak, 5=Strong)  6. Return to the Evaluation Matrix to update scores

- **Security & Compliance**: 1-5 scale (1=Inadequate, 5=Best-in-class)

- **Vendor Viability**: 1-3 scale (1=Concern, 3=Excellent)### 7️⃣ **Final Recommendation**

- **Commercial Terms**: 1-4 scale (1=Poor, 4=Excellent)- **Purpose:** Phase 5-6 - Executive decision package

- **Contents:**

**How to Score**:  - Executive summary with key strengths and risks

  - Evaluation summary statistics

1. **Enter Raw Scores** in columns D, F, H (for each vendor)  - Side-by-side scoring comparison

2. **Weighted Points Calculate Automatically** in columns E, G, I  - 5-year financial analysis and TCO

3. **Subtotals Sum Automatically** at the end of each category  - Implementation plan with timeline

4. **Grand Total Calculates** automatically (row 50)  - Risk assessment and mitigation strategies

  - Success criteria and KPIs

**Scoring Guidelines by Category**:  - Approval signature block

- **How to Use:**

#### 1️⃣ Functional Requirements (35% - Score 1-10)  1. Complete this after final scoring

Focus on **what the system can do**:  2. Tailor the narrative to your organization's priorities

- **HL7 v2 Message Support** (6%):  3. Include specific dollar amounts and dates

  - 10 = All message types, full parsing  4. Present to stakeholders before executive approval

  - 7-9 = Most common messages  5. Use as basis for contract negotiation

  - 4-6 = Basic support only  6. Obtain required signatures

  - 1-3 = Limited or custom development needed

### 8️⃣ **Lessons Learned**

- **FHIR R4 Implementation** (6%):- **Purpose:** Post-selection reflection and continuous improvement

  - 10 = Complete FHIR R4, all resources- **Contents:**

  - 7-9 = Core resources, some extensions  - Common pitfalls and how to avoid them

  - 4-6 = Basic FHIR support  - What went well in your evaluation

  - 1-3 = Roadmap item only  - What could be improved

  - Key takeaways

- **Message Transformation & Mapping** (5%):  - Recommended timeline for future evaluations

  - 10 = Visual mapper, templates, AI-assist- **How to Use:**

  - 7-9 = GUI mapper with library  1. Complete this AFTER vendor selection

  - 4-6 = Code-based mapping  2. Conduct a retrospective with your evaluation team

  - 1-3 = Manual scripting only  3. Document both successes and challenges

  4. Use these insights for your next evaluation

- **Data Validation & Quality** (5%):  5. Share with other teams in your organization

  - 10 = Real-time validation, data quality rules engine

  - 7-9 = Schema validation, basic checks### 9️⃣ **Build vs Buy vs Rent** 🆕

  - 4-6 = Manual validation rules- **Purpose:** Strategic decision framework for acquisition approach

  - 1-3 = Minimal validation- **Contents:**

  - Comprehensive comparison across BUILD (Mirth), BUY (InterSystems), RENT (SaaS) options

- **Error Handling & Recovery** (5%):  - Initial investment analysis

  - 10 = Automatic retry, alerting, dead-letter queues  - 5-year total cost of ownership (TCO)

  - 7-9 = Retry logic, manual recovery  - Capability and flexibility comparison

  - 4-6 = Basic error logging  - Risk and support considerations

  - 1-3 = Errors require manual intervention  - Scalability assessment

  - Decision matrix by organization type

- **Routing & Orchestration** (5%):  - Scenario-based recommendations

  - 10 = Visual workflow designer, complex routing- **How to Use:**

  - 7-9 = Rule-based routing  1. Review before starting vendor evaluation

  - 4-6 = Simple routing tables  2. Assess your organization's profile (size, budget, IT capability)

  - 1-3 = Point-to-point only  3. Evaluate risk tolerance and customization needs

  4. Calculate TCO for your specific context

- **Pre-built Connectors** (3%):  5. Use the decision matrix to guide BUILD vs BUY vs RENT choice

  - 10 = 50+ healthcare system connectors- **Sample Data:**

  - 7-9 = 20-50 connectors  - BUILD (Mirth): $2.74M over 5 years, high flexibility, high risk

  - 4-6 = 10-20 connectors  - BUY (InterSystems): $2.5M over 5 years, medium flexibility, medium risk

  - 1-3 = Few or custom development needed  - RENT (Cloud SaaS): $1.8M over 5 years, low flexibility, low risk



#### 2️⃣ Technical Capabilities (30% - Score 1-5)### 🔟 **Complexity Analysis** 🆕

Focus on **how well it's built**:- **Purpose:** Quantitative assessment of implementation complexity by vendor

- **System Architecture** (5%):- **Contents:**

  - 5 = Modern, cloud-native, microservices  - Technical complexity scoring (installation, learning curve, custom code)

  - 4 = Hybrid, containers supported  - Integration complexity (systems, data formats, volumes)

  - 3 = Monolithic but scalable  - Organizational complexity (skills, change management, training)

  - 2 = Legacy architecture  - Operational complexity (maintenance, support, upgrades)

  - 1 = Outdated, difficult to scale  - Compliance complexity (security, auditing, certifications)

  - Total complexity score (out of 125 points)

- **Performance & Throughput** (5%):  - Risk ratings and mitigation strategies

  - 5 = >100K messages/day proven  - Color-coded risk levels (red=high, yellow=medium, green=low)

  - 4 = 50K-100K messages/day- **How to Use:**

  - 3 = 10K-50K messages/day  1. Review complexity scores for each vendor option

  - 2 = <10K messages/day  2. Assess your team's capability against complexity requirements

  - 1 = Performance concerns  3. High complexity (>72%): Requires expert team and governance

  4. Medium complexity (40-72%): Standard implementation with training

- **API Management** (4%):  5. Low complexity (<40%): Straightforward deployment

  - 5 = Full API gateway, rate limiting, versioning  6. Use mitigation strategies to address high-complexity areas

  - 4 = RESTful APIs with basic management- **Sample Results:**

  - 3 = APIs available, limited management  - Mirth Connect: 86% complexity (HIGH RISK) - requires expert developers

  - 2 = Limited API support  - InterSystems: 50% complexity (MODERATE) - adequate with vendor support

  - 1 = No API layer  - Rhapsody: 48% complexity (MODERATE) - balanced approach



- **Integration Patterns** (4%):### 1️⃣1️⃣ **SWOT Analysis** 🆕

  - 5 = All patterns (Pub/Sub, Request/Reply, Batch, Streaming)- **Purpose:** Strategic assessment of strengths, weaknesses, opportunities, and threats for each vendor

  - 4 = Most patterns supported- **Contents:**

  - 3 = Common patterns only  - Individual SWOT matrices for all three vendor options

  - 2 = Limited patterns  - Color-coded quadrants (green=strengths, red=weaknesses, yellow=opportunities, gray=threats)

  - 1 = Basic point-to-point  - "Best For" and "Not Suitable For" summaries

  - Key success factors and deal breakers

- **Monitoring & Observability** (4%):  - Comparative SWOT summary table

  - 5 = Real-time dashboards, alerts, APM integration  - Strategic fit recommendations

  - 4 = Good monitoring, basic dashboards- **How to Use:**

  - 3 = Log files and basic metrics  1. Review each vendor's SWOT matrix

  - 2 = Limited visibility  2. Identify which strengths align with your priorities

  - 1 = Minimal monitoring  3. Assess whether weaknesses are acceptable trade-offs

  4. Evaluate opportunities for future growth

- **DevOps & CI/CD Support** (3%):  5. Determine if threats are manageable risks

  - 5 = Full GitOps, containerized, infrastructure-as-code  6. Match vendor characteristics to your organizational profile

  - 4 = Good CI/CD support- **Key Insights:**

  - 3 = Basic automation possible  - **Mirth Connect:** Best for tech-savvy teams with budget constraints, but high operational risk

  - 2 = Limited automation  - **InterSystems:** Best for large enterprises needing vendor support, but high cost and vendor lock-in

  - 1 = Manual deployment only  - **Rhapsody:** Best for mid-market seeking balance, but smaller ecosystem and market presence



- **Data Storage Options** (3%):---

  - 5 = Multiple options (SQL, NoSQL, object storage)

  - 4 = Good database support## 🎯 Quick Start Guide

  - 3 = Standard database

  - 2 = Limited storage options### For First-Time Users:

  - 1 = Proprietary storage only1. **Read Sheet 1 (Process Overview)** to understand the end-to-end flow

2. **Review Sheet 9 (Build vs Buy vs Rent)** to decide your acquisition strategy

- **Standards Compliance** (2%):3. **Start with Sheet 2 (Compliance Checklist)** to eliminate non-compliant vendors

  - 5 = All major standards (HL7, FHIR, DICOM, X12)4. **Move to Sheet 3 (Evaluation Matrix)** for detailed scoring (with sample data)

  - 4 = Most healthcare standards5. **Check Sheet 10 (Complexity Analysis)** to understand implementation risks

  - 3 = Core standards only6. **Review Sheet 11 (SWOT Analysis)** for strategic assessment

  - 2 = Limited standards7. **Use Sheets 4-5** during the validation phase

  - 1 = Proprietary protocols8. **Apply Sheet 6 (BAFO)** only if needed

9. **Complete Sheet 7** for executive presentation

#### 3️⃣ Security & Compliance (20% - Score 1-5)10. **Fill Sheet 8** after selection for future reference

Focus on **data protection and regulations**:

- **Authentication & Authorization** (3%):### For Experienced Users:

  - 5 = Enterprise SSO, RBAC, MFA, SAML/OAuth- Jump directly to the sheet relevant to your current phase

  - 4 = Good access controls- Use the Process Overview sheet as a checklist

  - 3 = Basic authentication- Customize scoring weights in the Evaluation Matrix to fit your priorities

  - 2 = Limited security- Leverage the sample vendor data as templates for your own evaluation

  - 1 = Weak authentication

### Understanding the Sample Data:

- **Encryption & Data Protection** (3%):The workbook includes realistic scores for three vendor types:

  - 5 = TLS 1.3, at-rest encryption, HSM support- **Mirth Connect (BUILD):** Low cost, high complexity, maximum flexibility

  - 4 = Strong encryption- **InterSystems (BUY):** High cost, medium complexity, enterprise features

  - 3 = Basic encryption- **Rhapsody (BUY):** Medium cost, medium complexity, user-friendly

  - 2 = Partial encryption

  - 1 = Weak encryptionUse these as benchmarks when scoring your actual vendors.



- **Audit & Compliance Logging** (3%):---

  - 5 = Comprehensive audit trails, immutable logs

  - 4 = Good logging## � Understanding the Sample Vendors

  - 3 = Basic audit logs

  - 2 = Limited loggingThe workbook includes three realistic vendor examples representing different acquisition strategies:

  - 1 = Minimal audit trail

### 1. Mirth Connect (BUILD Option)

- **Regulatory Certifications** (3%):**Profile:** Open-source integration engine

  - 5 = HITRUST, SOC 2, ISO 27001, FedRAMP- **Cost:** Free license, but high operational costs ($2.74M over 5 years)

  - 4 = SOC 2 + one other- **Strengths:** Zero licensing fees, full customization, no vendor lock-in

  - 3 = SOC 2 only- **Weaknesses:** Requires strong development team, no formal support, compliance burden

  - 2 = In progress- **Best For:** Tech-forward organizations with strong Java/JavaScript skills and tight budgets

  - 1 = None- **Complexity Score:** 86% (HIGH RISK)

- **Evaluation Score:** 70.5/100 (Acceptable)

- **Vulnerability Management** (2%):

  - 5 = Continuous scanning, bug bounty, rapid patching### 2. InterSystems HealthShare (BUY Option - Enterprise)

  - 4 = Regular scanning and patching**Profile:** Premium enterprise integration platform

  - 3 = Basic vulnerability management- **Cost:** High upfront investment ($2.5M over 5 years)

  - 2 = Reactive only- **Strengths:** 40+ years in healthcare, excellent FHIR support, 24/7 support, all certifications

  - 1 = Limited process- **Weaknesses:** Expensive, steep learning curve, vendor lock-in, requires Caché/ObjectScript

- **Best For:** Large health systems, high message volumes, complex enterprise integrations

- **Consent Management** (2%):- **Complexity Score:** 50% (MODERATE)

  - 5 = Built-in consent framework (FHIR Consent)- **Evaluation Score:** 85.5/100 (Good) 🏆 **TOP CHOICE**

  - 4 = Good consent support

  - 3 = Basic consent handling### 3. Rhapsody Integration Engine (BUY Option - Mid-Market)

  - 2 = Limited support**Profile:** User-friendly commercial integration engine

  - 1 = Manual process- **Cost:** Moderate pricing ($1.8M over 5 years)

- **Strengths:** Easy to use, good documentation, faster implementation, responsive support

- **Data Privacy Controls** (2%):- **Weaknesses:** Smaller market share, fewer pre-built connectors, less enterprise features

  - 5 = GDPR-ready, data residency, right-to-delete- **Best For:** Medium-sized hospitals prioritizing ease of use and reasonable cost

  - 4 = Good privacy controls- **Complexity Score:** 48% (MODERATE)

  - 3 = Basic privacy features- **Evaluation Score:** 81.5/100 (Good)

  - 2 = Limited controls

  - 1 = Minimal privacy features### Key Trade-offs Illustrated:



- **Network Security** (2%):| Factor | Mirth (BUILD) | InterSystems (BUY) | Rhapsody (BUY) |

  - 5 = VPN, firewall rules, network segmentation, DDoS protection|--------|---------------|-------------------|----------------|

  - 4 = Good network security| **Initial Cost** | Low | Very High | Medium |

  - 3 = Basic security| **5-Year TCO** | $2.74M | $2.5M | $1.8M |

  - 2 = Limited controls| **Complexity** | Very High | Medium | Medium |

  - 1 = Weak network security| **Flexibility** | Maximum | Moderate | Moderate |

| **Risk** | High | Medium | Medium |

#### 4️⃣ Vendor Viability (10% - Score 1-3)| **Support** | Community | Enterprise | Enterprise |

Focus on **vendor stability and support**:| **Time to Value** | 6-9 months | 4-6 months | 3-4 months |

- **Financial Stability** (2%):

  - 3 = Profitable, strong financials, established company### Strategic Insights:

  - 2 = Break-even or venture-backed- **Lowest TCO ≠ Best Choice:** Rhapsody has lowest TCO but InterSystems scored highest

  - 1 = Financial concerns or unknown- **Hidden Costs:** Mirth's "free" license becomes expensive with staffing ($400K/year)

- **Complexity Tax:** High complexity (Mirth) requires expert team or expensive consultants

- **Market Presence & Track Record** (2%):- **Vendor Lock-in:** InterSystems has highest score but creates dependency

  - 3 = 10+ years, 100+ customers- **Sweet Spot:** Rhapsody balances cost, features, and ease of use for mid-market

  - 2 = 5-10 years, 50+ customers

  - 1 = New or small customer base---



- **Healthcare Experience** (2%):## �🔢 Scoring Guidance

  - 3 = Specialized in healthcare, deep expertise

  - 2 = Healthcare is one focus area### Evaluation Matrix Scoring Scale:

  - 1 = Limited healthcare experience- **10/10 or 5/5:** Exceptional - Exceeds all requirements, industry-leading

- **8-9 or 4:** Strong - Meets all requirements with some nice-to-haves

- **Support & SLA Guarantees** (2%):- **6-7 or 3:** Adequate - Meets minimum requirements, nothing special

  - 3 = 24/7/365 support, 99.9% uptime SLA- **4-5 or 2:** Weak - Gaps in functionality, workarounds needed

  - 2 = Business hours support, standard SLA- **0-3 or 1:** Poor - Does not meet requirements, critical gaps

  - 1 = Community support or limited SLA

### Interpretation of Total Weighted Scores:

- **Training & Documentation** (1%):- **90-100:** Excellent - Highly Recommended (minimal risk)

  - 3 = Comprehensive training program, excellent docs- **80-89:** Good - Recommended (acceptable risk)

  - 2 = Good documentation, basic training- **70-79:** Acceptable - Gaps to Address (moderate risk)

  - 1 = Limited documentation- **60-69:** Marginal - High Risk (proceed with caution)

- **Below 60:** Not Recommended (reject)

- **Implementation Services** (1%):

  - 3 = Full professional services, certified partners---

  - 2 = Some implementation support

  - 1 = DIY or limited services## 💡 Best Practices



#### 5️⃣ Commercial Terms (5% - Score 1-4)### Do's:

Focus on **pricing and contract terms**:✅ Involve technical staff who will use the system daily  

- **Pricing Model Transparency** (1.5%):✅ Require live demos with your actual data/scenarios  

  - 4 = Clear, simple pricing✅ Check references beyond vendor-provided contacts  

  - 3 = Understandable with effort✅ Calculate 5-year TCO, not just upfront costs  

  - 2 = Complex pricing model✅ Negotiate SLAs, exit clauses, and IP rights upfront  

  - 1 = Opaque or confusing✅ Add 20-30% buffer to vendor timeline estimates  

✅ Document everything for audit trail and future reference  

- **Total Cost of Ownership (5yr)** (1.5%):

  - 4 = Very competitive TCO### Don'ts:

  - 3 = Market-average TCO❌ Skip the compliance check phase  

  - 2 = Above-average TCO❌ Accept PowerPoint demos instead of live systems  

  - 1 = Very expensive❌ Rush the evaluation to meet arbitrary deadlines  

❌ Ignore hidden costs (training, implementation, upgrades)  

- **Contract Flexibility** (1%):❌ Make decisions based on sales relationships alone  

  - 4 = Flexible terms, easy exit❌ Underestimate change management and training needs  

  - 3 = Standard terms❌ Proceed without clear success criteria  

  - 2 = Rigid terms

  - 1 = Vendor lock-in concerns---



- **Value for Money** (1%):## 📊 Key Decision Gates

  - 4 = Exceptional value

  - 3 = Good valueThroughout the process, you'll encounter critical decision points:

  - 2 = Fair value

  - 1 = Poor value1. **After Compliance Check:** PASS or REJECT each vendor

2. **After Detailed Evaluation:** Shortlist 3-5 vendors (or reject all and restart)

**Interpreting Results**:3. **After Demos & References:** Clear winner or need BAFO?

| Score Range | Rating | Interpretation |4. **After BAFO:** Final selection

|-------------|--------|----------------|5. **Executive Approval:** Proceed to contract or re-evaluate?

| 90-100 | Excellent | Top choice, minimal concerns |

| 80-89 | Good | Strong candidate, minor gaps |---

| 70-79 | Acceptable | Viable option with some concerns |

| 60-69 | Marginal | Significant gaps, proceed with caution |## 🕐 Expected Timeline

| <60 | Not Recommended | Too many concerns, likely reject |

| Phase | Duration | Can Overlap? |

**Pro Tips**:|-------|----------|--------------|

- Score based on **demonstrated capability**, not roadmap promises| Initial Compliance Check | 1 week | No |

- Use multiple evaluators and average scores to reduce bias| Detailed Evaluation | 2-3 weeks | No |

- Document reasoning for all scores (use Notes column)| Shortlisting | 1 week | No |

- Request proof/demos for high-impact criteria| Demos & Clarifications | 2-3 weeks | Partially |

- Compare against current state baseline if replacing existing system| Reference Checks | 1 week | Yes (with demos) |

| Site Visits (optional) | 1-2 weeks | Yes |

---| Final Scoring | 1 week | No |

| Recommendation & Approval | 2-3 weeks | No |

### Sheet 4: Demo Evaluation| Contract Negotiation | 4-8 weeks | No |

| **TOTAL** | **3-5 months** | |

**Purpose**: Assess vendor performance during live demonstrations

---

**Preparation (1 week before demo)**:

1. **Create Demo Script**: Define 5-10 key scenarios## 🎓 Training & Support

2. **Share with Vendors**: Send script 3-5 days ahead

3. **Assemble Team**: 5-8 stakeholders (clinical, IT, security)### For Evaluation Team Members:

4. **Prepare Questions**: Technical deep-dives ready- Review the Process Overview sheet together as a team

- Assign roles: Functional lead, Technical lead, Security lead, Commercial lead

**Demo Day Checklist**:- Schedule regular sync meetings (weekly during evaluation)

- ⏰ Allocate 2-3 hours per vendor- Use a shared drive to store vendor proposals and this Excel file

- 📝 Assign note-takers

- 🎥 Record session (with permission)### For Executives:

- 📊 Score immediately after (while fresh)- Focus on Sheet 7 (Final Recommendation)

- Review the executive summary and scoring comparison

**How to Score Each Scenario**:- Ask about risk mitigation strategies

1. **Scenario Column**: Pre-populate with your use cases- Validate financial analysis and ROI projections

2. **Score (1-10)**: Rate how well vendor demonstrated the scenario

   - 10 = Flawless, exactly what we need---

   - 7-9 = Very good, minor concerns

   - 4-6 = Adequate, some gaps## 📝 Customization Tips

   - 1-3 = Poor, major concerns or couldn't demonstrate

3. **Notes**: Document what worked, what didn'tYou can adapt this framework to your specific needs:

4. **Weight**: Assign importance (1-5) to each scenario

1. **Adjust Weights:** In Sheet 3, modify the weight percentages to reflect your priorities

**Example Scenarios**:   - Example: Increase Security from 20% to 30% for highly regulated environments

1. **HL7 ADT Message Processing** (Weight: 5)   

   - Inbound ADT^A01, validate, transform, route to 3 systems2. **Add/Remove Criteria:** Insert or delete rows in the Evaluation Matrix

2. **FHIR API Integration** (Weight: 4)   - Remember to adjust formulas if you add/remove rows

   - Query patient data via FHIR API, display in UI   

3. **Error Handling** (Weight: 5)3. **Change Scoring Scale:** Modify the Max Score column to use a different scale

   - Simulate failed connection, show retry logic and alerting   - Example: Change from 1-10 to 1-100 scale

4. **Data Transformation** (Weight: 4)   

   - Map complex ORU to internal format using GUI tool4. **Add Vendors:** Insert additional columns in sheets 2-5 for more than 3 vendors

5. **Performance Under Load** (Weight: 3)   - Copy formulas from existing vendor columns

   - Process 1000 messages, show throughput metrics

5. **Localization:** Translate section headers and criteria to your language

**Red Flags to Watch For**:

- 🚩 Vendor can't demonstrate core requirements---

- 🚩 Excessive "this is on our roadmap"

- 🚩 Demo environment crashes or has issues## 🔒 Data Security & Compliance

- 🚩 Evasive answers to technical questions

- 🚩 Pre-recorded demos instead of live- **Confidentiality:** This file contains sensitive vendor and pricing data

- **Access Control:** Limit access to evaluation team members only

**Scoring Formula**:- **Version Control:** Save dated versions after major updates

```- **Audit Trail:** Document all scoring rationale in the Notes columns

Weighted Score = Σ(Scenario Score × Weight) / Σ(Weights)- **Retention:** Keep completed evaluations for 3-7 years per your policy

```

---

---

## 📞 Common Questions

### Sheet 5: Reference Checks

**Q: What if we have more than 3 vendors?**  

**Purpose**: Validate vendor claims with existing customersA: Add additional columns in the Compliance Checklist and Evaluation Matrix. Copy formulas from existing columns.



**How to Conduct Reference Calls**:**Q: Can we skip the compliance check?**  

A: Not recommended. It saves time by eliminating unqualified vendors early.

**Before the Call**:

1. Request 3-5 references from vendor (prefer similar size/use case)**Q: Do we need to do site visits?**  

2. Schedule 30-45 minute callsA: Only for mission-critical systems or large investments ($1M+). Otherwise, demos and references are sufficient.

3. Prepare question list (Column B)

4. Assign interviewer roles**Q: How do we handle tie scores?**  

A: Use the BAFO process (Sheet 6) to request improved offers, or conduct deeper reference checks.

**During the Call**:

1. Explain your evaluation project**Q: What if no vendor scores above 70?**  

2. Ask open-ended questions firstA: Consider restarting the RFQ process with revised requirements or exploring alternative solutions.

3. Use provided questions as guide

4. Listen for unprompted concerns**Q: How often should we update the evaluation criteria?**  

5. Take detailed notesA: Annually, or when major technology/regulatory changes occur.



**Reference Question Categories**:---



**1. Implementation Experience** (Questions 1-5):## 📚 Related Artifacts

- Timeline vs. estimate

- Challenges encounteredThis Excel workbook complements:

- Vendor support quality- `Vendor RFQ Evaluation Checklist - Scoring Framework.pdf` - Detailed methodology

- Post-go-live issues- `Vendor-Comparison-Matrix-Analysis-Framework-Interactive-artifact.html` - Web-based scoring tool

- Would you do it again?- Your organization's procurement policies and procedures



**2. Product Performance** (Questions 6-10):---

- System reliability/uptime

- Performance under load## ✏️ Version History

- Integration capabilities

- Feature completeness| Version | Date | Changes |

- Hidden limitations|---------|------|---------|

| 1.0 | 2025-11-30 | Initial release with 8 worksheets |

**3. Support & Maintenance** (Questions 11-15):| 2.0 | 2025-11-30 | Added 3 new sheets: Build vs Buy vs Rent, Complexity Analysis, SWOT Analysis. Included 3 sample vendors with realistic scoring data |

- Support responsiveness

- Quality of technical support---

- Documentation adequacy

- Upgrade experience## 👤 Document Owner

- Ongoing costs

**Prepared by:** Solution Architect / IT Procurement Team  

**4. Overall Satisfaction** (Questions 16-20):**Approved by:** CIO / IT Leadership  

- Would you recommend?**Review Cycle:** Annual or per major RFQ

- What do you wish you knew?

- Best features---

- Worst features

- Alternatives considered## 📧 Feedback & Improvements



**Scoring Each Reference**:If you have suggestions for improving this framework, please document them in Sheet 8 (Lessons Learned) and share with your procurement/IT leadership team.

- **Green (5)**: Enthusiastic recommendation, no major concerns

- **Yellow (3)**: Mixed review, some concerns but overall positive---

- **Red (1)**: Negative experience, significant concerns

**Remember:** This is a framework, not a rigid checklist. Adapt it to your organization's size, risk tolerance, and specific requirements. The goal is a defensible, well-documented decision that balances technical fit, risk, cost, and organizational needs.

**Calculate Average**: Automatically sums all reference scores

Good luck with your vendor evaluation! 🚀

**Red Flags**:
- 🚩 Reference is evasive or rushed
- 🚩 Multiple negative experiences
- 🚩 "We're planning to replace it" comments
- 🚩 Vendor can't provide relevant references
- 🚩 All references are very recent (no long-term users)

**Pro Tips**:
- Ask for references NOT provided by vendor (LinkedIn, user groups)
- Speak to technical staff, not just managers
- Request follow-up calls if needed
- Check online reviews (Gartner, G2, KLAS)

---

### Sheet 6: BAFO Template

**Purpose**: Request Best and Final Offer from top 1-2 vendors

**When to Use**:
After completing Phase 4, you should have 1-2 finalists. Use BAFO to:
- Negotiate better pricing
- Clarify any remaining questions
- Get final commitment on terms

**BAFO Components**:

**Section 1: Pricing Request**
- Base license/subscription costs
- Implementation services breakdown
- Ongoing support costs
- Training costs
- Year-over-year escalation rates

**Section 2: Technical Clarifications**
- Specific feature confirmations
- Integration approach details
- Security/compliance specifics
- Performance guarantees

**Section 3: Commercial Terms**
- Payment terms
- Contract length options
- Termination clauses
- IP/Data ownership
- SLA specifics

**Section 4: Implementation Plan**
- Detailed timeline
- Resource requirements (vendor + customer)
- Milestone deliverables
- Acceptance criteria

**How to Fill Out**:
1. **Vendor Response Columns**: Forward to each vendor
2. **Due Date**: Typically 1-2 weeks
3. **Evaluation Notes**: Compare responses side-by-side
4. **Negotiation Points**: Highlight areas for discussion

**BAFO Meeting**:
- Schedule 2-hour session with each vendor
- Bring procurement and legal teams
- Review BAFO in detail
- Negotiate key terms
- Document commitments

**Pro Tips**:
- Use BAFO leverage for better pricing (10-20% reductions common)
- Get everything in writing
- Don't show vendor A's pricing to vendor B (unethical)
- Include "this is our final evaluation" disclaimer
- Set hard deadline for responses

---

### Sheet 7: Final Recommendation

**Purpose**: Document selection decision and present to leadership

**How to Complete**:

**1. Executive Summary** (1 paragraph):
- State recommendation clearly
- Summarize selection process
- Note key differentiators

**2. Vendor Overview Table**:
Fill in for all evaluated vendors:
- Final weighted scores
- Strengths (top 3)
- Weaknesses (top 3)
- Total Cost of Ownership (5 years)
- Contract terms summary

**3. Detailed Analysis**:

**Recommended Vendor Section**:
- Why they won
- Specific strengths aligning with requirements
- Implementation approach
- Risk mitigation plans

**Runners-Up**:
- Why not selected
- What they did well
- Where they fell short

**4. Implementation Roadmap**:
- Phase 1: Contract & Kickoff (Weeks 1-4)
- Phase 2: Design & Configuration (Weeks 5-12)
- Phase 3: Development & Testing (Weeks 13-20)
- Phase 4: Training & UAT (Weeks 21-24)
- Phase 5: Go-Live & Hypercare (Weeks 25-28)
- Phase 6: Optimization (Months 7-12)

**5. Financial Summary**:
| Cost Category | Year 1 | Years 2-5 | Total (5yr) |
|---------------|--------|-----------|-------------|
| License/Subscription | $XXX | $XXX | $XXX |
| Implementation | $XXX | $0 | $XXX |
| Support & Maintenance | $XXX | $XXX | $XXX |
| Training | $XXX | $XXX | $XXX |
| **TOTAL** | **$XXX** | **$XXX** | **$XXX** |

**6. Risk Assessment**:
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| Implementation delays | Medium | High | Phased approach, buffer time |
| Integration challenges | Low | Medium | POC completed, expert resources |
| Budget overruns | Low | High | Fixed-price contract, contingency |
| Vendor viability | Low | High | Financially stable vendor selected |

**7. Success Criteria** (define how you'll measure success):
- System uptime ≥99.9%
- Message throughput >50K/day
- Go-live within 6 months
- User satisfaction >80%
- ROI achieved within 18 months

**8. Approval Sign-offs**:
- [ ] IT Leadership
- [ ] Clinical Leadership
- [ ] Security Officer
- [ ] CFO/Finance
- [ ] CIO/Executive Sponsor

**Presentation Tips**:
- Create PowerPoint summary (10-15 slides)
- Lead with recommendation, then supporting data
- Anticipate objections
- Bring demo recordings if helpful
- Have detailed backup slides ready

---

### Sheet 8: Lessons Learned

**Purpose**: Capture insights for future vendor selections

**When to Complete**: 
- Immediately after vendor selection (hot wash-up)
- Again at 6 months post-implementation
- Final update at 12 months post-implementation

**What Went Well**:
- Effective practices
- Tools/templates that helped
- Team collaboration highlights
- Vendor relationship positives

**What Could Be Improved**:
- Process inefficiencies
- Missing criteria
- Timeline issues
- Communication gaps

**Surprises/Unexpected Issues**:
- Vendor behaviors
- Technical discoveries
- Budget variances
- Stakeholder concerns

**Recommendations for Next Time**:
- Process improvements
- Additional criteria to consider
- Better time estimates
- Stakeholder engagement tips

**Pro Tips**:
- Schedule dedicated lessons learned session
- Invite all evaluation team members
- Be honest and constructive
- Share with broader organization
- Update templates based on learnings

---

### Sheet 9: Build vs Buy vs Rent Analysis

**Purpose**: Strategic decision - should you build, buy, or rent (SaaS)?

**How to Use This Analysis**:

**Step 1: Understand Each Option**

**BUILD (In-house Development)**:
- Pros: Full control, custom fit, no licensing fees
- Cons: High initial cost, ongoing maintenance, resource intensive
- Best for: Unique requirements, strong dev team, long-term strategy

**BUY (Commercial License)**:
- Pros: Feature-rich, vendor support, faster deployment
- Cons: Licensing costs, vendor dependency, customization limits
- Best for: Standard requirements, proven need, dedicated budget

**RENT (SaaS/Cloud)**:
- Pros: Low upfront cost, vendor maintains, scalable
- Cons: Ongoing fees, less control, data residency concerns
- Best for: Fast deployment, variable demand, OpEx vs CapEx preference

**Step 2: Compare Total Cost of Ownership (5 years)**

Review the pre-populated example in the sheet:
- **Build**: Higher Year 1 (development), ongoing maintenance costs
- **Buy**: Moderate Year 1 (license + implementation), lower ongoing
- **Rent**: Lower Year 1 (subscription), consistent ongoing fees

**Step 3: Use Decision Matrix**

Score each option (1-5) on these dimensions:
1. **Time to Value**: How fast can we deploy?
2. **Total Cost**: 5-year TCO assessment
3. **Fit to Requirements**: How well does it meet needs?
4. **Risk**: Technical, vendor, implementation risks
5. **Flexibility**: Can we adapt/customize?
6. **Maintenance Burden**: Ongoing effort required
7. **Scalability**: Handles growth?
8. **Control**: Do we own the IP/data?

**Step 4: Apply Organizational Factors**

Different org types have different preferences:
- **Large Enterprise**: Often BUY (budget, complexity)
- **Mid-size Hospital**: Often RENT (balance cost/features)
- **Small Clinic**: Usually RENT (limited IT staff)
- **Tech-forward Org**: Might BUILD (innovation focus)

**Recommendation Guidelines**:
- **BUILD IF**: 
  - Unique requirements no vendor meets
  - Strong internal dev team (5+ engineers)
  - Long-term strategic advantage from custom solution
  - Budget >$2M over 5 years
  
- **BUY IF**:
  - Standard requirements well-covered by vendors
  - Proven ROI from feature set
  - Dedicated IT team for operations
  - Budget $1M-$3M over 5 years

- **RENT IF**:
  - Fast deployment critical (<3 months)
  - Variable/unpredictable demand
  - Limited IT staff
  - Prefer OpEx to CapEx
  - Budget <$1M over 5 years

---

### Sheet 10: Complexity Analysis

**Purpose**: Assess implementation complexity and risk for each vendor

**How to Score Complexity** (each factor rated 1-5):

**1 = Low Complexity** → Easy, standard, low risk
**3 = Medium Complexity** → Moderate effort, some challenges
**5 = High Complexity** → Difficult, significant challenges, high risk

**Dimension 1: Technical Complexity (25 points max)**
- **Architecture Modernization** (5 points):
  - 1 = Drop-in replacement, same architecture
  - 3 = Some modernization (cloud migration)
  - 5 = Complete re-architecture required

- **Integration Points** (5 points):
  - 1 = 1-3 systems to integrate
  - 3 = 4-10 systems
  - 5 = 10+ systems with custom protocols

- **Data Migration** (5 points):
  - 1 = No migration needed
  - 3 = Moderate data migration (<1TB)
  - 5 = Complex migration (>1TB, legacy formats)

- **Custom Development** (5 points):
  - 1 = Out-of-box solution
  - 3 = Some configuration/scripting
  - 5 = Extensive custom development

- **Infrastructure Changes** (5 points):
  - 1 = Use existing infrastructure
  - 3 = Some new infrastructure
  - 5 = Complete infrastructure overhaul

**Dimension 2: Integration Complexity (25 points max)**
Similar scoring for:
- Legacy System Compatibility
- API Maturity
- Protocol Support
- Real-time vs Batch
- External Partner Integration

**Dimension 3: Organizational Complexity (25 points max)**
- Stakeholder Alignment
- Change Management
- Training Requirements
- Process Changes
- Vendor Relationship Management

**Dimension 4: Operational Complexity (25 points max)**
- Monitoring & Support
- Disaster Recovery
- Security Operations
- Performance Tuning
- Ongoing Maintenance

**Dimension 5: Compliance Complexity (25 points max)**
- Regulatory Requirements
- Audit Trail Setup
- Security Certifications
- Data Privacy Controls
- Industry Standards

**Interpreting Complexity Scores**:

| Total Score | Complexity Level | Recommended Approach |
|-------------|-----------------|----------------------|
| 0-40 | LOW | Standard implementation, 3-4 months |
| 41-75 | MEDIUM | Phased approach, 6-9 months |
| 76-100 | HIGH | Extensive planning, 12-18 months |
| 101-125 | VERY HIGH | Consider alternatives or major PMO |

**Risk Mitigation by Complexity**:
- **Low**: Standard project management, small team
- **Medium**: Dedicated PM, phased rollout, pilot first
- **High**: Executive sponsor, change management program, extensive testing
- **Very High**: External consultants, multi-year program, consider simpler alternatives

---

### Sheet 11: SWOT Analysis

**Purpose**: Strategic analysis of each vendor option

**How to Conduct SWOT**:

**For Each Vendor, Document**:

**STRENGTHS** (Internal, Positive):
- What does this vendor do exceptionally well?
- Competitive advantages
- Proven capabilities
- Strong features
- Example: "Best-in-class FHIR implementation, visual mapping tool, 99.99% uptime SLA"

**WEAKNESSES** (Internal, Negative):
- Where does this vendor fall short?
- Missing features
- Technical limitations
- Support gaps
- Example: "Limited legacy system connectors, complex pricing model, steep learning curve"

**OPPORTUNITIES** (External, Positive):
- How could this vendor help us grow/improve?
- Future roadmap alignment
- Innovation potential
- Partnership possibilities
- Example: "AI-powered data transformation coming Q3, potential to expand to other use cases"

**THREATS** (External, Negative):
- What external risks exist?
- Market changes
- Vendor viability concerns
- Competition
- Technology shifts
- Example: "New competitor entered market with lower pricing, vendor acquired last year"

**Using SWOT for Decision-Making**:

1. **Strengths vs Weaknesses**: Must have more/stronger strengths
2. **Opportunities**: Can we capitalize on these?
3. **Threats**: Can we mitigate? Are they deal-breakers?

**Comparative SWOT**:
After completing individual SWOTs, create comparative table:

| Factor | Vendor A | Vendor B | Vendor C | Winner |
|--------|----------|----------|----------|---------|
| Technical Strength | High | Very High | Medium | Vendor B |
| Cost | Medium | High | Low | Vendor C |
| Support | Low | High | Medium | Vendor B |
| Innovation | Medium | High | Low | Vendor B |
| Risk | Medium | Low | High | Vendor B |

**SWOT-Based Recommendation**:
- Vendor with most strengths and opportunities
- Manageable weaknesses and threats
- Aligns with strategic direction

---

## Scoring Guidelines

### General Principles

1. **Score Based on Evidence**: 
   - ✅ Demonstrated capability
   - ✅ Customer references
   - ✅ Documentation proof
   - ❌ Vendor promises
   - ❌ Roadmap items
   - ❌ Marketing claims

2. **Use Multiple Evaluators**:
   - Assign 2-3 people per category
   - Average scores to reduce bias
   - Discuss significant disagreements

3. **Document Everything**:
   - Use Notes columns extensively
   - Save vendor responses
   - Record demo sessions
   - Keep email trails

4. **Be Consistent**:
   - Use same scale/criteria for all vendors
   - Score at same time (within days)
   - Same evaluators for same categories

5. **Focus on Differentiators**:
   - If all vendors score high/low, consider removing criterion
   - Weight factors that truly distinguish vendors
   - Don't get lost in minutiae

### Common Scoring Mistakes to Avoid

❌ **The Halo Effect**: One great feature makes everything look great
✅ **Fix**: Score each criterion independently

❌ **Recency Bias**: Last vendor seems best
✅ **Fix**: Review all vendors after all demos complete

❌ **Anchoring**: First vendor sets baseline
✅ **Fix**: Use absolute scale, not relative comparison

❌ **Confirmation Bias**: Favoring pre-selected vendor
✅ **Fix**: Blind scoring (hide vendor names during initial scoring)

❌ **Scoring Roadmap**: Giving credit for future features
✅ **Fix**: Only score current, proven capabilities

---

## Decision Gates

### Gate 1: After Initial Screening (Phase 1)
**Criteria to Proceed**:
- ✅ Passes compliance checklist (Sheet 2)
- ✅ Meets mandatory technical requirements
- ✅ Within budget range (rough estimate)
- ✅ No major red flags

**Action**: Proceed with 3-5 vendors to detailed evaluation

---

### Gate 2: After Detailed Evaluation (Phase 2)
**Criteria to Proceed**:
- ✅ Weighted score ≥70 (Acceptable or better)
- ✅ No category scored <50% of max points
- ✅ Positive initial reference checks
- ✅ Stakeholder consensus

**Action**: Invite 2-3 vendors for demos

---

### Gate 3: After Demos & References (Phase 4)
**Criteria to Proceed**:
- ✅ Demo score ≥7.0/10 average
- ✅ At least 2 positive reference calls
- ✅ No deal-breaker issues discovered
- ✅ Budget alignment confirmed

**Action**: Request BAFO from 1-2 finalists

---

### Gate 4: Final Selection (Phase 6)
**Criteria to Proceed**:
- ✅ Clear winner emerged from scoring
- ✅ Executive sponsor approval
- ✅ Budget approved
- ✅ Contract terms acceptable
- ✅ Implementation plan agreed

**Action**: Contract signature and kickoff

---

## Best Practices

### 1. Team Composition
**Core Evaluation Team** (5-8 people):
- Project Lead (1): Overall coordination
- Clinical Rep (1-2): Workflow/usability focus
- IT Architect (1-2): Technical evaluation
- Security Officer (1): Security/compliance
- Procurement (1): Commercial terms

**Extended Team** (consulted as needed):
- End users
- Department managers
- Legal counsel
- Finance
- Executive sponsor

### 2. Timeline Management
**Realistic Timeline**: 8-12 weeks total
- Week 1-2: Initial screening
- Week 3-5: Detailed evaluation
- Week 6-7: Demos
- Week 8-9: Reference checks
- Week 10: BAFO
- Week 11-12: Final decision

**Don't Rush**:
- Poor vendor selection costs millions
- Take time for thorough evaluation
- Build in buffer time for delays

### 3. Vendor Management
**Set Clear Expectations**:
- Share evaluation criteria upfront
- Provide demo scenarios in advance
- Set response deadlines
- Be transparent about timeline

**Maintain Fairness**:
- Same information to all vendors
- Same evaluation process
- No favoritism
- Professional communication

**Document Everything**:
- All vendor communications
- Demo recordings
- Q&A responses
- Commitments made

### 4. Stakeholder Engagement
**Early and Often**:
- Kick-off meeting with all stakeholders
- Weekly status updates
- Demo invitations (make it easy to attend)
- Final presentation with leadership

**Manage Expectations**:
- No perfect vendor exists
- Trade-offs are necessary
- Budget constraints are real
- Implementation takes time

### 5. Risk Management
**Identify Risks Early**:
- Technical integration challenges
- Vendor stability concerns
- Budget overruns
- Timeline delays
- Stakeholder misalignment

**Mitigation Strategies**:
- Proof of concept for high-risk integrations
- Escrow agreements for small vendors
- Fixed-price contracts where possible
- Phased implementation
- Change management program

---

## Troubleshooting

### Issue: Vendors score too similarly (all 70-80)
**Solution**: 
- Review weighting - may need adjustment
- Focus on differentiating criteria
- Conduct deeper technical demos
- Check references more thoroughly

### Issue: No vendor meets minimum score (all <70)
**Solution**:
- Review if criteria are too stringent
- Consider Build vs Buy analysis (Sheet 9)
- Expand vendor search
- Adjust budget/timeline expectations

### Issue: Stakeholders disagree on scoring
**Solution**:
- Facilitate discussion on specific criteria
- Use weighted voting
- Bring in neutral third-party
- Focus on objective evidence, not opinions

### Issue: Top-scoring vendor is most expensive
**Solution**:
- Revisit cost weight (currently only 5%)
- Conduct detailed ROI analysis
- Negotiate pricing (BAFO process)
- Consider total cost of ownership, not just price

### Issue: Vendor makes promises not in scoring
**Solution**:
- Get commitments in writing
- Include in contract terms
- Add penalty clauses for non-delivery
- Re-score if truly game-changing

### Issue: Demo reveals major gap after scoring
**Solution**:
- Re-score affected criteria
- Document as risk
- Request BAFO to address gap
- Consider if gap is show-stopper

### Issue: Reference gives conflicting information
**Solution**:
- Get multiple references (3-5)
- Seek independent references
- Verify with vendor (tactfully)
- Weight demonstrated capability over references

---

## Appendix: Customization Guide

### Adding Custom Criteria
1. Insert row in Sheet 3 (Evaluation Matrix)
2. Add criterion name
3. Assign weight (adjust others to keep total at 100%)
4. Set scoring scale (document in notes)
5. Update formulas to include new row

### Adjusting Category Weights
Current default: 35/30/20/10/5

Example alternatives:
- **Security-focused org**: 25/25/30/10/10
- **Cost-sensitive org**: 30/25/15/10/20
- **Innovation-focused org**: 30/35/15/10/10

To change:
1. Update category headers in Sheet 3
2. Adjust individual criterion weights within category
3. Verify totals still equal 100%
4. Update subtotal formulas

### Adding Vendors
1. Insert new columns (every 2 columns: Score + Weighted)
2. Copy formulas from adjacent vendor
3. Update column references in Grand Total
4. Add vendor to all other sheets

### Translating to Another Language
- All text is editable
- Preserve formula structure
- Update dropdown values if used
- Test calculations after translation

---

## Quick Reference Card

### The 6-Phase Process
1. ✅ Initial Screening → 3-5 vendors
2. 📊 Detailed Evaluation → Score all criteria
3. 🎯 Demonstrations → 2-3 vendors
4. 📞 Reference Checks → Validate claims
5. 💼 BAFO → Negotiate final terms
6. 🏆 Final Selection → Make decision

### Scoring Scales
- Functional: 1-10
- Technical: 1-5
- Security: 1-5
- Viability: 1-3
- Commercial: 1-4

### Decision Thresholds
- 90+ = Excellent
- 80-89 = Good
- 70-79 = Acceptable
- 60-69 = Marginal
- <60 = Not Recommended

### Key Deliverables
- [ ] Compliance checklist completed
- [ ] All vendors scored
- [ ] Demos conducted and scored
- [ ] References checked (3+ per vendor)
- [ ] BAFO received and analyzed
- [ ] Final recommendation documented
- [ ] Executive approval obtained

---

## Support & Questions

**Document Version**: 2.0  
**Last Updated**: November 30, 2025  
**Author**: Healthcare IT Evaluation Framework Team

For questions about using this framework:
- Review the README.md file
- Check the Process Flow diagram
- Refer to the Quick Reference card
- Consult with your IT evaluation team

**Additional Resources**:
- KLAS Research (healthcare vendor ratings)
- Gartner Magic Quadrants
- HIMSS Interoperability Showcase
- HL7 International (standards)
- FHIR.org (FHIR specifications)

---

**Good luck with your vendor evaluation!** 🎯

Remember: Take your time, be thorough, and document everything. A good vendor selection process today prevents years of problems tomorrow.
