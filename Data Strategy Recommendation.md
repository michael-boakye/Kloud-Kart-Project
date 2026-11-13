# DATA STRATEGY RECOMMENDATION AND 12-MONTH ROADMAP

**Organisation:** Kloud Kart  
**Prepared for:** Nana Adjei, Head of Operations

## Part A: Recommendation

### 1. Recommended Approach

Kloud Kart should establish a small, controlled reporting system that separates management reporting from the database supporting its live website.

The company does not need an expensive, complex data platform at this stage. Its immediate priority should be to protect website performance, improve the reliability of management reports and strengthen control over customer information.

I recommend that Kloud Kart:

1. Set up a separate reporting copy of its existing database so that large reporting activities do not run directly against the live website database.
2. Establish agreed reporting figures and definitions shared by Operations and Finance.
3. Introduce clear controls over customer information, including who can access, export, share and delete it.
4. Provide management with reliable daily reports and dashboards for business performance.
5. Recruit two specialists in the order set out below to build and manage the capability.

This approach addresses the company's current problems without creating a system that is more expensive or difficult to manage than its present needs justify.

### 2. What Kloud Kart Should Build First

#### 2.1 A Separate Reporting Environment

Kloud Kart should use the already approved second server to hold a separate copy of the operational database for reporting.

Large reports would run against this copy rather than placing additional pressure on the database supporting the live website. Before moving reporting activities, the company should test the arrangement to confirm that it reduces pressure on the live system and does not introduce unacceptable delays or interruptions.

The reporting copy must not be used to make live stock or order decisions. Stock availability and order processing must continue to use the main operational system. This is important because the reporting copy may not always contain the latest stock changes.

#### 2.2 Reliable Management Reports

Operations and Finance should agree on how key business figures are calculated and who is responsible for approving them.

The first reports should cover:

- Orders received and completed.
- Sales performance.
- Stock levels and inventory movements.
- Order fulfilment and delivery performance.
- Customer activity.

The reports should use agreed definitions and a common source of information. This will help Operations and Finance work from the same figures instead of maintaining separate versions of business performance.

Non-stock management information can be refreshed daily. Stock information used for operational decisions must remain current in the live system.

#### 2.3 Customer Information Controls

Kloud Kart should introduce a clear process for managing customer information, especially information exported for marketing activities.

The process should include:

- Assigning responsibility for customer information.
- Restricting access to authorised employees.
- Recording customer-list exports, their purpose and recipients.
- Keeping track of where exported copies are stored.
- Establishing a process for handling customer information and deletion requests across relevant systems and copies.
- Keeping evidence of actions taken so the company can respond to a complaint from the Data Protection Commission.

These controls should support the company's obligations under Ghana's Data Protection Act, 2012 (Act 843). The assignment also requires Kloud Kart to be able to respond to a complaint within 90 days. The company should therefore establish a documented process and retain evidence of its actions.

### 3. What Kloud Kart Should Not Build Yet

The company should resist the temptation to build everything investors may associate with a modern data strategy.

| Proposed investment | Recommendation | Reason |
|---|---|---|
| Large data warehouse or lakehouse | Defer | Kloud Kart's immediate reporting needs can be addressed without introducing a more complex platform. |
| Full real-time management dashboards | Defer | Most management information can refresh daily. Live stock and order decisions already belong in the operational system. |
| Machine-learning demand forecasting | Defer | Forecasting would depend on reliable historical information and consistent reporting, which the company has not yet established. |
| Multiple reporting platforms | Avoid | They would increase cost, maintenance and the difficulty of managing information. |

This does not mean these capabilities are permanently ruled out. They should be reconsidered when the business has reliable reporting, stronger data controls and a clear operational reason to invest in them.

**Answer to the investor question about real-time analytics:** Kloud Kart should keep stock and order decisions current through its live operational system. It does not need every management report to update continuously. Daily reporting is a more sensible starting point for the company's current needs.

### 4. The Two Roles to Hire

The two hires should be made in sequence. The first establishes a safe and reliable reporting foundation. The second turns that foundation into information that management can use.

#### First hire: Data Engineer

**Priority:** First quarter

This person will be responsible for setting up and maintaining the reporting environment, protecting the live database and ensuring information moves reliably between systems.

**First 90 days**

- Assess the existing database and reporting workload.
- Set up and test the separate reporting environment.
- Move suitable reporting activities away from the live website database.
- Confirm that stock and order decisions continue to use the live system.
- Establish basic access controls, backup arrangements and monitoring.
- Document how customer information is copied, stored and deleted.

**Expected outcome:** Reporting activities operate separately from the live website workload, with controls in place to protect operational information.

#### Second hire: Business Intelligence and Reporting Analyst

**Priority:** Second quarter

This person will work with Operations and Finance to produce consistent reports and make business information easier to understand.

**First 90 days**

- Review the reports currently produced by Operations and Finance.
- Agree on definitions for important business figures.
- Identify and explain differences between the two departments' reports.
- Build the first agreed management reports and dashboards.
- Establish a regular reporting process and check that figures remain consistent.
- Work with department heads to ensure reports answer real business questions.

**Expected outcome:** Operations and Finance use agreed reports and figures, reducing the need to rebuild and compare separate spreadsheets every week.

## Part B: 12-Month Roadmap

| Period | Main activities | Expected outcomes Nana can verify |
|---|---|---|
| **Quarter 1: Establish the foundation** | Recruit the Data Engineer. Assess the current database and reporting workload. Set up and test the separate reporting environment. Introduce basic access and export controls. | Reporting activities can run separately from the live website database. Website performance is monitored during reporting. Stock and order decisions remain on the live system. |
| **Quarter 2: Improve reporting** | Recruit the Reporting Analyst. Review Operations and Finance reports. Agree on key business figures. Build the first shared management reports. | Operations and Finance use agreed definitions and a common management report. Nana can identify and explain differences between previous reports. |
| **Quarter 3: Strengthen information control** | Improve customer-list tracking and access controls. Establish and test the customer information deletion process. Expand daily management reporting. | Customer-list exports have identifiable owners and recipients. Deletion requests can be tracked, acted on and supported with evidence. Management receives regular reports. |
| **Quarter 4: Review and prepare for growth** | Review reporting reliability, website performance and customer information controls. Assess whether the reporting system can support the Nigeria pilot. Identify whether demand forecasting is justified by the available information. | The board receives evidence of progress, outstanding weaknesses and the next investment priorities. Any proposal for forecasting or wider expansion is supported by reliable information. |

## Final Recommendation

Kloud Kart should invest first in protecting its live operations, establishing reliable management reporting and improving control over customer information.

The company should use its approved second server, recruit a Data Engineer first and a Reporting Analyst second, and build its reporting capability in stages.