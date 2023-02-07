# Database

## How are we storing images, audio, video etc.?

Images, videos, and audio are stored in a blob storage system and then the URLs to the blob storage URI are stored in a database. This approach has several benefits:

1. Scalability: Blob storage systems are designed for scalability and can handle a large volume of data without affecting the performance of your database.
2. Cost-effective: Blob storage is generally less expensive than traditional storage systems and can save you money on storage costs.
3. Durability: Blob storage is designed to be highly durable, with multiple redundant copies of the data stored in different locations. This helps ensure that your data is always available, even in the event of a failure.
4. Accessibility: By storing the URLs to the blob storage in your database, you can easily retrieve the data when needed, without having to access the blob storage system directly.

