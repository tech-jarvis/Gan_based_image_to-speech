# 🎭 Image to Story Narrator - AI-Powered Image Analysis & Storytelling

Transform any image into an engaging audio story using the power of multiple AI models! This innovative tool combines image analysis, creative storytelling, and voice synthesis to bring your pictures to life.

## ✨ Try It Now!

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://image-to-speech-genai-tool-using-llm.streamlit.app/)

## 🎯 What It Does

This application creates a unique audio narrative from any image through a three-stage AI pipeline:

1. **📸 Image Analysis** 
   - Uses [Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)
   - Extracts detailed scene description from your image

2. **✍️ Story Generation**
   - Powered by OpenAI's [GPT-3.5 Turbo](https://platform.openai.com/docs/models/gpt-3-5)
   - Crafts a creative 50-word story based on the image context

3. **🎙️ Voice Synthesis**
   - Leverages [espnet/kan-bayashi_ljspeech_vits](https://huggingface.co/espnet/kan-bayashi_ljspeech_vits)
   - Converts the story into natural-sounding speech

## 🎬 Demo Showcase

![Family Story Demo](img-audio/FamilyOutput.jpg)

*Audio samples for these demos are available in the `img-audio` folder*

## 🛠️ Setup & Installation

### Prerequisites
- Python environment
- OpenAI API key
- Hugging Face API token

### Quick Start

1. **Clone the Repository**
   ```bash
   git clone https://github.com/tech-jarvis/Gan_based_image_to-speech.git
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure API Keys**
   Create a `.env` file:
   ```env
   OPENAI_API_KEY=your_openai_key_here
   HUGGINGFACE_API_TOKEN=your_huggingface_token_here
   ```

4. **Launch the App**
   ```bash
   streamlit run app.py
   ```

## 📚 Required Libraries

- os
- python-dotenv
- transformers
- torch
- langchain
- openai
- requests
- streamlit

## 🚀 Usage Guide

1. Launch the application
2. Upload your image
3. Wait a few moments while the AI:
   - Analyzes your image
   - Generates a creative story
   - Synthesizes the audio narration
4. Enjoy your personalized audio story!

## 🌟 Deployment Options

The application is available on:
- Streamlit Cloud
- Hugging Space Cloud

## 💡 Tips

- Ensure your API tokens are properly configured
- Set up a virtual environment with ipykernel for local development
- Allow a few minutes for the complete processing pipeline


