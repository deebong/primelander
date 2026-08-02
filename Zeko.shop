# PrimeLander 🛒📊

[![Website](https://img.shields.io/badge/Website-PrimeLander.com-188038?style=flat-square)](https://primelander.com)
[![Status](https://img.shields.io/badge/Status-Work_In_Progress-ea4335?style=flat-square)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)

**Turn Google Sheets into a powerful storefront.**

PrimeLander is an open-source, headless commerce framework that uses Google Sheets as your database. Launch a blazing-fast, app-like store in minutes without ever logging into a complex admin dashboard.

## 🚀 Status: Work in Progress
The PrimeLander core is currently under active development. We are building the "WordPress of the Google Sheets generation." Star this repository to get notified when the beta drops!

---

## 🎯 Who is this for?

### For Startup Founders & Non-Techies
Stop fighting with bloated, complex ecommerce dashboards. If you know how to type into a Google Sheet, you know how to run a PrimeLander store. 
* **Zero Learning Curve:** Manage your inventory, pricing, and categories in a familiar spreadsheet interface.
* **Instant Orders:** Customer orders flow directly to your WhatsApp, perfectly formatted for quick fulfillment.
* **Lightning Fast:** Your store loads instantly, providing a seamless, app-like experience for your buyers.

### For Developers & Agencies
PrimeLander isn't just a site builder; it's a flexible framework. Use standard web technologies to build stores for your clients faster than ever.
* **Predictable Data:** We turn Google Sheets into clean, standardized JSON data structures.
* **Bring Your Own UI:** Build custom themes using HTML/CSS/JS. 
* **No Database Maintenance:** Hand off projects to clients without having to teach them a new CMS. They just update their spreadsheet.

---

## 🛠️ How it Works (Coming Soon)

1. **Clone the Sheet:** Copy our master template to your Google Drive and add your products.
2. **Connect the Engine:** Pass your Google Sheet ID to PrimeLander.
3. **Start Selling:** We instantly generate a beautiful Single Page Application (SPA). Customers browse, checkout, and you get the order on WhatsApp.

```javascript
// Example initialization (Draft API)
const store = new PrimeLander({
  sheetId: '1BxiM_xyz987...',
  theme: 'minimal-light'
});

store.on('order_placed', (cart) => {
  WhatsApp.send({
    to: config.merchantNumber,
    payload: cart.format()
  });
});
