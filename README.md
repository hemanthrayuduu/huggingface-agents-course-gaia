---
title: Template Final Assignment
emoji: 🕵🏻‍♂️
colorFrom: indigo
colorTo: indigo
sdk: gradio
sdk_version: 5.25.2
app_file: app.py
pinned: false
hf_oauth: true
hf_oauth_expiration_minutes: 480
short_description: Agent for GAIA Evaluation
---

# 🧠 Agent for GAIA Evaluation

This project contains a Gemini-powered CodeAgent built with [smolagents](https://github.com/smol-ai/smol-agents) for use 
in the **GAIA Unit 4 Evaluation**  of the [Hugging Face Course](https://hf.co/learn/agents-course/unit0/introduction).

> 🧑‍🏫 This app is part of the **Hugging Face Courses** series and was developed as an educational project to showcase how machine
> learning can be used in real-world event scenarios. Learn more at [Hugging Face Courses](https://huggingface.co/learn).
---

### 🗂 Folder Structure

```
Template Final Assignment_app/
│
├── app.py                       # Main app with Gradio UI and agent execution logic.
├── gaia_tools                   # Custom tools including RunPythonFileTool and download_server.
├── .env.template                # Environment variables template /Template file showing expected environment variables (e.g., API keys).
├── requirements.txt             # Python dependencies. 
└── README.md                    # Project overview, setup instructions, usage examples.
```


## 🚀 Features

* Uses the **Gemini 2.0 Flash** model via `LiteLLMModel`
* Equipped with essential tools:

  * `DuckDuckGoSearchTool` for quick lookups
  * `RunPythonFileTool` for executing `.py` scripts
  * `ReverseTextTool` for decoding reversed questions
  * `download_server` for fetching files from URLs
  * Base tools (math, string manipulation, etc.)

## 📋 Evaluation Strategy

The agent reads questions from the GAIA evaluation endpoint, applies reasoning using a system prompt with strict 
guidelines, and submits answers back for scoring.


## 🛠️ Setup

1. Clone this repository or Space
2. Set your environment variables:

   ```
   GEMINI_API_KEY=your_api_key_here
   SPACE_ID=your_hf_space_id
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run locally:

   ```bash
   python app.py
   ```

Or launch directly via [Hugging Face Spaces](https://huggingface.co/spaces/).

## 🧪 Evaluation Flow

1. Log in to Hugging Face through the UI
2. Click “Run Evaluation & Submit All Answers”
3. The agent will fetch tasks, solve them, and submit results


---
## 🤝 Contributing

We welcome contributions to improve GalaGuide!

1. Fork the repository  
2. Create a new branch:
   ```bash
   git checkout -b feature-xyz















Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference