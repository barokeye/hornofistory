
# Horn of History

Horn of History is a modern, AI-powered educational web app that allows users to explore the rich and diverse history of the world. From ancient civilizations to contemporary events, this app uses OpenAI's language model to answer historical questions and explain key topics.

## 🌍 Features

- 🔎 Search historical topics and titles with AI assistance
- 🤖 Built-in chatbot to ask history-related questions
- 🗂️ Tabbed navigation across historical eras
- 📜 Summary cards of major historical topics
- 🌐 Web-only interface, deployable on Vercel or Firebase

## 🛠️ Technologies

- React (with Vite)
- Tailwind CSS
- OpenAI API (via a custom backend route)
- Deployed via Vercel or Firebase Hosting

## 🧪 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/horn-of-history.git
   cd horn-of-history
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create a `.env` file** and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your-openai-key
   ```

4. **Run the app locally**
   ```bash
   npm run dev
   ```

## 🚀 Deployment

### Deploy to Vercel
- Push this code to GitHub
- Go to [vercel.com/import](https://vercel.com/import)
- Import your repo and deploy with:
  - **Framework**: Vite
  - **Output directory**: `dist`
  - **Environment variable**: `OPENAI_API_KEY`

### Deploy to Firebase
- Run `npm run build`
- Follow Firebase CLI setup
- Deploy to Firebase Hosting

## 📩 Contact

Built by Barok Kassa (getenetbarok@gmail.com)

---

> Made with ❤️ to help the world learn its shared story.
