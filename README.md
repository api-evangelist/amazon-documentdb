# Amazon DocumentDB (amazon-documentdb)
Amazon DocumentDB is a fully managed, MongoDB-compatible document database service that makes it easy to set up, operate, and scale MongoDB-compatible databases in the cloud. DocumentDB is designed from the ground up to give you the performance, scalability, and availability you need when operating mission-critical MongoDB workloads at scale.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/documentdb/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Database, Document Database, DocumentDB, Managed Database, MongoDB, NoSQL

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon DocumentDB API
API for managing Amazon DocumentDB clusters, instances, parameter groups, subnet groups, snapshots, and related resources.

**Human URL:** [https://aws.amazon.com/documentdb/](https://aws.amazon.com/documentdb/)

#### Tags:

 - AWS, Database, Document Database, MongoDB, NoSQL

#### Properties

- [Documentation](https://docs.aws.amazon.com/documentdb/latest/developerguide/)
- [OpenAPI](openapi/amazon-documentdb-openapi.yml)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/docdb/2014-10-31/openapi.yaml)
- [JSONSchema](json-schema/amazon-documentdb-dbcluster-schema.json)
- [JSONLD](json-ld/amazon-documentdb-context.jsonld)
- [Pricing](https://aws.amazon.com/documentdb/pricing/)
- [GettingStarted](https://aws.amazon.com/documentdb/getting-started/)
- [FAQ](https://aws.amazon.com/documentdb/faqs/)
- [APIReference](https://docs.aws.amazon.com/documentdb/latest/developerguide/API_Reference.html)
- [Authentication](https://docs.aws.amazon.com/documentdb/latest/developerguide/security.html)
- [RateLimits](https://docs.aws.amazon.com/documentdb/latest/developerguide/limits.html)
- [JSONStructure](json-structure/amazon-documentdb-dbcluster-structure.json)
- [Example](examples/amazon-documentdb-dbcluster-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/developer/)
- [Documentation](https://docs.aws.amazon.com/documentdb/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/database/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/docdb/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-documentdb)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://aws.amazon.com/security/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-documentdb-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-documentdb-vocabulary.yaml)
- [NaftikoCapability](capabilities/documentdb-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Serverless Architecture | Automatically scales capacity up or down in fine-grained increments based on application demand, with up to 90% cost savings versus peak provisioning. |
| MongoDB Compatibility | Migrate applications typically without code changes or downtime using existing MongoDB drivers and tools. |
| Global Clusters | Automatically replicates data across up to 10 AWS Regions for low-latency reads and disaster recovery. |
| Fully Managed | Eliminates database patching, backups, and monitoring overhead so you can focus on application development. |
| I/O-Optimized Storage | Provides up to 40% cost savings for I/O-intensive workloads with predictable pricing. |
| Memory-Optimized Instances | Offers memory-optimized instance types with up to 43% cost savings for large workloads. |
| Automated Backups | Continuous backups to Amazon S3 and point-in-time recovery within the backup retention window. |
| Encryption at Rest and in Transit | Data is encrypted using AES-256, with support for AWS KMS customer-managed keys. |

## Use Cases

| Name | Description |
|------|-------------|
| Content Management Systems | Store and retrieve flexible JSON-structured content with rich query capabilities for CMS platforms. |
| E-Commerce Platforms | Manage product catalogs, user profiles, and order data with scalable document storage. |
| Mobile and Web Applications | Power real-time application backends with low-latency, scalable document storage. |
| Generative AI Applications | Store and retrieve context, embeddings, and conversational history for AI-powered agentic applications. |
| Gaming Applications | Handle player profiles, leaderboards, and game state with flexible schema and high throughput. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon CloudWatch | Monitor DocumentDB cluster metrics, set alarms, and view performance data through CloudWatch dashboards. |
| AWS IAM | Control access to DocumentDB resources and operations using IAM policies and roles. |
| AWS Backup | Centrally manage and automate backups of DocumentDB clusters using AWS Backup policies. |
| Amazon OpenSearch Service | Zero-ETL integration to replicate DocumentDB data to OpenSearch for full-text search and analytics. |
| AWS CloudTrail | Log all DocumentDB API calls for auditing, compliance, and security analysis. |
| AWS Key Management Service | Manage encryption keys for DocumentDB clusters using KMS customer-managed keys. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Documentdb](openapi/amazon-documentdb-openapi.yml)

### JSON Schema

- [Amazon Documentdb Dbcluster](json-schema/amazon-documentdb-dbcluster-schema.json)
- [Documentdb Openapi Create Db Cluster Result](json-schema/documentdb-openapi-create-db-cluster-result-schema.json)
- [Documentdb Openapi Db Cluster](json-schema/documentdb-openapi-db-cluster-schema.json)
- [Documentdb Openapi Describe Db Clusters Result](json-schema/documentdb-openapi-describe-db-clusters-result-schema.json)

### JSON Structure

- [Amazon Documentdb Dbcluster](json-structure/amazon-documentdb-dbcluster-structure.json)
- [Documentdb Openapi Create Db Cluster Result](json-structure/documentdb-openapi-create-db-cluster-result-structure.json)
- [Documentdb Openapi Db Cluster](json-structure/documentdb-openapi-db-cluster-structure.json)
- [Documentdb Openapi Describe Db Clusters Result](json-structure/documentdb-openapi-describe-db-clusters-result-structure.json)

### JSON-LD

- [Amazon Documentdb](json-ld/amazon-documentdb-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Documentdb](capabilities/shared/documentdb.yaml) — 28 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Documentdb Management](capabilities/documentdb-management.yaml) | 5 | managing DocumentDB clusters, instances, and snapshots for DevOps and database administrators |

## Vocabulary

- [Amazon DocumentDB Vocabulary](vocabulary/amazon-documentdb-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 3 actions, 1 workflows, and 1 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Documentdb Spectral Rules](rules/amazon-documentdb-spectral-rules.yml) — 28 rules enforcing Amazon DocumentDB API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com