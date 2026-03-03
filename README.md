# AI-Powered Gmail Agent

סוכן AI חכם שמתממשק עם ה-Gmail API לניתוח, סיווג וסיכום אוטומטי של מיילים באמצעות מודלי Gemini.

## 🚀 יכולות עיקריות
- **Agentic Orchestration:** שימוש ב-Function Calling להפעלת כלים דינמיים בהתאם לתוכן המייל.
- **Gmail Integration:** שליפת מיילים מאובטחת באמצעות OAuth 2.0.
- **Content Analysis:** ניתוח אוטומטי של תוכן מיילים (Base64 decoding) וזיהוי דחיפות בעזרת Gemini 2.5 Flash.

## 🛠 טכנולוגיות
- Python
- Google Generative AI SDK
- Gmail API
- OAuth 2.0

## 🔐 אבטחה ופרטיות
פרויקט זה מוגדר עם `.gitignore` כדי למנוע חשיפת מפתחות API ופרטי אימות אישיים. 
*הערה: כדי להריץ את הפרויקט, יש ליצור קובץ `credentials.json` משלך על בסיס ה-template המצורף.*

## 💡 איך מריצים?
1. משכפלים את ה-Repo: `git clone <url>`
2. מגדירים credentials ב-Google Cloud Console.
3. מריצים את הסקריפט בסביבת פייתון מקומית או ב-Google Colab.