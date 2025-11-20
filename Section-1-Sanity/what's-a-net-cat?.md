

![GitHub repo size](https://img.shields.io/github/repo-size/Petrasec2025/picoGym-Beginner-Guide)
![GitHub stars](https://img.shields.io/github/stars/Petrasec2025/picoGym-Beginner-Guide?style=social)
![GitHub forks](https://img.shields.io/github/forks/Petrasec2025/picoGym-Beginner-Guide?style=social)
![GitHub issues](https://img.shields.io/github/issues/Petrasec2025/picoGym-Beginner-Guide)

---

## 📘 Challenge: What's a Netcat?  
**Author:** Sanjay C / Danny Tunitis  
**Category:** General Skills / Networking  
**Difficulty:** Easy  
**Solves:** 130,411  
**Rating:** ⭐ 91% Liked  

### 🔍 Description
This challenge introduces **Netcat (nc)**, a versatile networking tool. The instance will be launched on demand.

> "Additional details will be available after launching your challenge instance."  

**Hint:** Check an `nc tutorial` for guidance.

---

## 🛠️ Solution

### ✔️ Step 1 — Launch the instance  
Click **Launch Challenge** to start the instance and get the connection details.

### ✔️ Step 2 — Connect with Netcat  
Netcat can be used to connect to TCP/UDP services:

```bash
# Connect to a server on a specific port
$ nc hostname port
````

Example:

```bash
nc 123.45.67.89 9999
```

### ✔️ Step 3 — Receive or send data

Netcat will either print the flag directly or allow you to interact with the service to retrieve it.

### ✔️ Step 4 — Read the flag

```
picoCTF{FLAG}
```

---

## 📚 What We Learned

* **Netcat** is a networking Swiss Army knife:

  * Connects to remote ports
  * Sends and receives raw data
  * Can act as a server or client
* Essential tool for CTF networking challenges and pentesting.

---

## 🧠 Self‑Reflection

This challenge reinforced that:

* Understanding basic networking tools is key for CTFs.
* Practicing Netcat improves confidence in interacting with remote services.
* Early exposure to these commands sets a strong foundation for intermediate challenges.

---

## ⭐ Final Flag

```
picoCTF{FLAG}
```
<img width="1437" height="779" alt="Screenshot 2025-11-20 at 3 32 00 PM" src="https://github.com/user-attachments/assets/b02e654a-0e11-44e3-860a-64a9ecf4ad40" />

```
```
