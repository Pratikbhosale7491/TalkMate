# 🎙️ TalkMate  

TalkMate is an **English speaking practice app** that connects users with random partners for live voice conversations.  
The goal is to help learners improve fluency, confidence, and real-world communication skills.  

---

## ✨ Features
- 🔐 **User Authentication** (Firebase Auth – email, Google, phone)  
- 🎤 **1-to-1 Random Voice Calls** (matchmaking system)  
- 🔊 **Live Audio Communication** (WebRTC / Firebase RTC)  
- 🗂 **User Profiles** (basic info, practice history)  
- 🕒 **Call History & Matchmaking**  
- 🔔 **Push Notifications** (incoming call, reminders)  
- ⚡ **Scalable Backend** with Firebase  

---

## 🛠️ Tech Stack
**Frontend (Mobile App)**  
- React Native  
- React Navigation  
- Context API + Custom Hooks  

**Backend & Services**  
- Firebase Authentication  
- Firebase Firestore (database)  
- Firebase Cloud Functions (serverless logic)  
- Firebase Realtime Database / WebRTC (voice calls)  
- Firebase Cloud Messaging (notifications)  

---

## 📂 Folder Structure

talkmate-app/
└── src/
├── api/ # Firebase API calls (auth, db, rtc etc.)
├── components/ # Reusable UI components (buttons, cards, loaders)
├── contexts/ # React Context (AuthContext, CallContext)
├── hooks/ # Custom hooks (useAuth, useCall)
├── navigation/ # App navigation setup
├── screens/ # Screens (Login, Profile, Call, Matchmaking)
├── services/ # Services (Firebase, notifications, voice)
└── utils/ # Helpers (validators, formatters, constants)
.gitignore 
README.md 



## 🚀 Getting Started  

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Pratikbhosale7491/TalkMate.git
cd TalkMate/talkmate-app


2️⃣ Install dependencies
bash
Copy
Edit
npm install


3️⃣ Configure Firebase
Create a Firebase project in Firebase Console

Enable Authentication, Firestore, Realtime DB, Functions, and Messaging

Add your Firebase config to the app


4️⃣ Run the app
bash
Copy
Edit
npm run android   # for Android
npm run ios       # for iOS (Mac only)
📌 Roadmap
✅ Setup folder structure

✅ Add Firebase authentication

⬜ Implement voice call matchmaking

⬜ Add user profiles & history

⬜ Push notifications

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a PR.

📜 License
This project is licensed under the MIT License.

Made with ❤️ by Pratik Bhosale

yaml
Copy
Edit

---

