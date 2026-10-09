# AGORA AI PLATFORM 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![AI-Powered](https://img.shields.io/badge/AI-Gemini%20%7C%20OpenAI%20%7C%20Claude-orange)](https://ai.google.dev/)

**AGORA AI Platform** is an intelligent, modern document analysis and conversational AI workspace. It empowers users to upload documents (PDFs, research papers, reports), perform contextual chat and Q&A, generate automated executive summaries, manage multi-session conversational history, and customize AI model parameters with an intuitive, responsive interface.

---

## 🌟 Key Features

- 📄 **Smart PDF & Document Ingestion**  
  Upload and parse documents with real-time text extraction, tokenization, and vector retrieval.
- 💬 **Contextual AI Chat & Q&A**  
  Engage in real-time conversational intelligence with cited document references, streaming responses, and markdown code formatting.
- 📝 **Automated Document Summarization**  
  Generate multi-level executive summaries, key takeaways, and section-by-section breakdowns with a single click.
- 🗂️ **Session & History Management**  
  Maintain continuous workspace context with search, export, replay, and session branching.
- ⚙️ **Customizable AI Settings**  
  Configure system instructions, temperature, top-p parameters, API keys, and swap between leading model providers (Gemini, OpenAI, Anthropic).
- 🎨 **Sleek Modern UI**  
  Clean, ergonomic user interface engineered with modern React, TypeScript, and responsive styling.

---

## 📂 Project Architecture

The project is structured with scalability in mind, using a modular architecture:

```
AGORA-AI-PLATFORM/
├── apps/
│   └── web/
│       └── src/
│           ├── components/
│           │   ├── Chat.tsx            # Conversational message stream & prompt input
│           │   ├── SessionHistory.tsx  # Chat history, archives & session switcher
│           │   ├── Settings.tsx        # Model selection, temperature & API keys
│           │   ├── Sidebar.tsx         # Navigation bar & global state controls
│           │   ├── Summary.tsx         # AI summary card & key insights viewer
│           │   └── UploadPDF.tsx       # Drag-and-drop file ingestion & processing
│           ├── App.tsx                 # Main application view container
│           └── index.ts                # App entry point
├── .gitignore                          # Standard git ignore configuration
└── README.md                           # Documentation & project guide
```

---

## 🧩 Components Overview

| Component | Responsibility |
|---|---|
| [`Chat.tsx`](apps/web/src/components/Chat.tsx) | Handles chat input, message thread rendering, syntax highlighting, and AI streaming. |
| [`UploadPDF.tsx`](apps/web/src/components/UploadPDF.tsx) | Handles file dropzone, upload validation, extraction status, and document preview. |
| [`Summary.tsx`](apps/web/src/components/Summary.tsx) | Displays structured summaries, bulleted insights, TL;DR cards, and copy/export utilities. |
| [`SessionHistory.tsx`](apps/web/src/components/SessionHistory.tsx) | Displays previous chat and analysis sessions with filtering, rename, and delete actions. |
| [`Sidebar.tsx`](apps/web/src/components/Sidebar.tsx) | Primary navigation drawer for switching views, managing workspaces, and quick actions. |
| [`Settings.tsx`](apps/web/src/components/Settings.tsx) | Modal / panel for adjusting AI parameters, provider credentials, and interface themes. |

---

## 🛠️ Tech Stack

- **Frontend**: [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **AI Integrations**: Gemini API / OpenAI API / LangChain
- **Build System**: Vite / Next.js
- **Package Manager**: npm / pnpm / yarn

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
- **Node.js** (v18.0.0 or higher recommended)
- **npm**, **pnpm**, or **yarn**
- **Git**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BUNNY-RANGU/AGORA--AI-PLATFORM.git
   cd AGORA--AI-PLATFORM
   ```

2. **Navigate to the web app:**
   ```bash
   cd apps/web
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Configure Environment Variables:**
   Create a `.env` file in `apps/web/`:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   VITE_OPENAI_API_KEY=your_openai_api_key_here
   ```

5. **Run the development server:**
   ```bash
   npm run dev
   ```

6. **Open in browser:**
   Visit `http://localhost:5173` (or the port specified in terminal) to interact with the platform.

---

## 🗺️ Roadmap

- [x] Initial architecture and UI component scaffolds
- [ ] RAG (Retrieval-Augmented Generation) vector store pipeline
- [ ] Multi-document cross-comparison and comparative synthesis
- [ ] Audio/Voice multimodal Q&A integration
- [ ] Export session summaries to Markdown, PDF, and Notion
- [ ] Team collaboration and shared document workspaces

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📬 Contact & Support

Developed by [BUNNY-RANGU](https://github.com/BUNNY-RANGU).  
For questions, suggestions, or feedback, feel free to open an issue or pull request in the repository!
