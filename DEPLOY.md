# פרסום form-254 כאפליקציה חינמית על iPhone ו-Mac

## דרישות מוקדמות
- חשבון GitHub חינמי (github.com)
- 5 קבצים מוכנים בתיקייה זו

---

## שלב 1 — צור Repository ב-GitHub

1. כנס ל-[github.com](https://github.com)
2. לחץ **"+"** (פינה ימנית עליונה) → **"New repository"**
3. מלא:
   - **Repository name:** `form254`
   - השאר הכל ברירת מחדל
4. לחץ **"Create repository"**

---

## שלב 2 — העלה את הקבצים

1. בדף ה-repo החדש לחץ **"uploading an existing file"**
2. גרור את 5 הקבצים הבאים לחלון:
   ```
   form-254.html
   manifest.json
   sw.js
   icon-192.png
   icon-512.png
   ```
3. גלול למטה → לחץ **"Commit changes"**

---

## שלב 3 — הפעל GitHub Pages

1. לחץ **Settings** (גלגל שיניים בסרגל העליון של ה-repo)
2. בתפריט השמאלי לחץ **Pages**
3. תחת **"Branch"**: בחר `main` ואחר כך `/ (root)`
4. לחץ **Save**
5. המתן **2–3 דקות**

---

## שלב 4 — הכתובת של האפליקציה

```
https://USERNAME.github.io/form254/form-254.html
```

> החלף `USERNAME` בשם המשתמש שלך ב-GitHub

---

## התקנה על iPhone

1. פתח **Safari** (חובה — לא Chrome)
2. הזן את הכתובת למעלה
3. לחץ **⎋ (Share)** → **"הוסף למסך הבית"**
4. האפליקציה מופיעה כאייקון ועובדת offline

## התקנה על Mac

1. פתח **Chrome** או **Edge**
2. הזן את הכתובת למעלה
3. לחץ על אייקון **⬇** בסרגל הכתובות → **"התקן"**
4. מופיעה ב-Launchpad ועובדת offline

---

## פתרון בעיות

| בעיה | פתרון |
|------|--------|
| שגיאת 404 | בדוק שהפעלת Pages ב-Settings → Pages |
| הכתובת לא עובדת | המתן 3 דקות נוספות לאחר הפעלת Pages |
| "הוסף למסך הבית" לא מופיע | ודא שאתה ב-Safari (לא Chrome) |
| האפליקציה לא מתעדכנת | נקה cache: Safari → הגדרות → Safari → נקה היסטוריה |

---

## אפשרויות עתידיות

| אפשרות | iPhone | Mac | App Store | עלות |
|--------|--------|-----|-----------|------|
| GitHub Pages PWA (עכשיו) | ✅ | ✅ | ❌ | חינם |
| Capacitor + Apple Developer | ✅ נייטיב | ✅ נייטיב | ✅ | $99/שנה |
| Tauri (Mac בלבד) | ❌ | ✅ | ❌ | חינם |
