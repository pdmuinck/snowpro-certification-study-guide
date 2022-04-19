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

  - Credit usage & billing
  - Concurrency
  - Caching

 ### 2.2 Explain Virtual Warehouse best practices.

  - Scale up vs scale out
  - Types of virtual warehouses
  - Management/monitoring

## 3.0 Domain: Data Movement

 ### 3.1 Outline different commands used to load data and when they should be used.

  - COPY
  - INSERT
  - PUT
  - GET
  - VALIDATE

 ### 3.2 Define bulk as compared to continuous data loading methods.

  - COPY
  - Snowpipe

 ### 3.3 Define best practices that should be considered when loading data.

  - File size
  - Folders

 ### 3.4 Outline how data can be unloaded from Snowflake to either local storage or cloud storage locations.

  - Define formats supported for unloading data from Snowflake
  - Define best practices that should be considered when unloading data

 ### 3.5 Explain how to work and load semi-structured data.

  - Supported file formats
  - VARIANT column
  - Flattening the nested structure

## 4.0 Domain: Performance Management

 ### 4.1 Outline best practices for Snowflake performance management on storage.

  - Clustering
  - Materialized views
  - Search Optimization

 ### 4.2 Outline best practices for Snowflake performance management on virtual warehouses.

  - Query performance and analysis
  - Query profiles
  - Query history
  - SQL optimization
  - Caching

## 5.0 Domain: Snowflake Overview & Architecture

 ### 5.1 Outline key components of Snowflake’s Cloud data platform.

  - Data types
  - Continuous data protection
  - Cloning
  - Types of Caching
  - Web Interface (UI)
  - Data Cloud/Data Sharing/ Data Marketplace/ Data Exchange

 ### 5.2 Outline Snowflake data sharing capabilities.

  - Account types
  - Data Marketplace & Exchange
  - Access Control options
  - Shares

 ### 5.3 Explain how Snowflake is different compared to legacy warehouse solutions.

  - Elastic Storage
  - Elastic Compute
  - Account Management

 ### 5.4 Outline the different editions that are available, and the functionality associated with each edition.

  - Pricing
  - Features

 ### 5.5 Identify Snowflake’s Partner Ecosystem

  - Cloud Partners
  - Connectors

 ### 5.6 Outline and define the purpose of Snowflake’s three distinct layers.

  - Storage Layer
  - Compute Layer
  - Cloud Services Layer
  
 ### 5.7 Outline Snowflake’s catalog and objects.

  - Database
  - Schema
  - Tables Types
  - View Types
  - Data Types
  - External Functions

## 6.0 Domain: Storage and Protection

### 6.1 Outline Snowflake Storage concepts.

  - Micro partitions
  - Metadata Types
  - Clustering
  - Data Storage
  - Stage Types
  - File Formats
  - Storage Monitoring

 ### 6.2 Outline Continuous Data Protection with Snowflake.

  - Time Travel
  - Fail Safe
  - Data Encryption
  - Cloning
