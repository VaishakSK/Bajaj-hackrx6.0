# 📄 LLM Document Processing System

A smart system that leverages **Large Language Models (LLMs)** to process natural language queries and retrieve relevant information from **large unstructured documents** such as policy documents, contracts, and emails.

---

## 🚀 Objective

Given a **query** like:

> `"46-year-old male, knee surgery in Pune, 3-month-old insurance policy"`

The system should:

1. **Parse & Structure** the query into key fields (age, procedure, location, policy duration, etc.).
2. **Search & Retrieve** relevant clauses from documents using **semantic understanding** (not just keyword matching).
3. **Evaluate** the retrieved information to determine:
   - ✅ Decision (e.g., approved / rejected)
   - 💰 Amount (if applicable)
   - 📝 Justification with references to document clauses.
4. **Return** the result in a **structured JSON** format for easy integration into downstream systems.

---

## ❓ What is a Query?

In this system, a **query** is:
- A **short text input** from the user  
- Written in **plain, natural language** (can be incomplete or vague)  
- Contains **key information** for decision-making
