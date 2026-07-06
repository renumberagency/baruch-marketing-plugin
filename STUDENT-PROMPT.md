# הפרומפט לתלמידים — בדיקת התקנות

שלחו לתלמידים את ההוראה: **"הדביקו את הפרומפט הזה לתוך הצ'אט של Claude Code"** — ואת כל מה שבתוך הבלוק שלמטה.

---

בדוק את כל ההתקנות של סדנת Claude Code ותקן מה שחסר. אני כבר בתוך Claude Code אז אין צורך לבדוק אותו.

## הוראות כלליות
- זהה את מערכת ההפעלה (macOS/Windows) והשתמש בפקודות המתאימות:
  - macOS/Linux: `command -v <tool>`, נתיבים עם `~` או `$HOME`, shell = bash/zsh
  - Windows: `Get-Command <tool> -ErrorAction SilentlyContinue`, נתיבים עם `$HOME` או `$env:USERPROFILE`, shell = PowerShell
- לפקודות `claude`, `git`, `npm`, `node`, `gh`, `antigravity`, `code`, `cursor` - התחביר זהה בשתי המערכות.
- אם פקודה דורשת מירכאות בנתיב (רווחים, עברית) - השתמש במירכאות כפולות.

## מה לבדוק

### 1. כלים בסיסיים
- git
- node (גרסה 18+)
- npm
- gh (GitHub CLI)

בדיקה: `git --version`, `node --version`, `npm --version`, `gh --version`.

### 2. פלאגין baruch-marketing
- בדוק עם: `claude plugin list`
- שם מלא: `baruch-marketing@baruch-marketing`
- אם חסר, התקן:
  claude plugin marketplace add https://github.com/renumberagency/baruch-marketing-plugin
  claude plugin install baruch-marketing@baruch-marketing
- סקילים שצריכים להיות: `baruch-copy-agent`, `baruch-design-agent`, `landing-page`, `seo`, `seo-audit`, `page-cro`, `form-cro`, `signup-flow-cro`, `copywriting`, `design-strategist`, `landing-page-design`, `marketing-psychology`, `programmatic-seo`, `schema-markup`

### 3. תוספי IDE
בדוק בכל IDE שקיים במערכת (`antigravity`, `code`, `cursor`). לכל אחד שקיים - הרץ `<ide> --list-extensions` וודא שמופיעים:
- `anthropic.claude-code`
- `yechielby.claude-code-rtl`

אם חסר, התקן עם: `<ide> --install-extension <extension-id>`.

## פורמט תשובה
- הצג רשימה מסודרת עם ✓ לתקין ו-✗ לחסר.
- לכל דבר שהיה חסר - ציין אם הצלחת להתקין אותו.
- בסוף, אם הכל תקין, כתוב הודעה ירוקה בעברית: "כל הכבוד! הכל מותקן ומוכן לסדנה."
- אם משהו נכשל, כתוב בדיוק מה לעשות כדי לתקן (פקודה מדויקת למערכת ההפעלה של המשתמש).
- אל תציין בשום מקום שחסרים API keys או tokens.
