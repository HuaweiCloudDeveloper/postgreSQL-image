 <h1 align="center">PostgreSQL Database</h1>
  <p align="center">
    <strong>English</strong> | <a href="README_ZH.md"><strong>Simplified Chinese</strong></a>
  </p>


## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction

[PostgreSQL](https://www.postgresql.org/) is an open-source object-relational database management system (ORDBMS). It is renowned for its reliability, feature completeness, and high compatibility with SQL standards, supporting core features such as ACID transactions, complex queries, foreign key constraints, and triggers. This product provides an out-of-the-box PostgreSQL based on the Huawei Cloud EulerOS 2.0 64-bit system for Kunpeng servers.

## Core Features

- **SQL Standard Compatibility**:
  - Fully supports SQL standards, including advanced features such as window functions and CTEs (Common Table Expressions)
  - Supports unstructured data types like JSON, XML, and arrays
- **Extensibility**:
  - Supports extended functions such as time-series databases and geospatial data processing through a plug-in system
  - Allows custom data types and operators
- **Concurrency Control**:
  - Adopts the MVCC (Multi-Version Concurrency Control) mechanism to achieve high concurrent read and write operations
  - Supports fine-grained transaction isolation levels

The open-source image product [**PostgreSQL Database**](https://marketplace.huaweicloud.com/intl/hidden/contents/5071bca5-4d60-4ce9-aa07-1af6574955cc) provided by this project has pre-installed PostgreSQL database version 14.18 and its related runtime environment, and offers deployment templates. Follow the user guide to easily enjoy the efficient "out-of-the-box" experience.


> **System Requirements:**
> - CPU: 2vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                   | Feature Description | Remarks |
|--------------------------------------------------------------------------------------------------------------------| --- | --- |
| [PostgreSQL-14.18-kunpeng](https://github.com/HuaweiCloudDeveloper/postgreSQL-image/tree/PostgreSQL-14.18-kunpeng) | Installed and deployed based on Kunpeng server + Huawei Cloud EulerOS 2.0 64bit |  |

## Get Help
- For more questions, you can contact us through [issues](https://github.com/HuaweiCloudDeveloper/postgreSQL-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a pull request
- Synchronously update README.md based on your open-source image information