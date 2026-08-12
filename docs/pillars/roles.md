# Data Governance Roles & Responsibilities

Spotify's data organization follows a Center of Excellence (CoE) model - a hybrid between centralized and embedded structures. A central data team holds expertise and best practices while working closely with representatives embedded in each department, improving data–business collaboration and helping prevent silos.
This structure requires a unified, well-governed policy to succeed - which is the purpose of this framework.

## Chief Data Officer (CDO)

**The CDO is responsible for defining and executing Spotify's overall data strategy**, ensuring data is treated as a strategic asset that drives business value, innovation, and performance.

Key responsibilities:

- Establish and enforce data governance principles to ensure data is accurate, secure, and compliant;

- Promote a **data-driven culture** across the organization and ensure strategic compliance (aligning data use with business growth, innovation, and risk management);

- Define the **long-term data vision** and develop governance policies aligned with Spotify's mission and business objectives (podcasting, advertising, user personalization);

- Collaborate with executive leadership and cross-functional departments to align governance with operational priorities;

- Ensure data is managed, protected, and used responsibly;

- Ensure data is accessible, integrated, and secure across the organization

- Define backup and recovery policies (frequency, retention periods)

## Data Protection Officer (DPO)

Responsible for implementing data protection policies, including GDPR, CCPA, and other industry-specific regulations (banking, product compliance, etc.).

Key responsibilities:

- Act as the **primary point of contact for data protection compliance** (GDPR, CCPA, PDPA, LGPD, etc.) across departments

- **Coordinate responses to data breaches and conduct regular audits of data practices** in collaboration with legal and technical teams

- Serve as liaison with regulatory authorities and ensure data processing activities are documented and transparent

- Map data by region to align processes with local laws (PDPA, LGPD)

- Train employees on data protection principles and automate workflows for consent management, DSARs, and incident reporting

- Empower users with control over their data (e.g., personalization preferences) and build trust through transparency

- Apply data minimization, anonymization, and pseudonymization for internal analytics

- **Collaborate with Data Stewards** to strengthen transparency and governance

- Implement ethical and technical safeguards: prevent algorithmic bias, ensure AI explainability and accountability, secure data at every processing stage, and align data use with organizational values

## Data Steward

**Responsible for operationalizing the data strategy within an assigned domain** (e.g., user data, content metadata, payments) - implementing and enforcing the CDO's strategy so that domain-specific governance principles (quality, security, compliance) are applied, documented, and adopted by relevant teams.

As guardian of data quality, they:

- **Monitor, clean, and standardize data to ensure accuracy, completeness, consistency, and reliability within their domain** (e.g., resolving duplicates, missing values, errors);

- **Deploy dashboards to monitor data quality and requests**, and automate validations for critical data (payment info, user preferences);

- **Partner with Product Managers** to integrate data governance into product development;

- Break down silos by making domain-specific data discoverable and reusable, implementing secure APIs for cross-team data sharing (Marketing, Product, Data Science), and using MDM to harmonize information

- Facilitate collaboration between teams while enforcing access controls;

- Document data origin, lineage, and usage (metadata repositories, data catalogs) and suggest domain-specific improvements;

- Apply compliance rules defined by the CDO (e.g., masking sensitive payment info, restricting access to GDPR-protected data);

- Apply security controls (encryption, access reviews) and ethical guidelines (bias mitigation), ensure AI transparency, and protect data at every processing stage;

- Organize and classify unstructured data (logs, documents) within their domain;

- Identify scalability needs (storage, processing power) and prioritize investment where necessary

## Product Managers

Product Managers are responsible, at the local/product level, for using data insights to inform product development and enhance user experience. They work closely with data teams to ensure product data:

- Is accurate and reliable;

- Meets quality standards;

- Is **compliant with governance policies and regulations**;

- Drives product innovation and creates value for users;

## Head of Engineering

Responsible for managing Spotify's technical infrastructure for data collection, storage, processing and security. This role ensures data systems are scalable, reliable, and compliant with governance policies.

Key responsibilities:

- Implement technical solutions for data quality and integration;

- Maintain the security of data systems;

- Collaborate with the CDO to ensure data infrastructure supports strategic goals;

- Lead development of data-driven products and features

- Embed privacy-by-design into data pipelines and secure user data, including within AI/ML models

## Marketing Director

Leverages marketing data to design effective campaigns, working closely with data teams to ensure usage complies with best practices and regulations.

Key responsibilities:

- Align user segmentation and targeting with privacy policies

- Ensure marketing practices comply with regulations (GDPR, CCPA, etc.), in coordination with the DPO

- Verify the source and compliance of external data used in campaigns

- Ensure transparency and legitimacy of data partnerships

- Collaborate with Data Teams to optimize strategies using reliable, up-to-date insights

- Incorporate feedback from Data Stewards and the DPO to strengthen compliance and relevance of marketing actions