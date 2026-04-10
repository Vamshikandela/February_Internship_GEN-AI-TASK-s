
#  GenAI Prompt Engineering Assignment (LangChain)

## Overview

This project focuses on building a dynamic and reusable prompt system using LangChain instead of hardcoded prompts. The goal is to design flexible prompt templates that can handle multiple inputs, support different styles, and follow a structured pipeline.

---

##  Objective

- Replace hardcoded prompts with reusable templates
- Build dynamic prompt systems using LangChain
- Implement structured prompt pipelines
- Add input validation for robustness
- Ensure modular and clean code design

---

##  Tech Stack

- Python
- LangChain
- Jupyter Notebook

---

## Tasks Implemented

###  Task 1: Replace Hardcoded Prompt
Converted a static prompt into a reusable `PromptTemplate`.

---

### Task 2: Multi-Input Prompt System
Created a template that accepts:
- Topic
- Audience
- Tone

---

###  Task 3: Prompt Variations Engine
Designed multiple prompt styles:
- Teaching
- Interview
- Storytelling

---

###  Task 4: ChatPromptTemplate System
Implemented role-based prompts:
- Teacher
- Interviewer
- Motivator

---

###  Task 5: Input Validation Layer
Added validation logic to ensure:
- Audience is valid
- Tone is valid  
Fallback defaults are applied when needed.

---

### Task 6: Prompt Generator Function
Built a unified function that:
- Validates inputs
- Selects style
- Generates dynamic prompts

---

###  Task 7: Template Reusability Test
Used a single template with multiple inputs to verify reusability.

---

## Pipeline Flow

User Input → Validation → Prompt Template → Generated Output

---

## How to Run

1. Install dependencies:
   bash
   pip install langchain==0.1.17


## 👤 Author

Vamshi
- Aspiring Data Scientist
- Focused on building real-world AI projects
- Interested in Generative AI and Machine Learning
