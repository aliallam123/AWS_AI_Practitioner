# Amazon Bedrock & Generative AI – AIF-C01 Exam Essentials

This guide summarises key Amazon Bedrock and generative AI concepts relevant to the AWS Certified AI Practitioner (AIF-C01) exam. It focuses on topics likely to appear in the exam, providing concise explanations.

---

## 🧠 Foundation Models (FMs) in Amazon Bedrock

**Definition**: Pre-trained large language models (e.g., Amazon Titan, Anthropic Claude, Meta Llama 2) accessible via API.

**Key Concepts**:
- **Model selection**: Consider cost, latency, modality (text, image), multilingual support, and customisation needs.
- **Inference settings**: Adjust parameters like temperature and output length to influence results.
- **Access control**: IAM roles must have the right permissions, especially for encrypted S3 buckets.

---

## 🛠️ Fine-Tuning Models

**Purpose**: Customise a foundation model with your own data to improve performance on specific tasks.

**Steps**:
1. Prepare and curate training data.
2. Fine-tune the model in Bedrock.
3. Register the fine-tuned model.
4. Ensure correct permissions for use.

> Note: Fine-tuned models require **Provisioned Throughput** for inference.

---

## 📚 Retrieval-Augmented Generation (RAG) & Knowledge Bases

**RAG**: Enhances responses by retrieving relevant information from external documents before generating answers.

**Amazon Bedrock Knowledge Bases**:
- Connect your own data (PDFs, docs, FAQs, etc.).
- Supported sources include Amazon S3, Salesforce, and SharePoint.
- Automatically converts data into embeddings using vector stores (e.g. Amazon OpenSearch, Pinecone).
- Includes **citations** to reduce hallucinations and improve transparency.

---

## 🛡️ Guardrails for Responsible AI

**Purpose**: Control outputs and prevent inappropriate or sensitive content.

**Features**:
- Predefined content filters.
- Draft/test policies before applying.
- Monitored via Amazon CloudWatch.

---

## 🤖 Agents in Amazon Bedrock

**Purpose**: Automate multi-step workflows using foundation models and external tools.

**Key Capabilities**:
- Break down complex tasks.
- Call APIs and tools during execution.
- Use Knowledge Bases for context.

**Use Case Example**: Customer support agent that fetches account info and updates records based on conversation.

---

## 📊 Monitoring with Amazon CloudWatch

- Track usage metrics (token count, errors, latency).
- Set alarms for unusual behaviour or policy violations.
- Monitor guardrail violations and agent performance.

---

## 💰 Pricing Overview

**On-Demand Pricing**:
- Pay per input/output token.
- No upfront commitment.
- Great for prototyping and light usage.

**Provisioned Throughput**:
- Reserved capacity for consistent performance.
- Required for fine-tuned models.
- Monthly pricing model based on throughput units.

**Cost-Saving Tips**:
- Use smaller models where appropriate.
- Reduce token usage through prompt engineering.
- Use RAG instead of fine-tuning when possible.
