# Technical Approval Playbook for AI Startup Grants & Cloud Credits (2026)

## 1. Domain, DNS & Email Authentication Checklist
- **Live HTTPS Product Page:** Must clearly describe your software product, pricing/download or beta access, and company name.
- **SPF Record (`TXT @`):** `v=spf1 include:_spf.google.com ~all`
- **DKIM Record (`TXT google._domainkey`):** 2048-bit RSA key activated in Google Workspace Admin Console (`Status: Authenticating email with DKIM`).
- **DMARC Record (`TXT _dmarc`):** `v=DMARC1; p=quarantine; rua=mailto:security@yourdomain.com`

## 2. Pitch Deck Structure for Technical Reviewers (NVIDIA Inception / Google Cloud AI / AWS Activate)
1. **Title & Executive Summary:** Company name, domain, incorporation year, and core AI architecture.
2. **Problem Statement:** Quantified engineering or enterprise bottleneck.
3. **Architecture & GPU/Cloud Utilization:** How your pipeline uses NVIDIA NIM / TensorRT-LLM / Vertex AI / Bedrock / Kubernetes.
4. **Product Benchmarks:** Concrete latency, throughput, and accuracy metrics.
5. **Traction & Business Model:** B2B seat pricing, active deployments, and 12-month compute scaling roadmap.

## 3. Interactive Multi-Language Finder
Explore and filter all programs at **[https://fractalops.ai/grants](https://fractalops.ai/grants)**.
