# Web_Search_Assistant
A Python-based web search tool that uses DuckDuckGo API and OpenAI to perform searches and provide AI-powered summaries.

## Features

- 🔍 Web search using DuckDuckGo Instant Answer API
- 🤖 AI-powered result summaries using OpenAI GPT-4
- 🔄 Interactive loop for multiple searches
- 🛡️ SSL warning suppression for smooth operation

## Requirements

- Python 3.7+
- OpenAI API key
- Required packages: `requests`, `openai`, `python-dotenv`, `urllib3`

## Setup

1. Install dependencies:
```bash
pip install requests openai python-dotenv urllib3
```

2. Create a `.env` file with your OpenAI API key:
```
OPENAI_API_KEY=your_openai_api_key_here
```

3. Run the script:
```bash
python Web_Search.py
```

## Usage

1. Start the program
2. Enter your search query when prompted
3. View search results and AI summary
4. Type 'exit' to quit

## Example

```
🌐 Web Search Assistant Ready!

🔍 Enter your search query (type 'exit' to quit): Python programming

🔍 Searching for: Python programming

- Python is a high-level programming language... (https://python.org)
- Learn Python programming basics... (https://example.com)

📌 Summary:
Python is a versatile programming language known for its simplicity...
```

## Note

The DuckDuckGo API has limitations and may not return results for all queries. Best results are achieved with topic-based searches rather than direct URLs.
