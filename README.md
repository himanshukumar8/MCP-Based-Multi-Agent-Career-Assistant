# MCP-Based Career Assistant

> An MCP-powered AI system for resume generation, resume optimization, and job-description alignment through intelligent tool integration and automated workflows.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FastMCP](https://img.shields.io/badge/FastMCP-MCP%20Framework-green)
![OpenAI](https://img.shields.io/badge/OpenAI-LLM-black)
![LangChain](https://img.shields.io/badge/LangChain-Agent%20Framework-orange)
![AWS](https://img.shields.io/badge/AWS-Cloud-yellow)

---

## Overview

MCP-Based Career Assistant is an AI-powered career intelligence platform built using the Model Context Protocol (MCP). The system enables users to generate, optimize, and tailor ATS-friendly resumes through AI-driven workflows and MCP tool integrations.

The project demonstrates how Large Language Models can interact with external tools using MCP to automate resume creation, job-description alignment, and candidate profile enhancement.

### Key AI Concepts Demonstrated

- Model Context Protocol (MCP)
- Tool Calling
- Agent Workflows
- LLM-Powered Content Generation
- Resume Intelligence Systems
- Structured Output Generation

---

## Features

### Resume Generation

- Generate ATS-friendly resumes from raw text input
- Create resumes from LinkedIn profiles
- Process existing PDF and DOCX resumes
- Generate role-specific resume variants

### Resume Optimization

- Enhance existing resumes using AI
- Align resumes with target job descriptions
- Improve ATS compatibility
- Optimize professional summaries and experience sections

### MCP-Powered Architecture

- Modular MCP tool design
- Structured tool execution workflows
- Extensible architecture for future integrations

### Cloud Integration

- Secure file storage using AWS S3
- Resume content extraction using AWS Textract
- Automated document generation pipeline

---

## System Architecture

> Add architecture diagram here

### Workflow

1. User submits career information through text, file upload, or LinkedIn profile.
2. MCP tools validate and process incoming data.
3. AI extracts and structures candidate information.
4. Resume optimization workflows enhance content quality.
5. Resume templates are populated automatically.
6. Professional resume documents are generated.
7. Download links are returned to the user.

---

## Technology Stack

### AI & MCP

- FastMCP
- OpenAI
- LangChain

### Backend

- Python
- PostgreSQL

### Cloud Services

- AWS S3
- AWS Textract

### DevOps

- GitHub Actions
- Render

---

## MCP Tools

### Core Tools

| Tool | Description |
|--------|-------------|
| Generate Resume | Generate resumes from raw text input |
| Resume Enhancement | Improve existing resumes using AI |
| Job Alignment | Tailor resumes for specific job descriptions |
| LinkedIn Resume Builder | Generate resumes from LinkedIn profile data |

### Utility Tools

| Tool | Description |
|--------|-------------|
| Upload Resume | Upload and process resume files |
| File Validation | Verify uploaded documents |
| Health Check | Monitor MCP server status |

---

## Installation

### Prerequisites

- Python 3.10+
- PostgreSQL Database
- AWS Account (S3 and Textract)
- OpenAI API Key

### Setup

```bash
# Clone repository
git clone https://github.com/<username>/MCP-Based-Career-Assistant.git

# Navigate to project
cd MCP-Based-Career-Assistant

# Create virtual environment
uv venv

# Activate environment
.venv/Scripts/activate

# Install dependencies
uv sync

# Configure environment variables
cp .env.example .env

# Run MCP server
uv run main.py
```

---

## Future Enhancements

- Multi-agent career planning workflows
- Interview preparation assistant
- Automated job matching
- Career analytics dashboard
- Multi-language resume generation
- Additional MCP tool integrations

---

## Project Goals

This project was built to explore practical applications of the Model Context Protocol (MCP) and demonstrate how AI systems can interact with external tools to automate real-world career and resume workflows.

The focus is on building scalable, modular, and production-oriented AI systems rather than standalone prompt-based applications.
