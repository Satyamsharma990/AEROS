# 🚨 AEROS – AI-Powered Emergency Response System

AEROS is a cross-platform mobile app that enables users to report emergencies quickly and intelligently using AI, with fallback options like SMS for offline functionality. Designed to assist during accidents, medical emergencies, and disasters, it ensures that no cry for help goes unheard—even without the internet.

---

## 📱 Key Features

- 🆘 One-tap SOS alert for instant help
- 🧠 AI-based incident classification using OpenAI
- 📍 Google Maps location sharing
- ☁️ Firebase Firestore for real-time data storage
- 📤 Twilio SMS fallback when internet is unavailable
- 🔐 Secure key management via `.env` files

---

## 🛠 Built With

- **Frontend**: Expo React Native (TypeScript), React Navigation
- **Backend**: Node.js + Express (TypeScript)
- **Database**: Firebase Firestore
- **APIs & Services**: OpenAI, Twilio
- **Utilities**: Axios, dotenv, Yarn, Expo Go

---

## 📂 Folder Structure

AEROS-Emergency-Response-App/
├── aeros-app/ # React Native frontend
│ ├── components/
│ ├── screens/
│ ├── App.tsx
│ └── ...
├── aeros-server/ # Node.js backend
│ ├── src/
│ ├── .env
│ └── index.ts
└── README.md

yaml
Copy
Edit

---

## 🔧 Environment Setup

**Backend `.env` example:**
OPENAI_API_KEY=your_openai_api_key
FIREBASE_API_KEY=your_firebase_config
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
TWILIO_PHONE=your_twilio_phone_number

yaml
Copy
Edit

⚠️ **Note**: Do not upload your `.env` to GitHub. Add it to `.gitignore`.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Satyamsharma990/AEROS-Emergency-Response-App.git
cd AEROS-Emergency-Response-App
2. Start the Backend
bash
Copy
Edit
cd aeros-server
npm install
npx ts-node src/index.ts
3. Start the Frontend (Expo App)
bash
Copy
Edit
cd ../aeros-app
yarn install
npx expo start --tunnel
Ensure your mobile device and PC are on the same network, or use tunnel mode for remote testing.

📷 Screenshots
Add these images to a /screenshots/ folder and update links here.

Home Screen – App entry point

Report Incident – Form with category selection & AI classification

SOS Button – Emergency one-tap alert

Dashboard – Incident log view

Map View – Live location using Google Maps

📹 Demo
🎥 Watch the 2-minute demo
[🔗 Add Your Video Link Here]

🧠 Methodology
Defined pain points in current emergency systems

Designed clean UI/UX with minimal taps to report

Used OpenAI for classifying incident type from user input

Stored reports in Firebase for real-time access

Used Twilio SMS for offline users

Tested and debugged using Expo Go on real devices

🔭 Scope
Current:

AI + manual incident reporting

Real-time map sharing

SMS fallback

Fully demo-ready with mock data

Future:

Responder dashboards

Notification system for nearby responders

Government/civic integration

Voice/video reporting

Multi-language support

👨‍💻 Developer
Satyam Sharma
GitHub: @Satyamsharma990

📄 License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

✅ Just create a `README.md` file in the root of your GitHub repo and paste the above into it.

Would you like me to generate a LICENSE file too?
