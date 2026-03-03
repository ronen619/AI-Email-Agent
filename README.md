# 📧 AI-Powered Gmail Agent

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/AI-Gemini_2.5-orange.svg" alt="AI Model">
  <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status">
</p>

הסוכן החכם שמנהל לך את תיבת המייל. הפרויקט משלב **Gmail API** יחד עם **Gemini LLM** כדי לבצע אוטומציה חכמה: סיכום מיילים, סיווג דחיפות, וניהול משימות – כל זה מבוצע דרך ארכיטקטורת סוכן (Agentic Orchestration).

---

## 🏗️ ארכיטקטורת המערכת
המערכת בנויה כסוכן עצמאי המשתמש ב-`Function Calling` כדי לבצע פעולות (Tools) בהתאם להקשר המייל.



---

## ✨ יכולות הליבה
- **🧠 Agentic Orchestration:** המודל לא רק "מדבר", הוא מחליט אילו כלים להפעיל (סיכום, סיווג, או ניסוח) בהתאם לתוכן.
- **🛡️ אבטחה בראש סדר העדיפויות:** מימוש OAuth 2.0 המבטיח גישה מאובטחת ללא חשיפת פרטי אימות.
- **⚡ אוטומציה חכמה:** זיהוי מובנה של מיילים דחופים (Urgency Detection) והפרדתם מרעש רקע.
- **🛠️ גמישות:** תשתית מוכנה להוספת כלים נוספים (Calendar, Slack, Drive).

---

## 🚀 מדריך התקנה (Quick Start)

### 1. הכנות ב-Google Cloud
- צור פרויקט ב-[Google Cloud Console](https://console.cloud.google.com/).
- הפעל את **Gmail API**.
- צור `credentials.json` והצב אותו בתיקיית השורש של הפרויקט.

### 2. התקנת תלויות
התקן את כל הספריות הנדרשות בלחיצה אחת:
```bash
pip install -r requirements.txt
3. הרצה
הפעל את הסקריפט:

Bash
python main.py
בעת ההרצה הראשונה, יפתח דפדפן לאישור גישה לחשבון הג'ימייל שלך.

🛠 טכנולוגיות
שפה: Python 3.x

מנוע AI: Google Gemini 2.5 Flash

API: Gmail API

SDK: Google Generative AI SDK

🛣️ מפת דרכים (Roadmap)
[ ] אינטגרציה עם Google Calendar: יצירת אירועים ישירות מתוך מיילים רלוונטיים.

[ ] התראות בזמן אמת: חיבור ל-Slack / Telegram לעדכונים דחופים.

[ ] Serverless Deployment: העברת הסוכן לענן (Google Cloud Functions) לריצה אוטומטית 24/7.

💡 למה הפרויקט הזה קיים?
בניתי את הפרויקט הזה כדי להתמודד עם אתגר ה-"Information Overload". המטרה הייתה להפסיק להשתמש ב-AI כצ'אט-בוט בלבד, ולעבור לבניית מערכות מנהלות שיודעות לבצע פעולות בפועל בסביבה אמיתית.

נבנה באהבה. מוזמנים לשלוח Issues או Pull Requests! 🤖
