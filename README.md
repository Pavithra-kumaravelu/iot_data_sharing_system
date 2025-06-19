
# 🔐 Smart IoT Data Sharing System

A secure, cloud-integrated platform for encrypted IoT data sharing and access control. This project enables privacy-preserving data exchange between IoT devices and users using role-based permissions, OTP verification, and AES encryption. Ideal for edge-cloud environments, it supports real-time log ingestion, secure cloud storage, and fine-grained access.

---

## 📌 Features

* 🔒 **AES Encryption** of all IoT-generated data
* 🧑‍💼 **Role-based Access Control** (Viewer, Analyst, Editor, Auditor, Admin)
* 📧 **OTP-based Authentication** for secure data decryption
* 🌐 **Firebase Integration** for encrypted cloud storage
* 📡 **ThingSpeak Support** for IoT edge simulation
* 🧾 **Audit Logs** for admin & auditor monitoring
* 🖥️ **Responsive Dashboard** for all roles
* 🗃️ **Session-based Previews** for temporary data access

---

## ⚙️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript (vanilla)
* **Backend**: Python (Flask)
* **Database**: SQLite
* **Cloud**: Firebase (for storing encrypted IoT logs)
* **Edge Platform**: ThingSpeak (IoT simulation)
* **Security**: AES-GCM Encryption, OTP validation, role guards

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/smart-iot-data-sharing.git
cd smart-iot-data-sharing
```

### 2. Create & Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Setup Firebase (optional)

* Add your Firebase credentials (API key, project ID, etc.) in a `firebase_config.py` or environment variables.

### 5. Run the App

```bash
python final.py
```

Visit: `http://127.0.0.1:4000/` in your browser.

---

## 🧪 Roles and Access

| Role    | Permissions                                 |
| ------- | ------------------------------------------- |
| Viewer  | Request + Preview decrypted data            |
| Analyst | Decrypt/download logs using OTP + key       |
| Editor  | Request + Edit IoT logs (post-approval)     |
| Auditor | View audit trails                           |
| Admin   | Manage roles, approvals, logs, and policies |

---

## 📂 Folder Structure

```
├── static/                # CSS, custom JS
├── templates/             # HTML templates
├── final.py               # Main Flask app
├── requirements.txt       # Python dependencies
├── README.md              # This file
└── ...                    # Firebase config, DB, etc.
```

---

## 🛡️ Security Measures

* AES-GCM 256-bit encryption
* OTP verification for sensitive data
* Role & group-based policy enforcement
* Encrypted cloud backup (Firebase)

---

## 👨‍💻 Author

Pavithra Kumaravelu
Email: [kanagask0210@gmail.com](mailto:pavivel2004@gmail.com)
GitHub: [@Pavithra-kumaravelu](https://github.com/Pavithra-kumaravelu)

