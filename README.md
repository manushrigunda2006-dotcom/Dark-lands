🛡️ DARK LANDS

Understand Before You Sign.

A privacy-focused AI-powered legal document triage assistant.

DARK LANDS aims to make complex legal documents easier to understand by identifying important clauses, obligations, deadlines, and potentially concerning terms through AI-powered document analysis.

📌 Problem Statement

Legal documents such as rental agreements, contracts, and government documents often contain complex terminology and lengthy paragraphs. Many people struggle to identify important conditions, deadlines, penalties, and obligations, which can lead to misunderstandings before signing an agreement.

The challenge is to build a privacy-focused legal document assistant that helps users understand documents efficiently while protecting sensitive information.

💡 Our Solution

DARK LANDS is designed to help users review legal documents through a simple, accessible interface. Users can upload supported documents, explore important clauses, ask questions, and review evidence from the original text.

The project aims to use a locally running, hackathon-approved Gemma model to analyse document contents while prioritising privacy, evidence grounding, and responsible AI behaviour.

✨ Key Features

- AI Document Analysis: Generate plain-language summaries and identify important information.
- Clause Compass: Explore potentially concerning clauses, unclear terms, and obligations.
- Evidence & Citations: Connect findings to supporting document passages.
- Ask My Document: Ask questions about an uploaded document.
- Document Comparison: Compare two documents to identify textual differences.
- Obligation Timeline: Organise relevant dates, deadlines, and responsibilities.
- Privacy Centre: Explain document processing and data storage.
- AI Safety Guardrails: Handle uncertainty and avoid unsupported legal claims.
- Responsive Interface: Simple light-blue and white design for desktop and mobile.

Note: Features are planned capabilities unless they have been implemented and tested in the current version.

🖥️ Technology Stack

The intended technology stack includes:

- Frontend: HTML, CSS, JavaScript; Next.js, React, and TypeScript for the full application where applicable.
- AI Model: Gemma, using a verified model version accepted by the hackathon.
- Local Inference: Ollama or another compatible local runtime, if configured.
- Document Processing: PDF and TXT text extraction.
- Backend: Server-side API routes for document processing and AI inference.

The exact stack should be updated to match the implementation in this repository.

🔄 How It Works

1. The user uploads a supported legal document.
2. The application extracts readable text.
3. The configured Gemma model analyses the document.
4. The system validates findings and supporting evidence.
5. The user reviews summaries, clauses, obligations, and answers.

🔐 Privacy and AI Safety

DARK LANDS is designed with privacy and responsible AI use in mind.

- Prefer local processing for sensitive document contents.
- Keep model configuration and secrets out of frontend code.
- Ground document-specific answers in the uploaded document.
- Verify quotations and page references where available.
- Communicate uncertainty when evidence is insufficient.
- Avoid inventing clauses, penalties, or deadlines.
- Protect document access and support appropriate data deletion.

Privacy claims depend on the actual deployment, storage, and network architecture.

🚀 Getting Started

Prerequisites

Install the tools required by the actual implementation, such as:

- Git
- Node.js and npm, if the project uses a Node.js framework
- A compatible local Gemma inference runtime, if required

Installation

Clone the repository:

git clone YOUR_PUBLIC_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER

Install dependencies if the project has a "package.json":

npm install

Configure the required environment variables using the project's ".env.example" file, if provided.

Start the development server if supported:

npm run dev

For a standalone HTML prototype, open the HTML file in a browser instead. The commands above apply only to a compatible Node.js application.

🧪 Testing

Test the application with non-sensitive sample documents.

Important checks include:

- PDF and TXT extraction.
- AI analysis and response validation.
- Evidence and citation verification.
- Handling of missing information.
- Unavailable model and timeout errors.
- Document privacy and access controls.
- Responsive layout and navigation.

Only report tests as passed after they have actually been run.

⚠️ Limitations

- AI-generated analysis may contain errors.
- Scanned PDFs may require OCR.
- Local model performance depends on hardware and configuration.
- Evidence verification depends on successful text extraction.
- Legal interpretation may depend on jurisdiction and context.
- The application is not a substitute for advice from a qualified lawyer.

🗺️ Future Improvements

- Improve document extraction and OCR.
- Add multilingual explanations.
- Improve document comparison.
- Add verified legal-source integrations.
- Improve latency and large-document handling.
- Expand automated safety and privacy tests.

⚖️ Disclaimer

DARK LANDS is an informational tool intended to help users understand legal documents. It does not provide definitive legal advice and does not replace consultation with a qualified legal professional.

📄 License

Add the appropriate open-source license after choosing one for this repository.

---

DARK LANDS — Understand Before You Sign.
