# Wifi-Hack

==========================================
📦 SAFE BACKUP TOOL
Developer: Md Rifat Islam
==========================================

⚠️ IMPORTANT:
এই টুলটি ফোনের গুরুত্বপূর্ণ ফাইল (Photo, Video, Audio, Documents) একসাথে ZIP করে ব্যাকআপ তৈরি করে।

👉 কোনো ডাটা ইন্টারনেটে পাঠায় না
👉 শুধু লোকাল backup.zip তৈরি করে

==========================================
🟢 REQUIREMENTS (TERMUX SETUP)
==========================================

1️⃣ Termux Update
pkg update && pkg upgrade -y

2️⃣ Python Install
pkg install python -y

3️⃣ Storage Permission
termux-setup-storage

👉 Allow চাপতে হবে

==========================================
🟢 REQUIRED LIBRARY
==========================================

pip install zipfile

(👉 zipfile সাধারণত আগে থেকেই থাকে, তবুও লাগলে দিন)

==========================================
🟢 RUN TOOL
==========================================

cd /sdcard/Download
python backup_tool.py

==========================================
🟢 OUTPUT
==========================================

📦 backup.zip ফাইল তৈরি হবে এখানে:
/sdcard/backup.zip

এর ভিতরে থাকবে:
✔ Download files
✔ DCIM (Photos & Videos)
✔ Pictures
✔ Movies
✔ Music
✔ Documents

==========================================
🟢 FEATURES
==========================================

✔ Fast file scan
✔ Progress bar
✔ Single ZIP backup
✔ No internet required
✔ Safe local storage backup

==========================================
🟢 TROUBLESHOOT
==========================================

❌ Module not found:
pip install requests (যদি অন্য script লাগে)

❌ Permission issue:
termux-setup-storage আবার চালাও

==========================================
✨ END OF README
==========================================
