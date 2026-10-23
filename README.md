# 🛡️ Verify Portal

## Secure authentication, seamless recovery, and role-based access.

> **Infosys Springboard Internship 7.0 | Batch 4 | Milestone 1**

🐍 **Python** · 🎈 **Streamlit** · 🔐 **JWT** · 🔒 **bcrypt** · 🗃️ **SQLite**

## ✨ About the project

**Verify Portal** is a modern, secure authentication system built with Streamlit. It lets users create accounts, sign in safely, recover passwords through two secure methods, and access a role-aware dashboard.

The project focuses on making authentication feel both **safe** and **simple** - from signup to account recovery. 🔐

## 🌟 Key features

| 🔑 Authentication | 🛡️ Security | 📊 Experience |
| :--- | :--- | :--- |
| Login with username or email | JWT-based protected sessions | Modern responsive interface |
| Signup with email verification | bcrypt password hashing | Password-strength feedback |
| Six-digit OTP verification | Login and OTP attempt limits | User dashboard |
| Password reset flow | Security-question recovery | Administrator dashboard |
| Logout and session cleanup | Generic login errors | Registered-user directory |

## 🧭 User journey

```text
Sign Up  →  Verify OTP  →  Secure Login  →  Dashboard
                              │
                              ▼
                     Forgot Password?
                    ┌─────────┴─────────┐
                    ▼                   ▼
             Email OTP 🔢      Security Question ❓
                    └─────────┬─────────┘
                              ▼
                     Create New Password ✅
```

## 🧰 Tech stack

| Technology | Purpose |
| :--- | :--- |
| 🐍 **Python** | Core application logic |
| 🎈 **Streamlit** | Interactive web interface |
| 🔐 **PyJWT** | Secure session tokens |
| 🔒 **bcrypt** | Password hashing |
| 🗃️ **SQLite** | User data storage |
| 📧 **Gmail SMTP** | One-time-password email delivery |
| 🌐 **ngrok** | Public access from Google Colab |


## ☁️ Run with Google Colab

1. Upload and open `Verify_portal.ipynb` in Google Colab.
2. Add `JWT_SECRET`, `NGROK_AUTHTOKEN`, `EMAIL_ADDRESS`, and `EMAIL_PASSWORD` in **Colab Secrets**.
3. Allow notebook access for every secret.
4. Run all cells, then open the public ngrok link. ✨

## 📸 Project screenshots

### 🔐 Login page

<img width="1917" height="970" alt="image" src="https://github.com/user-attachments/assets/25c62dba-b1fa-42d3-b66d-3a5e55412c1c" />

### 📝 Create account

<img width="1917" height="968" alt="image" src="https://github.com/user-attachments/assets/17fca2e9-2dad-48fd-9817-b90960c4aade" />


### 🔢 OTP verification

<img width="1917" height="972" alt="image" src="https://github.com/user-attachments/assets/400c2b0f-cfdb-4eaa-9897-e34a87f33154" />


### 🔄 Password recovery

<img width="1917" height="970" alt="image" src="https://github.com/user-attachments/assets/38eae06b-a942-44e2-abcb-ed8df6e626a4" />


### 👤 User dashboard

<img width="1917" height="971" alt="image" src="https://github.com/user-attachments/assets/80ef2172-8b11-4350-97d9-e8f87293038a" />


## 🔒 Security reminder

🚫 Never upload `.env` files, email app passwords, JWT secrets, real OTPs, ngrok tokens, or private database files to GitHub.

