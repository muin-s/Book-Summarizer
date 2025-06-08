# GPT Book Summarizer

## 🔍 About  
**GPT Book Summarizer** is an automated tool that leverages the **GPT-3.5 Turbo** model and **recursive meta summarization** techniques to generate concise and high-quality book summaries.

---

## ✨ Key Features

- **Recursive Meta Summarization**  
  Implements a layered summarization strategy to refine content through multiple passes.

- **Token Limit Management**  
  Dynamically manages input/output token counts to stay within model constraints.

- **Caching Mechanism**  
  Stores and retrieves summaries to improve performance and recover from failures.

- **Rate Limit Control**  
  Custom logic to handle OpenAI's rate limits and ensure request reliability.

---

## 🛠 Tech Stack

- **Language Model**: GPT-3.5 Turbo  
- **Programming Language**: Python  
- **Key Libraries**: `openai`, `python-dotenv`, `requests`, `tiktoken`

---

## 📘 Example Use Case

**Test Case**: *The Great Gatsby*  
Used as a benchmark book to demonstrate and validate the summarization process.

---

## ⚙️ Setup Instructions

1. **Create and Activate Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate
