JOMS Android Project — প্রাথমিক সংস্করণ

এই প্রজেক্টটি JOMS Day 101 HTML ডেমোকে Android WebView অ্যাপ হিসেবে চালানোর জন্য তৈরি।

Android Studio-তে খোলার নিয়ম:
1. ZIP ফাইল Extract করুন।
2. Android Studio খুলে Open নির্বাচন করে JOMS_Android_Project ফোল্ডারটি খুলুন।
3. Gradle sync সম্পন্ন হতে দিন (Android SDK Platform 35 লাগবে)।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
5. তৈরি হওয়া APK Android ফোনে ইনস্টল করে পরীক্ষা করুন।

গুরুত্বপূর্ণ:
- এটি প্রাথমিক Android wrapper/source project; APK এখনো compile বা ফোনে পরীক্ষা করা হয়নি।
- অ্যাপটি অফলাইনে HTML ফাইল চালায় এবং WebView DOM storage ব্যবহার করে।
- প্রথমবার ব্যবহারের পর JSON backup আলাদা করে রাখুন।
- এই সংস্করণে লগইন/অ্যাডমিন অনুমতি, cloud sync, Play Store release, এবং সম্পূর্ণ native Android UI এখনো যোগ করা হয়নি।
- কোম্পানির লোগো/স্বাক্ষর HTML ডেমোর settings-এ সংরক্ষিত থাকলে সেগুলো নতুন app installation-এ স্বয়ংক্রিয়ভাবে স্থানান্তর হবে না; প্রয়োজন হলে ব্যাকআপ/রিস্টোর পরীক্ষা করুন।
