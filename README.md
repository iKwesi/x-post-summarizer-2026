# x-post-summarizer-2026

This repository contains an AI-generated summary of a public figure's 2026 X posts.

## Project Description
This project summarizes the 2026 X posts of a public figure (@llm_wizard) using AI. The summary includes key themes, notable posts, and statistics derived from recent posts retrieved via the X API v2.

## How It Was Built
The project was built using a LangGraph agent that leverages GitHub MCP tools for repository operations and the X API v2 for retrieving posts. The process involves searching and analyzing posts, generating summaries, and managing the repository programmatically.

## Replicating the Process
To replicate this project, follow these steps:

1. **Set up your X API Bearer Token:**
   - Obtain your Bearer Token from the X developer portal.
   - Set it as an environment variable in your system:
     ```bash
     export X_BEARER_TOKEN='your_bearer_token_here'
     ```

2. **Install Python dependencies:**
   - This project requires the `requests` library.
   - Install it using pip:
     ```bash
     pip install requests
     ```

3. **Run the search script:**
   - Use the provided `x_search.py` script to fetch recent posts from a specified X handle.
   - Example:
     ```bash
     python x_search.py llm_wizard
     ```

4. **Analyze and summarize posts:**
   - Use AI tools or scripts to process the fetched posts and generate summaries.

## Repository Contents
- `summary.md`: The AI-generated summary of the analyzed posts.
- `metadata.json`: Metadata about the analysis including date range and themes.
- `x_search.py`: Python script to search and retrieve recent posts from X.

---

Feel free to explore and adapt this project for your own analysis needs.
