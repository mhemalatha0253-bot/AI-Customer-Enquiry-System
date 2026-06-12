# AI-Powered Customer Enquiry Management System

## Project Overview

This project automates customer enquiry handling using AI and workflow automation. Customer emails are automatically captured, classified, processed, and responded to after manager approval.

## Objectives

- Automate customer enquiry processing
- Reduce response time
- Improve customer satisfaction
- Generate AI-powered draft responses
- Enable manager approval before sending replies

## Technologies Used

- n8n
- Groq AI
- Gmail
- Data Tables

## Workflow

```text
Customer Email
       ↓
Gmail Trigger
       ↓
Extract Email Data
       ↓
AI Classification
       ↓
Store in Data Table
       ↓
Generate AI Response
       ↓
Manager Approval
       ↓
Approved?
   ↓        ↓
 Yes       No
 ↓          ↓
Send      Request
Reply     Changes
 ↓
Update Status
```
<img width="681" height="306" alt="image" src="https://github.com/user-attachments/assets/0fa50336-8cc7-45a5-b548-f1849529ea8a" />


## Features

### Email Collection
Automatically captures customer emails.

### AI Classification
Classifies enquiries into:
- General Enquiry
- Product Enquiry
- Complaint
- Support Request

### AI Response Generation
Generates professional responses using Groq AI.

### Manager Approval
Ensures human review before sending replies.

### Automated Reply
Sends approved responses to customers.

## Future Enhancements

- Multi-language support
- Sentiment Analysis
- CRM Integration
- Analytics Dashboard



## Author

Hemalatha M
