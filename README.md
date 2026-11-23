# Money Harvest 🌿 — Grow Your Financial Intelligence

A clean, modern financial-education and cyber defense platform with interactive calculators, scam threat analysis, learning quizzes, and an AI companion. Designed for **Web** and ready to bundle into an **Android/iOS Mobile App** via Capacitor.

---

## ✨ Key Features

1. **Interactive Scam & Threat Detector (`#/scam`)**
   - Real-time pattern matching for **"Digital Arrest" extortion**, fake CBI/police impersonation, illegal Telegram high-yield clubs, and malicious .apk power bill scams.
   - Severity scoring (0–100), itemized red flags, and immediate 1930 reporting advice.

2. **Smart Financial Calculators (`#/calculators`)**
   - **SIP Calculator**: Monthly contributions, expected return rates, and wealth accumulation projections.
   - **Loan EMI**: Principal breakdown, total interest payable, and monthly amortization.
   - **50/30/20 Budgeting**: Automatic income split across Essentials, Lifestyle Wants, and Future Savings.
   - **Inflation Impact**: Visual purchasing power erosion over 1–35 years.

3. **Financial Education Hub & Quizzes (`#/education`)**
   - Jargon-free lessons on budgeting, UPI safety rules, compounding interest, and cyber defense.
   - Practice questions with instant scoring and explanations.

4. **Harvest AI Assistant (`#/ai`)**
   - Educational AI companion explaining financial terms, comparing FDs vs Mutual Funds, and offering safety guidelines.

5. **Official Verification Gateways (`#/cyber`)**
   - Direct emergency links: **National Cyber Crime Helpline (1930)**, Chakshu (Sanchar Saathi), SEBI Investor Education, and RBI Kehta Hai.

6. **Verified Certificates (`#/certificates`)**
   - Customizable completion certificates with verifiable course track identifiers ready to print or save.

7. **Community Discussion Forum (`#/community`)**
   - User-submitted scam alerts, SIP milestones, and budgeting success stories.

---

## 🎨 Theme & Organic Aesthetics
Styled with the signature Money Harvest organic palette:
- **Background**: `#FEFAE0`
- **Forest Slate**: `#2F3625`
- **Bronze Gold**: `#8F6B44`
- **Sage Olive**: `#CCD5AE` & `#E9EDC9`
- **Parchment**: `#FAEDCD`

---

## 🚀 Getting Started (Web)

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed (v18 or higher recommended).

### 1. Install Dependencies
```bash
npm install
```

### 2. Start the Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### 3. Build for Production
```bash
npm run build
```
The optimized production bundle will be created in the `dist/` directory.

---

## 📱 Converting into a Mobile App (Android / iOS)

The project includes **Capacitor** configuration (`capacitor.config.json`) and mobile safe-area styling, allowing you to convert it into a native mobile app in a few simple commands:

### 1. Build the Web Assets
```bash
npm run build
```

### 2. Add Android or iOS Platforms
```bash
# Add Android
npx cap add android

# Add iOS (macOS required)
npx cap add ios
```

### 3. Sync Web Code into Native Project
```bash
npm run cap:sync
```

### 4. Open and Run in Android Studio or Xcode
```bash
# For Android Studio
npm run cap:open:android

# For Xcode
npm run cap:open:ios
```
From Android Studio / Xcode, you can build an APK/AAB or run on a connected mobile device or emulator!

---

## 🐙 Push to GitHub

To push this project to your GitHub account:

```bash
# 1. Initialize git
git init

# 2. Add all files
git add .

# 3. Create your initial commit
git commit -m "feat: initial commit of Money Harvest web and mobile app"

# 4. Set main branch
git branch -M main

# 5. Connect your remote repository
git remote add origin https://github.com/<YOUR-USERNAME>/money-harvest.git

# 6. Push to GitHub
git push -u origin main
```

---

## ⚖️ Disclaimer
Money Harvest provides educational content only and does not offer accredited degrees or personalized investment, legal, or tax advisory services.
