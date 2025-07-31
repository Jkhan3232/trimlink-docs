---
sidebar_position: 2
sidebar_label: "Sign-In"
---

# Sign-In

This document explains how users can log in to the system.

---

## 🔐 Social Sign-In (Google, LinkedIn, X, GitHub, Facebook)

Users can log in using any supported social account.  
If the user is **new**, they are **automatically registered and logged in** without needing to verify their email.

### 🧠 Behind the Scenes:

- **First-time user** → Registers automatically + logs in
- **Existing user** → Simply logs in
- ✅ No email verification is required
- ✅ Secure identity via OAuth2 (Google, etc.)

```plaintext
[Login via Google]
    ↓
[Google OAuth Profile Sent to Backend]
    ↓
[Check if user exists]
    → No → Register + Login
    → Yes → Login
```

### 📝 You Can See This Sign-In Form Image For Social and Manual Sign-In

<div style={{ display: 'flex', justifyContent: 'center', marginTop: '3rem' }}>
  <img
    src="/img/auth-images/signin.png"
    alt="Sign-Up Form Preview"
    style={{
      width: '50%',
      borderRadius: '10px',
      boxShadow: ' 0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>
