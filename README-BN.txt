SIFAT GAMER MODS V2 - NO STORAGE

এই ভার্সনে Firebase Storage ব্যবহার করা হয় না, তাই Blaze billing/Storage upgrade দরকার নেই।

Features:
- Admin Login
- Add/Edit/Delete Mod
- MediaFire download link
- Thumbnail URL
- Search and category filter
- Firestore database

Setup:
1. Firebase Authentication -> Email/Password enabled.
2. Firestore Database তৈরি করুন।
3. Firebase Web App তৈরি করে firebase-config.js-এ Config বসান।
4. firestore.rules-এ YOUR_ADMIN_EMAIL বদলে আপনার Admin email দিন এবং Rules publish করুন।
5. GitHub Pages-এ এই ফোল্ডারের সব ফাইল upload করুন।

Thumbnail:
আপনার thumbnail image-এর direct URL দিন। GitHub repository-এর assets/ folder-এ image upload করে সেই image-এর URL ব্যবহার করা যায়।

MOD:
MediaFire-এ .mcpack/.mcaddon/.zip upload করুন -> Copy Link -> Admin -> Add Mod -> MediaFire Link + Thumbnail URL -> Add Mod.

গুরুত্বপূর্ণ:
Firebase Storage চালু করার দরকার নেই এবং Billing/Blaze upgrade করার দরকার নেই।
