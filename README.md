# 📧 AI-Powered Gmail Agent

סוכן AI חכם שמתממשק עם ה-Gmail API לניתוח, סיווג וסיכום אוטומטי של מיילים באמצעות מודלי Gemini. הפרויקט נועד להפוך את הניהול היומיומי של תיבת המייל ליעיל יותר, תוך הבנה עמוקה של הקשר (Context) ודחיפות.

---

## 🏗️ ארכיטקטורת המערכת
הסוכן מבוסס על תהליך של שליפת מידע גולמי (Raw Data), עיבודו באמצעות LLM, וביצוע החלטות מבוססות כלים (Tool Use).



---

## ✨ יכולות עיקריות
- **Agentic Orchestration:** שימוש ב-Function Calling המאפשר למודל להחליט באופן דינמי אילו כלים להפעיל (סיכום, סיווג, או ניסוח תגובה).
- **חילוץ נתונים חכם:** טיפול במבני MIME מורכבים של אימיילים ופענוח נתונים בפורמט Base64.
- **אוטומציה מבוססת בינה:** זיהוי אוטומטי של מיילים דחופים (Urgency Detection) והפרדתם מתוך עומס המידע.
- **ניהול הרשאות מאובטח:** מימוש OAuth 2.0 למניעת חשיפת סיסמאות וגישה מוגבלת (Least Privilege).

---

## 🛠️ טכנולוגיות
- **שפה:** Python 3.x
- **בינה מלאכותית:** Google Gemini 2.5 Flash / Pro
- **אינטגרציות:** Gmail API, Google Cloud Platform
- **כלים:** Google Generative AI SDK, OAuthlib

---

## 🔒 אבטחה ופרטיות (Security First)
פרויקט זה תוכנן תוך דגש על אבטחה. הקבצים הרגישים (כגון מפתחות API ו-Credentials) **אינם נכללים במאגר** ומוחרגים באמצעות קובץ `.gitignore`.

* **איך להגדיר בצורה בטוחה:** יש ליצור קובץ `credentials.json` מקומי ולוודא שהוא אינו נדחף ל-GitHub.

---

## 🚀 איך להתחיל?

1. **שכפול המאגר:**
   ```bash
   git clone [https://github.com/YourUsername/AI-Email-Agent.git](https://github.com/YourUsername/AI-Email-Agent.git)
   cd AI-Email-Agent