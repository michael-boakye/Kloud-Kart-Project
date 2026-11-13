# DATA FINDINGS AND RISK ASSESSMENT

**Organisation:** Kloud Kart  
**Prepared for:** Nana Adjei, Head of Operations

## 1. Executive Summary

Kloud Kart's current data management and reporting arrangements present three significant risks to its operations and future growth.

- **Customer data protection:** Marketing exports customer lists containing approximately 300,000 records without tracking where copies are stored or who receives them.
- **Website performance:** Large reporting exports are run against the same database server that supports the live website. Significant website slowdowns have been reported during Monday reporting.
- **Management reporting:** Operations and Finance produce different Monday figures, making it difficult for management to rely on a consistent view of business performance.

These are business concerns, not simply technical issues. They affect how well Kloud Kart protects customer information, serves customers and makes business decisions.

The findings are ranked according to their potential impact on the business and the urgency of addressing them. Resolving these weaknesses will provide a stronger foundation for the company's planned growth and expansion into Nigeria.

## 2. Key Findings and Risk Assessment

### 2.1 Customer Data Protection and Control (Critical Risk)

**Root Cause**

Kloud Kart does not have a reliable process for controlling customer information after it has been exported from the main system. Marketing maintains customer lists containing approximately 300,000 records but does not track where copies are stored or who has received them.

The underlying problem is the lack of clear ownership and accountability for customer information outside the main database.

**Evidence**

Marketing exports customer lists without keeping a record of where the files are stored or who receives them.

**Business Impact**

Kloud Kart may be unable to locate all copies of customer information or confirm that customer deletion requests have been completed across relevant locations. This makes it harder to manage customer information responsibly and respond to customer requests.

**Compliance Implications**

The company must handle personal information responsibly and in a manner that can be defended under Ghana's Data Protection Act, 2012 (Act 843). The lack of control over exported customer records creates a compliance concern and could expose the company to regulatory scrutiny and reputational damage.

### 2.2 Website Performance and Reporting (Critical Risk)

**Root Cause**

Kloud Kart runs large reporting exports from the same MySQL database server that supports its live website. Reporting activity may therefore compete with normal website operations for system resources.

The underlying problem is that reporting activities and the live customer-facing service depend on the same server.

**Evidence**

The website experienced significant slowdowns during Monday reporting on two occasions in the previous month. The reporting exports contain a few hundred thousand rows.

**Business Impact**

Slow website performance can delay customer orders, disrupt daily operations and affect customer confidence. As Kloud Kart grows, continued pressure from reporting activities could make the problem more difficult to manage.

### 2.3 Management Reporting Consistency (High Risk)

**Root Cause**

Operations and Finance produce different Monday figures without a sufficiently agreed process for how those figures are prepared.

The underlying problem appears to be the absence of shared reporting definitions and clear ownership of the figures used in management reviews.

**Evidence**

Operations and Finance produce different Monday figures. Nana uses CSV exports, while Finance maintains its own spreadsheet.

**Business Impact**

Management may receive conflicting information about sales and operational performance. This makes it harder to understand the company's actual performance, monitor progress and make sound business decisions.

## 3. Important Notes on the Findings

This assessment is based on the operational information provided about Kloud Kart. The following points clarify what is known and what still needs to be checked.

- The two website slowdowns occurred during Monday reporting, but the exact cause and extent of their impact have not been established.
- Operations and Finance produce different Monday figures, but their reports have not been compared to establish why they differ.
- Marketing exports customer lists without tracking where copies are stored or who receives them. The full extent of the company's control over these copies has not been established.

These points distinguish confirmed information from matters that require further checks. They do not change the risks identified in this assessment.