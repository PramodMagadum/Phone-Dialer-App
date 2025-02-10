# Phone Dialer App

## 📱Overview
The objective is to build a **Phone Dialer App** for Android that allows users to:
- **Make phone calls** via a dial pad
- **View recent call logs**
- **Save and search contacts**

## 🚀 Features Implemented
### **1. Dial Pad**
- Traditional phone dial pad UI
- Users can input numbers and initiate a call

### **2. Call History**
- Displays a list of recent calls (incoming, outgoing, and missed calls)
- Fetches call logs using device permissions

### **3. Contacts Management**
- Allows users to save new contacts
- Lists stored contacts
- Implements a simple search functionality

### **4. Error Handling & Debugging**
- Handles permissions gracefully
- Displays appropriate error messages

## 🛠️ Technical Implementation
- **Framework**: React Native with Expo or React Native CLI
- **Call Detection**: React Native Call Detection package for call state management
- **State Management**: React Context API for managing app state
- **UI/UX**: Efficient and modern UI design with React Native components
- **Permissions Handling**: Manages required Android permissions properly

## 🎯 Bonus Features (Optional Enhancements)
- 🌙 Dark Mode Toggle
- 🌍 International Dialing Code Selector
- 🚫 Number Block/Unblock Feature
- 🔄 Google Contacts API Integration for contact syncing

## 📂 Project Structure
```
phoneapp/
│-- android/                   # Android native code
│-- ios/                       # iOS native code
│-- src/                       # Main app code
│   │-- classComponents/       # Class-based components
│   │-- statelessComponents/   # Functional components
│   │-- static/icons/          # Static assets
│   │-- utils/                 # Utility functions
│   │-- App.js                 # Main App Component (Inside `src/`)
│
│-- index.js                   # Entry Point (Outside `src/`)
│-- package.json
│-- babel.config.js
│-- metro.config.js
│-- app.json
│-- README.md
```

## 🔧 Installation & Setup
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/phone-dialer-app.git
cd phone-dialer-app
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Run the Application**
For Android:
```sh
npx react-native run-android
```
For iOS:
```sh
npx react-native run-ios
```

### **4️⃣ Start Metro Bundler (If not running automatically)**
```sh
npx react-native start
```

## 📦 Dependencies Used
- `react-native-navigation`
- `react-native-call-detection`
- `react-native-contacts`
- `react-native-permissions`
- `react-navigation`


## 🎯 Expected Outcome
This assignment aims to evaluate:
- Your understanding of **React Native/Flutter development**
- Your ability to **structure code efficiently**
- Your debugging skills and ability to handle app permissions
- Your approach to best practices in mobile app development

---

**💡 Need Help?**
If you encounter any issues, check the documentation or raise an issue in the repository!



