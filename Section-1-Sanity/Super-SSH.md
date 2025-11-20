

![GitHub repo size](https://img.shields.io/github/repo-size/Petrasec2025/picoGym-Beginner-Guide)
![GitHub stars](https://img.shields.io/github/stars/Petrasec2025/picoGym-Beginner-Guide?style=social)
![GitHub forks](https://img.shields.io/github/forks/Petrasec2025/picoGym-Beginner-Guide?style=social)
![GitHub issues](https://img.shields.io/github/issues/Petrasec2025/picoGym-Beginner-Guide)

---

## 📘 Challenge: Super SSH  
**Author:** Jeffery John  
**Category:** General Skills / Networking  
**Difficulty:** Easy  
**Solves:** 130,411  
**Rating:** ⭐ 91% Liked  

### 🔍 Description
This challenge introduces **Secure Shell (SSH)**, a fundamental tool for remote system access. The challenge launches an instance on demand for you to connect.

> “Using a Secure Shell (SSH) is going to be pretty important.”

---

## 🛠️ Solution

### ✔️ Step 1 — Launch the instance  
Click **Launch Challenge** to start the SSH server instance. The challenge will provide:  
- **Hostname / IP**  
- **Port**  
- **Username**  
- **Password or Key** (if required)

### ✔️ Step 2 — Connect using SSH  
In your terminal, run:

```bash
$ ssh username@hostname -p port
````

Example:

```bash
ssh picoUser@123.45.67.89 -p 2222
```

> This will log you into the remote challenge instance.

### ✔️ Step 3 — Locate the flag

Once logged in, find the flag file. Usually it is in the home directory:

```bash
$ ls
flag
$ cat flag
```

### ✔️ Step 4 — Read the flag

```
picoCTF{FLAG}
```

---

## 📚 What We Learned

* **SSH** allows secure remote access to servers using encrypted connections.
* Essential command-line skill for CTFs and real-world cybersecurity work.
* Familiarity with SSH increases efficiency when working on remote systems.

---

## 🧠 Self‑Reflection

This challenge helped me understand:

* The importance of secure remote access.
* How to navigate a remote Linux system safely.
* Confidence in connecting to instances, which is critical for future CTF and pentesting tasks.

---

## ⭐ Final Flag

```
picoCTF{FLAG}
```
<img width="1440" height="732" alt="Screenshot 2025-11-20 at 3 15 12 PM" src="https://github.com/user-attachments/assets/408a5f24-53e7-4943-a24f-be3dd0eabb99" />


```
```
