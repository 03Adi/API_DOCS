## 🌐 Multi-language API Docs Viewer
This project provides a lightweight, interactive HTML-based interface to view API request examples in multiple programming languages (JSON, Node.js, Python, PHP, Java, Ruby). It dynamically converts a single JSON request object into language-specific request formats on the fly.
        
##🚀 Features
 
✅ Centralized JSON request data
🔄 Dynamic conversion into multiple languages using JavaScript
🌈 Syntax highlighting with highlight.js
🖱️ Language dropdown to switch between JSON, Node.js, Python, PHP, Java, Ruby
📜 Includes a sample static API response block

## 📸 Preview
 
## 📁 File Structure
.
├── index.html       # Main interactive HTML page
├── README.md        # Project documentation (you’re here)

##🧪 Sample JSON Request
The JSON payload represents a comprehensive KYC onboarding API example, including nested structures like Prospect, Address, Phone, Identification Document, etc.
💡 How It Works

A JavaScript function jsonToCode(lang, payload) takes the language and base JSON, and returns the correctly formatted code snippet.
Highlight.js is used for code block formatting and syntax highlighting.
Language dropdown triggers onChange events to rerender the code in real-time.

## 🌐 Supported Languages

JSON
Node.js (Axios)
Python (Requests)
PHP (Stream Context)
Java (HttpClient)
Ruby (Net::HTTP)

## 📦 Usage
Just open the index.html file in your browser — no backend or build step required.
# Clone and run
git clone https://github.com/your-username/multi-lang-api-docs.git
cd multi-lang-api-docs
open index.html

## 🛠️ Tech Stack

HTML, CSS, JavaScript
highlight.js

## ✨ Future Improvements

Add support for more languages (Go, C#, etc.)
Code copy buttons
Live API tester (e.g., with Fetch)
Toggle request/response structure separately
