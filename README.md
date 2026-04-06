 AI Finance Management Platform

##  Overview

The **AI Finance Management Platform** is a full-stack web application designed to help users **track, manage, and analyze their personal finances** efficiently.

This project combines **modern web development + AI capabilities** to simplify financial tracking. Users can manually add transactions or use **AI-powered receipt scanning** to automatically extract details like amount, date, and category.

---

##  Why I Built This

Managing daily expenses is still a manual and time-consuming task. Most people:

* Forget to track expenses
* Lose receipts
* Don’t analyze spending patterns

I built this project to:

* Automate expense tracking using AI
* Reduce manual data entry
* Provide a smarter way to manage personal finances

---

##  Key Features

### 🧾AI Receipt Scanner

* Upload a receipt image
* Automatically extracts:

  * Amount
  * Date
  * Merchant name
  * Category
* Auto-fills transaction form

---

### Transaction Management

* Add, update, delete transactions
* Categorize expenses (food, shopping, etc.)
* Support for income & expenses

---

###  Account Management

* Create multiple accounts
* Track balances in real-time
* Default account support

---

###  Dashboard & Insights

* Visual overview of spending
* Category-wise breakdown
* Budget tracking

---

###  Recurring Transactions

* Daily / Weekly / Monthly / Yearly tracking
* Automatically calculates next transaction date

---

###  Authentication

* Secure login/signup using **Clerk**
* User-specific data isolation

---

##  Tech Stack

### Frontend

* Next.js (App Router)
* React
* Tailwind CSS
* ShadCN UI

### Backend

* Next.js Server Actions
* Prisma ORM

### Database

* PostgreSQL (Neon)

### Authentication

* Clerk

### AI Integration

* Google Gemini API (for receipt scanning)

### Other Tools

* Arcjet (rate limiting & protection)
* Zod (validation)

---

##  How AI Works

1. User uploads receipt image
2. Image converted to base64
3. Sent to Gemini API
4. AI extracts structured JSON
5. Form auto-filled with extracted data

---

##  Installation & Setup

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

npm install
npm run dev
```

---

##  Environment Variables

Create `.env.local`:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_key

DATABASE_URL=your_db_url
DIRECT_URL=your_db_url

GEMINI_API_KEY=your_api_key
```

---

##  Future Enhancements (My Vision)

This is where the project becomes powerful 

###  AI Payment Tracking (My Idea)

Today many users pay via:

* Google Pay
* PhonePe
* UPI apps

 These transactions are NOT automatically tracked in finance apps.

###  My Next Goal:

* Detect payment screenshots / messages
* Auto-log transactions from:

  * SMS
  * Screenshots
  * Payment notifications

 Example:

> User pays via PhonePe → App automatically records transaction

---

###  Smart Insights (Future)

* Spending predictions
* Monthly reports
* AI financial suggestions

---

###  Mobile Optimization

* Better UX for mobile users
* Camera-based instant scanning

---

##  What I Learned

* Full-stack development with Next.js
* Real-world API integration (AI)
* Debugging production-level issues
* State management with React Hook Form
* Building scalable architecture

---

##  Conclusion

This project is not just about tracking expenses —
it is about **building an intelligent financial assistant using AI**.

---

##  Author

**Naresh Bondla**

---

