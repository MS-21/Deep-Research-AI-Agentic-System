# Deep-Research-AI-Agentic-System
## Overview
The Deep Research AI Agentic System is a dual-agent system designed to crawl websites, gather information, and generate a comprehensive, well-structured answer based on the data collected. The system uses LangChain and Groq to organize, analyze, and generate insights from the collected data. The system is split into two main agents:
1. Research Agent: Focused on crawling websites and collecting research data.
2. Answer Drafter Agent: Processes the collected data and drafts a well-structured answer based on the findings.

## Table of Contents
- Installation
- Usage
- Agents
- Technologies Used
- Acknowledgments

## Installation
1. Clone the repository
2. Install required dependencies

## Usage
1. Set up environment variables:
- Groq API Key: Obtain your Groq API key from the Groq platform and set it as an environment variable.
- OpenAI API Key (optional): If you're using OpenAI's models for any processing, set the OpenAI API key.
2. Run the system: The system runs with a simple query passed into the input_query variable in the script.
3. Viewing the Result: Once the system completes its task, it will output a structured and informative answer based on the research data collected.

## Agents
1. Research Agent:
  - The Research Agent is responsible for crawling websites and collecting relevant data based on the input query. It retrieves the first few pages from search results and scrapes useful content.
2. Answer Drafter Agent:
 - The Answer Drafter Agent processes the data gathered by the Research Agent. It drafts a clear and concise answer by leveraging LangChain and Groq to organize the content and generate a well-structured response.
   
## Technologies Used
- LangChain: For managing chains of logic and integrating with LLMs like Groq.
- Groq API: For running inference with AI models to process and generate responses.
- BeautifulSoup: For web scraping and extracting text content from HTML pages.
- Requests: For making HTTP requests to fetch web pages.
- Python: The programming language used to build and run the system.
  
## Acknowledgments
- LangChain: A powerful library for building language model-based applications.
- Groq: For providing a robust platform for AI/ML model inference.
- BeautifulSoup: For web scraping and HTML parsing.
- Requests: For making HTTP requests.

