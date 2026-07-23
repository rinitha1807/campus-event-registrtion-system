EventEase – Smart Campus Event Registration System

Problem Statement
College clubs conduct several technical and non-technical events throughout the academic year. Managing registrations manually often leads to:
- Duplicate registrations
- Difficulty in tracking participants
- Last-minute confusion regarding student attendance
- Schedule clashes between events
- Difficulty forming teams for hackathons and competitions
- Poor communication between organizers and participants
Challenge:
Design and develop a smart platform that simplifies event registration, participant management, attendance tracking, and event communication for both students and organizers
Our Solution
EventEase is an AI-powered campus event management platform that goes beyond traditional event registration. It provides intelligent recommendations, smart team formation, conflict detection, and real-time participant tracking.
 Unique Features
1.  AI Event Recommendation
Instead of displaying every event, the system recommends events based on:
- Department
- Year of Study
- Skills
- Interests
- Previously attended events
Example
A student interested in:
- AI
- Coding
- Hackathons
will receive recommendations such as:
- AI Workshop
- 24-Hour Hackathon
- Coding Contest
While a Commerce student receives:
- Business Quiz
- Marketing Challenge
- Entrepreneurship Workshop
2. Smart Team Formation
Students often struggle to find teammates for hackathons.
Our solution allows students to create a profile including:
- Skills
- Programming Languages
- Interests
- Experience Level
The system automatically suggests compatible teammates based on complementary skills.
Example
Student| Skills
Ravi| Python, AI
Priya| UI/UX
Karthik| Backend Development
 Suggested Team:
- Ravi
- Priya
- Karthik
3. Duplicate Registration Detection
Instead of checking only the Roll Number, EventEase intelligently detects duplicate registrations using:
- Roll Number
- Email
- Phone Number
- Similar Names
This prevents duplicate entries and ensures accurate participant records.
4.  Smart Schedule Clash Detection
If a student registers for two overlapping events, the system immediately alerts them.
Example
Coding Contest
 10:00 AM – 12:00 PM
Hackathon
 11:00 AM – 5:00 PM
"This event overlaps with another registered event.
5. Live Attendance Tracking
Every registered student receives a unique QR code.
On the event day:
- Student scans QR at entry
- Attendance is marked automatically
- Organizer views real-time attendance
Dashboard Example:
- Registered: 120
- Present: 98
- Not Arrived: 22
This eliminates last-minute confusion regarding participant presence.
6.  Instant Event Notifications
Organizers can instantly notify all registered participants about:
- Venue changes
- Time changes
- Event updates
- Important announcements
Notifications are sent in real time.
7.  Organizer Dashboard
The dashboard provides live analytics such as:
- Total Registrations
- Live Attendance
- Event Popularity
- Department-wise Participation
- Registration Statistics
 Technologies Used
Frontend
- React.js
- HTML5
- CSS3
- JavaScript
- Tailwind CSS
Backend
- Node.js
- Express.js
Database
- MongoDB
Authentication
- Firebase Authentication / JWT
AI Recommendation
- Python
- Scikit-Learn
- Reccommendation Algorithm
QR Code
- QR Code Generator
QR Scanner API
 Notifications
- Firebase Cloud Messaging (FCM)
- Email Notifications
Deployment
- Vercel (Frontend)
- Render / Railway (Backend)
- MongoDB Atlas





