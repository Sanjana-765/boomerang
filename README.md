# AI Placement Assistant — V1

Responsive React + TypeScript + Tailwind app for placement resources, with server-side Groq AI extraction for PDFs and images.

## Run locally

```bash
npm install
npm run dev
```

Before starting, copy `.env.example` to `.env` and set `GROQ_API_KEY`. The key is read only by `server/index.js`, never by frontend code.

## Included flow

- Overview dashboard with company folders, recent resources, and deadlines
- Add resource with PDF/image upload or link tab
- Real AI-backed extraction from text-based PDFs and images
- Structured, validated placement details with a review-and-edit step
- Automatic organization using the user-confirmed company name
- Company resource folder and resource detail view with extracted metadata

The uploaded resource is processed in memory and not saved by the server. No authentication, RAG, embeddings, vector database, search, chatbot, notifications, or resume tracking are included.
