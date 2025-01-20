# HealthDataPipeline

## Summary

The project involves building an end-to-end Azure data engineering pipeline using EMR, claims, NPI, and ICD data, implementing a medallion architecture with fact and dimension tables for reporting.

## Highlights

📊 End-to-end pipeline: Establishes a robust Azure data pipeline for healthcare data.

🏗️ Medallion architecture: Utilizes a three-layer approach (bronze, silver, gold) for data processing.

🔄 Slowly Changing Dimensions: Implements SCD Type 2 for historical data tracking.

🗃️ Delta tables: Leverages Delta tables in the silver layer for ACID transactions and data consistency.

🌐 Unity catalog: Centralizes metadata management for improved data governance.

📈 Performance enhancement: Transforms the pipeline to run activities in parallel for efficiency.

📜 Comprehensive documentation: Code stored in GitHub for version control and collaboration.

## Key Insights

🏥 Healthcare focus: Specifically addresses healthcare data needs, facilitating better insights and reporting. Highlights the importance of managing claims and EMR data effectively.

🔍 Data quality assurance: Implements data quality checks to ensure accuracy and reliability, which is vital in healthcare analytics.

⏳ Change data capture: Enables real-time updates and historical tracking, enhancing decision-making capabilities.

📊 Reporting readiness: Structures data into fact and dimension tables in the gold layer, preparing it for actionable business intelligence.

🔗 API integration: Enhances the pipeline by integrating public APIs to provide additional context and insights.

🛡️ Enhanced security: Implements Azure Key Vault to securely store and manage sensitive information.

📚 Continuous learning: Serves as a valuable educational resource for aspiring data engineers, illustrating real-world data engineering challenges and solutions.

## Features

### Medallion Architecture:

Bronze Layer: Raw data ingestion from EMR, claims, NPI, and ICD sources.

Silver Layer: Data transformation and quality checks using Delta tables.

Gold Layer: Creation of fact and dimension tables for reporting and analytics.

### Data Management:

Support for Slowly Changing Dimensions (Type 2).

Centralized metadata with Unity Catalog.

### Performance Optimization:

Parallelized processing to reduce execution time.

### Data Security:

Secure storage of sensitive data using Azure Key Vault.

### API Integration:

Calls public APIs to enrich healthcare data with additional insights.

### Comprehensive Documentation:

Detailed codebase and user guides stored on GitHub for easy collaboration.
