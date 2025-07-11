# 🤖 AI Scraping Kit

> **Complete self-hosted stack for building AI-powered web scraping automation**

A production-ready template that combines **n8n workflow automation**, **Playwright MCP browser control**, **AI analysis**, and **Supabase backend** to create powerful web scraping agents. Perfect for cybersecurity automation, OSINT workflows, and any AI-driven web analysis projects.

<div align="center">

[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker)](https://docker.com) [![AI](https://img.shields.io/badge/AI-Multiple_LLMs-FF6B35)](https://n8n.io) [![n8n](https://img.shields.io/badge/Automation-n8n-FF6D5A)](https://n8n.io) [![Supabase](https://img.shields.io/badge/Backend-Supabase-3ECF8E)](https://supabase.com) [![RAG](https://img.shields.io/badge/RAG-pgvector-9333EA)](https://github.com/pgvector/pgvector) [![VNC](https://img.shields.io/badge/VNC-Remote_Desktop-FF5722)](https://github.com/novnc/noVNC)

</div>

## 🎯 What This Is

This is a **foundational template** for building AI-powered web scraping automation using the best open-source tools available. Instead of building from scratch, you get a complete, production-ready stack that handles the complex infrastructure so you can focus on creating your scraping workflows.

## 🔥 Why This Stack is Perfect for AI Scraping

### **🤖 AI-First Architecture**
- [**Playwright MCP**](https://github.com/microsoft/playwright-mcp) - AI agents control browsers with accessibility snapshots
- **Multiple LLM Support** - Google Gemini (free), OpenAI, Claude, or self-hosted Ollama
- **RAG Ready** - Built-in vector embeddings with pgvector for conversational data queries

### **🔧 Visual Workflow Builder**
- [**n8n**](https://docs.n8n.io/hosting/installation/docker/) - Drag-and-drop workflow creation, no coding required
- **100+ Integrations** - Connect to APIs, databases, webhooks, and more
- **Queue System** - Redis-powered background processing for large-scale scraping

### **🗄️ Enterprise Database**
- [**Supabase**](https://supabase.com/docs/guides/self-hosting/docker) - PostgreSQL with real-time subscriptions and REST API
- **Vector Search** - Store and query embeddings for semantic search
- **Self-hosted or Cloud** - Your data stays under your control

### **🐳 One-Command Deployment**
- **Docker Compose** - Everything runs locally with a single command
- **Auto-configuration** - Database schemas, workflows, and services pre-configured
- **Scalable** - Add workers, scale databases, deploy to production

## 🛠️ Perfect for Building

- **🔍 URL Analysis Tools** - Like threat intelligence and phishing detection
- **📊 Data Collection** - OSINT automation and research workflows  
- **🛒 E-commerce Monitoring** - Price tracking and product analysis
- **📰 Content Aggregation** - News monitoring and content curation
- **🕷️ Web Research** - Academic research and data mining

## 🚀 Quick Start

### Deploy the Complete Stack
```bash
# Clone the repository
git clone https://github.com/brunosergi/ai-scraping-kit.git
cd ai-scraping-kit

# Configure environment
cp .env.example .env
# Edit .env with your AI API keys

# Launch everything
docker compose up -d
```

### Your AI Scraping Stack is Ready!
- **🎛️ n8n Workflow Builder**: http://localhost:5678
- **🗄️ Supabase Database**: http://localhost:3000
- **🤖 Playwright MCP**: http://localhost:8831
- **🖥️ Test VNC**: http://localhost:6080 - Watch browser automation in real-time via VNC

**Manual Browser Control:** Access VNC at http://localhost:6080, press Alt+F2 and enter `chromium` for manual debugging and troubleshooting.

## 📋 What You Get

### **Core Infrastructure**
- **PostgreSQL Database** with vector extensions for embeddings
- **n8n Automation Server** with worker queue system
- **Playwright MCP Server** for AI-controlled browser automation with VNC access
- **Redis Queue** for background task processing
- **Supabase Stack** for real-time database and storage

### **AI & Analysis**
- **Multi-LLM Support** - Switch between AI providers easily
- **Vector Embeddings** - Store and search semantic content
- **Structured Outputs** - JSON schemas for consistent AI responses
- **RAG Capabilities** - Query your scraped data conversationally

## 💡 See It In Action

Want to see a complete implementation? Check out **[Alive URL Scan](https://github.com/brunosergi/alive-url-scan)** - a cybersecurity tool built with this exact stack that:

- ✅ Analyzes suspicious URLs with AI
- ✅ Takes automated screenshots for evidence  
- ✅ Processes thousands of URLs from threat feeds
- ✅ Provides real-time dashboard and exports
- ✅ Uses the same tech stack and architecture

It's a perfect example of what you can build with this template!

## 🎯 Building Your First Workflow

1. **Access n8n**: Go to http://localhost:5678
2. **Create Workflow**: Start with a webhook or chat trigger
3. **Use Playwright MCP**: Let AI analyze web content
4. **Save to Database**: Store results in Supabase
5. **Create Embeddings**: Enable RAG for conversational queries

The infrastructure handles scaling, queuing, and data management automatically.

## 🔄 Architecture Benefits

### **For Individual Developers**
- **Free Tier Friendly** - Works with free AI APIs and self-hosted options
- **Local Development** - Everything runs on your machine
- **Easy Customization** - Modify workflows visually, no complex deployments

### **For Production Use**  
- **Horizontally Scalable** - Add more n8n workers as needed
- **Cloud Ready** - Deploy to any Docker-compatible platform
- **Monitoring Built-in** - Logs, metrics, and health checks included

---

<div align="center">

**🚀 Ready to build AI-powered automation?**

*The complete stack for AI scraping automation* 🤖

</div>