# Internship-By-Elevate-Labs
🛡️ Task 2 – Phishing Email Analysis Report

## 📩 Sample Email Summary

- **Subject**: High-severity alert: Phish delivered due to tenant or user override  
- **Sender**: microsoft@email-records.com  
- **Date**: January 22, 2021  
- **Body Summary**:  
  The email claims that a high-severity phishing alert was triggered in the recipient’s Office 365 environment and prompts the user to click on a button labeled "View alert details" to investigate further.

---

## 🔍 Phishing Indicators Identified

1. **Suspicious Sender Domain**  
   The email originates from `email-records.com`, which is not an official Microsoft domain. Legitimate Microsoft emails are usually sent from domains like `@microsoft.com` or `@office365.microsoft.com`.

2. **Urgent and Fear-Inducing Language**  
   The subject and content use high-stress phrases such as “High-severity alert” to create panic and push the user to take immediate action — a classic social engineering tactic.

3. **Lack of Personalization**  
   The email does not mention the recipient’s name, organization, or any specific detail. Official alerts from Microsoft typically include account-related information.

4. **Broken or Vague Technical Details**  
   The body includes a confusing message:  
   *“sent by Unknown to at time…”*  
   This is grammatically incorrect and indicates poor construction, often found in phishing attempts.

5. **Unverifiable Call-to-Action (CTA)**  
   The “View alert details” button does not display the actual destination URL. Without verifying the target domain, this link poses a significant risk of redirecting the user to a malicious site.

6. **Unbranded, Generic Signature**  
   The email closes with “The Office 365 Team” without any verification mechanism, contact details, or digital signature typically used by enterprise-level services.

---

## 🧰 Tools and Methods Used

- **Manual Header & Domain Inspection**  
  Reviewed the sender address and matched it against official Microsoft domains.

- **Social Engineering Pattern Recognition**  
  Identified use of urgency, fear, and vague language typical of phishing campaigns.

- **Link Analysis**  
  Evaluated the button-based CTA for hidden URLs (without clicking).

---

## ✅ Conclusion

The email analyzed in this report exhibits clear signs of phishing. It attempts to spoof Microsoft branding and uses fear-based messaging, a suspicious sender domain, and ambiguous technical language to manipulate the recipient into clicking a potentially dangerous link.

This case reinforces the importance of:
- Always verifying sender domains,
- Hovering over links before clicking,
- Being cautious with urgent or threatening emails,
- Reporting suspicious messages to IT/security teams.

---

## 📎 Attachment

A screenshot of the phishing email is included in the repository as supporting evidence.

