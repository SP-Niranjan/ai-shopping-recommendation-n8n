# 🛍️ AI-Powered Product Recommendation System using N8N + Gemini

This project provides personalized product recommendations for ecommerce users based on their past purchases and browsing history using Google's Gemini LLM and N8N workflow automation.

## 🔧 Tech Stack

- [Google Gemini API](https://ai.google.dev/)
- [N8N](https://n8n.io/)
- Gmail API (to send styled email)
- HTML Email Styling
- (Optional) PDF Generator, Google Sheets

## 🧠 Gemini Prompt Example

- Give 3 personalized product recommendations for a 25-year-old woman who bought sneakers, yoga pants, and a sports bra, and is browsing fitness trackers and running shoes...


## 📩 Output Sample

See the `assets/` folder for the final styled email.

## 📄 N8N Workflow

Located in: `workflow/gemini_email_workflow.json`

Import this into your N8N instance and configure:
- Your Gemini API Key
- Gmail credentials

## 📊 Features

- AI-powered recommendations
- Markdown cleanup
- HTML-formatted, professional emails
- Can scale to 100+ users via Google Sheets
- Can export recommendations to PDF

## 📂 Folder Structure

- `workflow/` → JSON file for N8N
- `prompts/` → AI prompt used

