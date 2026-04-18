# 🧠 SkinWizard – AI-Powered Skin Disease Detection System (Backend)

## 📌 Overview

SkinWizard is a web-based platform designed to assist doctors by providing AI-powered analysis of skin images. The system acts as a **second-opinion diagnostic tool**, helping identify potential skin diseases from uploaded images.

This repository contains the **backend implementation** built with Django and Django REST Framework.

---

## 🚀 Features

* 🔍 AI-based skin disease detection (image analysis)
* 👨‍⚕️ Doctor–Patient interaction system
* 💊 Prescription management via Pharmacy module
* 🔐 Secure authentication (JWT & OAuth)
* ☁️ Cloud integration with AWS:

  * Image storage
  * AI model hosting
* 📄 Medical report generation (PDF support)
* 🌐 RESTful APIs for frontend/mobile integration

---

## 🏗️ Project Structure

```
.
├── accounts/         # Authentication & user management
├── consultation/     # Doctor-patient interaction logic
├── content/          # Static and dynamic content
├── diagnosis/        # AI diagnosis handling
├── pharmacy/         # Prescription and medicine module
├── patient_form/     # Patient data collection
├── skinwizard/       # Main project settings
├── manage.py
├── requirements.txt
└── db.sqlite3
```

---

## ⚙️ Tech Stack

* **Backend Framework:** Django, Django REST Framework
* **Authentication:** JWT (SimpleJWT), Djoser, Django Allauth
* **Database:** PostgreSQL / SQLite (dev)
* **Cloud:** AWS (S3, model hosting)
* **AI Integration:** External ML model (image classification)
* **Other Tools:** Docker , CORS, Swagger (drf-yasg)

---


## 🔗 API Documentation

Swagger UI available at:

```
/swagger/
```

---

## 🧪 Example API Endpoints

| Endpoint         | Method   | Description                  |
| ---------------- | -------- | ---------------------------- |
| `/auth/`         | POST     | User authentication          |
| `/diagnosis/`    | POST     | Upload image for prediction  |
| `/consultation/` | GET/POST | Doctor-patient communication |
| `/pharmacy/`     | GET/POST | Manage prescriptions         |

---

## 🔐 Authentication

* JWT-based authentication
* Social login via Google (Django Allauth)
* Token-based API protection

---

## 📊 AI Model Integration

* Accepts image uploads
* Sends images to AI model (hosted on AWS)
* Returns predicted disease with confidence score

---

## 🧩 Future Improvements

* Real-time chat between doctors and patients
* Model accuracy enhancement
* Deployment with Kubernetes (in progress 🚀)
* CI/CD pipeline integration

---

## 👩‍💻 Author

**Zakya Akram**

---



