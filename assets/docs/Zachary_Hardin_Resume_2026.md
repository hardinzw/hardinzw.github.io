**ZACHARY HARDIN**  
*Software Developer*

Richmond, VA   \|   (540) 798-8984   \|   hardinzw@gmail.com

**PROFESSIONAL SUMMARY**

Full-stack .NET developer with 5+ years building and maintaining data integration and ETL pipelines for the appraisal and mortgage industries. Skilled at translating business requirements into reliable, well-tested features within an agile team, and known for identifying inefficient code and refactoring it for performance and long-term maintainability.

**TECHNICAL SKILLS**

**Languages & Frameworks:** .NET, C\#, T-SQL, LINQ, JavaScript, jQuery, XML, JSON, AJAX, HTML, CSS

**Databases & Platforms:** SQL Server, SQLite, DBeaver, Windows Server

**Tools & Workflow:** Git, Azure DevOps, AWS, Jira, Teams, Slack

**AI-Assisted Development:** Claude Code, Cursor, Kiro

**EMPLOYMENT HISTORY**

**Class Valuation**  –  Troy, MI (Remote) 	 *June 2021 – Present*

*Software Engineer  (acquired Valuation Connect, a subsidiary of Mortgage Connect LP, in 2024\)*

* Leading UAD 3.6 compliance for a core application at Class Valuation — ahead of the GSE-mandated appraisal data standard taking effect November 2026 — architecting an EAV (Entity-Attribute-Value) data model so new UAD attributes are added via seed data and configuration rather than schema migrations or stored procedure changes; future-proofing the system as the standard continues to evolve.

* Built configurable, per-order UAD 3.6 attribute settings for business users on top of that model, along with fee generation logic driven by attribute configuration and order geography, and data mapping of the new attribute set across dozens of integrated appraisal management clients.

* Eliminated a peak-volume email bottleneck by refactoring 35 HTML email templates to use dedicated DTOs instead of pulling entire top-level database objects, cutting per-email generation time from 30 minutes–3 hours down to 1–30 seconds.

* Rebuilt the admin portal's order search view — previously 30+ seconds to load and prone to crashing under large datasets — by lazy-loading multi-select filters, adding fast client-side search across lists with thousands of values, and layering in HTTP Runtime–based caching so concurrent users with similar saved queries skip redundant database calls.

* Built a service library connecting to Class Valuation's in-house payment API, moving clients off third-party processors that charged per-transaction fees onto a fully in-house-managed service handling payments, refunds, and a new "pay later" option for clients and customers.

* Built a custom C\# authorization attribute applied across HttpGet controller endpoints system-wide, filtering returned data by each user's permitted appraisal management companies, clients, products, and states — centralizing access control instead of duplicating checks per endpoint.

* Introduced memory diagnostic logging across integration transforms to identify performance inefficiencies, using the resulting data to remediate bottlenecks and optimize the speed of client-facing communications.

* Design and maintain ETL integrations using object-oriented C\#/.NET that extract, transform, and load data from appraisal management partners, backed by SQL stored procedures that supply the exact datasets each integration requires.

* Lead code reviews and help manage the codebase pipeline; translate feedback from senior engineers into best practices for teammates I mentor.

**IT4Causes**  –  Richmond, VA 	*June 2020 – June 2021*

*IT Intern*

* Served as primary technical support contact for Senior Connections, a private nonprofit client.

* Administered Windows Server and Azure Active Directory for group and user account maintenance.

* Managed Jira service tickets end-to-end, ensuring timely response, troubleshooting, and resolution.

* Handled on-premises device procurement, inventory, and deployment for client organizations.

* Assisted with planning and rolling out software and domain service updates.

* Supported network implementation for newly onboarded nonprofit clients across the city.

**Towne Park, LLC**  –  Conshohocken, PA 	*March 2008 – May 2019*

*Account Manager*

* Partnered with General Managers and Market VPs to design, implement, and measure strategic business objectives across multiple accounts.

* Trained associates on sales and account management practices to reduce process lags and improve daily performance.

* Forecasted annual profit/loss margins to maintain accurate expectations and profitability across accounts.

**EDUCATION**

**ECPI University**  –  Richmond, VA 	*August 2019 – June 2021*

A.A.S. in Computer and Information Sciences, Cybersecurity — Dean's List, 3.92 GPA

**University of Richmond**  –  Richmond, VA 	*September 2019 – January 2020*

24-week full-stack coding bootcamp: HTML5, CSS3, JavaScript, jQuery, Express.js, React.js, Node.js, MongoDB, MySQL, progressive web apps, database theory, agile methodology, and Git.