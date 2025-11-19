Project 1 – AI Career Advisor (Prompt Engineering)

Overview
This project is part of the Generative AI & LLMs assignment.
The goal is to build an AI Career Advisor chatbot using only Prompt Engineering, without external datasets or APIs.

It demonstrates:

Role-based prompts

Instruction-style prompts

Few-shot examples

Prompt refinement

Testing model responses

 I use a local LLM such as Llama 3, Mistral 7B, or Phi-3 Mini, loaded through an inference library like ollama or transformers.
 

📁 Folder Structure
Project1_PromptEngineering/
│── Project1_AI_Career_Advisor.ipynb
│── README.md


Goal of the Project

To create a structured prompt that makes an LLM behave like a Career Advisor, offering:

Resume suggestions

Career path guidance

Skill development advice

Interview preparation tips


Prompt Design

The project includes 3 key prompt types:

1️ Role-Based Prompt (System Message)

Defines the identity and behavior of the AI Career Advisor.

2️ Instruction-Based Prompt

Tells the model what tasks it must perform.

3️ Few-Shot Prompt

Provides input–output examples to guide consistent responses.

I also include iterative prompt refinement, showing:

Initial prompt version

Improved prompt version

Difference in model behavior


How to Run the Notebook
🔹 Step 1: Install Python & Create Virtual Environment
python -m venv .venv


Activate environment:

Windows

.venv\Scripts\activate

🔹 Step 2: Install Required Libraries
pip install jupyter notebook transformers accelerate


If using Ollama for a local model:

pip install ollama

🔹 Step 3: Run Jupyter Notebook
jupyter notebook


Open:

Project1_AI_Career_Advisor.ipynb


Dependencies

Python 3.10+

Jupyter Notebook

Transformers / Ollama (depending on your model)

Install with:

pip install -r requirements.txt
