# Amazon Storage Gateway (amazon-storage-gateway)

AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage via file, volume, and tape interfaces.

**URL:** [https://aws.amazon.com/storagegateway/](https://aws.amazon.com/storagegateway/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Storage, Hybrid Cloud, Data Transfer, NFS, SMB

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Storage Gateway API

AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage via file, volume, and tape interfaces.

**Human URL:** [https://aws.amazon.com/storagegateway/](https://aws.amazon.com/storagegateway/)

#### Tags:

 - Storage, Hybrid Cloud, NFS, SMB

#### Properties

- [Documentation](https://docs.aws.amazon.com/storagegateway/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-storage-gateway.yaml)
- [GettingStarted](https://aws.amazon.com/storagegateway/)
- [Pricing](https://aws.amazon.com/storagegateway/pricing/)

## Common Properties

- [Portal](https://aws.amazon.com/storagegateway/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/storagegateway/)
- [StatusPage](https://health.aws.amazon.com/health/status)

## Features

| Name | Description |
|------|-------------|
| File Gateway | Provides NFS and SMB access to objects stored in Amazon S3. |
| Volume Gateway | Provides iSCSI block storage backed by Amazon S3 and Glacier. |
| Tape Gateway | Virtual tape library backed by S3 and Glacier for backup. |
| Hybrid Storage | Seamlessly integrate on-premises environments with AWS storage. |

## Use Cases

| Name | Description |
|------|-------------|
| Cloud Backup | Back up on-premises data to AWS using existing backup workflows. |
| Disaster Recovery | Store data in AWS for disaster recovery with low RTO. |
| Data Archiving | Archive cold data to Amazon Glacier through virtual tape library. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store all gateway data in S3 with intelligent tiering. |
| Amazon Glacier | Archive tape data to Glacier for long-term retention. |
| AWS Backup | Centralized backup of Storage Gateway volumes and file shares. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-storage-gateway-api-openapi.yml](openapi/amazon-storage-gateway-api-openapi.yml)
- [amazon-storage-gateway.yaml](openapi/amazon-storage-gateway.yaml)

### JSON Schema

- [amazon-storage-gateway-activate-gateway-input-schema.json](json-schema/amazon-storage-gateway-activate-gateway-input-schema.json)
- [amazon-storage-gateway-activate-gateway-output-schema.json](json-schema/amazon-storage-gateway-activate-gateway-output-schema.json)
- [amazon-storage-gateway-active-directory-status-schema.json](json-schema/amazon-storage-gateway-active-directory-status-schema.json)
- [amazon-storage-gateway-add-cache-input-schema.json](json-schema/amazon-storage-gateway-add-cache-input-schema.json)
- [amazon-storage-gateway-add-cache-output-schema.json](json-schema/amazon-storage-gateway-add-cache-output-schema.json)
- ... and 217 more

### JSON Structure

- [amazon-storage-gateway-activate-gateway-input-structure.json](json-structure/amazon-storage-gateway-activate-gateway-input-structure.json)
- [amazon-storage-gateway-activate-gateway-output-structure.json](json-structure/amazon-storage-gateway-activate-gateway-output-structure.json)
- [amazon-storage-gateway-active-directory-status-structure.json](json-structure/amazon-storage-gateway-active-directory-status-structure.json)
- [amazon-storage-gateway-add-cache-input-structure.json](json-structure/amazon-storage-gateway-add-cache-input-structure.json)
- [amazon-storage-gateway-add-cache-output-structure.json](json-structure/amazon-storage-gateway-add-cache-output-structure.json)
- ... and 217 more

### JSON-LD

- [amazon-storage-gateway-context.jsonld](json-ld/amazon-storage-gateway-context.jsonld)

### Examples

- [amazon-storage-gateway-activate-gateway-input-example.json](examples/amazon-storage-gateway-activate-gateway-input-example.json)
- [amazon-storage-gateway-activate-gateway-output-example.json](examples/amazon-storage-gateway-activate-gateway-output-example.json)
- [amazon-storage-gateway-active-directory-status-example.json](examples/amazon-storage-gateway-active-directory-status-example.json)
- [amazon-storage-gateway-add-cache-input-example.json](examples/amazon-storage-gateway-add-cache-input-example.json)
- [amazon-storage-gateway-add-cache-output-example.json](examples/amazon-storage-gateway-add-cache-output-example.json)
- ... and 217 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions.

### Shared Per-API Definitions

- [amazon-storage-gateway.yaml](capabilities/shared/amazon-storage-gateway.yaml) — Amazon Storage Gateway operations for resource management

## Vocabulary

- [Amazon Storage Gateway Vocabulary](vocabulary/amazon-storage-gateway-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas

## Rules

- [Amazon Storage Gateway Spectral Rules](rules/amazon-storage-gateway-spectral-rules.yml) — Rules enforcing Amazon Storage Gateway API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
