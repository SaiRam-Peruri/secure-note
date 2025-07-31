🔐 SecureNote – Encrypted Note Sharing Platform (MERN Stack)
SecureNote is a production-ready web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that enables secure, anonymous, and self-destructing note sharing. It provides features like end-to-end encryption, password protection, read-tracking, and auto-expiring links, making it ideal for privacy-focused users such as journalists, lawyers, or internal teams sharing sensitive data.

🚀 Key Features
🔒 End-to-End Encryption
Notes are encrypted on the client side and can only be decrypted with a valid key, ensuring complete confidentiality.

🕒 Self-Destructing Notes
Notes are automatically deleted after being read once or when they expire at a specified time.

🔗 One-Time Shareable Links
Generate secure, single-use URLs for sharing notes.

🛡️ Password Protection
Add an extra layer of security by requiring a password to open a note.

📩 Read Notifications
Get instant email alerts when a note is accessed.

🧠 Lessons Learned
Technical Proficiency
Designed modular MongoDB schemas and implemented secure Express routes.
Developed async workflows for encryption/decryption using Node.js.
Managed secure client-server communication with RESTful APIs.
Problem-Solving
Solved encryption challenges while maintaining performance.
Handled simultaneous note expiration events and email notification race conditions.
Teamwork & Project Management
Adopted an Agile workflow with modular milestones.
Efficient debugging and collaboration helped resolve complex integration issues.
🐞 Known Issues
Minor delays in email alerts under heavy server load.
Rare edge cases in simultaneous note expiration handling.
🔮 Future Enhancements
📎 File attachments (secure image/document sharing)
👥 Group notes with multi-user read tracking
📶 Offline note creation/viewing
🔐 Custom encryption algorithm selection
🛠 Tech Stack
Technology	Usage
MongoDB	Encrypted data storage (NoSQL DB)
Express.js	RESTful API backend
React.js	Frontend UI and state management
Node.js	Backend runtime and crypto functions
SendGrid	Email delivery for read alerts
Crypto	End-to-end encryption of notes
📂 Folder Structure

SecureNote/
├── models/
├── routes/
├── utils/
├── components/
├── pages/
├── .env
└── README.md

⚙️ How to Run Locally
Clone the repository

git clone https://github.com/yourusername/SecureNote.git
cd SecureNote
Install dependencies

npm install
Start the app

npm start
⚠️ Ensure .env contains your MongoDB URI, SendGrid API key, and encryption secrets.

💼 Ideal Use Cases
Internal secure messaging in organizations
Anonymous whistleblower or journalist portals
Confidential legal or medical data transmission
📣 Final Note
SecureNote was not just built to showcase a MERN app, but to demonstrate how privacy, encryption, and modern web development can be integrated to create secure, real-world-ready software. Its modular design and scalability make it fit for future enhancements and cloud-based deployments.

🚀 Deployment to Google Cloud Run
SecureNote is successfully deployed on Google Cloud Run. It is fully functional and publicly accessible via the following URL:

SecureNote – Live App

Cloud Run Deployment
Backend: Hosted on Cloud Run in a serverless, scalable environment.
Environment Variables: Managed securely via Google Cloud Secret Manager.
Scalable: Auto-scaling based on incoming traffic (no server management required).
HTTPS Enabled: SSL/TLS is automatically provided for secure connections.
Languages:

JavaScript: 57.7%
EJS: 38.9%
CSS: 3.4%
