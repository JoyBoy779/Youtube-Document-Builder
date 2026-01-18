# YouTube Document Builder

A lightweight Python tool that converts YouTube video subtitles into a **.docx document**, making it easy to use long-form video content with **LLMs** for summarization, Q&A, and in-context learning — without relying on expensive APIs.

---

## Why This Tool Exists

In day-to-day life, we often watch **useful or educational content on YouTube**:
- Tech tutorials
- University lectures
- Podcasts
- Interviews
- Long explanations

But when we want an **LLM to work on that content**, we face two problems:

1. **LLM APIs are expensive** for long videos  
2. YouTube videos are **not directly usable as input**

This tool solves that by:
- Extracting the video transcript
- Saving it as a **.docx file**
- Letting you upload that document directly to an LLM for analysis

No API usage. No token burn.

---

## What It Does

- Takes a **YouTube URL or video ID**
- Accepts a **subtitle language** (if available)
- Extracts the full transcript
- Saves it as a **Word (.docx) file**

The output document is **LLM-ready**.

---

## Common Use Cases

### 📚 In-Context Learning with LLMs
- Convert long lectures into documents
- Upload to ChatGPT / Claude / Gemini
- Ask questions, generate notes, summarize concepts

---

### 🧠 Study & Revision
- Turn YouTube tutorials into readable study material
- Create summaries before exams
- Extract definitions, steps, and explanations

---

### 🎧 Podcasts & Talks
- Convert podcasts or interviews into text
- Quickly understand key points
- Ask LLMs to extract insights

---

### 💰 Avoid Expensive APIs
- No transcription APIs required
- No per-token billing
- Works fully offline after transcript extraction

---

### 🧩 RAG & Knowledge Base Preparation
- Use the document as input for:
  - Vector databases
  - Retrieval-Augmented Generation (RAG)
  - Personal knowledge systems

---

## Tech Stack

- Python
- youtube-transcript-api
- python-docx

---

## Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/github.com/JoyBoy779/Youtube-Document-Builder.git
cd Youtube-Document-Builder
```
### 2️⃣ Create a Virtual Environment
macOS / Linux
```bash
python3 -m venv venv
source venv/bin/activate
```
### 3️⃣ Install Requirements
```bash
pip install -r requirements.txt
```

## Usage
```bash
python script.py
```
You will be asked to:   
1. Enter a YouTube URL or video ID.  
2. Choose the subtitle language.  

A `.docx` transcript file will be generated automatically.

## Output
- Cleanly formatted Word document.    
- Ready to upload to any LLM.  
- Suitable for summarization, Q&A, and analysis.  

## Note

This tool is designed to be simple, practical, and cost-effective.
It bridges the gap between YouTube content and LLM-based learning.
