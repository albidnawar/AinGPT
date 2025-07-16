# 🧠 AinGPT – AI-Powered Bengali Legal Document Analyzer & Chatbot

**AinGPT** is a powerful AI platform built to digitize, analyze, and simplify Bengali legal documents—especially historical and handwritten ones. It leverages OCR, NLP, and AI chatbot technologies to modernize legal processes in Bangladesh and empower lawyers, researchers, students, and the general public.

---

## 🚀 Features

- 📄 **Handwritten & Typed Bengali OCR**
  - Supports both printed and handwritten legal documents
  - Uses `bbOCR` for standard Bengali text
  - Custom model in training for handwritten historic contracts

- 🧠 **Legal NLP Engine**
  - Summarizes and translates old-style Bengali legal documents into modern Bengali and English
  - Detects key clauses, flags risky/missing sections

- 🔍 **Clause Analysis & Suggestions**
  - Identifies common clauses like indemnity, arbitration, liability, etc.
  - Suggests corrections and additions based on legal best practices

- 🤖 **AI Legal Chatbot (AinBot)**
  - Trained on Bangladesh Constitution, contract law, and legal precedents
  - Responds to user queries in Bengali and English
  - Can extract and explain clauses from uploaded documents

- 🎙️ **Voice Input Support**
  - Users can ask legal questions or dictate contracts via voice

- 📊 **Law Firm Dashboard**
  - Upload, analyze, and store multiple documents
  - Access bulk tools and export reports

- 🪙 **Token-Based Access System**
  - Free tier for students and basic users
  - Token purchase for advanced features (clause suggestion, summaries, chatbot API)

- 📚 **Legal Education & Training Module** *(Coming Soon)*
  - Learn contracts, legal clauses, and case laws interactively

---

## 📦 Tech Stack

| Layer           | Technologies Used                              |
|----------------|-------------------------------------------------|
| Frontend        | Flutter (Mobile) / React (Web)                 |
| Backend         | FastAPI / Django                               |
| OCR             | bbOCR, Custom CNN/LSTM Models                  |
| NLP             | HuggingFace Transformers, IndicNLP             |
| Chatbot         | LangChain, RAG, Constitution Dataset (BD)      |
| Storage         | PostgreSQL, Firebase (optional)                |
| Deployment      | Docker, Render / Heroku / Railway              |

---

## 🎯 Target Users

- ⚖️ Law firms & legal professionals  
- 🏛️ Government & regulatory agencies  
- 👨‍🎓 Legal students & educators  
- 📄 Contract analysts in corporations  
- 🧑‍💻 NGOs & citizen legal aid groups

---

## 🗓️ Project Timeline (2025)

| Milestone                             | Status      |
|--------------------------------------|-------------|
| UI/UX Frontend Design                | ✅ Completed |
| bbOCR Integration                    | ✅ Completed |
| Handwritten OCR Model Training       | 🔄 Ongoing   |
| Chatbot with Constitution + Clause DB| 🔄 Ongoing   |
| Voice Input System                   | 🔄 In Progress |
| Token-Based Access System            | 🔜 Upcoming  |
| Legal Education Module               | 🔜 Upcoming  |

---

## 📂 Folder Structure (Planned)

```bash
AinGPT/
├── backend/
│   ├── api/
│   ├── ocr/
│   ├── nlp/
│   └── chatbot/
├── frontend/
│   ├── web/
│   └── mobile/
├── data/
│   ├── handwritten_samples/
│   └── legal_corpus/
├── models/
├── docs/
└── README.md
