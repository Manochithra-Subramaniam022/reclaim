
🚀 Reclaim – College Lost & Found System

Reclaim is a secure, campus-exclusive Lost & Found web application designed for students of CIT.
The system ensures verified access, secure claim approval, and controlled communication between users.
This is not a public marketplace.
It is a secure institutional system built specifically for college students.

🎯 Project Objective

To create a safe and structured digital platform where:
Students can report lost items
Students can report found items
Claims are verified before communication
Chats are enabled only after approval
Items are archived once returned


🔐 Key Features

1️⃣ Secure Authentication

Only users with @cit.edu.in email can register
Email uniqueness enforced
Session-based authentication


2️⃣ Dashboard

Active Items section
Previous (Returned) Items section
Clean card-based UI
Description & image hidden initially (for security)


3️⃣ Add Lost / Found Item

Users can submit:
Reporter name
Item name
Location
Date
Description
Contact information
Image upload

All items are stored securely with ownership tracking.

4️⃣ Secure Claim Approval System (Core Logic)

When a user sees a Found item:
They cannot view description or image
They can only send a request

Owner receives the request in Inbox.
Before accepting, the owner sees:
Lost item description
Found item description + image (comparison step)


Owner can:

✅ Accept → Chat enabled
❌ Reject → No chat access

Users can re-request later.


5️⃣ Chat System

Available only after request approval
WhatsApp-style layout
Messages stored with timestamp
Only owner and requester can access

If item is marked returned:
Chat becomes read-only

6️⃣ Mark as Returned

Owner can mark item as returned.
System automatically:

Moves item from Active → Previous section
Disables chat permanently


🛠️ Tech Stack

Backend

Python
Flask
SQLite
Session-based authentication

Frontend

React.js
Vite
Axios
Modern SaaS-style UI



🌐 Deployment

🔗 Live Application

Deployed using:

Frontend: Ngrok tunnel / Cloud hosting
Backend: Flask server


👉 Live URL:
https://davin-vaccinial-ardelia.ngrok-free.dev/


📂 Project Structure

Reclaim/
│
├── backend/
│   ├── app.py
│   ├── lostfound.db
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── services/
│
└── README.md


🔒 Security Rules Implemented

Only official college emails allowed
Description & image hidden before approval
Only owner can mark item returned
Only involved users can access chat
Chat disabled after item returned


📈 Future Enhancements

Email OTP verification
Admin moderation panel
Image similarity detection (AI-based)
Cloud storage for images
Notification system


Or using Ubuntu VPS?


I’ll customize the Deployment section properly with exact commands and instructions so your README looks industry-level.
