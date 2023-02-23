# Database

[Codebook](https://docs.google.com/document/d/1Z6dCQ9iEyyHJ-b1aDA93F3tFqB0ICluw2i8Ex-WeENM/edit#)

## Field Naming Conventions

Snake case: all lowercase letters with underscores between words (e.g., start_date, budget_allocation).

- Try to limit the name to 50 characters (shorter is better)
- Use only letters or underscores (try to avoid numbers – and limit the use of underscores)
- Limit the use of abbreviations (can lead to misinterpretation of names)
- Limit the use of acronyms (some acronyms have more than one meaning e.g. "ASP")
- Make the name readable (they shouldn't sound funny when read aloud).
- Avoid using spaces in names even if the system allows it.

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
