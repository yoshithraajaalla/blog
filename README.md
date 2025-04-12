# Blog

## Resume Assistant with Gen AI
This is a Resume Assistant built as part of the **5-day Gen AI Intensive Course with Google (2025)**. It leverages cutting-edge generative AI to help job seekers improve their resumes by analyzing job descriptions, identifying gaps, and providing actionable feedback—all within a simple Jupyter Notebook.

---

#### 🚀 What This Project Does
Many job seekers struggle to tailor their resumes to specific job descriptions. Recruiters and ATS systems often miss out on great candidates simply because the resume doesn't reflect the language of the job post.
This Resume Assistant helps solve that by:
1. **Accepting resumes** (TXT, PDF, or DOCX) and **target job descriptions**.
2. **Parsing** the resume using `PyPDF2` and `python-docx`.
3. **Embedding** the content with **Gemini 2.0 Flash** and storing it in **ChromaDB**.
4. **Retrieving similar resumes** from the vector DB to provide context.
5. **Using few-shot prompting and RAG** to generate personalized critiques.
6. **Displaying feedback** in clean, user-friendly Markdown format.

---

#### 🛠️ How It Works
- **Document Understanding**: Extracts raw text from uploaded resumes.
- **Vector Search**: Embeds resumes using Gemini 2.0 Flash and stores them in ChromaDB for similarity search.
- **Few-Shot Prompting & RAG**: Retrieves relevant resumes and uses them in LLM prompts to generate detailed, tailored feedback.
- **Interactive Jupyter Notebook**: Easy to modify and re-run as needed.

---

#### 🤖 Why Use Generative AI?
- Understands context and nuance in resumes.
- Offers qualitative suggestions, not just keyword matching.
- Helps rewrite and refine resume content with role alignment in mind.

---

#### 💡 What I Learned
- **Prompt engineering** is critical to get high-quality outputs from LLMs.
- Gen AI tools work best as **co-pilots**, not full replacements.
- Combining multiple AI tools (document parsing, embedding, RAG) results in a powerful end-to-end system.

---

#### 📁 Try It Out
Want to explore the tool, test it out with your own resume, or build on top of it?
👉 [View the Kaggle Notebook](https://www.kaggle.com/code/yoshithraajaalla/resume-assistant-capstone-project)

---

#### 📌 Future Plans
- Add a simple web interface.
- Enable real-time feedback and live editing.
- Expand the vector database with curated, role-specific resumes.

---

#### 🧠 Summary
This project shows how generative AI can make job hunting smarter and more personalized. It's a practical tool built with real use cases in mind, and a strong starting point for future AI-powered career tools.
