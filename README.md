# Baruch Marketing — Claude Code Plugin

פלאגין רשמי של **ברוך חדד** ל-Claude Code: כל הסקילים של קופירייטינג, עיצוב דפי נחיתה, SEO ו-CRO — מאוגדים לחבילה אחת שמתקינים בפקודה אחת.

> בנוי בשבילכם, התלמידים. כל המתודולוגיה של 24 הצעדים, פלייבוקי העיצוב, ה-CRO frameworks — הכול במקום אחד.

---

## מה זה כולל

### 14 סקילים

**🚀 Workflow ראשי**
- **`landing-page`** — האורקסטרטור: פייפליין מלא של 9 שלבים מקופי לדף חי

**✍️ קופירייטינג**
- **`baruch-copy-agent`** — מחולל הקופי לפי שיטת 24 הצעדים (פלט JSON מובנה)
- **`copywriting`** — עקרונות קופי שיווקי כלליים, headlines, CTAs
- **`marketing-psychology`** — פסיכולוגיה התנהגותית ושכנוע

**🎨 עיצוב**
- **`design-strategist`** — בוחר playbook עיצוב + פלטת צבעים מתוך 6 פלייבוקים
- **`baruch-design-agent`** — בונה דפי Next.js עם Framer Motion, RTL, מובייל קודם
- **`landing-page-design`** — formula above-the-fold, מבנה דף, מיקום CTA

**📈 CRO**
- **`page-cro`** — אופטימיזציית המרות לדפי נחיתה
- **`form-cro`** — אופטימיזציית טפסים
- **`signup-flow-cro`** — אופטימיזציית הרשמה / signup

**🔍 SEO**
- **`seo`** — meta tags, on-page, technical SEO
- **`seo-audit`** — אודיט SEO מקיף עם צ'קליסט מלא
- **`programmatic-seo`** — דפי SEO בסקייל מתבניות
- **`schema-markup`** — JSON-LD ו-structured data

### 5 Slash Commands

| Command | מה זה עושה |
|---------|------------|
| **`/baruch-marketing:landing-page`** | מפעיל את הפייפליין המלא של 9 שלבים — מקופי לדף חי |
| **`/baruch-marketing:copy`** | כתיבת קופי בלבד לפי 24 הצעדים |
| **`/baruch-marketing:design`** | בחירת אסטרטגיית עיצוב + בנייה |
| **`/baruch-marketing:seo`** | אודיט SEO + תיקונים מעשיים |
| **`/baruch-marketing:cro`** | אופטימיזציית המרות לדף/טופס/הרשמה |

---

## התקנה (3 פקודות)

פתחו את Claude Code ב-VS Code (או terminal), והקלידו:

```
/plugin marketplace add renumberagency/baruch-marketing-plugin
/plugin install baruch-marketing@baruch-marketing
```

זהו. תקבלו אישור התקנה והפלאגין יהיה זמין מיידית.

**לבדיקה שזה עובד:** הקלידו `/help` ותראו את ה-commands החדשים תחת `baruch-marketing`.

---

## שימוש

### דוגמה 1 — בנייה מלאה של דף נחיתה

```
/baruch-marketing:landing-page
```

Claude יעבור איתכם על 9 השלבים — שאלות על המוצר, אסטרטגיה, קופי, עיצוב, ובסוף ירכיב לכם דף Next.js מלא.

### דוגמה 2 — רק קופי

```
/baruch-marketing:copy

המוצר שלי הוא קורס פרטי למדריכי כושר.
המחיר 1,997 ש"ח. הקהל זה מדריכים שמרוויחים 8K-15K ורוצים להגיע ל-30K+.
```

תקבלו 11 צ'אנקים של קופי מלא ב-JSON.

### דוגמה 3 — אודיט CRO לדף קיים

```
/baruch-marketing:cro

הנה הדף שלי: https://example.com/sales
שיעור ההמרה כרגע 1.2% ואני רוצה להגיע ל-3%.
```

Claude ינתח את הדף וייתן לכם 3-5 שיפורים מסודרים לפי impact.

### דוגמה 4 — שימוש ישיר בסקיל מסוים

אפשר גם לקרוא לסקיל ספציפי בלי command:

```
תפעיל את ה-skill baruch-copy-agent עכשיו ותכתוב לי headline למוצר X
```

או בעברית פשוטה — Claude יזהה אוטומטית מה צריך:

```
אני רוצה לכתוב דף מכירה לקורס שלי
```

---

## מה הפלאגין **לא** כולל

- ❌ אין דשבורד Meta Ads (זה ריפו נפרד)
- ❌ אין API keys, tokens, או קרדנציאלים אישיים
- ❌ אין נתונים אישיים של עסק/תלמידים
- ❌ אין קוד backend — רק skills ו-commands

---

## דרישות

- **Claude Code** מותקן (CLI / VS Code Extension / Desktop App)
- חשבון Anthropic פעיל
- (אופציונלי) פרויקט Next.js + Tailwind v4 + Framer Motion אם רוצים שהסקילים יבנו לכם דפים

---

## עדכונים

הפלאגין מתעדכן באופן רציף. כדי למשוך גרסה חדשה:

```
/plugin marketplace update baruch-marketing
/plugin update baruch-marketing
```

---

## תמיכה

נתקעתם? יש באג? רעיון לשיפור?
- פתחו Issue ב-GitHub
- שלחו הודעה בקבוצת התלמידים

---

## רישיון

לשימוש פנימי של תלמידי ברוך חדד בלבד. אסור להפיץ הלאה ללא אישור.
