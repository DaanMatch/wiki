# Database

## How are we storing images, audio, video etc.?

Images, videos, and audio are stored in a blob storage system and then the URLs to the blob storage URI are stored in a database. This approach has several benefits:

1. Scalability: Blob storage systems are designed for scalability and can handle a large volume of data without affecting the performance of your database.
2. Cost-effective: Blob storage is generally less expensive than traditional storage systems and can save you money on storage costs.
3. Durability: Blob storage is designed to be highly durable, with multiple redundant copies of the data stored in different locations. This helps ensure that your data is always available, even in the event of a failure.
4. Accessibility: By storing the URLs to the blob storage in your database, you can easily retrieve the data when needed, without having to access the blob storage system directly.

## How to protect Personally Identifiable Information (PII) in a database?

1. Encryption: Encrypt sensitive data such as social security numbers, credit card information, and other PII using strong encryption algorithms to protect the data.
2. Access control: Limit access to PII data to only those who need it and ensure that all access is properly authenticated and authorized.
3. Data masking: Mask sensitive data such as social security numbers, credit card information, and other PII to reduce the risk of exposure.
4. Data backup and disaster recovery: Ensure that all PII data is backed up regularly and that there is a disaster recovery plan in place to ensure that the data can be recovered in the event of a disaster.
5. Physical security: Store physical copies of PII data in a secure location to reduce the risk of theft or loss.
6. Regular audits and security assessments: Regularly audit the database and perform security assessments to identify and address any vulnerabilities.
7. Data retention and disposal: Have a plan in place for the retention and disposal of PII data, and ensure that all data is securely deleted when it is no longer needed.

### projects

- Project ID: UUID - Unique identifier for the project.
- Project Name: VARCHAR (255) - The name of the project.
- Project Location: VARCHAR (255) - The location where the project is taking place.
- Project Start Date: DATE - The date when the project started.
- Project End/Expected Close Date: DATE - The date when the project is expected to be completed.
- Nature of Intervention: VARCHAR (255) - The nature of the project intervention.
- Project Sector: VARCHAR (255) - The sector in which the project operates.
- Budget: NUMERIC (12, 2) - The budget allocated for the project.
- External Funding Received: NUMERIC (12, 2) - The funding received from external sources for the project.
- Number of Beneficiaries: INTEGER - The number of people who are directly or indirectly impacted by the project.
- Project Type: ENUM (e.g. Community Development, Health, Education, etc.) - The type of project.
- Project Photos: TEXT - Link to the photos related to the project.
- Project Documents: TEXT - Link to the documents related to the project.
- Project Description: TEXT - Detailed description of the project.
- Project Status: ENUM (Active, Completed, Suspended, etc.) - The current status of the project.
- Project Manager: VARCHAR (255) - The name of the person responsible for managing the project.
- Project Budget Allocation: NUMERIC (12, 2) - The budget allocated for the project.
- Project Budget Utilization: NUMERIC (12, 2) - The portion of the budget utilized for the project.
- Project Impact: VARCHAR (255) - The impact the project has on the community or environment.
- Project Report: TEXT - Link to the report related to the project.
