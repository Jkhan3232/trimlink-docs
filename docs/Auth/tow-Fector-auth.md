---
sidebar_position: 4
sidebar_label: "Two-Factor Authentication"
---

# 🔐 Two-Factor Authentication (2FA)

Two-Factor Authentication (2FA) adds an extra layer of security to your account. You can enable it from your **profile settings** using an authenticator app and download backup codes for recovery.

---

## 👤 Step 1: Enable 2FA from Your Profile

Click your profile icon, go to **My Profile**, scroll down, and click **"Enable Two-Factor Authentication"**.

<div style={{ display: 'flex', justifyContent: 'center', marginTop: '1rem' }}>
  <img
    src="/img/auth-images/profile-enable-2fa.png"
    alt="Enable 2FA from Profile"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>

---

## 📲 Step 2: Scan the QR Code

Scan the QR code using an authenticator app like Google Authenticator, Authy, or Microsoft Authenticator.

<div style={{ display: 'flex', justifyContent: 'center', marginTop: '1rem' }}>
  <img
    src="/img/auth-images/2fa-qr.png"
    alt="2FA QR Code"
    style={{
      width: '50%',
      borderRadius: '8px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>

---

**Can't scan the code?**

Use this manual key to set it up manually:

> **Manual Key:** `YX2SZVOJGXEZMGVJ`

---

## ✅ Step 3: Complete the Setup

Enter the **6-digit code** from your authenticator app along with your **account password** to confirm and enable 2FA.

After successful verification:

- 2FA is activated on your account
- You'll be logged out once
- Future logins will require both password and 2FA code

---

## 🛡️ Backup Codes

Once 2FA is enabled, you’ll be prompted to **download backup codes**.

- Use them if you can’t access your authenticator app
- Click **“Download Backup Codes”** and store them securely
- Each code is valid for one-time use only

> ⚠️ Never share your backup codes. Store them safely.

<div style={{ display: 'flex', justifyContent: 'center', marginTop: '2rem' }}>
  <img
    src="/img/auth-images/2fa-backup.png"
    alt="2FA Backup Code Download"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>

---

## 🔐 Login Flow with 2FA

Once 2FA is enabled:

- You must log in with:
  - Your **password**
  - A **6-digit code** from the authenticator app  
    _or_
  - A valid **backup code** (if your app is unavailable)

---
