# Research Assistant Backend

This is the backend for the **AI-powered Research Assistant**, built with **Spring Boot** and integrated with **Google Gemini API**. It serves as the core engine that summarizes content from web pages in real time and powers a Chrome extension for seamless research workflows.

## 🔍 Features

* AI-generated summaries of web content
* Gemini 2.0 Flash model integration
* Lightweight, scalable REST API
* Secure environment variable handling

## 🧠 Powered by AI

The backend uses generative AI to process and summarize large chunks of text, enabling users to gain insights faster. It's designed to support browser-based extensions and other tools that aim to make online research smarter and more efficient.

## 💠 Tech Stack

* Java 17+
* Spring Boot
* Google Gemini API
* RESTful Web Services

## 🚀 Getting Started

### Screenshots

<img width="452" height="538" alt="Screenshot 2025-07-09 164646" src="https://github.com/user-attachments/assets/c346932a-f965-47db-b5f7-9699bfbb9039" />
<br>
<br>
<img width="1000" height="745" alt="Screenshot 2025-07-09 164544" src="https://github.com/user-attachments/assets/86a804b0-8409-40cf-a2a8-461bd7c37fd7" />


### Prerequisites

* Java 17+
* Maven
* Gemini API Key from [Google AI Studio](https://makersuite.google.com/app)

### Environment Setup

Create a `.env` file or configure environment variables:

```
GEMINI_KEY=your-gemini-api-key
GEMINI_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent
```

> Do not commit your actual `.env` or credentials.

### Run the App

```bash
mvn spring-boot:run
```

### API Endpoint (Sample)

```
POST /api/summarize
{
  "text": "Paste the content to summarize..."
}
```

## 📁 Project Structure

```
src/
└── main/
    ├── java/
    │   └── com/researchassistant/
    │       └── controllers/
    │       └── services/
    └── resources/
        └── application.properties
```

## 🧪 Example Use Cases

* Research automation
* Academic summarization
* AI note-taking tools
* Browser extension backends
