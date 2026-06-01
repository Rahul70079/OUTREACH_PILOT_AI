# 🚀 OUTREACH_PILOT_AI

AI-powered cold outreach platform built with the MERN Stack and Groq AI. Generate personalized cold emails, LinkedIn DMs, and follow-up emails instantly to accelerate job outreach, networking, and sales campaigns.

## ✨ Features

* 🤖 AI-Powered Email Generation
* 📩 Personalized Cold Emails
* 💼 LinkedIn DM Generation
* 🔄 Follow-Up Email Creation
* 🔐 JWT Authentication
* 📧 OTP Email Verification
* 📜 Campaign History Tracking
* 🎨 Modern Responsive UI
* ⚡ Fast AI Responses with Groq API

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Tailwind CSS
* Axios
* Hero Icons

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Nodemailer

### AI Integration

* Groq API
* Llama 3.3 70B Versatile Model

---

## 📂 Project Structure

```bash
OUTREACH_PILOT_AI/
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── Backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   └── server.js
│
└── README.md
```

## 🔧 Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/OUTREACH_PILOT_AI.git
cd OUTREACH_PILOT_AI
```

### Backend Setup

```bash
cd Backend
npm install
```

Create `.env`

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

GROQ_API_KEY=your_groq_api_key

JWT_SECRET=your_jwt_secret

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
```

Run Backend

```bash
npm run dev
```

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

## 🚀 Usage

1. Register a new account.
2. Verify your email using OTP.
3. Login to the dashboard.
4. Create a new campaign.
5. Enter context or prompt.
6. Generate:

   * Cold Email
   * LinkedIn DM
   * Follow-Up Email
7. Save and access campaign history anytime.

---

## 🔐 Environment Variables

| Variable     | Description               |
| ------------ | ------------------------- |
| PORT         | Backend Port              |
| MONGODB_URI  | MongoDB Connection String |
| GROQ_API_KEY | Groq AI API Key           |
| JWT_SECRET   | JWT Secret Key            |
| EMAIL_USER   | Gmail Address             |
| EMAIL_PASS   | Gmail App Password        |

---

## 🎯 Example Prompt

```text
MERN Stack Developer with 1+ years of experience seeking Software Engineer opportunities in product-based companies.
```

Generated Output:

* Subject Line
* Personalized Cold Email
* LinkedIn DM
* Follow-Up Email

---

## 🌟 Future Enhancements

* Multi-AI Model Support
* Campaign Analytics
* Email Scheduling
* CRM Integration
* Team Collaboration
* Export to PDF
* AI Personalization Scoring

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

GitHub: https://github.com/Rahul70079

---

⭐ If you found this project useful, please consider giving it a star.
