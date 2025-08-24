# AI Secretary Agent for Appointments

This project is an **AI-powered secretary agent** that extracts appointment requests from natural language text (emails, chat messages, etc.) and automatically generates an `.ics` calendar file, which can be imported into Google Calendar, Outlook, and other calendar applications.

## 🚀 Features
- Extracts **multiple dates and times** from a text message.  
- Automatically creates separate calendar events for each detected appointment.  
- Saves all events in a universal `.ics` calendar file.  
- Supports natural language time expressions like:  
  - "next Tuesday at 3 pm"  
  - "Wednesday morning at 10"  
  - "tomorrow afternoon"  

## 🛠️ Technologies
- [spaCy](https://spacy.io/) for Named Entity Recognition (NER).  
- [dateparser](https://dateparser.readthedocs.io/) for flexible date/time parsing.  
- [ics.py](https://icspy.readthedocs.io/) for generating `.ics` calendar files.  

## 📂 Project Structure
ai-secretary/
│── secretary.py # Main script
│── requirements.txt # Dependencies
│── README.md # Documentation
│── appointments.ics # Example output file

## ▶️ How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/ai-secretary.git
   cd ai-secretary

2. Install dependencies:
pip install -r requirements.txt

3. Run the script:
python secretary.py

4. Import the generated appointments.ics into your calendar application.


## 📈 Next Improvements
Extract participant names (e.g., "Call with John").
Integrate with Gmail/WhatsApp APIs for real-time appointment scheduling.
Add reminders and recurring events.

👨‍💻 Author: Angelo Sorte
📅 Version: 1.0
