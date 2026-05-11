# IT Talent Hub 🇰🇪
### A Specialized Marketplace for Verified Technical Talent

![PHP](https://img.shields.io/badge/PHP-8.x-777bb4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-9.1-4479a1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-ES6+-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![AI](https://img.shields.io/badge/Gemini_AI-1.5_Flash-4285f4?style=for-the-badge&logo=google-gemini&logoColor=white)

---

## 🌟 Project Overview
The **IT Talent Hub** is a specialized digital ecosystem built to bridge the "Trust Deficit" in the Kenyan technical gig economy. Unlike generic marketplaces, this platform enforces a **Verification-First** model where every professional is manually vetted by specialized technical reviewers before they can bid on projects.

It combines a secure **M-Pesa Escrow Engine** with **Heuristic AI assistance** to ensure financial integrity and professional communication standards for Kenyan SMEs and IT Professionals.

## 🔄 The Marketplace Lifecycle
The platform manages the complete project lifecycle, enforcing technical quality at every stage:

### 1. The Quality Gate (Vetting)
- **Specialized Tracks:** IT Professionals can manage up to **4 specialization tracks** (e.g., Web Dev, Data & AI, Cloud).
- **Manual Audit:** A professional cannot bid on a job until a Technical Reviewer manually audits their GitHub repositories and certifications for that specific track.
- **Client Verification:** Businesses must upload valid licenses, which are vetted by the Compliance Team before they can post opportunities.

### 2. Structured Job Posting
- **AI-Assisted Drafting:** Clients use the integrated **Gemini AI** to translate vague needs into professional technical requirements (minimum 50 characters).
- **Categorization:** Jobs are siloed into 5 departments to ensure they are only seen by the relevant verified experts.

### 3. Merit-Based Bidding & Negotiation
- **Verified Bidding:** Only professionals with a "Verified" status in a specific track can submit proposals.
- **Project-Linked Messaging:** An internal messaging drawer allows for price negotiation and scope definition. Conversations are permanently linked to the job ID for audit purposes.

### 4. The Escrow Handshake
- **Automated Locking:** Once a professional is selected, the system triggers an **M-Pesa STK Push**. 
- **Asynchronous Activation:** The contract is only "born" and the workroom opened once the Safaricom API confirms the funds are secured in the Hub's vault.

---

## 🚀 Key Innovations

### 1. Asynchronous M-Pesa Escrow Handshake
- **Problem:** "Ghost Contracts" where work starts without confirmed funding.
- **Solution:** Integrated Safaricom’s **Daraja API**. Contracts are only "born" upon a successful STK Push callback (`ResultCode: 0`). Funds are locked in a digital vault and released only upon client approval and mandatory rating.

### 2. Heuristic AI Assistant (Gemini 1.5 Flash)
- **Context-Aware Assistance:** A sliding AI panel that recognizes user roles (Admin, Client, or Prof).
- **Grounded Intelligence:** The AI is fed real-time platform data to help clients draft technical requirements (min. 50 characters) and assist freelancers in summarizing GitHub repositories for winning proposals.

### 3. Multi-Role Administrative Governance (RBAC)
A 6-tier administrative hierarchy designed for separation of duties:
- **Compliance:** Vets business licenses.
- **Technical Reviewers:** Departmentalized specialists (Engineering, Data & AI, Design, etc.) who audit GitHub links and certifications.
- **Finance Admins:** Handle M-Pesa payout releases.
- **Operational Moderators:** Enforce professional tone via a contextual messaging-flagging system.
- **Reporting Team:** Analyze platform growth via real-time **Chart.js** dashboards.

## 🛠️ Technical Stack
- **Backend:** Native PHP 8.x (Clean, modular architecture)
- **Database:** MySQL (InnoDB Engine) with **Atomic Transactions** for financial data.
- **Frontend:** HTML5, CSS3, Vanilla JavaScript.
- **Security:** 
  - Cryptographic 2FA (Two-Factor Authentication).
  - Strict Prepared Statements to prevent SQL Injection.

## 📂 System Architecture
The system follows a **3-Tier Architecture**:
1. **Presentation Layer:** Responsive UI with an adaptive navigation drawer for mobile.
2. **Logic Layer:** PHP-driven business rules and API integrations.
3. **Data Layer:** Normalized schema consisting of 20 interconnected tables.

## 📊 Business Intelligence
The platform includes a specialized **Analytics Center** that visualizes:
- **Marketplace Velocity:** Ratio of Open vs. Completed projects.
- **Financial Audit:** Total Inflow (Deposits) vs. Outflow (Payouts) to track current Escrow liquidity.
- **Track Popularity:** Real-time demand for specific technical skills in Kenya.

---

## 🔒 Security & Privacy
- **Privacy-by-Design:** Administrators cannot read private chats unless a user explicitly raises a "Flag."
- **Temporal Gatekeeping:** Automated 48-hour suspensions for users violating conduct rules.
- **Input Sanitization:** Global XSS protection and Regex-enforced password entropy.

## 👨‍💻 Author
**Grace Mueni**  
Final-year IT Project — Mount Kenya University  
[LinkedIn](https://www.linkedin.com/in/grace-mueni/) • [GitHub](https://github.com/GraceReece)
---
*Note: This repository is currently private to protect proprietary integration logic and API configurations. Access can be granted upon professional request.*
