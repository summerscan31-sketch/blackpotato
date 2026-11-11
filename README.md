# Mihon GitHub upload starter

এই ফোল্ডারে BanglaManga Mihon extension-এর APK, icon এবং license আছে। GitHub Actions, secret, build command বা signing setup লাগবে না।

## এখন যা করবেন

1. ZIP extract করুন।
2. আপনার **public** GitHub repository-এর root-এ এই ফোল্ডারের ভেতরের সব ফাইল upload করুন—ফোল্ডারটিকে আরেকটি nested folder হিসেবে নয়। `main` branch-এ commit করুন।
3. Repository-র ঠিকানাটি (উদাহরণ: `https://github.com/আপনার-নাম/আপনার-repo`) আমাকে পাঠান।

`repo.json` ও `index.pb` ফাইল দুটো এই starter-এ ইচ্ছা করেই রাখা হয়নি: Mihon-এর APK এবং index URL-এ আপনার repository-র সঠিক ঠিকানা বসাতে হয়। আপনার link পেলে আমি এই ২টি তৈরি করে দেব; সেগুলো একই repository root-এ upload করলেই প্রস্তুত। তারপর Mihon-এ `index.pb`-এর raw URL যোগ করবেন।

## গুরুত্বপূর্ণ

এটি BanglaManga extension APK; Mihon অ্যাপ নয়। এই নির্দিষ্ট APK-টি Android debug signing certificate দিয়ে signed—বর্তমান APK install হবে, কিন্তু পরের সংস্করণকে existing install-এর ওপর update করতে হলে একই signing key দিয়ে sign করতে হবে।
