#  LingoStudy.AI
### Multilingual PDF Study Companion

[![A_Award_Target](https://img.shields.io/badge/Target_Category-AI_for_Education-blueviolet?style=for-the-badge&logo=academia)](https://github.com)
[![B_Award_Target](https://img.shields.io/badge/Target_Category-Best_Web_AI_App-blue?style=for-the-badge&logo=googlechrome)](https://github.com)
[![C_Award_Target](https://img.shields.io/badge/Target_Category-Most_Impactful-green?style=for-the-badge&logo=target)](https://github.com)

LingoStudy.AI is an advanced full-stack web application designed to break the global language barrier in modern education. The platform empowers students to upload complex English textbooks, research papers, or documentation PDFs and interactively study them entirely in their preferred local or international language (e.g., German, French, Spanish, Arabic, Urdu, Sindhi, and more).

---

## Key Features

*   ** Multi-Language RAG Dashboard:** Upload any English academic PDF and converse with it in 10+ major international and regional languages.
*   ** AI Executive Summary:** Instantly generates a high-level, comprehensive summary of the uploaded document right upon upload in the selected target language.
*   ** Smart Glossary Mapping:** Automatically extracts difficult English technical terms and maps them side-by-side with their contextual definitions and translations in the chosen language.
*   ** AI Flashcard Generator:** Dynamically creates flippable digital study cards for key concepts, allowing students to test active recall and flag cards as "Mastered" or "Review Later".
*   ** Voice-to-Voice Learning (Audio Support):** 
    *   **Speech-to-Text:** Features a built-in microphone integration allowing students to speak their queries naturally instead of typing.
    *   **Text-to-Speech:** Includes audio playback for all AI responses to assist students with proper pronunciation and auditory learning.
*   ** Automated Quiz Generator:** Creates dynamic multiple-choice questions (MCQs) directly from the PDF content with an integrated "Explain Mode" that breaks down why an answer is right or wrong.
*   ** Progress & Analytics Tracker:** A visual micro-dashboard showing the user's quiz metrics, reading completion estimation, and overall content mastery.

---

##  Tech Stack & Architecture

LingoStudy.AI is built using a highly scalable and decoupled full-stack architecture:

*   **Frontend:** React.js, Tailwind CSS, Vite (Optimized for lightning-fast state management and clean UI layout components).
*   **Backend Orchestration:** Node.js / Python processing simulation environment.
*   **AI Integration:** Robust LLM system prompting pipelines leveraging advanced multi-language models (OpenAI GPT-4o / Google Gemini API).
*   **Data Pipeline:** Advanced document text extraction and Retrieval-Augmented Generation (RAG) simulation logic.

---

##  Project Structure

```text
├── src/
│   ├── components/       # Core UI Windows (Sidebar, Chat, Glossary, Quiz, Cards)
│   ├── context/          # Global application state (Language configuration, PDF parsing)
│   ├── hooks/            # AI API integration hooks (Speech handlers, LLM request streams)
│   └── App.jsx           # Main application layout shell
├── public/               # Static assets, fonts, and icon packs
├── package.json          # Project node dependencies
└── README.md             # Project documentation
