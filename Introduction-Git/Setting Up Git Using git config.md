# Git Configuration Guide

## 📌 Introduction
Git requires user identity information before making commits. This guide explains how to configure your username and email in Git.

---

## ✅ Step 1: Configure Username

Run the following command:

```bash
git config --global user.name "Your Name"

- Example 
git config --global user.name "Raju Kumar"

This sets your username for all Git repositories.

✅ Step 2: Configure Email

Run the following command:
git config --global user.email "your-email@example.com"
Example:
git config --global user.email "raju@gmail.com"


This connects your commits to your GitHub account.

✅ Step 3: Check All Configuration Settings

Use this command:

git config --list


This will display:

Username

Email

Other Git settings

✅ Step 4: Check Specific Configuration Values
Check Username
git config user.name

Check Email
git config user.email

📌 Global vs Local Configuration
Global Configuration

Applies to all repositories.

git config --global

Local Configuration

Applies to only one repository.

git config

🎯 Conclusion

Configuring Git username and email is important for tracking commits and collaboration. Always verify your configuration before starting a project.


---
