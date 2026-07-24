# AfyaFlow – AI-Powered Hospital Appointment Automation

## Overview

AfyaFlow is an AI-powered hospital appointment routing system built with n8n Cloud, Google Forms, Google Sheets, Google Gemini AI, and Gmail.

The system helps hospital reception teams automatically process patient appointment requests by analysing symptoms, recommending the appropriate department, assigning a priority level, generating an administrative reception summary, updating hospital records, and sending a confirmation email to the patient.

**Note:** AfyaFlow is designed for **administrative triage only**. It does not diagnose medical conditions or replace healthcare professionals.

---

## Problem

Many hospitals rely on manual appointment booking and patient routing, which can lead to:

- Long waiting times
- Inefficient patient routing
- Administrative workload
- Delays in directing patients to the correct department

---

## Solution

AfyaFlow automates the administrative intake process by using AI to assist reception staff with patient routing.

The workflow:

1. Receives a patient appointment request through Google Forms.
2. Detects the submission using an n8n Google Sheets trigger.
3. Uses Google Gemini AI to analyse the reported symptoms.
4. Recommends the appropriate hospital department and priority.
5. Updates the patient record in Google Sheets.
6. Sends an appointment confirmation email automatically.

---

## Features

- AI-assisted administrative patient routing
- Automatic department recommendation
- Priority assignment
- Clinic recommendation
- Administrative reception summary
- Google Sheets integration
- Gmail confirmation emails
- Fully automated workflow using n8n Cloud

---

## Technologies Used

- n8n Cloud
- Google Forms
- Google Sheets
- Google Gemini AI
- Gmail
- JavaScript

---

## Workflow

Google Form → Google Sheets Trigger → Gemini AI → JavaScript Parsing → Update Google Sheet → Gmail Notification

---

## Future Improvements

- Hospital dashboard
- Calendar integration
- SMS notifications
- Multi-language support
- Analytics and reporting

---

## Disclaimer

AfyaFlow provides administrative assistance only and does not provide medical diagnosis or treatment recommendations.
