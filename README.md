## 🦷 AI Dental Clinic - Lead Follow-Up & Appointment Booking System

An end-to-end AI automation system that acts as a 24/7 virtual 
receptionist for dental clinics.

### What it does
- Captures leads from Facebook/Instagram Ads, website forms, 
  SMS, WhatsApp, and email
- Responds to new leads within 60 seconds across all channels
- Qualifies patients and detects treatment interest automatically
- Checks Google Calendar availability and offers real appointment slots
- Books confirmed appointments and sends SMS/email confirmations
- Sends automated reminders 24h and 2h before each appointment
- Runs a Day 1 / Day 3 / Day 7 follow-up sequence for cold leads
- Escalates emergencies and upset patients to human staff instantly
- Logs every interaction to Airtable CRM

### Tech Stack
- n8n (workflow automation)
- OpenAI GPT-4o (AI receptionist - Dr. Riley)
- Twilio (SMS + WhatsApp)
- Google Calendar (availability + booking)
- Airtable (CRM + appointments database)
- Gmail (email channel)

### Setup
1. Import the workflow JSON into n8n
2. Fill in the CONFIGURATION node (clinic details, API keys, table IDs)
3. Create Airtable tables using the schema in the workflow notes
4. Build the two calendar sub-workflows and link their IDs
5. Connect all credentials and activate
