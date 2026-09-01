# computerlab

מערכת לניהול שיבוץ חדרי מחשבים ומשאבי תקשוב.

## מה קיים בפרויקט
- עמוד HTML סטטי אחד: [index.html](index.html)
- קונפיגורציית Vercel: [vercel.json](vercel.json)
- אייקון האתר: [favicon.svg](favicon.svg)
- הגדרת הרצה מקומית: [package.json](package.json)

## הפעלה מקומית
```bash
cd /workspaces/computerlab
python3 -m http.server 3000
```

לאחר מכן פתח בברוסר:
http://localhost:3000

## חיבור ל-Vercel
1. העלה את ה-repo ל-GitHub.
2. היכנס ל-Vercel והקש על "Add New Project".
3. בחר את ה-repository.
4. Vercel יזהה אוטומטית אתר סטטי.
5. שמור/Deploy.

## הערות
- אין צורך ל-build step.
- האתר עובד כעמוד HTML סטטי.
- המידע נשמר ב-localStorage בדפדפן, כך שאין צורך ב-backend.
