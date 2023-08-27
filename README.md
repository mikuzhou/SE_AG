
## LangChain Article Expander/Condenser

The LangChain Article Expander/Condenser is a Streamlit app that utilizes OpenAI's GPT-3.5 Turbo language model to modify articles to meet a specific word count. This tool can be useful for students and writers who need to adjust the length of their text while retaining its core content.

### Usage Instructions

1. Install the required dependencies by running:

   ```bash
   pip install streamlit langchain
   ```

2. Run the Streamlit app:

   ```bash
   streamlit run sourceCode.py
   ```

3. In the app interface:
   - Enter the original article in the provided text area.
   - Specify the desired word count in the corresponding input field.
   - Click the "Expand/Condense" button.

### How It Works

The app leverages the LangChain library to interact with the GPT-3.5 Turbo model. It uses a chat-based approach, where a system message sets the context, and a human message instructs the model to modify the article's word count. The LangChain library handles the communication with the model and provides the modified article as output.

### Important Notes

- This app requires access to OpenAI's GPT-3.5 Turbo model, which may involve API usage and costs.
- The generated modifications are based on the input instructions and may not always produce perfect results. Manual review and adjustments might be necessary.
- The app provides a streamlined interface for text modification, but it should not replace critical writing skills.

### Limitations

- The app's success in achieving the desired word count while maintaining content quality depends on the complexity and nature of the input article.
- The app might require adjustments and refinements to produce optimal results for specific use cases.

### About LangChain

The LangChain library offers an intuitive way to interact with language models and streamline text generation tasks. It simplifies the process of setting up and running complex language tasks using OpenAI's models.

For more information, please refer to the official LangChain documentation.

### Disclaimer

This tool is provided as-is, and the accuracy of the modifications cannot be guaranteed. Users are advised to review and refine the generated content as necessary.
