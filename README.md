# AfyaFlow AI Appointment Automation

## Overview

AfyaFlow is an AI-powered hospital appointment automation workflow that helps hospital reception teams efficiently route patient appointment requests.

Patients submit an appointment request through a Google Form. The workflow automatically analyses symptoms using Google Gemini AI, assigns the appropriate department and priority level, updates Google Sheets with the results, and sends a confirmation email to the patient.

This workflow supports administrative triage only and does not provide medical diagnosis.

---

## Features

- Google Forms patient intake
- Automatic AI symptom classification
- Department recommendation
- Priority assignment
- Clinic recommendation
- Administrative reception summary
- Automatic Google Sheets updates
- Email confirmation via Gmail
- Built using n8n Cloud

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

1. Patient submits appointment form
2. Google Sheets trigger detects new response
3. Gemini AI analyses symptoms
4. JavaScript parses AI response
5. Google Sheets updates patient record
6. Gmail sends appointment confirmation

---

## Disclaimer

AfyaFlow provides administrative routing assistance only and does not diagnose medical conditions. Patients are always referred to qualified healthcare professionals for clinical assessment.
