# Text-to-Story Generator ✨

Welcome to the **Text-to-Story Generator**! This is a Streamlit-based web app that generates creative stories using Cohere's powerful language models. 📝💡 You can provide a story prompt, and the app will generate a creative continuation or full story based on your prompt. Adjust the creativity level and length of the story as per your preference. 🌟

Access the deployed version of the app here:  
[**Text-to-Story Generator**](https://text-to-story.streamlit.app/) 🚀

## Features 🌟

- **Generate Stories**: Provide a prompt, and the app will generate a continuation or full story. 📖✨
- **Adjustable Story Length**: Control the length of the story using a slider that determines the maximum number of tokens (words/characters). 🎚️📏
- **Creativity Control**: Use a slider to adjust the "creativity" level (temperature). Higher values lead to more creative outputs. 🎨🖌️
- **Cohere API Integration**: The app uses Cohere's API to generate text, ensuring high-quality, natural language generation. 🔌🤖

## Requirements 📦

- Python 3.x 🐍
- Streamlit 🌊
- Cohere Python Client 🔑

## Installation 🛠️

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/text-to-story-generator.git
   cd text-to-story-generator
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

   **requirements.txt**
   ```
   streamlit
   cohere
   ```

4. Get your **Cohere API key** by signing up at [Cohere](https://cohere.ai/). Once you have the key, replace the placeholder `API_KEY` in your code with your actual API key. 🔑

## Running the App Locally 🖥️

1. Start the Streamlit app:
   ```bash
   streamlit run app.py
   ```

2. Open the app in your browser at `http://localhost:8501`. 🌐

## How to Use 📝

- **Enter a prompt**: Provide a starting point for the story in the text input area (e.g., "A lone traveler ventures into a mysterious forest..."). 🌳
- **Adjust Story Length**: Use the "Story Length" slider to set the maximum number of tokens (words/characters) in the generated story. ⏳
- **Set Creativity Level**: Use the "Creativity Level" slider to control how creative or random the generated text is. 🎨✨
- **Generate**: Click the "Generate Story" button to get a creative continuation of your story idea. 🔮

## Example 🖋️

**Prompt**: `A lone traveler ventures into a mysterious forest where strange things begin to happen.`

**Generated Story**:
```
As the sun began to set over the dense woodland, casting an eerie glow across the landscape, the traveler could not help but feel a sense of trepidation as they ventured deeper into the mysterious forest...
```

## API Reference ⚙️

The app integrates with Cohere's text generation API using the `command-xlarge` model. You can adjust parameters like:
- `max_tokens`: Controls the maximum length of the generated story. 📏
- `temperature`: Controls randomness; higher values result in more creativity and diversity in the generated text. 🔥

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
