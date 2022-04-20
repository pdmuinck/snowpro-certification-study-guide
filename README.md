# snowpro-certification-study-guide


## 1.0 Domain: Account and Security

 ### 1.1 Explain how to manage Snowflake accounts.

  - [Account usage](https://docs.snowflake.com/en/sql-reference/account-usage.html)
  - [Information schema](https://docs.snowflake.com/en/sql-reference/info-schema.html)

 ### 1.2 Outline security principles.

  - [Multi-factor Authentication (MFA)](https://docs.snowflake.com/en/user-guide/security-mfa.html)
  - [Data Encryption](https://docs.snowflake.com/en/user-guide/security-encryption.html)
  - [Network Security & Policies](https://docs.snowflake.com/en/user-guide/network-policies.html)
  - [Access Control](https://docs.snowflake.com/en/user-guide/security-access-control.html)
  - [Federated Authentication](https://docs.snowflake.com/en/user-guide/admin-security-fed-auth.html)
  - [Single Sign-On (SSO)](https://docs.snowflake.com/en/user-guide/admin-security-fed-auth.html)

 ### 1.3 Define the entities and roles that are used in Snowflake.

  - Outline how privileges can be granted and revoked (covered in Access Control 1.2)
  - Explain Role Hierarchy and Privilege Inheritance (covered in Access Control 1.2)
  
 ### 1.4 Explain the Security capabilities associated with each Snowflake edition.

  - [Data masking](https://docs.snowflake.com/en/user-guide/security-column-ddm.html)

 ### 1.5 Outline Data Governance capabilities in Snowflake

  - Data masking 
  - Account usage views (see Account Usage 1.1)
  - [External Tokenization](https://docs.snowflake.com/en/user-guide/security-column-ext-token.html)

## 2.0 Domain: Virtual Warehouses

 ### 2.1 Outline compute principles.

  - [Credit usage & billing](https://docs.snowflake.com/en/user-guide/admin-usage-billing.html)
  - [Concurrency](https://www.youtube.com/watch?v=MfM4Qit_iGE), video
  - [Caching](https://community.snowflake.com/s/article/Caching-in-Snowflake-Data-Warehouse)

 ### 2.2 Explain Virtual Warehouse best practices.

  - [Scale up vs scale out, types of warehouses, management/monitoring](https://docs.snowflake.com/en/user-guide/warehouses.html)

## 3.0 Domain: Data Movement

 ### 3.1 Data Loading
 
 [Documenation](https://docs.snowflake.com/en/user-guide-data-load.html)

 ### 3.2 Outline how data can be unloaded from Snowflake to either local storage or cloud storage locations.

  [Documentation](https://docs.snowflake.com/en/user-guide-data-unload.html)

 ### 3.3 Explain how to work and load semi-structured data.

  [Documentation](https://docs.snowflake.com/en/user-guide/semistructured-concepts.html)

## 4.0 Domain: Performance Management

 ### 4.1 Outline best practices for Snowflake performance management on storage.

  - [Clustering](https://docs.snowflake.com/en/user-guide/tables-micro-partitions.html)
  - [Materialized views](https://docs.snowflake.com/en/user-guide/views-materialized.html)
  - [Search Optimization](https://docs.snowflake.com/en/user-guide/search-optimization-service.html)

 ### 4.2 Outline best practices for Snowflake performance management on virtual warehouses.

  - [Query performance and analysis](https://community.snowflake.com/s/article/Checklist-Query-Performance)
  - [Query profiles](https://docs.snowflake.com/en/user-guide/ui-query-profile.html)
  - [Query history](https://docs.snowflake.com/en/sql-reference/account-usage/query_history.html)
  - SQL optimization
  - Caching (see 2.1)

## 5.0 Domain: Snowflake Overview & Architecture

 ### 5.1 Outline key components of Snowflake’s Cloud data platform.

  - [Data types](https://docs.snowflake.com/en/sql-reference/data-types.html)
  - [Continuous data protection](https://docs.snowflake.com/en/user-guide/data-cdp.html)
  - [Cloning](https://docs.snowflake.com/en/user-guide/object-clone.html)
  - Types of Caching (see 2.1)
  - [Web Interface (UI)](https://docs.snowflake.com/en/user-guide/ui-snowsight.html)
  - [Classic UI](https://docs.snowflake.com/en/user-guide/ui-using.html)
  - [Data Marketplace](https://other-docs.snowflake.com/en/data-marketplace.html)
  - [Data Sharing](https://docs.snowflake.com/en/user-guide/secure-data-sharing-across-regions-plaforms.html)
  - [Data Exchange](https://docs.snowflake.com/en/user-guide/data-exchange.html)

 ### 5.2 Outline Snowflake data sharing capabilities.

  - Account types (see 5.4)
  - Data Marketplace & Exchange (see 5.1)
  - Access Control options (see 1.2)
  - [Shares](https://docs.snowflake.com/en/user-guide/data-sharing-provider.html)

 ### 5.3 Explain how Snowflake is different compared to legacy warehouse solutions.

  - Elastic Storage
  - Elastic Compute
  - Account Management

 ### 5.4 Outline the different editions that are available, and the functionality associated with each edition.

  - [Pricing & Features](https://docs.snowflake.com/en/user-guide/intro-editions.html)

 ### 5.5 Identify Snowflake’s Partner Ecosystem

  - [Documentation](https://docs.snowflake.com/en/user-guide/ecosystem.html)

 ### 5.6 Outline and define the purpose of Snowflake’s three distinct layers.

  - [Docs](https://docs.snowflake.com/en/user-guide/intro-key-concepts.html)
  - Storage Layer
  - Compute Layer
  - Cloud Services Layer
  
 ### 5.7 Outline Snowflake’s catalog and objects.

  - [Database, tables, views](https://docs.snowflake.com/en/user-guide/databases.html)
  - [Schema](https://docs.snowflake.com/en/sql-reference/ddl-database.html)
  - [External Functions](https://docs.snowflake.com/en/sql-reference/external-functions.html)

## 6.0 Domain: Storage and Protection

### 6.1 Outline Snowflake Storage concepts.

  - [Metadata Types](https://docs.snowflake.com/en/sql-reference/metadata.html)
  - [Clustering and micro partitions](https://docs.snowflake.com/en/user-guide/tables-clustering-micropartitions.html)
  - [Data Storage](https://docs.snowflake.com/en/user-guide/credits.html#data-storage-usage)
  - [Stage Types](https://docs.snowflake.com/en/sql-reference/sql/create-stage.html)
  - [File Formats](https://docs.snowflake.com/en/sql-reference/sql/create-file-format.html)
  - [Storage Monitoring](https://docs.snowflake.com/en/user-guide/tables-storage-considerations.html)

 ### 6.2 Outline Continuous Data Protection with Snowflake.

  - [Time Travel & Fail Safe](https://docs.snowflake.com/en/user-guide/data-availability.html)
  - [Data Encryption](https://docs.snowflake.com/en/user-guide/security-encryption.html)
