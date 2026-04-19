# Amazon Cloud9 (amazon-cloud9)
AWS Cloud9 is a browser-based integrated development environment (IDE) that enables developers to write, run, and debug code without installing local software. Supports 40+ programming languages with real-time collaboration, integrated terminal, and pre-authenticated AWS CLI.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloud9/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cloud9, IDE, Development, Browser-Based

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Cloud9 API
API for creating and managing Cloud9 development environments — browser-based IDEs running on EC2 instances or SSH-connected servers.

**Human URL:** [https://aws.amazon.com/cloud9/](https://aws.amazon.com/cloud9/)

#### Tags:

 - AWS, Cloud9, IDE, Development

#### Properties

- [Documentation](https://docs.aws.amazon.com/cloud9/latest/APIReference/)

- [APIReference](https://docs.aws.amazon.com/cloud9/latest/APIReference/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloud9/)
- [SpectralRules](rules/amazon-cloud9-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloud9-vocabulary.yaml)
- [NaftikoCapability](capabilities/development-environment.yaml)

## Features

| Name | Description |
|------|-------------|
| Browser-Based IDE | Write, run, and debug code from any browser without local software installation. |
| Real-Time Collaboration | Pair program with teammates seeing edits simultaneously with built-in chat. |
| Pre-Authenticated AWS CLI | Terminal with pre-configured AWS credentials for seamless service access. |
| 40+ Language Support | Syntax highlighting and code completion for Python, JavaScript, PHP, Ruby, Go, and more. |
| Serverless Development | Integrated local testing environment for AWS Lambda serverless functions. |

## Use Cases

| Name | Description |
|------|-------------|
| Remote Development | Develop from any internet-connected device without local environment setup. |
| Collaborative Coding | Pair program and share development environments in real time. |
| Serverless Development | Develop, test, and deploy AWS Lambda functions with integrated tooling. |
| AWS-Native Development | Develop AWS applications with pre-installed SDKs and pre-authenticated CLI. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Develop and test serverless functions with integrated Lambda tooling. |
| AWS CodeCommit | Access CodeCommit repositories from Cloud9 environments. |
| AWS CodePipeline | Integrate Cloud9 into CI/CD pipelines for automated deployment. |
| Amazon EC2 | Cloud9 environments run on managed EC2 instances. |
| AWS IAM | Control access to Cloud9 environments with IAM policies. |

## Artifacts

### JSON Schema

- No schemas generated

### JSON-LD

- [Amazon Cloud9 Context](json-ld/amazon-cloud9-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon Cloud9](capabilities/shared/cloud9.yaml) — 5 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Development Environment Management](capabilities/development-environment.yaml) | Amazon Cloud9 | 5 | Software Developer |

## Vocabulary

- [Amazon Cloud9 Vocabulary](vocabulary/amazon-cloud9-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon Cloud9 Spectral Rules](rules/amazon-cloud9-spectral-rules.yml) — 19 rules enforcing Amazon Cloud9 API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
