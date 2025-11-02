# 🚀 SAHU-FCA: Unofficial Facebook Chat API

![npm](https://img.shields.io/npm/v/sahu-fca) ![License](https://img.shields.io/badge/License-MIT-green) ![GitHub issues](https://img.shields.io/github/issues/shahadat-sahu/sahu-fca) ![GitHub forks](https://img.shields.io/github/forks/shahadat-sahu/sahu-fca) ![GitHub stars](https://img.shields.io/github/stars/shahadat-sahu/sahu-fca)

A **lightweight**, **fast**, and **unofficial** API to interact with **Facebook Chat** programmatically — perfect for **bots**, **automation**, and **custom messaging tools**.

---

## 📦 Installation

```bash
npm install sahu-fca
```

### ⚡ Quick Start

### 🔐 Login Example

```javascript 
const login = require('sahu-fca');

async function login() {
  try {
    const api = await login({
      email: 'your_facebook_email',
      password: 'your_password'
    });
    console.log('✅ Logged in successfully!');
    return api;
  } catch (error) {
    console.error('❌ Login failed:', error);
  }
}

login();
```




### 💬 Send Message Example

```javascript
const api = await login();
api.sendMessage("Hello from sahu-fca!", "friend_user_id");




👂 Listen for Messages

api.listen((err, message) => {
  if (err) return console.error(err);
  console.log('📩 Received message:', message.body);
});
```


## 🧰 API Methods
| Method               | Description                          |
|----------------------|--------------------------------------|
| `login()`            | Authenticate with Facebook           |
| `sendMessage()`      | Send text message                    |
| `listen()`           | Receive incoming messages            |
| `getUserInfo()`      | Fetch user profile data              |
| `handleRequest()`    | Accept/reject friend requests        |



### ⚠️ Disclaime
> Note: This is an unofficial Facebook API.
Use at your own risk.
This project is not affiliated with or endorsed by Meta / Facebook in any way.



### 🌐 GitHub & Repository

- **MIRAI PROJECT:** **[Click Here](https://github.com/shahadat-sahu/SHAHADAT-CHAT-BOT.git)**

- **FCA:** **[Click Here](https://github.com/shahadat-sahu/sahu-fca.git)**

- **ISLAMIC CHAT BOT:** **[Click Here](https://github.com/shahadat-sahu/SHAHADAT-ISLAMIC-CHAT-BOT.git)**



## 👨‍💻 **ABOUT THE DEVELOPER**  
  
**Name:** **`SHAHADAT ISLAM`**  
**Nice Name:** **`SA HU`**  
**Profession:** **`STUDENT & CHATBOT DEVELOPER`**  
**Location:** **`KHAGRACHARI, BANGLADESH`**  

### 📞 **CONTACT INFORMATION**  
- **WhatsApp:** **[01882 333052](https://wa.me/+8801882333052)**  
- **Facebook:** **[Facebook ID](https://facebook.com/100001039692046)**  
- **Messenger:** **[Message Me](https://m.me/100001039692046)**  

### 🚀 **DEVELOPMENT APPROACH**  
- 💻 **Copy-paste techniques with customizations**  
- 🤝 **Collaborative development with friends**  
- 🤖 **AI-powered using ChatGPT and other advanced tools**  




### Thanks for using FCA
