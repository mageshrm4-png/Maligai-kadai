மளிகை கணக்கு - Android Studio Project
=====================================

இந்த project-ல் உள்ள வசதிகள்:
- Offline பொருள் பட்டியல்; பொருட்கள் தனியாக சேமிக்கப்படும்.
- Kg பொருட்களுக்கு Gram / Kg அளவில் பில் போடலாம். 100g, 250g, 500g போன்ற அளவுகளுக்கு விலை தானாக கணக்கிடப்படும்.
- Piece, Packet, Litre பொருட்களுக்கும் பில் போடலாம்.
- பில் சேமித்தால் இருப்பு குறையும்.
- பில் Delete செய்தால் அந்த பில்லில் விற்ற பொருட்களின் இருப்பு மீண்டும் சேர்க்கப்படும்.
- தினசரி / மாத விற்பனை மற்றும் மாத gross profit.
- செலவு பதிவு, Backup / Restore.

APK உருவாக்குவது:
1. Android Studio நிறுவவும்.
2. இந்த ZIP-ஐ Extract செய்யவும்.
3. Android Studio > Open > Extract செய்த MaligaiKadai folder தேர்வு செய்யவும்.
4. Gradle Sync முடியும் வரை காத்திருக்கவும் (முதல் முறை Internet தேவை; Android SDK 35 தேவைப்படலாம்).
5. Build > Build Bundle(s) / APK(s) > Build APK(s) தேர்வு செய்யவும்.
6. APK app/build/outputs/apk/debug/app-debug.apk என்ற இடத்தில் கிடைக்கும்.

கவனிக்க:
- இங்கு Android SDK / Gradle build சூழல் இல்லாததால் APK binary உருவாக்கப்படவில்லை; இது APK build செய்யக்கூடிய Android Studio source project.
- தரவு போனின் app storage-ல் சேமிக்கப்படுகிறது. App uninstall / Clear data செய்தால் local data அழியலாம். அதனால் Dashboard-ல் Backup எடுத்து வைத்துக்கொள்ளவும்.
- பில் Delete நிரந்தர செயல்; உறுதிப்படுத்தல் கேட்கப்படும். Product Master-ஐ bill deletion அழிக்காது.
