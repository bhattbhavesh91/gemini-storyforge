# 🏰 Storyforge (Dhairya Edition)

![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)
![Google GenAI](https://img.shields.io/badge/Google%20GenAI-Veo%20%7C%20Gemini-orange)
![License](https://img.shields.io/badge/license-MIT-green)

Storyforge is an automated, AI-powered pipeline for generating magical children's storybooks. It combines cutting-edge generative AI models to create the narrative, illustrate the pages, and bring the cover to life with subtle, cinematic animations.

## ✨ Features
* **Automated Story Generation:** Uses Gemini models to craft engaging and magical narratives.
* **Rich Illustrations:** Generates high-quality, visually consistent images for the book pages.
* **Magical Cover Animation:** Transforms static book covers into captivating video animations using Google's `veo-3.1-generate-preview` (Image-to-Video API).
* **End-to-End Pipeline:** Seamlessly moves from a simple text prompt to a final multimedia asset.

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- `google-genai` SDK
- Google API Key with access to the latest Gemini and Veo models

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bhattbhavesh91/storyforge_dhairya.git
   cd storyforge_dhairya
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   ```bash
   export GOOGLE_API_KEY="your-api-key-here"
   ```

## 🛠️ Usage

Run the main pipeline to generate a complete storybook:

```bash
python main.py --prompt "A brave little fox discovering a hidden magical forest"
```

### The Animation Pipeline
Storyforge leverages the Veo 3.1 model via long-running video generation to animate book covers with soft sparkles, parallax, and face-preservation.

```python
# Example animation configuration
ANIMATOR = "veo-3.1-generate-preview"
```

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/bhattbhavesh91/storyforge_dhairya/issues).

## 📝 License
This project is licensed under the MIT License.
