# AI-Powered Lead Qualification & Automated Follow-Up System

An AI-powered n8n automation workflow that receives new leads, analyzes their intent, qualifies them based on multiple factors, stores the lead information, and triggers personalized follow-up actions.

## Workflow Overview

Webhook
↓
Lead Data Processing
↓
AI Lead Qualification
↓
Lead Data Extraction
↓
Google Sheets CRM
↓
Lead Temperature Classification
↓
Automated Follow-Up

## Key Features

- Receives new leads through a webhook
- Uses AI to analyze lead intent
- Extracts customer interest, budget, and urgency
- Assigns a Hot, Warm, or Cold lead temperature
- Generates a lead score from 0 to 100
- Stores qualified leads in Google Sheets
- Sends personalized AI-generated follow-up messages
- Alerts the sales team about hot leads
- Uses delayed follow-up for cold leads

## Lead Qualification

The AI analyzes each lead and determines:

- Main interest
- Budget
- Urgency
- Lead temperature
- Lead score
- Reason for the score

## Automation Flow

1. A new lead is received through a webhook.
2. Lead information is extracted and organized.
3. AI analyzes and qualifies the lead.
4. The lead is stored in a Google Sheets CRM.
5. The lead is classified as Hot, Warm, or Cold.
6. Different automated actions are triggered based on the lead temperature.
7. Personalized follow-up communication is generated and sent automatically.

## Technologies Used

- n8n
- OpenAI
- Google Sheets
- Gmail
- JavaScript

## Purpose

This automation helps businesses reduce manual lead processing, respond faster to potential customers, and improve lead follow-up efficiency.

> Note: Credentials and sensitive information are not included in this public repository.
