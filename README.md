# CHEFAI - Intelligent Cooking Assistant

**Description:**
This repository contains the `chefaI_gradio_interface.py`, a simple Gradio-based cooking assistant designed for Google Colab. It integrates multiple LLMs (OpenAI GPT-4o, Anthropic Claude, Google Gemini) and GPT-4 Vision to allow users to:

- **Manage ingredients:** Add manually or via image analysis
- **Set preferences:** Dietary restrictions and cuisine type
- **Generate recipes:** Based on current ingredients and preferences
- **Modify recipes:** Request adjustments (e.g., make it spicier)
- **Ask cooking questions:** Get practical advice with context

**Project Context:**
This project was created as the final assignment for a Generative AI course. It demonstrates:

1. **Multimodal AI integration:** Text and vision-based inputs for ingredient recognition
2. **Multi-LLM routing:** Using different LLMs for recipe generation, Q&A, and routing logic
3. **Interactive web UI:** Gradio interface for real-time user interactions

**Usage:**
1. Upload this script to Colab.
2. Uncomment the pip install line and run the cell to install dependencies.
3. Set your API keys in Colab secrets (`OPENAI_API_KEY`, optional `CLAUDE_API_KEY`, `GEMINI_API_KEY`).
4. Run the script and open the Gradio share link to interact with ChefAI.

**Files:**
- `chefaI_gradio_interface.py`: Main code with detailed comments
- `README.md`: Project overview and usage instructions

**Course:** Generative AI Final Project
**Date:** June 2025
