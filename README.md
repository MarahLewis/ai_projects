# AI Projects - Student Application Suite

This project contains three simple browser-based applications built with Bootstrap 5 and plain JavaScript:

- Chat app for programming and system design Q&A
- MCP information app for Model Context Protocol learning
- RAG demo app using user-provided text files

## Project Files

- [index.html](index.html) - Main landing page and submission instructions
- [chat.html](chat.html) - AI chat application using Groq API
- [mcp.html](mcp.html) - MCP learning and setup page
- [rag.html](rag.html) - Simple Retrieval-Augmented Generation demo

## Prerequisites

- A modern browser (Chrome, Edge, Firefox)
- Internet connection (for CDN assets and API calls)
- A Groq API key for applications that use AI responses

## How To Run

1. Download or clone this project folder.
2. Open [index.html](index.html) in your browser.
3. Navigate to each app from the links on the index page.
4. Update required values where needed (for example API key fields).
5. Test each application end-to-end.

## Application Overview

### 1. Chat Application

Open [chat.html](chat.html).

What it does:
- Lets students ask programming and system design questions
- Calls Groq chat completions API
- Displays conversational responses in a Bootstrap chat interface

What to configure:
- Paste a valid Groq API key in the provided input field

### 2. MCP Application

Open [mcp.html](mcp.html).

What it does:
- Explains Model Context Protocol (MCP)
- Shows common MCP servers and setup guidance
- Provides educational examples and walkthrough sections

What to configure:
- No required runtime configuration for viewing content

### 3. RAG Application

Open [rag.html](rag.html).

What it does:
- Accepts `.txt` uploads as local knowledge data
- Splits text into chunks
- Retrieves relevant chunks using simple keyword overlap
- Sends context + question to Groq for grounded answers

What to configure:
- Paste a valid Groq API key
- Upload one or more `.txt` files

## Final Submission Requirements

Students must submit screenshots from all three applications.

1. Run and verify [chat.html](chat.html).
2. Run and verify [mcp.html](mcp.html).
3. Run and verify [rag.html](rag.html).
4. Capture one screenshot from each application while working.
5. Submit all three screenshots as the final submission.

## Notes

- Keep API keys private and never share them in screenshots.
- If API calls fail, first verify the API key and internet connection.
- This project is intentionally simple for classroom learning and demonstration.
