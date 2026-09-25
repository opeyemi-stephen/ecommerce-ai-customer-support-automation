# E-Commerce AI Customer Support Automation

An AI-powered customer support automation designed for e-commerce businesses. The workflow uses **Make.com, DeepSeek API, and Google Sheets** to automate customer inquiries, order-related requests, support tickets, and escalation to a human agent when AI assistance is not appropriate.

## 🚀 Project Overview

This automation is designed to reduce repetitive customer-support tasks while ensuring that customers can still be transferred to a human when necessary.

The system separates customer requests into different support processes:

1. **FAQ & General Questions** — Handles common customer questions and provides automated answers.
2. **Orders & Support Tickets** — Handles order-related inquiries and organizes customer support requests.
3. **Human Escalation** — Identifies situations that require human assistance and routes them for manual handling.

DeepSeek is integrated through its API to generate AI-powered responses, while Google Sheets is used to store and manage relevant customer/order information.

## 🔄 How the Automation Works

**Customer Message → Make.com → Request Classification → Appropriate Workflow → AI Response / Human Escalation**

### 1. FAQ Automation

The system receives a customer's question and uses the AI to generate an appropriate response for common questions such as:

* Product information
* Shipping questions
* Return policies
* Store information
* Frequently asked questions

### 2. Order & Support Ticket Automation

Order-related requests are processed separately so that customers can receive assistance with issues such as:

* Order status
* Order questions
* Delivery-related issues
* Customer support requests
* Ticket creation or follow-up

Google Sheets can be used as a simple data source for storing and retrieving customer/order information.

### 3. Human Escalation

Not every customer issue should be handled entirely by AI.

The workflow includes an escalation path for situations where human intervention is required, allowing the conversation to be passed to a human support representative instead of continuing with automated responses.

## 🛠️ Technologies Used

* **Make.com** — Workflow automation and orchestration
* **DeepSeek API** — AI-powered response generation and request processing
* **Google Sheets** — Customer/order data management
* **API Integration** — Connecting external AI services to the automation
* **Automation Logic & Routing** — Separating different customer-support scenarios

## 🎯 Business Use Case

This type of automation can help an e-commerce business reduce repetitive support work by allowing AI to handle routine customer questions while keeping a human-in-the-loop for more complex situations.

The goal is not to replace human support completely, but to automate repetitive requests and allow support agents to focus on cases that require human attention.

## 💡 Skills Demonstrated

This project demonstrates practical experience with:

* AI workflow automation
* Make.com
* REST API integration
* DeepSeek API integration
* Google Sheets integration
* Workflow routing
* Customer-support automation
* AI prompt design
* Data handling
* Human-in-the-loop automation
* Error and escalation logic

## 🔐 Security

API keys and other private credentials should **never be committed to a public GitHub repository**.

The version of this project uploaded to GitHub should use placeholders or secure credential management instead of exposing real API keys.

## 📌 Project Purpose

This project was built as a practical AI automation portfolio project to demonstrate how AI, APIs, spreadsheets, and workflow automation can be combined to create an e-commerce customer-support system.
