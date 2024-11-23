# README for ChatGPT API Python Project

## Overview
This project demonstrates how to use the OpenAI ChatGPT API in Python to create a simple chat interface. It allows users to interact with the ChatGPT model in real-time.

## Requirements
- Python 3.x
- OpenAI Python package

## Installation
To install the necessary package, run the following command:

```bash
pip install openai
```

## Setup
1. **API Key**: Obtain your OpenAI API key from the OpenAI website and replace the placeholder in the script:
   ```python
   openai.api_key = 'your_api_key_here'
   ```

2. **Run the Script**: Execute the script in your Python environment. The program will prompt you for input, and you can start chatting with the model.

## Usage
- After running the script, type your message into the console when prompted.
- The assistant will respond based on your input.
- To exit the chat, simply terminate the program (e.g., by pressing `Ctrl+C`).

## Code Explanation
- The script initializes a conversation with a system message defining the assistant's role.
- It enters a loop where it continuously accepts user input, sends it to the ChatGPT model, and prints out the response.

## Contributing
Feel free to fork this repository and submit pull requests for improvements or new features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Citations:
[1] https://colab.research.google.com/drive/1JA_TmRGrOofA1cnuZx3B4D6MlJDT4C18
