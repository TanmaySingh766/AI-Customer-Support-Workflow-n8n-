# AI Customer Support Workflow (n8n)

This repository contains an **n8n workflow** that automates customer support email handling using AI.

## What it does
- Monitors incoming Gmail emails
- Classifies emails using an LLM
- Retrieves relevant answers from a Pinecone knowledge base (RAG)
- Generates friendly AI responses
- Labels and replies automatically via Gmail

## Tech Stack
- n8n
- OpenAI / OpenRouter (Claude, GPT)
- Pinecone Vector Database
- Gmail API

## Workflow File
- `Customer Support Workflow.json`

## How to use
1. Import the JSON into n8n
2. Configure Gmail, OpenAI, OpenRouter, and Pinecone credentials
3. Activate the workflow
