# Image-to-Speech-GenAI-Tool-Using-LLM

**🌟♨️ AI tool that generates an Audio short story based on the context of an uploaded image by prompting a GenAI LLM model, Hugging Face AI models together with OpenAI & LangChain. Deployed on Streamlit & Hugging Space Cloud Separately.**

## 📢 Run App

- **Streamlit Cloud**: [Launch App On Streamlit](https://gurpreetkaurjethra-image-to-speech-genai-tool-using-llm-app-xjbx2w.streamlit.app/)
- **Hugging Face Space Cloud**: [Launch App On HuggingFace Space](https://huggingface.co/spaces/GURPREETKAURJETHRA/Image-to-Speech-GenAI-Tool-Using-LLM)

## 🎯 Demo

You can listen to the respective audio file of the test demo images in the `img-audio` folder.

## 📈 System Design

### 🏆 Approach

The app uses Hugging Face AI models to generate text from an image, which then generates audio from the text. The execution is divided into 3 parts:

1. **Image to Text**: Using Hugging Face's computer vision models to generate text from the uploaded image.
2. **Text to Audio**: Using OpenAI's text-to-speech model to generate audio from the generated text.
3. **Audio Playback**: Providing the user with the ability to listen to the generated audio.

## 🌟 Requirements

- Python 3.7+
- OpenAI API key
- Hugging Face API token

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/GURPREETKAURJETHRA/Image-to-Speech-GenAI-Tool-Using-LLM.git
