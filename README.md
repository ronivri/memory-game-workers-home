
# משחק זיכרון – התאמת עובד ליישוב (מודל A)

פרויקט סטטי (HTML/JS/CSS) לפריסה ב-GitHub Pages/Netlify. לכל עובד יש שני קלפים: שם העובד ותמונת היישוב שלו. גם אם כמה עובדים גרים באותו היישוב, ההתאמה מתבצעת לפי מפתח ייחודי לכל עובד.

## מבנה
```
memory-game/
├── index.html
├── data.js
└── images/
    ├── 1.png
    ├── 2.png
    ├── 5.jfif
    ├── 6.png
    ├── 7.jfif
    ├── 9.png
    ├── 10.jfif
    ├── 11.png
    └── 23.png
```

## שימוש מקומי
פשוט פתחו את `index.html` בדפדפן.

## פריסה ל-GitHub Pages
1. צרו ריפו חדש והעלו את התיקייה כפי שהיא.
2. Settings → Pages → Source: Deploy from branch, Branch: `main`, Folder: `/ (root)`.
3. ה-URL ייראה כך: `https://<username>.github.io/memory-game/`.

## הערות
- אם תוסיפו עובדים חדשים, הוסיפו שורה ל-`EMPLOYEES` ב-`data.js` והוסיפו קובץ תמונה מתאים בתיקיית `images/` עם אותה סיומת.
- ניתן להמיר קבצי JFIF ל-PNG/JPG לשמירה על אחידות, אך הקוד תומך גם בסיומות מעורבות.
