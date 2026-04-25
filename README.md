# SHEGUARD X — Offline Emergency Safety System

> Designed to ensure emergency communication even when internet or normal SOS systems fail.

---

## 🌐 Live Demo
👉 https://women-safety-xzdn.vercel.app/

---

# 📌 Problem Statement

In real-world emergency situations:

- Internet may not be available ❌  
- Users may panic and cannot communicate clearly ❌  
- Standard SOS systems send limited information ❌  
- No structured or contextual data reaches responders ❌  

👉 This leads to delayed or ineffective emergency response.

---

# 💡 Solution

SHEGUARD X is an **offline-first intelligent emergency safety system** that ensures help can still be triggered in any condition.

It enhances emergency communication using:

- 📍 Real-time location tracking  
- 🚨 Structured emergency alerts  
- 📶 Offline fallback mechanism  
- ⚡ Fast multi-trigger SOS system  
- 🎙 Voice + manual emergency activation  

---

# ⚙️ Key Features (Advanced Implementation)

## 📍 Geolocation Tracking
- Uses `navigator.geolocation.getCurrentPosition()`
- Captures real GPS coordinates
- Falls back to cached coordinates if needed

---

## 📲 Emergency SMS (Simulation Ready)
- Prepares full SOS message
- Includes:
  - Location link (Google Maps)
  - Time stamp
  - Emergency status
- Opens native SMS app via `sms:` link

---

## 💬 WhatsApp Alert System
- Uses `wa.me` deep link
- Sends pre-filled emergency message instantly

---

## 📋 One-Click Copy Alert
- Uses `navigator.clipboard.writeText()`
- Copies full emergency message instantly

---

## 🎙 Voice Detection System
- Uses `getUserMedia()` + Speech Recognition API
- Detects keywords like:
  - "help"
  - "emergency"
  - "SOS"
- Auto-triggers emergency mode

---

## 🔴 Evidence Recording (Advanced Feature)
- Uses `MediaRecorder API`
- Captures audio during emergency (when permission granted)
- Acts as evidence simulation system

---

## ⚡ Smart Risk Engine
- Calculates risk level:
  - LOW / MEDIUM / HIGH
- Based on:
  - Time of day
  - Network status
  - Trigger type

---

# 🔄 System Flow (Judge-Friendly)

1. User opens app → SAFE mode shown  
2. System detects online/offline state  
3. User triggers SOS (button / voice)  
4. System captures GPS location  
5. Emergency message is generated  
6. Alert options activated:
   - SMS
   - WhatsApp
   - Copy alert  
7. If offline → data stored locally  
8. When network returns → alert can be sent  

---

# 🧪 Demo Flow (Judge Presentation Script)

1. Open application → SAFE state  
2. Click “SIMULATE DANGER” → RED ALERT mode  
3. Show GPS location captured  
4. Show pre-filled emergency message  
5. Click SMS → message opens ready to send  
6. Show WhatsApp alert option  
7. Explain offline fallback behavior  

👉 Judges see: Trigger → Location → Message → Action

---

# 🧠 Tech Stack

- HTML5  
- CSS3  
- JavaScript  
- Geolocation API  
- MediaRecorder API  
- Web Speech API  
- Vercel (Deployment)

---

# 🚀 Deployment

- Platform: Vercel  
- Type: Static Web App  
- Status: Live  

👉 https://women-safety-xzdn.vercel.app/

---

# 🧠 Innovation Highlights

- Offline-first emergency architecture  
- Multi-channel emergency communication (SMS + WhatsApp + Copy)  
- Voice-triggered SOS system  
- Evidence-based emergency recording concept  
- Real-world panic-friendly UI design  

---

# 📈 Future Scope

- Real SMS API integration (Twilio / Firebase)  
- AI-based threat detection system  
- Background location tracking  
- Mobile application version  
- Emergency network relay system  

---

# 👨‍💻 Project Type

Hackathon Prototype (12-hour build)  
Focused on real-world emergency usability and reliability.

---

# 🏁 Conclusion

SHEGUARD X ensures that emergency communication is never blocked by poor connectivity or panic situations by enabling multiple fallback communication methods and structured alerts.

---

⭐ “Built for situations where every second matters.”
