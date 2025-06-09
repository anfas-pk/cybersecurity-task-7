# Task 7 - Identifying & Removing Suspicious Browser Extensions

## 🎯 Objective
Learn to inspect browser extensions, identify suspicious ones, and remove unnecessary or risky tools to improve browser security and performance.

## 🔧 Browser Used
- Brave (same process applies to Chrome)

## 🔍 Extension Reviewed: Free VPN for Chrome - VPN Proxy VeePN , Screen Recorder

### 📝 Extension Details
- **Name**: VPN Proxy VeePN
- **Version**: 3.4.4
- **Size**: 3.7 MB
- **Status**: Enabled
- **Description**: Fast, ultra secure, and easy-to-use VPN service to protect your privacy online. Enjoy Unlimited Traffic and Bandwidth!

### ⚠️ Permissions Requested:
- Read and change **all your data on all websites**
- Display notifications
- Manage your apps, extensions, and themes
- Change your privacy-related settings

### 📎 Screenshot:
![Extension Details](extension_details.png)

---

## 🔐 Risk Analysis

> 🔍 **Observation**:  
This extension requests **full access to all websites**, **privacy settings**, and **extension management** — permissions that are commonly abused by malicious or untrustworthy extensions.

> ✅ **Action Taken**:
- This extension was **disabled** and marked for removal after verifying I don’t rely on it actively.
- Decision was based on:
  - High-risk permissions
  - Vague privacy practices
  - No necessity in my daily browsing

---

## 🧠 What I Learned

- Extensions can compromise privacy if given high-level permissions.
- Always check:
  - Reviews
  - Publisher authenticity
  - Permissions before installing
- It’s safer to install only **essential extensions** from **trusted sources** (like Chrome Web Store).

---

## 📸 Screenshots
- `before_removal.png`: Shows all installed extensions
- `after_removal.png`: After disabling/removing suspicious ones
- `extension_details.png`: Details of VPN Proxy VeePN extension

---

## 🔐 Security Concepts Recap

| Concept | Explanation |
|--------|-------------|
| **Permissions to watch for** | "Read and change all data", "Manage apps" |
| **Sandboxing** | Browser isolates extensions in their own container |
| **Can extensions steal passwords?** | Yes, if permissions are misused |
| **Safe install practices** | From official store, known developers, minimal permissions |
| **Extensions vs Plugins** | Extensions = browser add-ons; Plugins = external software |
| **How to report** | Use Chrome/Edge "Report Abuse" feature |

---

## 📤 GitHub Submission
All findings and screenshots are uploaded in this repository:  
👉 [GitHub Repo Link](https://github.com/YOUR_USERNAME/task7-browser-extension-audit)

---

## ✅ Conclusion
Browser extensions, even those claiming to provide privacy, can be risky. Always audit them regularly, check permissions, and remove what you don’t need.
