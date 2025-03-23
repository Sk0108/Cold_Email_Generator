# ❄️ Cold Email Generator

An intelligent AI-powered tool to automate and generate highly personalized cold emails based on a user's LinkedIn or other public profile. This project leverages LLMs and NLP pipelines to streamline the process of generating outreach emails, saving valuable time for business development, marketing, and sales professionals.

---

## ✨ Features

- 🔍 Profile scraping and parsing (LinkedIn or custom input)
- 🧠 AI-powered email generation using large language models (LLMs)
- 🎯 Customizable tone and templates (e.g., formal, friendly, persuasive)
- 🔄 Generates multiple email variations for A/B testing
- 💬 Skill extraction & personalized hooks based on profile analysis
- ⚡ Supports batch processing for bulk outreach
- 🛠️ Modular and easy to extend for additional platforms and templates

---

## 🚀 Tech Stack

| Technology     | Purpose                                  |
|----------------|-------------------------------------------|
| **Python 3.x** | Core scripting & backend logic           |
| **Google Colab** | Development & testing environment       |
| **LangChain**  | Output parsing and integration with LLMs |
| **OpenAI API** | LLM-based email content generation       |
| **ChromaDB**   | Vector database for profile embeddings   |
| **BeautifulSoup / Scrapy** | Profile scraping (optional)   |
| **Pandas**     | Data processing and structuring          |
| **dotenv**     | Securely manage API keys & environment variables |

---

## 🧩 How it Works

1. **Profile Input**  
   Input can be a LinkedIn profile summary or structured data from a user profile.

2. **Skill Extraction & Embedding**  
   Extract key skills and context, then embed into a vector database using **ChromaDB**.

3. **Query & Retrieval**  
   Query relevant hooks, templates, and examples from the DB.

4. **Cold Email Generation**  
   Using **OpenAI GPT-4 / GPT-3.5**, generate highly tailored cold emails.

5. **Output**  
   Multiple email drafts ready for A/B testing and outreach.

---

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/Sk0108/Cold_Email_Generator.git
cd Cold_Email_Generator

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt
