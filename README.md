# Google Generative AI - Gemini Pro

This repository contains a Python script that demonstrates how to use the Google Gemini Pro model from the Google Generative AI platform to generate content based on a prompt and the text extracted from a PDF file.

## Prerequisites

- Python 3.6 or later
- PyPDF2
- docx
- google.generativeai
- dotenv

## Setup

1. Install the required Python packages: PyPDF2, docx, google.generativeai, and dotenv.
2. Create a `.env` file and add your Gemini Pro API key: `GEMINI_API_KEY=your_api_key`.

## Usage

1. Run the script and provide a prompt when prompted.
2. The script will read the text from the specified PDF file and use it along with the prompt to generate content using the Gemini Pro model.
3. The generated content will be printed to the console.

## References

- [Google Generative AI - Gemini Pro](https://microsoft.github.io/TaskWeaver/docs/llms/gemini)
- [Gemini Pro Documentation](https://cloud.google.com/vertex-ai/docs/generative-ai/multimodal/send-chat-prompts-gemini)
