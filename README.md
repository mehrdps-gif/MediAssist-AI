# MediAssist-AI
 an intelligent healthcare management companion that centralizes medicines, appointments, medical reports and wellness analytics into a premium experience. With AI-style report summarization, adherence tracking, health scoring, and visual insights, it empowers users to stay organized while supporting safe, non-diagnostic healthcare decision-making.
MediAssist AI is a polished healthcare organization MVP built with Python and Streamlit. 

This application provides educational and organizational assistance only and does not provide medical advice, diagnosis or treatment.

## Features

- Premium Apple Health, Flo, Headspace-inspired UI
- Personalized dashboard with health score, wellness summary, recent activity, and quick statistics
- Medicine manager with add, edit, delete, search, dosage, frequency, reminder times, notes, and adherence controls
- Appointment manager with upcoming visit cards and full CRUD support
- Health tracker for water, sleep, weight, exercise, BMI, and Plotly analytics
- Medical vault for PDF, JPG, PNG, and JPEG uploads with file metadata and previews
- Educational AI-style report summaries for text-based PDF reports, with key values and doctor questions
- Daily medicine timeline with Taken/Missed tracking
- Doctor visit prep brief with profile, medicines, wellness snapshot, and downloadable notes
- User profile with emergency contact, allergies, and medical conditions
- SQLite persistence for medicines, dose events, appointments, profile, health logs, activities, report summaries, and vault metadata
- Responsive Streamlit layout with reusable components and custom CSS

## Tech Stack

- Python
- Streamlit
- Pandas
- Plotly
- SQLite
- PyPDF2
- Pillow
- datetime
- streamlit-option-menu

## Installation

```bash
git clone <your-repository-url>
cd mediassist-ai
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

On macOS or Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

## Screenshots

Add screenshots here after running the application:

- Dashboard
- Medicine Manager
- Doctor Visit Prep
- AI Report Summary
- Medical Vault
- Health Tracker

## Project Structure

```text
mediassist-ai/
├── app.py
├── requirements.txt
├── README.md
├── mediassist.db        # created automatically
└── uploads/             # created automatically
```

## Future Scope

- Secure authentication and multi-user accounts
- Calendar integrations for appointment reminders
- Email and SMS medicine reminders
- Wearable device integrations
- Encrypted medical file storage
- Clinician sharing workflows
- FHIR-compatible health record import/export
- AI-powered educational summaries with strict medical safety guardrails

## License

MIT License. Use freely for learning, demos, hackathons, and portfolio projects.
