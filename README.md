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
# optional, default duration is 8 hours/480 minutes. Max duration is 30 days/43200 minutes.
hf_oauth_expiration_minutes: 480
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

# 🤖 GAIA Benchmark Agent | Hugging Face Agents Course

## 🎯 Project Overview
This repository contains an implementation of an AI agent designed to tackle the GAIA benchmark, focusing specifically on Level 1 questions. The project is part of the Hugging Face Agents Course Final Assignment.

## 🏗️ Architecture
- **Agent Framework**: LangGraph for reliable agent orchestration
- **Language Model**: Mixtral-8x7B via HF Inference API
- **Interface**: Gradio UI for easy interaction
- **Tools**: Free, open-source tools for web search, math, and text processing

## 🛠️ Core Features
- Web search using DuckDuckGo
- Basic mathematical operations
- File handling and text processing
- Answer validation and formatting
- Optional: Image analysis (if core is stable)

## 🚀 Getting Started

### Prerequisites
```bash
# Install dependencies
pip install -r requirements.txt
```

### Running the Agent
```bash
# Start the Gradio interface
python app.py
```

## 📊 Performance Goals
- Primary Target: 20-25% accuracy on GAIA Level 1
- Stretch Goal: Push towards 30% if core is stable
- Focus on reliability and consistent results

## 🔧 Technical Stack
- **Core**: Python, LangGraph, LangChain
- **API**: Hugging Face Inference API
- **Search**: DuckDuckGo + BeautifulSoup
- **UI**: Gradio

## 🤝 Contributing
This is a course project, but suggestions and improvements are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request

## 📝 License
MIT License - feel free to use this code for your own projects!

## 🙏 Acknowledgments
- Hugging Face for the excellent Agents Course
- GAIA benchmark team for the evaluation framework
- Open-source community for the tools and libraries

---
> 🔍 Part of the [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) Final Assignment