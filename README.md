# 🕌 মসজিদ ফান্ড হিসাব

একটি সহজ, বাংলা ভাষার **মসজিদ/কমিটি ফান্ড হিসাব ব্যবস্থাপনা অ্যাপ**।  
ব্রাউজার থেকেই ব্যবহার করা যায় এবং GitHub Pages-এর মাধ্যমে বিনামূল্যে ওয়েবে চালানো যায়।

> **নোট:** এই repository-তে কোনো বাস্তব মসজিদ, সদস্য বা দাতার ব্যক্তিগত হিসাব/ফোন নম্বর/ব্যক্তিগত ডেটা প্রকাশ করবেন না।

## ✨ প্রধান সুবিধা

- 🧾 মাসভিত্তিক ফান্ডের হিসাব
- 💰 দান/জমা ও খরচের হিসাব
- 👤 দাতার প্রোফাইল ও মাসভিত্তিক তথ্য
- ⏳ যারা টাকা দেয়নি বা কম দিয়েছে তাদের আলাদা করে দেখা
- 💬 WhatsApp, কল ও SMS-এর জন্য রিমাইন্ডার
- 🧹 একই ব্যক্তির আলাদা নামে থাকা রেকর্ড মিলিয়ে নেওয়ার সুবিধা
- 🔍 হিসাবের গরমিল/ডুপ্লিকেট/ভুল খরচের লাইন শনাক্ত করার সুবিধা
- 📸 Backup ও আগের অবস্থায় ফিরে যাওয়ার সুবিধা
- ↩️ Undo এবং 🗑️ Trash/Restore সুবিধা
- 🔒 মাস Lock করার সুবিধা
- 🎯 লক্ষ্য ও তহবিল ব্যবস্থাপনা
- 📅 বার্ষিক হিসাব
- 💾 HTML/JSON backup ও restore
- ☁️ Google Drive-এ backup/sync-এর সুবিধা
- 🔐 Owner / Keeper / Viewer ধরনের ভূমিকা
- 🔑 PIN ও Google account ভিত্তিক access-এর সুবিধা
- 📱 মোবাইল ও 💻 কম্পিউটার—দুইভাবেই ব্যবহারযোগ্য
- 🌐 ইন্টারনেট না থাকলেও স্থানীয়ভাবে হিসাব লেখার সুবিধা

উপরের ফিচারগুলো বর্তমান অ্যাপের কোডে থাকা সুবিধার ভিত্তিতে লেখা হয়েছে। fileciteturn1file5L1-L1

## 🚀 ব্যবহার

### 1. সরাসরি ব্রাউজারে
`index.html` ফাইলটি Chrome/Edge-এ খুললেই অ্যাপ চালানো যায়।

### 2. GitHub Pages-এ বিনামূল্যে চালানো
1. GitHub-এ একটি নতুন **Public repository** তৈরি করুন।
2. এই repository-তে `index.html` এবং `README.md` upload করুন।
3. **Settings → Pages** এ যান।
4. **Deploy from a branch** নির্বাচন করুন।
5. Branch হিসেবে `main` এবং folder হিসেবে `/ (root)` নির্বাচন করে Save করুন।
6. কিছুক্ষণ পর GitHub একটি website link দেবে।

## ☁️ Google Drive / Online Sync

অ্যাপের মধ্যে Google Drive backup এবং Firebase ভিত্তিক web sync/access-এর code রয়েছে। Google Drive ব্যবহার করতে নিজের Google Apps Script deploy করতে হবে; Firebase sync ব্যবহার করতে নিজের Firebase configuration দিতে হবে। fileciteturn2file5L1-L1 fileciteturn4file1L1-L1

**গুরুত্বপূর্ণ:** নিজের Apps Script URL, private credentials, service-account private key বা অন্য কোনো গোপন তথ্য GitHub-এ প্রকাশ করবেন না।

## 📱 Android APK

APK repository-র সাধারণ source file হিসেবে না রেখে **GitHub Releases**-এ দেওয়া ভালো।

প্রস্তাবিত release asset:

`Mosque-Fund-Hisab-v1.0.0.apk`

Release-এর সঙ্গে চাইলে source code-এর ZIP-ও দেওয়া যায়।

## 📦 Project structure

```text
mosque-fund-hisab/
├── index.html
├── README.md
└── LICENSE
```

## 🤝 সবার জন্য ব্যবহার

এই project-টি অন্যরা ব্যবহার, পরিবর্তন ও নিজেদের মসজিদ/কমিটির প্রয়োজন অনুযায়ী customize করতে পারবে—যদি repository-তে দেওয়া license-এর শর্ত মেনে চলে।

## ⚠️ Privacy

এই ধরনের অ্যাপে দাতা/সদস্যের নাম, ফোন নম্বর, ঠিকানা ও আর্থিক তথ্য থাকতে পারে। তাই:

- বাস্তব ব্যক্তিগত হিসাব public repository-তে দেবেন না।
- Demo/public repository-তে খালি বা dummy data ব্যবহার করুন।
- Google Drive/Firebase access rules ঠিকভাবে configure করুন।
- কোনো password, PIN, token বা private key source code-এ রাখবেন না।

## 📄 License

এই project-এ repository-র `LICENSE` ফাইলের license প্রযোজ্য।
