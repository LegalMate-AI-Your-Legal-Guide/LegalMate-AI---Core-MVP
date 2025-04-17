# ⚖️ LegalMate AI – Core MVP

LegalMate AI is an AI-powered legal assistant tailored to provide general legal information based on Indian laws. This Minimum Viable Product (MVP) is designed to bridge the awareness gap around legal rights and procedures by offering accessible, localized, and AI-generated insights. The project aims to empower users with general understanding, especially those without easy access to legal counsel.

> 🚨 **Disclaimer**: This project is in the early MVP stage. All AI responses are informational and do not constitute legal advice or replace consultation with a licensed legal practitioner.

---

## 🔥 Key Features

- 💬 **AI Chat Interface** – Ask questions about Indian laws and receive AI-generated responses in seconds.
- 🇮🇳 **India-Specific Legal Context** – Custom-tuned prompts to generate information aligned with Indian Penal Code (IPC), Criminal Procedure Code (CrPC), RTI Act, IT Act, and more.
- 🧾 **Predefined Legal Categories** – Easily explore topics like police rights, property law, cybercrime, workplace rights, traffic fines, RTI, family law, etc.
- 🌐 **Multilingual Support (Planned)** – Future support for Hindi, Kannada, and English to ensure linguistic inclusivity.
- ⚖️ **Built-in Legal Disclaimers** – Every response includes a clearly marked disclaimer to emphasize its informational nature.
- 🔐 **Freemium-Ready Architecture** – Built with future monetization and tiered access models in mind.
- 📊 **Analytics Hooks (Optional)** – Designed to support basic user analytics and behavioral data integration (e.g., Google Analytics, PostHog).
- 👥 **Scalable Authentication System (Planned)** – JWT/Firebase-based user authentication and session management.

---

## 🧠 Prompt Tuning Strategy

To ensure contextual accuracy and user-friendly responses, LegalMate AI uses the following prompt-tuning strategy:

- Inject Indian legal knowledge across criminal, civil, cyber, and consumer laws.
- Use neutral, fact-based tone to avoid bias or opinionated responses.
- Answer using layman's language to make legal content digestible.
- Each response automatically includes a disclaimer for clarity.

### 🔰 Example System Prompt

```
You are LegalMate AI, a legal assistant trained on Indian laws. 
You provide general legal information to help users understand their rights under Indian jurisdiction. 
You never provide legal advice, do not make case-specific judgments, and always include a disclaimer that legal advice must be obtained from a licensed professional.
```

---

## 🛠️ Tech Stack

| Layer       | Stack                        |
|-------------|------------------------------|
| Frontend    | React.js (Vite or Next.js)   |
| Backend     | Node.js + Express.js         |
| AI Service  | OpenAI GPT-4 (API-based)     |
| Styling     | TailwindCSS / CSS Modules    |
| State Mgmt  | React Hooks / Context API     |
| Auth (Planned) | Firebase Auth / JWT       |
| Deployment  | Vercel (frontend), Render/Railway (backend) |
| Analytics (Optional) | PostHog / Google Analytics |

---

## 📁 Project Structure

```
legalmate-ai-core-mvp/
├── client/              # React Frontend
│   ├── components/      # Reusable UI components
│   ├── pages/           # Pages/Routes (Next.js or Vite)
│   ├── assets/          # Icons, images, etc.
│   └── ...
├── server/              # Node + Express Backend API
│   ├── routes/          # Route handlers
│   ├── controllers/     # Request processing logic
│   ├── services/        # API services (OpenAI, etc.)
│   └── ...
├── prompt-engine/       # Prompt templates and tuning logic
├── data/                # Sample prompts, FAQ categories
├── .env.example         # Example environment config
├── README.md
└── LICENSE
```

---

## ⚙️ How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/legalmate-ai-core-mvp.git
cd legalmate-ai-core-mvp
```

### 2. Setup Environment Variables

```bash
cp .env.example .env
```

Update `.env` with your **OpenAI API Key** and other environment variables for Express.js and frontend (e.g., port, API base URL).

### 3. Run Backend Server

```bash
cd server
npm install
npm run dev
```

The backend will start on: `http://localhost:5000`

### 4. Run Frontend Client

```bash
cd ../client
npm install
npm run dev
```

Frontend will run at:  
🌐 `http://localhost:3000`

---

## 🚀 Roadmap (Planned Features)

- [x] AI Chat Interface
- [x] Legal Disclaimer Integration
- [ ] User Authentication (JWT / Firebase)
- [ ] Multilingual Input and Response (Kannada, Hindi)
- [ ] User Feedback & Ratings for AI Answers
- [ ] Bookmark / Save Q&A
- [ ] Subscription & Premium Access Tiers
- [ ] Admin Dashboard for Usage Analytics
- [ ] Integration with Legal Aid Resources

---

## 📄 Legal Disclaimer

LegalMate AI is a **general-purpose educational and informational platform**. It does **not** offer legal advice, legal representation, or act as a substitute for qualified legal consultation.

For any legal matter or dispute, **always consult a certified legal professional or advocate licensed to practice law in your jurisdiction.**

---

## 🌍 Vision

To democratize access to legal awareness for over **600 million Indians** who lack access to reliable legal counsel. By combining AI, vernacular language support, and open access principles, LegalMate AI strives to build a world where understanding your rights is not a privilege but a basic utility.

---

## 📦 Contributing

Want to contribute to LegalMate AI?

We welcome:

- 🧠 Prompt Engineers – To improve AI output relevance
- 👨‍⚖️ Legal Experts – To validate Indian legal context
- 💻 Developers – To build features and squash bugs
- 🌐 Translators – To enable multilingual support
- 📢 Marketers – To increase reach and public access

> Contributions, feedback, and feature requests are welcome!  
> Feel free to open an issue or pull request.

---

## 📧 Contact

**Made with ❤️ by [Ramu R]**

Want to contribute, collaborate, or support?

- Email: ramuconnect45@gmail.com  
- Linkedin: [Ramu R](www.linkedin.com/in/ramu-r-nayak1904)  
- GitHub: [github.com/ramu1904](https://github.com/ramu1904)

---

## 📜 License

MIT License.  
Please refer to the `LICENSE` file for full license details.

---
