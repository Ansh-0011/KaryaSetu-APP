# KaryaSetu-APP
A software which innovates the workflow of the lobourer work system in India.

# 🇮🇳 KaryaSetu: Empowering Laborers, Enabling Contractors

## 🔥 Problem Statement

> *"Over 92% of India’s workforce is informal, with more than 50 million daily wage laborers struggling every day to find work, get paid fairly, or even prove they worked at all."*  
> — [NSSO Survey, 2019]

In India, millions of laborers still rely on verbal work agreements with **zero proof** and **zero accountability**. Due to digital illiteracy and lack of access to smartphones, they’re easily **cheated by contractors** or forgotten in the payment cycle. On the other side, **genuine contractors** suffer false accusations from workers seeking unearned wages.

## 💡 Our Solution

**KaryaSetu** is a two-way, secure platform designed for **daily-wage laborers** and **contractors**, with **government oversight** to ensure accountability and fairness. With offline-first features, proof-based work logs, and third-party arbitration (via govt login), we’re solving a multi-layered socio-economic problem.

## 🎯 Key Features

- 🔄 **Dual Access**: Separate dashboards for contractors, workers & govt admins.
- 📸 **Proof of Work**: Upload image/video, attendance logs.
- 🧾 **Online Ledger**: Transparent, tamper-proof record of wages and workdays.
- 👮 **Govt Oversight**: Registered admins can verify disputes, approve complaints.
- 🌐 **Offline SMS Mode**: Labourers can get job alerts and wage receipts via SMS.
- 📍 **Nearby Jobs**: Geo-based job suggestions to save travel costs.
- 🔐 **Digital Identity**: Aadhar-based or facial authentication to prevent fraud.

## 🧱 Architecture

- Frontend: React + React Native + Tailwind  
- Backend: Node.js + Express  
- Database: PostgreSQL + Firebase Auth  
- File Storage: Firebase / Cloudinary  
- Cloud Deployment: Vercel / Railway  
- Notification: Twilio + Firebase  
- Govt Verification API: Mocked for MVP  
- Optional ML: Worker validation using images

## 👥 User Roles

| Role       | Access Level                | Abilities |
|------------|-----------------------------|-----------|
| Labourer   | Basic (SMS/Smartphone)      | View job offers, mark attendance, receive payment |
| Contractor | Full                        | Post jobs, track attendance, pay digitally |
| Govt Admin | Super Admin                 | Handle disputes, verify logs, see analytics |

## 📊 Why It Matters

| Data Point | Insight |
|------------|---------|
| 70% of wage complaints | Are due to lack of written agreements |
| 53% laborers | Have been unpaid at least once |
| ₹20,000 crores/year | Lost in unclaimed or unpaid wages |
| 48% contractors | Report trouble verifying work done |

## 🛠️ Tech Stack

- **Frontend**: React.js, React Native, Tailwind CSS
- **Backend**: Node.js, Express.js, JWT
- **Database**: PostgreSQL, Firebase Realtime DB
- **Storage**: Firebase Storage, Cloudinary
- **Auth**: Firebase Auth, OTP (Twilio)
- **APIs**: Google Maps API, SMS Gateway, OCR/FaceMatch (Optional)

## 🧪 MVP Milestones

- [ ] Dual-auth login (laborer/contractor)  
- [ ] Job posting and assignment  
- [ ] Work attendance with proof upload  
- [ ] Payment request + approval + ledger  
- [ ] Dispute system for verification  
- [ ] SMS-based offline mode  
- [ ] Govt admin panel  

## 🧠 Future Enhancements

- Voice-bot assistant for low-literacy laborers  
- Blockchain-based immutable ledger for payments  
- Auto-match based on skill & location  
- Integration with govt employment schemes (MGNREGA)

## 🌍 Impact

If scaled nationwide, **KaryaSetu** could:
- Save ₹5000 crore in wage disputes
- Bring 10M+ workers into the formal economy
- Improve trust between laborers and contractors
- Empower poor families with transparent digital proof

---

> **Let’s not build just another app. Let’s build dignity, trust, and impact.**


