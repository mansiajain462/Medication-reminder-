# Medication-reminder-
It will basically keep a track of your schedule on your medicines and remind you to take it
Medication_-Reminder_-For_The-_Elderly The Medication Reminder App is a user-friendly application designed to help individuals manage their medication schedules effectively. The app provides a graphical user interface (GUI) using the Tkinter library in Python, making it accessible and easy to use. my name is MANSI MANEKAR i have created this project under vityarthi flipped course .

Project Requirements

Create a Medication Reminder App with a GUI using Tkinter. Allow users to add medication schedules by providing medication name, dosage, frequency, and schedule time. Store medication schedules in a CSV file. Provide a functionality to display all medication schedules. Allow users to set reminders for medication based on schedule time. Include an option to exit or close the application. Implement text-to-speech functionality for voice feedback and instructions.

Medication Reminder App
Project Overview
The Medication Reminder App is a desktop application built using Python's Tkinter library that helps users manage their medication schedules effectively. The application provides an intuitive graphical interface with voice feedback capabilities to assist users in tracking their medications, setting reminders, and maintaining adherence to their prescribed medication regimens.
Features
Core Functionalities

Add Medication Schedule: Users can input medication details including name, dosage, frequency, and scheduled time
Display Medication Information: View all stored medication schedules in an organized format

Set Medication Reminders: Automatic time-based reminders that alert users when it's time to take their medication
Voice Feedback: Text-to-speech functionality provides audio guidance for better accessibility
Data Persistence: All medication data is stored in CSV format for easy retrieval and management
Additional Features

Clean and intuitive dark-themed user interface
Real-time reminder notifications using message boxes
Easy-to-navigate menu system
Secure data storage in local CSV files

Technologies & Tools Used

Programming Language: Python 3.x
GUI Framework: Tkinter (built-in Python library)
Text-to-Speech: pyttsx3 library
Date/Time Parsing: dateutil library
Data Storage: CSV (Comma-Separated Values) file format
Version Control: Git/GitHub
Prerequisites
Before running the application, ensure you have Python 3.x installed on your system along with the required libraries.
Installation & Setup
Step 1: Clone the Repository
bashgit clone https://github.com/yourusername/medication-reminder-app.git
cd medication-reminder-app
Step 2: Install Required Dependencies
bashpip install pyttsx3
pip install python-dateutil
Step 3: Create Medication Data File
Create a file named medication.csv in the same directory as the main script with the following header:
csvMedication Name,Dosage,Frequency,Schedule Time
Step 4: Run the Application
bashpython medication_app.py
How to Use
Adding a Medication

Click the "Add Medication" button on the main window
Enter the medication name (e.g., "Aspirin")
Enter the dosage (e.g., "500mg")
Enter the frequency (e.g., "Once daily", "Twice daily")
Enter the schedule time in format HH:MM or natural language (e.g., "14:30" or "2:30PM")
Click "Add Medication" to save

Viewing Medications

Click the "Display Medication" button
Click "Click to view Medication" to see all stored medications
All medication details will be displayed in a scrollable list

Setting Reminders

Click the "Set Reminder" button
The system will check current time against all scheduled medications
If any medication matches the current time, a reminder popup will appear
Console will also log the reminder message

Exiting the Application

Click the "Exit/Close" button to safely close the application
Project Structure
medication-reminder-app/
│
├── medication_app.py          # Main application file
├── medication.csv             # Data storage file
├── README.md                  # Project documentation
├── statement.md               # Project statement
└── requirements.txt           # Python dependencies
Testing Instructions
Manual Testing

Add Medication Test:

Open the app and add a medication with current time +2 minutes
Verify the data is saved in medication.csv
Display Test:

Add multiple medications
Click Display Medication
Verify all entries appear correctly


Reminder Test:

Add a medication with current system time
Click Set Reminder
Verify popup appears with correct medication name


Voice Feedback Test:

Navigate through different screens
Verify voice announcements are clear and relevant



Data Validation Testing

Test with empty fields
Test with invalid time formats
Known Limitations

Reminders only trigger when "Set Reminder" button is clicked (not continuous monitoring)
Time format parsing depends on dateutil library interpretation
No edit or delete functionality for existing medications
Single-user application (no multi-user support)

Future Enhancements

Continuous background reminder monitoring
Edit and delete medication functionality
User authentication and multi-user profiles
Mobile app integration
Cloud synchronization
Medication history and adherence tracking
Integration with pharmacy APIs
Dosage tracking and refill reminders

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository
Create a feature branch (git checkout -b feature/NewFeature)
Commit your changes (git commit -m 'Add NewFeature')
Push to the branch (git push origin feature/NewFeature)
Open a Pull Request

License
This project is developed as part of academic coursework at VIT.
Author
Mansi Manekar
VIT Student
Contact: mansi.25bcy10094@vitbhopal.ac.in 
Acknowledgments

VIT Faculty for project guidance
Python community for excellent documentation
pyttsx3 and dateutil library contributors
