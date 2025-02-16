# Using DynamoDB Instead of RDS
## Context:
### Our API requires a highly scalable database with minimal maintenance.

## Decision:
### We choose AWS DynamoDB over RDS (PostgreSQL/MySQL) due to:

## Rationale:
 - No maintenance (fully managed NoSQL)
 - Auto-scaling support
 - Low-latency performance for serverless applications
