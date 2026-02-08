## Project Overview

This project demonstrates **domain-specific fine-tuning of a Large Language Model (LLM)** using **LoRA (Low-Rank Adaptation)** to build a **customer support Q&A chatbot** for an ed-tech platform.
<img width="1355" height="552" alt="image" src="https://github.com/user-attachments/assets/7c9837d2-2058-4966-b4b5-26878c8b7de3" />

The model is fine-tuned on a custom dataset covering course information, enrollment, payments, refunds, certificates, login issues, and company details, enabling accurate and polite support-style responses while keeping GPU and memory usage low.

- **Base Model:** deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B  
- **Fine-tuning Method:** LoRA (PEFT) with TRL SFTTrainer  
- **Hardware:** Single 15GB GPU (Google Colab)  
- **Use Case:** Domain-specific support assistant (not open-domain chat)

---

## Dataset Information

The dataset is a **manually curated CSV** created specifically for this project, containing real-world styled **question–answer pairs** for an ed-tech platform.

- Focus areas: courses, payments, refunds, access issues, certificates, and company info  
- Small-data setting (≈100 samples) to showcase **efficient fine-tuning**
- 100% of data used for training, with 20% reused for validation due to limited size

**Dataset created by:** *Injamul Haque*

---

## Author

**Injamul Haque**  
AI / ML Engineer  
Focus: LLM fine-tuning, domain adaptation, and production deployment
