# Hey, I'm Mehdi 👋

Computer Science student at SNHU (graduating November 2026), AWS Certified Solutions Architect Associate and Cloud Practitioner, focused on cloud and DevOps engineering.

I design, deploy, and secure production-grade systems on AWS and automate them end to end with infrastructure as code and CI/CD. My work ranges from a serverless FinOps tool that monitors cloud cost and waste to AI applications on Amazon Bedrock (LLMs, RAG, and agents), all built with Terraform and GitHub Actions.

**Open to entry-level and internship roles in cloud, DevOps, and AI engineering.**

## 🔧 Tech I use

**AWS**
Lambda · API Gateway · DynamoDB · S3 · EventBridge · SNS · CloudWatch · ECR · Secrets Manager · WAF · AWS Config · Cost Anomaly Detection · Bedrock · IAM · VPC

**Infrastructure as Code**
Terraform · AWS SAM · CloudFormation

**Containers & CI/CD**
Docker · GitHub Actions · CI/CD pipelines

**Security**
IAM least-privilege · WAF · OIDC · HMAC-verified webhooks · Secrets Manager

**Languages & Tools**
Python · Bash · Linux · Git · YAML · JavaScript/TypeScript · SQL

**AI**
Amazon Bedrock · Amazon SageMaker · LLMs · RAG · prompt engineering · AI agents (Strands SDK) · LLM integration

**📚 Currently learning:** Kubernetes

## 🚀 Projects

- **[AWS Cost Watchdog](https://github.com/medysaly/aws-cost-watchdog)** — a serverless FinOps tool that tracks AWS spend and waste: daily cost digests to Slack/Telegram, idle-resource detection, tag-policy enforcement via AWS Config, and ML-based anomaly alerts via Cost Anomaly Detection, with a React dashboard. Four event-driven Lambdas on EventBridge Scheduler and SNS, provisioned with Terraform (remote S3 state + DynamoDB locking) and deployed through GitHub Actions with OIDC federation, no static credentials. Caught real savings in production.
- **[StockWatch](https://github.com/medysaly/stockwatch)** — a serverless AI market-brief on AWS: a container ARM64 Lambda that pulls market data and news (yfinance) and summarizes it with Claude on an EventBridge daily schedule. LLM output is tested with pytest checks in a GitHub Actions pipeline (ruff + terraform plan), deployed on ECR with OIDC and secrets in Secrets Manager.
- **[Unkommon](https://github.com/medysaly/unkommon)** — a full-stack AI website on a serverless AWS backend, designed, built, and deployed solo. A React site with an AI chatbot and a VAPI voice receptionist on Bedrock that answer questions, book appointments, and capture leads. Hardened with WAF, HMAC-verified webhooks, least-privilege IAM, and Secrets Manager, over a layered, tested architecture with a DynamoDB data layer (Global Secondary Indexes) and a GitHub Actions pytest pipeline. Live at [unkommon.ai](https://unkommon.ai).
- **[Company Policy RAG](https://github.com/medysaly/company-policy-rag)** — a Retrieval-Augmented Generation system over policy documents: hybrid retrieval (dense embeddings + BM25), cross-encoder reranking, and RAGAS evaluation (1.00 faithfulness and context precision on a 10-question set). FastAPI backend with a Streamlit UI, containerized with Docker and deployed on Hugging Face Spaces.

## 📫 Connect

- LinkedIn: https://www.linkedin.com/in/mehdi-salhi-work
- Email: mehdisalhi.dev@gmail.com
- Site: https://mehdisalhi.com
