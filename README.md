# 🎓 GVIT College AI Chatbot

## 1. Project Overview

GVIT College AI Chatbot is a ChatGPT-like chatbot developed for a fictional college called **Green Valley Institute of Technology (GVIT)**.

The chatbot allows students to ask questions about:

- Courses
- Admissions
- Hostel
- Scholarships
- Placements
- Campus facilities
- Cafeteria
- College information

The chatbot uses a local Large Language Model (LLM) through **Ollama**, so an external OpenAI API key is not required.

---

# 2. Objective

The objective of this project is to build a simple AI chatbot that can:

1. Answer questions about a fictional college.
2. Provide responses based on a predefined college knowledge base.
3. Continue a conversation using previous questions and answers.
4. Provide a simple web-based chatbot interface.
5. Evaluate chatbot performance using predefined test questions.

---

# 3. Features

### 💬 Question Answering

Students can ask questions about the fictional college.

Example:

> What is the hostel fee?

The chatbot provides an answer using the college knowledge base.

### 🧠 Conversation Context

The chatbot remembers previous questions and answers during the current browser session.

Example:

**Student:**  
What is the hostel fee?

**Bot:**  
The hostel fee is ₹75,000 per year and includes mess facilities.

**Student:**  
What does it include?

**Bot:**  
It includes mess facilities.

The chatbot understands that "it" refers to the hostel fee.

### 🎓 College Knowledge Base

College information is stored in:

```text
data/college_data.json