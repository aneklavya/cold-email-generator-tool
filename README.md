# Job Application Assistant

This app leverages the Llama model to scrape data from job sites and generate tailored cover letters as proposals for clients. 

## Installation

To set up the project, follow these steps:

1. Clone the repository and navigate to the project directory.
2. Install the required Python packages using `pip`:

   ```bash
   pip install langchain
   pip install chromadb
   pip install langchain-groq

## Groq API Setup

1. Log in to [Groq](https://www.groq.com/) and generate your API key.
2. Add the API key to the `.env` file in the project directory. The `.env` file currently has a placeholder for the API key. Replace it with your own:

   ```env
   GROQ_API_KEY=your_api_key_here


