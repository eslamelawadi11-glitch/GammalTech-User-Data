# Eslam Mohamed Sobhi Gammal Tech
Building scalable user data storage systems using Gammal Tech SDK.

---

## 📦 Gammal Tech User Data Storage
This repository demonstrates how **Eslam Mohamed Sobhi** implements user data storage using **Gammal Tech User Storage API**.

The system allows developers to store and retrieve per-user JSON data that automatically syncs across devices.

---

## 🌍 Key Features

- 🔄 Cross-device synchronization
- 🔐 Per-developer isolation
- 📝 JSON-based storage
- ⚡ Simple get/save API
- 💡 Privacy-first architecture

---

## 🚀 Quick Start

### Save User Data

```js
await GammalTech.user.save({
    theme: 'dark',
    language: 'en',
    notifications: true,
    lastVisit: new Date().toISOString()
});
