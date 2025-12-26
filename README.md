Nice README already 👍
I’ve **updated it cleanly** and added **clear steps for using a separate CSS file** (Shopify-correct way).
Below is the **FULL UPDATED README** — you can replace your existing one.

---

# Why Choose Us – Shopify Trust Icons Section

This repository contains a **custom Shopify section** that displays trust icons such as **Easy Support, Happy Customers, Pan India Shipping, and Secure Payments**.
It is fully responsive and optimized for **mobile, tablet, and desktop**.

---

## ✨ Features

* ✅ Clean grid-based layout
* ✅ Mobile: 2 columns
* ✅ Desktop: 4 columns
* ✅ Uses Shopify theme assets for icons
* ✅ Separate CSS file (clean & maintainable)
* ✅ Lightweight (no JavaScript required)
* ✅ Perfect for home page, product page, or footer

---

## 📂 Files Used

* `sections/why-choose-us.liquid`
* `assets/why-choose-us.css`
* Icon images uploaded to **Assets**

---

## 🚀 Installation Steps (Shopify)

Follow these steps carefully 👇

---

### **Step 1: Open Shopify Admin**

* Go to **Shopify Admin → Online Store**

---

### **Step 2: Edit Theme Code**

* Click the **three dots (⋮)** next to your active theme
* Select **Edit code**

---

### **Step 3: Upload Trust Icons**

* Go to **Assets**
* Upload the following icon images:

  * `icon-easy-support.png`
  * `icon-success-delivery.png`
  * `icon-pan-india-shipping.png`
  * `icon-secure-payment.png`

> ⚠️ Make sure the file names match exactly.

---

### **Step 4: Create CSS File (Important)**

* Go to **Assets**
* Click **Add a new asset**
* Select **CSS**
* Name the file exactly:

```
why-choose-us.css
```

* Paste the CSS code into this file
* Click **Save**

---

### **Step 5: Create Section File**

* Go to **Sections**
* Click **Add a new section**
* Name the file exactly:

```
why-choose-us.liquid
```

* Paste the section HTML code into this file
* At the **top of the file**, add this line to load the CSS:

```liquid
{{ 'why-choose-us.css' | asset_url | stylesheet_tag }}
```

* Click **Save**

---

### **Step 6: Add Section to Theme**

* Go to **Online Store → Themes**
* Click **Customize**
* Navigate to the page where you want the section (Home / Product / etc.)
* Click **Add section**
* Select **Why Choose Us**
* Click **Save**

---

## 🎨 Customization

You can easily customize:

* Icons (replace images in Assets)
* Text content inside `<h4>` and `<p>`
* Background color in `why-choose-us.css`
* Spacing, grid columns, and font sizes

---

## 📱 Responsive Behavior

* **Mobile:** 2 items per row
* **Tablet & Desktop:** 4 items per row

Handled automatically using CSS media queries.

---

## 🧩 Use Cases

* Homepage trust badges
* Product page credibility section
* Footer trust section
* Conversion Rate Optimization (CRO)

---

## ⭐ Support

If this section helped you, consider **starring the repository** ⭐
Feel free to fork and customize it for your store.

---

### ✅ Recommended Structure

```
shopify-why-choose-us-section/
│── README.md
│
├── sections/
│   └── why-choose-us.liquid
│
└── assets/
    └── why-choose-us.css
```

---


