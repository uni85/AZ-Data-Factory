
# Azure Data Integration Pipeline
Project Overview: > Migrated relational data from Azure SQL Database to an Azure Synapse Analytics Dedicated Pool using Azure Data Factory.

Key Technical Challenges Overcome:

Security: Implemented a Managed Virtual Network with Private Endpoints to ensure data never traveled over the public internet.

Authentication: Configured Managed Identity (RBAC) for password-less, secure authentication between services.

Performance: Utilized Staged Copying via Azure Blob Storage to optimize loading into Synapse.

Tools Used: > Azure Data Factory, Azure Synapse Analytics, Azure SQL DB, Managed Private Endpoints.
