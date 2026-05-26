# ARIA — AI Medical Receptionist

An AI-powered voice receptionist built to automate clinic appointment booking using VAPI and Zapier system integration.

---

## 🔴 Live Demo
Call ARIA right now: **+1 (925) 332-3065**
Speak in English, Hindi, or Marathi — she will check real-time availability and book a real appointment on a live Google Calendar.

---

## Features
- Automated inbound call handling via AI voice agent
- Real-time appointment booking on Google Calendar
- Slot conflict prevention — zero double bookings
- Multilingual support — English, Hindi, and Marathi
- Automated email confirmation sent post-booking
- Full call transcript and workflow logs on VAPI dashboard

---

## Tech Stack
- VAPI (Voice AI Platform)
- Zapier (Automation & System Integration)
- GPT-4.1 by OpenAI (Language Model)
- Deepgram (Multilingual Speech-to-Text)
- Google Calendar API (via Zapier)
- Gmail (Automated Email via Zapier)
- Prompt Engineering

---

## How It Works
1. Patient calls +1 (925) 332-3065
2. ARIA answers and detects preferred language (English / Hindi / Marathi)
3. Zapier Workflow 1 queries Google Calendar for free and busy slots in real time
4. Patient selects a slot — Zapier Workflow 2 creates the appointment on the doctor's calendar
5. If patient provides their email, confirmation is sent automatically via Gmail
6. ARIA confirms the booking verbally and ends the call

---

## System Integration Architecture
**VAPI ↔ Zapier ↔ Google Calendar**

- Zapier Workflow 1 — Find Busy Periods in Calendar
- Zapier Workflow 2 — Quick Add Event to Calendar

Both workflows are triggered mid-call by ARIA through VAPI's tool calling feature.

---

## Results
- 100% booking success rate across all test calls
- Zero double bookings
- Average latency — ~1,150ms
- Average cost — ~$0.10 per minute
- Tested in English, Hindi, and Marathi

---

## Note on Phone Number
A US number is used because VAPI's free tier allocates US numbers. Obtaining an Indian number requires a registered business, GST number, PAN card, and license — which as a student I don't currently have. Getting an Indian number is the first planned upgrade.

---

## Future Improvements
- Indian phone number once business registration is available
- Multi-doctor calendar support with specialty routing
- WhatsApp and web chat interface
- Symptom pre-screening before appointments
- Analytics dashboard for clinic management
- Patient data privacy — DPDP Act compliance

---

## Project Context
Developed independently as a First Year Capstone Project
B.Tech CSE (AI & ML) — DY Patil College of Engineering and Technology, Kolhapur
A.Y. 2025-26

---

## Author
**Hrujula Patil**
hrujula2@gmail.com
