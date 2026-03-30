# 📄 Oshofy – Privacy Policy & Security (Invisible reCAPTCHA)

## 📌 Overview
This repository contains the Privacy Policy and security configuration for the Oshofy Application, including implementation guidelines for Google Invisible reCAPTCHA to protect forms from spam and automated abuse.

The policy explains how user data is collected, used, stored, and protected when using the Oshofy service.

---

# 🔐 Privacy Policy

**Last updated:** March 30, 2026  

This Privacy Policy describes our policies and procedures on the collection, use, and disclosure of your information when you use the Service and tells you about your privacy rights and how the law protects you.

By using the Service, you agree to the collection and use of information in accordance with this Privacy Policy.

---

# 📊 Data We Collect

## 1. Personal Data
We may collect personally identifiable information such as:

- First name and last name
- Phone number
- Email address
- Uploaded files or images

## 2. Usage Data
Usage Data is collected automatically and may include:

- IP address
- Browser type
- Browser version
- Pages visited
- Time and date of visit
- Device information
- Diagnostic data

## 3. Device Permissions
Our application may request permission to access:

- Camera
- Photo library
- Files stored on device

This information is used to provide features of our service and improve user experience.

---

# 🎯 Purpose of Data Collection

We use Personal Data for:

- Providing and maintaining our Service
- Managing user accounts
- Providing customer support
- Improving application performance
- Sending notifications
- Preventing fraud or misuse
- Legal compliance

---

# 🤝 Third-Party Services

We may use third-party services to improve performance and analytics.

Example:
Mouseflow – session replay and heatmap tool.

Privacy Policy:
https://mouseflow.com/privacy/

---

# 🔐 Security Measures

We use reasonable security measures to protect your data:

- HTTPS encryption
- Secure database storage
- Access control
- Authentication protection
- Invisible bot protection using reCAPTCHA

However, no system is 100% secure.

---

# 🗂 Data Retention Policy

We retain data only as long as necessary:

| Data Type | Retention |
|----------|-----------|
| User Account | Duration of account + 24 months |
| Usage Logs | Up to 24 months |
| Analytics Data | Up to 24 months |

We may delete or anonymize data earlier when no longer required.

---

# 🌍 Data Transfer

User data may be processed in locations outside your country.

We ensure proper safeguards are implemented to protect your data.

Country reference: Haryana, India

---

# 🗑 User Rights

You have the right to:

- Access your data
- Update your data
- Delete your data
- Request correction
- Withdraw consent

You may contact us for any data-related request.

---

# 🛡 Invisible reCAPTCHA Condition

We use Google Invisible reCAPTCHA to protect our application from spam, bots, and automated misuse.

Invisible reCAPTCHA works automatically in the background without requiring user interaction.

### Purpose of using reCAPTCHA
- Prevent fake registrations
- Stop spam submissions
- Protect APIs
- Detect automated abuse
- Improve platform security

By using our service, you agree that Invisible reCAPTCHA verification may be performed to confirm that requests are made by real users and not automated bots.

Google reCAPTCHA may collect hardware and software information such as:

- Device information
- IP address
- Browser activity

This information is used strictly for security purposes.

Google Privacy Policy:
https://policies.google.com/privacy

Google Terms:
https://policies.google.com/terms

---

# ⚙ Example Integration

## Install package (React)
```bash
npm install react-google-recaptcha
```

## Add Environment Variable

Create `.env` file:

```
REACT_APP_RECAPTCHA_SITE_KEY=your_site_key
```

## Example Code

```jsx
import ReCAPTCHA from "react-google-recaptcha";

function Form() {

  const handleCaptcha = (token) => {
    console.log(token);
  };

  return (
    <form>
      <ReCAPTCHA
        sitekey={process.env.REACT_APP_RECAPTCHA_SITE_KEY}
        size="invisible"
        onChange={handleCaptcha}
      />

      <button type="submit">
        Submit
      </button>

    </form>
  );
}

export default Form;
```

---

# 👶 Children's Privacy

Our service does not address anyone under the age of 16.

We do not knowingly collect personal data from children.

---

# 🔗 External Links

Our Service may contain links to other websites.

We are not responsible for their privacy practices.


---

# 📜 License

This document is provided for informational purposes and may be updated at any time.
