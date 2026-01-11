# Smart-Event-Managment-
<img width="807" height="620" alt="image" src="https://github.com/user-attachments/assets/555c6a96-597c-4c32-885d-6d25b4978a87" />
**frontend run**
cd frontend
npm install
npm start
Twilio WhatsApp API integrated
Registration confirmation sent to users API keys hidden for security
**backend**
cd backend
npm install
node server.js
**how to run smart event management web app**
REQUIREMENTS (Install first)

Make sure these are installed on your system:

Node.js (v16 or above)
Check:(Open in Terminal)
node -v
npm -v
MongoDB

Install MongoDB Compass or MongoDB Community Server

Start MongoDB service

Check:
mongod
**RUN BACKEND (IMPORTANT)**
Open terminal / command prompt inside the project folder
cd backend

Install backend dependencies
npm install

Start backend server
node server.js


✅ You should see:

MongoDB Connected
Backend running on http://localhost:5000
**RUN FRONTEND (NEW TERMINAL)**
Open a new terminal window
cd frontend

Install frontend dependencies
npm install

Start React app
npm start


✅ Browser opens automatically:

http://localhost:3000
**CREATE AN EVENT (ONE-TIME)**

Open Postman or browser extension:

POST → Create Event
POST http://localhost:5000/api/events/create


Body (JSON):

{
  "title": "College Hackathon",
  "date": "28-29 Jan 2026",
  "venue": "SRM Campus"
}
**UPDATE EVENT ID (VERY IMPORTANT)**

Open file:

frontend/src/pages/Events.js


Replace:

const eventId = "PASTE_EVENT_ID_FROM_DB";


with:

const eventId = "PASTE_THE_EVENT_ID_HERE";
<img width="1600" height="716" alt="image" src="https://github.com/user-attachments/assets/f08d8244-7068-45dc-8964-795b06f6708d" />
<img width="1600" height="234" alt="image" src="https://github.com/user-attachments/assets/fbd20f34-8cb7-46fd-a8da-5e18d6bd7e41" />

