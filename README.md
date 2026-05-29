# Compound Chat AI

**Privacy-first, zero-cost-to-launch AI chatbot SaaS platform**

Embed a powerful AI chatbot on your website with all knowledge stored securely in your Google Drive.

---

## 🚀 Features

- **100% Private**: All documents stay in your Google Drive
- **Easy Embed**: Single script tag (~15KB lightweight widget)
- **AI-Powered**: Groq API (primary) + DeepSeek (fallback)
- **Smart Fallback**: Rule-based responses after 30 free conversations
- **Free Integrations**: Webhooks, Google Sheets export, email notifications
- **Simple Dashboard**: Manage widgets, track usage, connect Drive

---

## 📋 Tech Stack

- **Frontend/Dashboard**: Next.js 15 + TypeScript + Tailwind CSS
- **Widget**: Lightweight vanilla JavaScript + Web Components
- **Backend**: Next.js API Routes
- **Auth & Database**: Supabase (Free tier)
- **LLM**: Groq + DeepSeek
- **RAG**: LlamaIndex (coming soon)
- **Hosting**: Vercel + Supabase

---

## 🛠️ Installation

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Supabase account
- Google OAuth credentials

### Local Setup

```bash
git clone https://github.com/BrotherKayman/compound-chat.git
cd compound-chat
npm install
cp .env.example .env.local
npm run dev
```

Visit `http://localhost:3000`

---

## 📚 Project Structure

```
src/
├── app/
│   ├── page.tsx              # Landing page
│   ├── login/                # Login page
│   ├── signup/               # Signup page
│   └── dashboard/            # User dashboard
├── components/               # Reusable components
├── pages/api/                # API routes
├── lib/                      # Utilities
└── styles/                   # Global styles
```

---

## 🚀 Deployment

```bash
vercel deploy
```

---

## 📄 License

MIT License - see LICENSE file

Built by **M Creative Compound**
