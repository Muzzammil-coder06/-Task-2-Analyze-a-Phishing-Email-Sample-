# 📧 Phishing Email Analysis Report

## 🔍 Email Sample Overview
A suspicious email claiming to be from PayPal urging immediate verification.

---

## 🛑 Phishing Indicators Identified

### 1. **Sender Email Address**
- **Actual:** support@paypa1.com
- **Issue:** Domain uses `paypa1` (with number 1 instead of "l") — **spoofed domain**.

### 2. **Suspicious Link**
- **Visible:** https://www.paypal.com.verify-info-login.com
- **Real Target:** A spoofed domain (legitimate PayPal domain is **paypal.com**) — **mismatched URL**.

### 3. **Email Header Check**
- Use tool like: [https://mxtoolbox.com/EmailHeaders.aspx]
- Look for inconsistencies in SPF, DKIM, and “Received from” headers.

### 4. **Urgent/Threatening Language**
- “Failure to act within 24 hours…” — induces panic — classic **social engineering** tactic.

### 5. **Grammar & Spelling**
- Slightly formal but overly generic and robotic language. Often a red flag.

### 6. **Suspicious Attachment**
- Executable file `.exe` named “Account_Verification_Form.exe” — very dangerous!

---

## ✅ Conclusion

This email is a **phishing attempt** using spoofed email address, fake links, threatening language, and malicious attachments to deceive users.

---

## 🔧 Tools Used
- Online Header Analyzer: https://mxtoolbox.com/EmailHeaders.aspx
- Hover URL inspection
- Manual grammar & logic review

---

## 🎯 Learning Outcome

- Gained hands-on experience in phishing detection
- Learned about email spoofing, social engineering, and header analysis
