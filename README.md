# 💰 Smart Wallet – Personal Finance Tracker

![Smart Wallet Screenshot](https://raw.githubusercontent.com/zeexz/Smart-Wallet/main/screenshots/home_screen.png) <!-- Replace if you add screenshots later -->

**Smart Wallet** is an Android expense tracker built with **Java** that helps you manage personal finances, set budgets, monitor real-time currency exchange rates, and stay updated with curated financial news—all in one intuitive app.

---

## ✨ Key Features

- **Expense Management**  
  ➕ Add, edit, and delete expenses with custom categories, amounts, and dates.
  
- **Budget Control**  
  📊 Set monthly budgets and track spending against your limits.

- **Live Currency Exchange**  
  💱 Real-time conversion rates using the **ExchangeRate-API** (free open-source service).

- **Financial News Feed**  
  📰 Relevant finance news powered by **[NewsData.io](https://newsdata.io/)**, filtered to show only market and money-related updates.

- **Offline Support**  
  All expense and budget data stored locally on your device (no account required).

---

## 🛠️ Tech Stack

| Component          | Technology                     |
|--------------------|--------------------------------|
| Language           | Java                           |
| IDE                | Android Studio                 |
| APIs               | ExchangeRate-API, NewsData.io  |
| Local Storage      | SQLite (via Room or raw DB)    |
| Min SDK            | API 21 (Android 5.0 Lollipop)  |

---

## 📲 How to Run

### Prerequisites
- Android Studio (latest stable version)
- Internet connection (for news & exchange rates)

### Setup Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/zeexz/Smart-Wallet.git

Add your API keys
Create a Constants.java file in your main package:

public class Constants {
    public static final String NEWS_API_KEY = "YOUR_NEWSDATA_IO_API_KEY";
    public static final String EXCHANGE_API_KEY = "YOUR_EXCHANGERATE_API_KEY"; // Use "YOUR_ACCESS_KEY" if using exchangerate-api.com
}
Never commit API keys! Add Constants.java to your .gitignore.

#3.Build & Deploy
Open project in Android Studio
Sync Gradle dependencies
Run on emulator or physical device

🖼️ App Screenshots



