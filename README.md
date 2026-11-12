# Awesome-Contract-AI-Model-Training-Fine-Tuning

# Top Contract AI Model Training & Fine-Tuning Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Legal Domain Adaptation, Clause Classification & Contract Reasoning Models*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Contract AI Model Training & Fine-Tuning**. These tools help legal and engineering teams adapt foundation models to contract-specific tasks—covering clause extraction, risk scoring, playbook application, and legal natural language inference—while preserving confidentiality through self-hosted or on-premises deployment.

**Examples** include Icertis AI Studio, Kira Systems, Luminance, Evisort, Lexion, Robin AI, Spellbook, and open-source alternatives like Legal-Peace and LiTiL (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted contract AI models, open-source fine-tuning frameworks, and community-driven legal NLP—ideal for organizations seeking data sovereignty and transparent model behavior over opaque vendor APIs.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis AI Studio](https://www.icertis.com/)** | Enterprise CLM platform with AI model customization capabilities. Vera Copilot and AI agents trained on contract data for extraction, obligation tracking, and risk analysis. Used by one-third of the Fortune 100. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Kira Systems](https://kirasystems.com/)** | Legal contract analysis platform with pre-trained models for clause extraction and due diligence. Acquired by Litera. Models can be trained on firm-specific clause variations. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Luminance](https://www.luminance.com/)** | AI-powered contract analysis with pattern recognition trained on legal documents. Positioned for high-volume review with minimal configuration. | Quote-only (enterprise contract) | No free tier; trial via sales |
| **[Evisort Studio](https://www.evisort.com/)** | AI contract intelligence platform (acquired by Workday) with model training capabilities for custom clause extraction and risk detection. REST API supports document upload and field extraction. | $30,000–$60,000/year (small teams); $60,000–$120,000/year (mid-market) | Free trial available; self-serve signup |
| **[Lexion AI](https://www.lexion.ai/)** | AI contract management (acquired by Docusign for ~$165M) with extraction models trained on legal documents. No public REST API for model training; sales-led onboarding. | Quote-only (enterprise contract) | No free trial; sales-led onboarding |
| **[Robin AI](https://www.robinai.com/)** | AI legal assistant with contract review capabilities. Uses Claude models with legal-specific fine-tuning. Positioned for in-house legal teams. | Quote-only (per-seat or enterprise) | Free trial available via sales |
| **[Spellbook](https://www.spellbook.legal/)** | AI contract drafting and review assistant built on GPT-4/Claude. Suggests redlines and clause language within Microsoft Word. No custom model training for customers. | Quote-only (per-seat) | Free trial available |
| **[Casetext CoCounsel](https://casetext.com/)** | AI legal assistant (acquired by Thomson Reuters) with contract analysis capabilities. Uses GPT-4 with legal-specific prompting rather than customer fine-tuning. | Quote-only (per-seat) | No free tier; demo via sales |
| **[Ironclad AI](https://ironcladapp.com/)** | CLM platform with Contract Review Agent for playbook-based redlining and AI-assisted extraction. Models trained on Ironclad's contract corpus, not customer-specific fine-tuning. | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Legal-Peace-7B](https://huggingface.co/olaverse/legal-peace-v1.0)** | [![Stars](https://img.shields.io/github/stars/Olaverse-Labs/olaverse-legal?style=social&color=white)](https://github.com/Olaverse-Labs/olaverse-legal/stargazers) | Fine-tuned Mistral-7B-v0.3 model for contract analysis and legal reasoning. Trained with SFT (4,800 cases) + DPO (419 legal reasoning examples). Claims 32.6% faster contract analysis and 14% faster case predictions vs. base Mistral. Apache 2.0 licensed; **beta model for research, not production** . |
| **[LiTiL Open Intelligence Models](https://huggingface.co/collections/litillabs/litil-open-intelligence-models)** | [![Stars](https://img.shields.io/github/stars/litillabs?style=social&color=white)](https://github.com/litillabs/stargazers) | Collection of specialized legal AI models with defined jobs: legal request router (1.5B), legal intake (4B), PII finder (0.3B), clause check (1.5B), clause tagger (4B), clause classifier (0.4B), contract extractor (1.7B), contract playbook (3B), and financing review (9B). Open, task-specific models for legal workflows . |
| **[PAKTON](https://aclanthology.org/2025.emnlp-main.403/)** | [![Stars](https://img.shields.io/github/stars/petrosrapto/PAKTON?style=social&color=white)](https://github.com/petrosrapto/PAKTON/stargazers) | Fully open-source multi-agent framework for question answering in long legal agreements. Uses collaborative agent workflows and RAG for privacy-preserving contract analysis. Outperforms general-purpose models on predictive accuracy, retrieval, and explainability . |
| **[contractnli-llms](https://github.com/fbaratov/contractnli-llms)** | [![Stars](https://img.shields.io/github/stars/fbaratov/contractnli-llms?style=social&color=white)](https://github.com/fbaratov/contractnli-llms/stargazers) | Code and evaluation for open-source LLMs on legal natural language inference. Finds Gemma-4 26B reaches 81.2% accuracy on ContractNLI, outperforming supervised baselines on one metric. Demonstrates zero-shot open-source LLMs are viable for legal NLI when no labeled data exists . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Hermes Legal Advisor](https://github.com/Lethe044/hermes-legal)** | [![Stars](https://img.shields.io/github/stars/Lethe044/hermes-legal?style=social&color=white)](https://github.com/Lethe044/hermes-legal/stargazers) | Open-source contract analysis CLI with offline scanner, LLM provider fallback (Groq, Gemini, OpenRouter, Ollama), risk scoring, redlining, and batch processing. Supports custom firm playbooks via YAML. Python package with Docker deployment . |
| **[contractguardian](https://pypi.org/project/contractguardian/)** | [![Stars](https://img.shields.io/github/stars/contractguardian/contractguardian?style=social&color=white)](https://github.com/contractguardian/contractguardian/stargazers) | Open-source contract scanner supporting PDF, DOCX, TXT, and MD. Detects contract type (lease, NDA, employment, freelance, SaaS, loan, purchase) and applies type-specific red flag checks. Supports OpenAI, OpenRouter, and local Ollama models. Fairness grading with structured JSON output . |
| **[Contract Review AI](https://github.com/xiaodingfeng/contract-review-v2)** | [![Stars](https://img.shields.io/github/stars/xiaodingfeng/contract-review-v2?style=social&color=white)](https://github.com/xiaodingfeng/contract-review-v2/stargazers) | Chinese-language contract review platform with AI pre-analysis, risk flagging, OnlyOffice collaborative editing, legal knowledge base with vector retrieval (Milvus), and intelligent Q&A. Docker Compose deployment with PostgreSQL, MinIO, and etcd . |
| **[awesome-legaltech](https://github.com/chen-friedman/awesome-legaltech)** | [![Stars](https://img.shields.io/github/stars/chen-friedman/awesome-legaltech?style=social&color=white)](https://github.com/chen-friedman/awesome-legaltech/stargazers) | Curated list of open-source Legal AI tools, datasets, and benchmarks. Covers document signing, OCR/PDF processing, document assembly, and rules-as-code platforms. Jurisdiction-tagged for global scope . |

**Frameworks for building custom systems**: Combine **Legal-Peace-7B** or **LiTiL models** for specialized contract reasoning, **PAKTON** for multi-agent RAG over long agreements, **Hermes Legal Advisor** for CLI-based analysis with playbook customization, and **contractguardian** for type-specific red flag detection—all deployable locally or via Docker without per-document API costs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract AI models process legally sensitive documents; enforce strict access controls, encryption, and data residency compliance. Outputs must always be reviewed by qualified legal professionals before reliance.
- Commercial platforms (Icertis, Kira, Luminance, Evisort) are quote-only and rarely offer customer-specific fine-tuning on their infrastructure; most rely on pre-trained models. Open-source alternatives like Legal-Peace are explicitly beta/research models **not recommended for production** without extensive validation . LegalBench research indicates F1 ≥ 0.85 is the threshold for production-grade contract review; below this, false negatives on risk clauses become unacceptably high .

---

**Made for legal engineers, contract AI researchers, legal ops teams, and developers building domain-specific legal models.**  
Let's make contract AI training and fine-tuning more open, transparent, and legally sound.
