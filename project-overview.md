# Project Overview

Project Name: DeepSeek PDF Assistant

Description: A web application that allows users to upload PDFs and interact with them using the DeepSeek R1 LLM. The app provides analysis, summarization, and chat functionalities for uploaded documents.

Features:

*   PDF Upload and Grouping: Users can upload up to 10 PDFs per group, with a maximum of 100 pages total per group.
*   DeepSeek R1 Integration: Leverage the DeepSeek R1 LLM for analysis, summarization, and chat.
*   Analysis: Generate short analyses of the PDF content (under 200 characters).
*   Summarization: Create summaries of the PDF content (under 200 characters).
*   Chat: Chat with the content of uploaded PDFs (responses limited to 200 characters).

Target Audience: Students, researchers, and professionals who need a simple and efficient way to analyze and extract information from PDFs using AI.

Technology Stack:

*   Cloudflare next-on-pages framework (NextJS) for the web application.
*   API for PDF parsing and text extraction.
*   DeepSeek R1 LLM API for AI-powered analysis, summarization, and chat.