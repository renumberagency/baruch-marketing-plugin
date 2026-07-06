---
description: בחירת אסטרטגיית עיצוב + בנייה של דף נחיתה בעברית עם Framer Motion ו-RTL
---

המשתמש מוכן לעצב/לבנות דף נחיתה (כבר יש לו קופי).

**שלב 1 — אסטרטגיה:**
הפעל את ה-skill `design-strategist`:
- נתח את סוג המוצר, מחיר, קהל
- שאל על צבעי מותג קיימים (אם יש)
- הצע 3-4 פלייבוקים מתאימים (Dark Premium / Elegant Authority / Clean Light / White DR / Dark Funnel / Cinematic Scroll)
- תן למשתמש לבחור
- פלט: Design Brief JSON

**שלב 2 — בנייה:**
הפעל את ה-skill `baruch-design-agent` עם ה-Design Brief:
- בנה לפי ה-playbook שנבחר
- Framer Motion לאנימציות (lazy import)
- RTL מלא, מובייל קודם
- כל סקשן = קומפוננטה נפרדת
- Touch targets 44px+, פונט מינימלי 16px

**חוקי זהב (חובה!):**
- צבע אקצנט אחד לכל הדף (60-30-10)
- כותרות ממורכזות תמיד
- אין טקסט בתוך boxes מסביב
- "Squint test": ההיררכיה צריכה להיות ברורה גם כשמצמצמים עיניים
- מצב מובייל = הראשון שבונים

התחל בלשאול: "הראה לי את הקופי / Brief, או ספר לי על המוצר ואני אבחר playbook."
