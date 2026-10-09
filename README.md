
# Step FAQ Support Assistant

### Customer Support Automation | Conversational FAQ Demo

**[View Live Demo](https://kentjh200.github.io/step-faq-agent-demo/)** | **[Official Step FAQs](https://step.com/faq)**

> **Disclaimer:** This is an independent portfolio project created for educational and demonstration purposes. It is not affiliated with, endorsed by, or maintained by Step.

## Project Overview

The Step FAQ Support Assistant is an interactive, browser-based chatbot prototype designed to help customers find answers to common questions about Step's financial products and services.

The project explores how conversational interfaces and automated knowledge retrieval can improve customer support efficiency, reduce repetitive inquiries, and make self-service resources more accessible.

It was developed as a practical demonstration of my interest in AI-powered customer support, workflow optimization, and support operations.

## The Problem

Customer support teams frequently receive repetitive questions about account management, card functionality, transactions, and product features.

Traditional FAQ pages require customers to navigate categories or manually search for relevant information.

A conversational support assistant can simplify this experience by allowing customers to ask questions naturally and receive relevant information without navigating multiple pages.

## The Solution

This prototype provides a conversational interface that matches customer questions with relevant information from a curated knowledge base based on Step's publicly available FAQs.

### Key Features

- **Conversational Interface:** Customers can ask questions using everyday language.
- **FAQ Knowledge Base:** Answers are drawn from curated Step FAQ content.
- **Question Matching:** Matches customer inquiries to relevant FAQ entries.
- **Self-Service Support:** Helps customers find information without contacting an agent.
- **Escalation Guidance:** Directs customers to official support resources when a question cannot be answered.
- **Responsive Design:** Provides a consistent experience across desktop and mobile devices.
- **Brand-Inspired UI:** Uses design elements inspired by Step's website.

## How It Works

1. A customer enters a question in the chat interface.
2. The application processes the question and searches its local FAQ knowledge base.
3. The application identifies a relevant FAQ entry.
4. The customer receives the corresponding answer and, where available, a link to the official source.
5. If a suitable answer is unavailable, the assistant recommends consulting Step's official support resources.

## Technology

| Component | Implementation |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Knowledge Base | Curated Step FAQ content |
| Question Matching | Client-side matching logic |
| Hosting | GitHub Pages |
| External API | Not required |
| AI / LLM Integration | Planned enhancement |

The current implementation runs entirely in the browser and does not require an API key, backend server, or paid subscription.

## Customer Support Design Principles

This project was designed around several principles important to customer support operations.

**Accuracy Over Speculation**

Financial support interactions require reliable information. When the assistant cannot confidently identify a relevant answer, it should direct the customer to official resources rather than inventing information.

**Self-Service First**

Frequently asked questions are strong candidates for automation, allowing customers to resolve straightforward inquiries independently.

**Clear Escalation Paths**

Not every issue should be automated. Account-specific problems, sensitive requests, and unsupported questions should be directed to appropriate support channels.

**Continuous Improvement**

Customer questions that cannot be answered successfully can help identify knowledge gaps and future automation opportunities.

## Future Improvements

The current prototype provides a foundation for a more advanced AI-powered support assistant.

Potential enhancements include:

- **Retrieval-Augmented Generation (RAG):** Retrieve relevant FAQ documents and use a language model to generate grounded conversational answers.
- **Prompt Engineering:** Develop and test system prompts for answer accuracy, tone, and escalation behavior.
- **Conversation Context:** Support follow-up questions that reference earlier messages.
- **MCP Integration:** Explore Model Context Protocol tools for accessing external knowledge and support systems.
- **Support Ticket Integration:** Connect to platforms such as Zendesk to support escalation workflows.
- **Analytics:** Track answer relevance, fallback frequency, common customer questions, and potential ticket deflection.
- **Automated Evaluation:** Create a repeatable test suite to measure answer accuracy and identify failure patterns.

These are planned enhancements and are not represented as completed functionality.

## Project Goals

This project aims to demonstrate practical thinking around:

- Identifying repetitive customer support workflows suitable for automation.
- Translating support knowledge into accessible self-service experiences.
- Designing customer-friendly conversational interactions.
- Recognizing the importance of accurate responses and escalation safeguards.
- Evaluating opportunities to integrate AI into existing support operations.

## Running Locally

1. Download or clone this repository.
2. Locate the `index.html` file.
3. Open it in a modern web browser.
4. Start asking questions through the chat interface.

No installation, API credentials, or backend configuration is required.

## About the Creator

Created by **Kent Huynh**, a technical support professional with over 10 years of experience in SaaS customer support, troubleshooting, quality assurance, and support operations.

My professional background includes working with support platforms, investigating technical issues, improving internal processes, and collaborating with Product and Engineering teams.

I'm particularly interested in how AI, automation, and better knowledge management can help support organizations deliver faster, more consistent, and more scalable customer experiences.

---

*Independent demonstration project. For official product information, visit [Step](https://step.com) or its [FAQ page](https://step.com/faq).*
