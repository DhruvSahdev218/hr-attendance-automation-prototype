
# HR Attendance Automation Prototype

## Overview
This prototype automates biometric attendance processing using n8n workflows.

Features:
- Webhook-based Excel upload
- Attendance extraction
- Daily check-in/check-out consolidation
- Late arrival detection
- Monthly strike counting
- AI-generated warning emails
- Calendar escalation logic
- Google Sheets tracking
- Airtable setup task

## Included Files
- workflow.json
- documentation.docx
- sample_attendance.csv
- daily_processed_records.csv
- monthly_late_counter.csv
- airtable_setup_notes.txt

## Workflow Logic
1. Upload attendance Excel via Webhook
2. Extract biometric data
3. Consolidate IN/OUT records
4. Detect late arrivals after 11:00 AM
5. Update monthly strike counter
6. Generate AI warning messages
7. Trigger escalation on 3rd strike
8. Schedule HR calendar meeting

## Technologies
- n8n
- Google Sheets
- OpenAI API
- Gmail API
- Google Calendar API

