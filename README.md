# AWS Architecture Reference Hub

This repository is a reference hub for AWS architecture projects focused on backend and cloud engineering with Node.js, TypeScript, AWS Serverless, Terraform, and cloud architecture.

The architecture implementations live in separate repositories linked below. This hub is not a deployable infrastructure repository and does not contain Terraform code, application code, or environment-specific deployment assets.

## Reference Goal

The goal of this collection is to make AWS backend and cloud architecture examples easy to review, compare, and discuss from a technical perspective.

It demonstrates:

- Backend and cloud architecture patterns on AWS
- Serverless API design, containerized application deployment, and managed model integration
- Terraform and Infrastructure as Code concepts through linked project repositories
- Awareness of security, observability, scalability, and cost trade-offs
- Clear architecture communication without presenting the examples as deployable production systems

These projects are reference and learning-oriented architecture examples. The maturity labels below are intentionally modest.

## Recommended Review Path

If you only review three projects, start with:

1. [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend) - strongest fit for backend/serverless API discussion.
2. [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter) - shows cloud application design around managed model capabilities.
3. [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app) - shows container deployment, networking, and service operation concepts.

These are the featured projects and the clearest review path for backend and cloud architecture topics.

## Featured Projects

| Project | What it demonstrates | Main AWS services | Technical focus | Current maturity/status |
|---|---|---|---|---|
| [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend) | Serverless API architecture, request handling, persistence, and backend service boundaries. | Amazon API Gateway, AWS Lambda, Amazon DynamoDB, IAM, Amazon CloudWatch. | Directly maps to API backend work, serverless application design, service integration, and discussions about validation, IAM, observability, scaling, and cost. | Improving. This is the main project being deepened with clearer API design notes, security considerations, observability notes, and cost trade-offs. |
| [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter) | A starter architecture for integrating managed model capabilities into a cloud application. | Amazon Bedrock, AWS Lambda, API/application integration patterns, IAM, Amazon CloudWatch. | Relevant for systems that add model-assisted workflows while still needing backend fundamentals: service boundaries, permissions, operational visibility, and cost awareness. | Basic. Useful as a focused managed-model architecture reference, with room to deepen implementation detail and operational notes. |
| [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app) | Containerized web application architecture, service deployment, networking, and scaling concepts. | Amazon ECS, AWS Fargate, Elastic Load Balancing, Amazon EFS, Amazon VPC, IAM, Amazon CloudWatch. | Supports discussion of backend service hosting outside pure serverless, including container operations, traffic routing, health checks, scaling, and deployment flow. | Basic. A baseline container architecture reference that should be reviewed as a foundation rather than a production platform claim. |

## Maturity Labels

| Maturity | Meaning |
|---|---|
| Basic | Initial implementation or architecture baseline exists in the linked repository. |
| Improving | The project is being enhanced with clearer documentation, security notes, observability notes, cost notes, and architecture trade-offs. |
| Reference-ready | Target state where a project has enough structure to explain architecture choices, limitations, and trade-offs clearly. |

None of the projects are presented as deployable production systems. The focus is clear architecture communication, practical AWS learning, and steady improvement.

## Technical Discussion Topics

This collection is designed to make the most relevant backend and cloud architecture examples easy to find first.

The strongest discussion areas are:

- Explaining service selection and trade-offs for serverless and containerized backends
- Discussing how IAM, observability, cost, and scalability would be improved over time
- Comparing serverless, containerized, event-driven, data, streaming, and CI/CD architectures
- Showing practical familiarity with Terraform and Infrastructure as Code through the linked implementation repositories
- Communicating cloud architecture clearly and honestly

## Roadmap

| Phase | Focus | Outcome |
|---|---|---|
| Phase 1 | Improve the main reference hub | Make the README and GitHub Pages content a clear landing point for backend and cloud architecture topics. |
| Phase 2 | Standardize sub-repository READMEs | Align project documentation around overview, services, architecture diagram, deployment notes, trade-offs, and next steps. |
| Phase 3 | Deepen Serverless API Backend | Improve API design notes, IAM boundaries, validation, observability, and cost considerations. |
| Phase 4 | Deepen GenAI Starter and Containerized Web App | Improve managed-model application boundaries and container architecture notes, including networking, scaling, health checks, and deployment flow. |
| Phase 5 | Improve supporting references | Add clearer cross-project notes on CI/CD, security, observability, cost drivers, data, streaming, and event-driven patterns. |

## Feedback

Suggestions, issues, and improvements are welcome. This collection is being improved iteratively as the linked architecture projects become more complete and better documented.
