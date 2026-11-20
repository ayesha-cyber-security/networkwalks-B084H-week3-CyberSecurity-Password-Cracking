# 🔓 Password Cracking with John The Ripper & NetworkWalks Tools

### Cracking the password of a locked file using hash extraction and wordlist attack in an isolated lab

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red?style=for-the-badge)
![Tool](https://img.shields.io/badge/Tool-John_The_Ripper-black?style=for-the-badge)
![Tool](https://img.shields.io/badge/Tool-NetworkWalks_Tools-orange?style=for-the-badge)
![OS](https://img.shields.io/badge/OS-Windows-blue?style=for-the-badge)
![Skill](https://img.shields.io/badge/Skill-Password_Cracking-red?style=for-the-badge)
![Skill](https://img.shields.io/badge/Skill-Hash_Extraction-black?style=for-the-badge)
![Ethical Hacking](https://img.shields.io/badge/Ethical_Hacking-Lab_Practice-orange?style=for-the-badge)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-Week_3-black?style=for-the-badge)
![Ayesha](https://img.shields.io/badge/Ayesha-B084H-red?style=for-the-badge)

## ⚠️ Disclaimer / Ethical Note

> This project was created *only for study and learning purposes* as part of my Cyber Security Internship at NetworkWalks.
>
> All activities were performed in an *isolated lab environment* on a file provided by NetworkWalks for practice.
>
> I did *NOT* use these tools on any real person, real account, or real system without permission.
>
> The purpose of this lab is to learn how hackers crack weak passwords, so that we can protect ourselves and others from such attacks.

## 📖 Introduction

In this project, I performed password cracking in two different labs. Both labs were done in an isolated lab environment on Windows, only for study and learning purposes.

**Lab 1:** I used John The Ripper and Jonny to crack the password of a locked PDF file. For this, I used an online tool to extract the hash of the file, then John gave me the password.

**Lab 2:** I used NetworkWalks tools. First I used NetworkWalks Hash Calculator to get the hash of the locked file, then I used NetworkWalks Password Cracker to guess the password from a wordlist.

Both labs helped me understand how hashes work and why weak passwords are easy to crack.

---

## 🛠️ Tools Used

| Tool | Use |
| --- | --- |
| **Windows OS** | The whole lab was performed on Windows |
| **John The Ripper** | To crack the password of the hash in Lab 1 |
| **Jonny (GUI for John)** | To run John The Ripper easily with a graphical interface |
| **Online PDF Hash Extractor** | To extract the hash of the locked PDF file in Lab 1 |
| **NetworkWalks Hash Calculator** | To calculate the hash of the locked file in Lab 2 |
| **NetworkWalks Password Cracker** | To guess the password from the hash using a wordlist in Lab 2 |
| **Wordlist** | A list of passwords used to try and guess the real password |

---

## 🔍 What is Hash?

When a file is locked with a password, the computer does not save the real password. It saves a coded form of the password, which is called a **Hash**.

We cannot read the Hash directly. We have to crack it with tools like John The Ripper to find the real password.

**Example:**
Password = `12345`
Hash = `827ccb0eea8a706c4c34a16891f84e7b` 





---

