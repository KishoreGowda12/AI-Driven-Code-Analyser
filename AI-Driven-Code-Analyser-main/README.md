# AI-Driven Code Analyzer

A web application powered by Next.js and the Gemini API to provide detailed explanations of code snippets. Simply paste your code, and the AI will analyze and explain it in simple, step-by-step language.

---

## 🚀 Features
- **AI-Powered Code Explanation:** Utilizes Google's Gemini API for accurate code explanations.
- **User-Friendly Interface:** Clean and minimal design for easy code input and reading explanations.
- **Responsive Design:** Works seamlessly across devices.

---

## 📂 Project Structure
```
├── src
│   ├── app
│   │   ├── layout.tsx        # Root layout with global styles
│   │   └── page.tsx          # Main code analyzer component
├── .env.local                # Environment variables (API key)
├── tailwind.config.js        # Tailwind CSS configuration
├── postcss.config.js         # PostCSS configuration
├── next.config.js            # Next.js configuration
└── package.json              # Project dependencies
```

---

## ⚙️ Installation and Setup

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/code-analyzer.git
cd code-analyzer
```

2. **Install dependencies:**
```bash
npm install
```

3. **Configure Environment Variables:**
Create a `.env.local` file in the root directory and add your Gemini API key:
```env
NEXT_PUBLIC_GEMINI_API=your_actual_api_key
```

4. **Run the development server:**
```bash
npm run dev
```

5. **Open your browser:**
Visit [http://localhost:3000](http://localhost:3000) to access the app.

---

## 🛠️ Technologies Used
- **Next.js:** React framework for server-side rendering.
- **TypeScript:** For static type-checking.
- **Tailwind CSS:** For styling and responsive design.
- **Gemini API:** To provide AI-driven code explanations.

---

## 💡 Usage
1. Paste your code into the provided text area.
2. Click the "Explain Code" button.
3. View the detailed explanation generated by the AI.

---

## 🐞 Troubleshooting
- **Missing Modules:** If you encounter module errors, delete `node_modules` and `package-lock.json` and reinstall:
```bash
rm -rf node_modules package-lock.json .next
npm install
```

- **API Key Errors:** Ensure the `.env.local` file has the correct API key and restart the development server.

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements.

---

## 🙏 Acknowledgements
- [Google Gemini API](https://ai.google.dev/) for AI-powered content generation.
- [Next.js](https://nextjs.org/) for the robust web framework.
- [Tailwind CSS](https://tailwindcss.com/) for utility-first styling.

# AI-Driven-Code-Analyser
