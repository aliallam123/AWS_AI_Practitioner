# AWS AI Managed Services – AIF-C01 Exam Notes

This covers only the AWS AI services you need to know for the exam. These are **fully managed** services – no ML expertise required.

---

## 🤖 Amazon Lex
- **Build chatbots and voice assistants**.
- Uses automatic speech recognition (ASR) + natural language understanding (NLU).
- Integrates with Amazon Connect for call centers.
- Use case: Build a customer support chatbot.

---

## 🗣️ Amazon Polly
- **Converts text into natural-sounding speech (Text-to-Speech)**.
- Supports multiple voices, accents, and languages.
- Use case: Read out messages for voice-enabled applications.

---

## 🎙️ Amazon Transcribe
- **Speech-to-Text** service (converts audio to text).
- Supports real-time and batch transcription.
- Use case: Transcribing customer support calls or meeting recordings.

---

## 🌍 Amazon Translate
- **Neural machine translation** between 75+ languages.
- Real-time and batch translation.
- Use case: Localizing website content or user messages.

---

## 🖼️ Amazon Rekognition
- **Image and video analysis**.
- Detects faces, objects, text, unsafe content.
- Use case: Security, content moderation, facial recognition.

---

## 🧠 Amazon Comprehend
- **Natural language processing (NLP)** service.
- Extracts insights from text: sentiment, key phrases, entities, language.
- Use case: Analysing customer reviews or support tickets.

---

## 📊 Amazon Forecast
- **Time-series forecasting** using ML.
- Fully managed – just provide historical data + related variables.
- Use case: Sales forecasts, demand planning.

---

## 🧮 Amazon Personalize
- **Personalized recommendations** (like Netflix or Amazon).
- Requires user interaction data.
- Use case: Product, content, or music recommendations.

---

## 🧾 Amazon Textract
- **Extracts text, tables, forms from scanned documents** (OCR with structure).
- Smarter than basic OCR – preserves layout.
- Use case: Automating form processing from PDFs.

- ## Amazon Mechanical Turk
- It’s a crowdsourcing platform.
- It’s used to get human-labeled data.
- It’s often used for tasks like image annotation or data validation.

- ## Amazon Augmented AI
- Human oversight of ML predictions in production
- These humans can be:
- Your own employees
- over 500.000 contractors from AWS, or AWS Mechanical Turk
- The ML model can be built on AWS or elsewhere (SageMaker, Rekognition...)

- ## Amazon Comprehend Medical & Transcreibe Medical
- The same two Amazon AI services but geared towards medical use cases
- Use NLP to detect protected health information (PHI)
- Can detect symptoms for example

- Amazon's Hardware for AI - EC2
- Stands for Elastic Compute Cloud = Infrastructure as a servicde
- Consists of the capability of:
- Renting virtual drives
- Storing data on virtual drives
- Knowing how EC2 works is fundamental to knowing how the Cloud works

- Now the ones for AI...
- GPU based EC2 instances, 
- AWS Tranium = ML chip built to perform Deep learning on 100B+ parameter models
- 50% cost reduction when training a model

- AWS Inferentia
- ML chip built to deliver inference at high performance and low cost

- Tranium and Inferentia has the lowest environmental footprint! Might come up in the exam
- EC2 instances are virtual servers and they can be of different types, GPU based types and AWS Tranium and AWS Inferentia
- Instance types

---

## Key Exam Tip
- Focus on **what each service does**, not how it’s built.
- Know basic **input/output** and **example use cases**.
