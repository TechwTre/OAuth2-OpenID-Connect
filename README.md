# OAuth2 & OpenID Connect Implementation and Attacks

## 📌 Project Overview
This project covers both **OAuth2 & OpenID Connect (OIDC) implementation** and **security attacks** against these protocols. It includes practical examples of setting up OAuth2/OIDC and demonstrating common attack vectors.

## 🚀 Features
- 🔑 **OAuth2 Authorization Code Flow Implementation**
- 🔓 **Common OAuth2/OIDC Attacks (Token Hijacking, Code Injection, etc.)**
- 🛡 **Mitigation Techniques Against Security Threats**
- 🏗 **Okta & OpenID Connect Integration**

---

## 🛠 Prerequisites
- [ ] Okta Developer Account ([Sign up for free](https://developer.okta.com/))
- [ ] Python 3.x installed
- [ ] OAuth2 Client ID & Secret
- [ ] Web Application for authentication testing

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourgithubusername/oauth2-oidc-attacks.git
cd oauth2-oidc-attacks
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the project root and add:
```
OKTA_ORG_URL=https://your-okta-domain.okta.com
OAUTH2_CLIENT_ID=your_client_id
OAUTH2_CLIENT_SECRET=your_client_secret
```

### 4️⃣ Run the OAuth2/OIDC Setup & Attack Simulations
```bash
python setup_oauth2.py
python attack_simulations.py
```

---


