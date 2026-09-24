# Sorkar Agro Care (সরকার এগ্রো কেয়ার) - Production Website

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fsnigdhaurmiurma%2Fsorkar-agro-care)

A complete, production-ready landing and e-commerce website clone of [sorkaragrocare.com](https://www.sorkaragrocare.com/) configured for instant free publishing, telephone calling, and online order management.

- **Hotline & WhatsApp Number**: `01708-938787` (`+880 1708-938787`)
- **Ordering System**: Dual-channel order capture:
  1. **Direct WhatsApp Forwarding**: Customers' orders are formatted into an instant WhatsApp message to `01708-938787`.
  2. **Internal Merchant Database & Admin Dashboard**: Every order is recorded with customer details, order ID, phone, address, and live status.
  3. **Steadfast / Pathao Courier CSV Export**: 1-click export of orders ready for courier parcel booking.
  4. **Optional Email / Webhook Integration**: Supports free instant email notifications via Web3Forms or Google Sheets.

---

## 🚀 How to Publish for Free (3 Easy Methods)

### Method 1: Netlify Drop (Easiest - 30 Seconds, No Coding Required)
1. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)** (free account).
2. Drag and drop the folder `C:\Users\user\.gemini\antigravity\scratch\sorkaragrocare` into the browser window.
3. Your website is instantly live with a free SSL certificate (e.g. `https://sorkar-agro-care.netlify.app`)!
4. *(Optional)* Add your custom domain (e.g. `www.sorkaragrocare.com`) in Netlify Site Settings > Domain Management.

### Method 2: Vercel (1 Minute)
1. Go to **[vercel.com](https://vercel.com)**.
2. Click **Add New Project** and import this folder (or link via GitHub).
3. Click **Deploy**. Vercel will immediately deploy using the included `vercel.json`.

### Method 3: GitHub Pages
1. Push this git repository to a GitHub repository:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/sorkar-agro-care.git
   git branch -M main
   git push -u origin main
   ```
2. In GitHub, go to **Settings** > **Pages** > select **main branch / root**, then click **Save**.

---

## 📱 How Calling & Ordering Works for Visitors

### 1. Direct Calling:
- When visitors tap any **Call** button (in header, contact section, floating bar, or error modals), their mobile phone opens the dialer ready to call **`01708-938787`**.

### 2. Website Ordering:
- Visitors select their pond package (10, 20, 30, 40, or 50 decimal).
- Fill in their **Name**, **Mobile Number**, and **Delivery Address**.
- Click **"অর্ডার কনফার্ম করুন"**.
- A confirmation modal pops up with their Order Number and an option to send the order details to your WhatsApp **`01708-938787`**.
- The order is also instantly logged into your **Merchant Admin Dashboard**.

---

## 🔐 Merchant Admin Dashboard
You can view, manage, and download all orders placed on your website:
- **How to Open**: 
  - Click the **"অ্যাডমিন প্যানেল"** link at the very bottom of the website footer.
  - Or press `Ctrl + Shift + A` on desktop.
- **Default PIN Code**: `8787` (Can be changed inside settings).
- **Features in Admin**:
  - Live order statistics (Total Orders, Total Revenue, Today's Orders).
  - Search orders by customer name, phone number, or Order ID.
  - 1-click **Call Customer** (`tel:...`) and **WhatsApp Customer**.
  - Update status: *Pending*, *Confirmed*, *Shipped*, *Delivered*, *Cancelled*.
  - **"Excel/CSV ডাউনলোড"**: Downloads a clean CSV formatted for Steadfast, Pathao, or RedX couriers.
