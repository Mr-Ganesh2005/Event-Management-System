📘 Event Management System
A conflict-free scheduling web app using Greedy & Graph Algorithms
⭐ Overview

The Event Management System is a web-based application that schedules events without time or venue clashes.
It uses Interval Scheduling (Greedy Algorithm) and Topological Sorting to optimize event allocation and ensure efficient resource usage.

This project was developed as part of the Design and Analysis of Algorithms (DAA) course.

🎯 Features

Add events with name, start time, end time, and venue

Automatically prevents overlapping events

Implements Greedy Scheduling for optimal event selection

Uses Topological Sorting for dependency resolution

Clean, simple, user-friendly web interface

Fast backend built with Python Flask

🧠 Algorithms Implemented
1️⃣ Interval Scheduling (Greedy Algorithm)

Sorts events by earliest finishing time

Selects non-overlapping events

Produces an optimal maximum set of events

2️⃣ Topological Sorting

Constructs a graph for overlapping events at the same venue

Ensures valid ordering when dependencies exist

Avoids cycles and conflicting schedules


🏛️ System Architecture
Frontend (Client)

HTML for structure

CSS for styling and layout

JavaScript (Fetch API) for sending requests to backend

Backend (Server)

Python Flask

Implements scheduling logic

Validates times and venue

Returns final timetable as JSON

📂 Project Structure
Event-Management-System/
│── app.py               # Flask backend + algorithms
│── DAA AAT.html         # Frontend UI (HTML, CSS, JS)
│── README.md            # GitHub documentation
│── requirements.txt     # Dependencies (Flask, NetworkX)
└── static/              # (Optional) CSS/JS assets

🖥️ User Interface

(You can replace the image below with screenshots from your local project)

Event Scheduler  
Event Name: __________  
Start Time (HH:MM): ___  
End Time (HH:MM): _____  
Venue: Auditorium / Conference Hall / Seminar Room  
[ Add Event ]  


Example output from your report (page 15) 

DAA AAT

:

Scheduled Events:
Seminar: 09:00 - 10:00 at Auditorium
Workshop: 10:30 - 11:30 at Auditorium

🔧 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/Event-Management-System.git
cd Event-Management-System

2️⃣ Install dependencies
pip install flask networkx

3️⃣ Run the server
python app.py

4️⃣ Open in browser
http://127.0.0.1:5000

🚀 How It Works

User submits event details from the form

JavaScript sends the data to Flask backend using Fetch API

Backend validates the inputs

Events are processed using:

Greedy Interval Scheduling

Topological Sorting (if conflicts)

The final conflict-free timetable is returned

Frontend displays the result

📈 Future Enhancements

Real-time venue availability

Calendar-style UI

Advanced algorithms like Genetic Algorithms

User priority & preferences

Venue utilization analytics

🏁 Conclusion

This project demonstrates how DAA concepts such as Greedy algorithms and Graph algorithms can be effectively applied to real-life scheduling problems. The system ensures optimal event allocation and provides a simple and efficient interface for event organizers.

📚 References

Flask Documentation

NetworkX Documentation

DAA Course Material
