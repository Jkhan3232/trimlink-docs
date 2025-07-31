---
sidebar_position: 12
sidebar_label: "Add & Verify Domain"
---

# 🌐 Add & Verify Your Custom Domain

Adding a **custom domain** allows you to brand your links, increase trust, and drive better engagement. Follow this step-by-step guide to connect your domain to the platform.

---

## ✅ Step 1: View Domain List

Navigate to the **Domain List** page:

- Shows all added domains with status.
- Columns include:
  - **Domain Name**
  - **Status**
  - **Domain Usage**
  - **Domain State**
  - **Created At**
- If no domains exist, the table will show:  
  _"No data found"_

Click on the **`+ Add New Domain`** button to begin setup.

---

## 📝 Step 2: Add New Domain

You’ll be asked:

### ➤ Does this domain have any content?

- 🔘 Yes – Used for a website/blog etc.
- 🔘 No – New or unused domain

### ➤ How to proceed?

- ✅ **Yes, I want to set up DNS records for my subdomain** (Recommended)
- 🔘 No, just want to learn about short URLs (no domain)

### ➤ Enter your subdomain

> Example: If your domain is `example.com`, and subdomain is `india`, enter:
>
> ```
> india
> ```

The platform will configure it as:  
`india.example.com`

---

## 🌐 Step 3: DNS Configuration

You will receive **DNS instructions** like below:

### 🔗 DNS Records for Subdomain

| Record Type  | Hostname | Points To         |
| ------------ | -------- | ----------------- |
| CNAME Record | india    | cname.trimlink.ai |

> Example: This sets up `india.example.com` to point to Trimlink.

### 🧾 Optional: Full Domain Setup

| Record Type  | Hostname    | Points To         |
| ------------ | ----------- | ----------------- |
| CNAME Record | www.coco.me | cname.trimlink.ai |

### 🔧 Domain Provider Details

- **Registrar:** Network Solutions, LLC
- **Name Servers:**
  - `ns1.safesecureweb.com`
  - `ns2.safesecureweb.com`
  - `ns3.safesecureweb.com`

---

## 🔒 Step 4: Domain Verification

After saving DNS records:

> Your domain will show as **Pending Verification**.

- Usually completes within **24 hours**
- Once verified, you’ll receive a **confirmation email**
- Status will change automatically in the dashboard

---

## 📷 Visual Reference

## Here’s a preview of the DNS setup and domain verification screens:

---

<div style={{ display: 'flex', justifyContent: 'center', marginTop: '1.5rem' }}>
  <img
    src="/img/domains/add-new-domain1.png"
    alt="Search Custom Domain"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
  </div>
---
  <div style={{ display: 'flex', justifyContent: 'center', marginTop: '1.5rem' }}>
  <img
    src="/img/domains/add-new-domai2.png"
    alt="Search Custom Domain"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>
---
<div style={{ display: 'flex', justifyContent: 'center', marginTop: '1.5rem' }}>
  <img
    src="/img/domains/dns.png"
    alt="Search Custom Domain"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>
---
<div style={{ display: 'flex', justifyContent: 'center', marginTop: '1.5rem' }}>
  <img
    src="/img/domains/verify.png"
    alt="Search Custom Domain"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>
---
<div style={{ display: 'flex', justifyContent: 'center', marginTop: '1.5rem' }}>
  <img
    src="/img/domains/domain.png"
    alt="Search Custom Domain"
    style={{
      width: '100%',
      borderRadius: '10px',
      boxShadow: '0 4px 12px rgba(0, 0, 0, 0.1)'
    }}
  />
</div>
