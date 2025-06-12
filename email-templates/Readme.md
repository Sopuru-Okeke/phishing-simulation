# 📧 Email Templates

This folder contains custom phishing email templates used in my Gophish simulation project.

---

## 📨 Template: `fb-security-alert.html`

**Description:**  
A fake Facebook login alert email designed to simulate a social engineering scenario where the recipient is warned about an unauthorized login attempt.

**Purpose:**  
To study how users respond to realistic-looking phishing emails and how Gophish tracks interactions like email opens and link clicks.

### 🔧 Gophish Template Variables Used:
- `{{.Tracker}}`: Inserts an invisible pixel to track when the email is opened.
- `{{.URL}}`: Automatically replaced by Gophish with the unique phishing link for each recipient.

---

> ⚠️ **Disclaimer:** This email template is for educational and ethical use only. Do not deploy or distribute this content without proper authorization or legal consent.
