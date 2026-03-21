[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/enMIuyaD)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23221767)
# משימה 2: Android Studio, מבנה הפרויקט ו-Gradle 📱

## מטרת המשימה
להתנסות בסביבת הפיתוח Android Studio, להבין את מבנה הפרויקט, ולהוסיף dependency פשוט.

---

## הוראות

### חלק א' - סיור ב-Android Studio (30 נקודות)

1. פתח את הפרויקט ב-Android Studio
2. צלם screenshots של:
   - חלון Project (תצוגת Android)
   - קובץ AndroidManifest.xml
   - build.gradle (Module)
   - תיקיית res
3. השב על השאלות ב-`EXPLORATION.md`

**טיפ:** השתמש ב-View → Tool Windows כדי לפתוח חלונות שונים

---

### חלק ב' - עבודה עם Gradle (40 נקודות)

1. פתח את `build.gradle (Module: app)`
2. הוסף את ה-dependency הבא:
```gradle
implementation 'com.google.code.gson:gson:2.10.1'
```
3. לחץ על "Sync Now"
4. צור קובץ `GsonExample.java` עם דוגמת שימוש פשוטה
5. הסבר מה Gson עושה ב-`EXPLORATION.md`

---

### חלק ג' - ארגון קבצים (30 נקודות)

1. צור resource file חדש: `strings.xml` (אם לא קיים)
2. הוסף 3 strings לפחות
3. צור layout file חדש
4. תעד את התהליך ב-`EXPLORATION.md`

---

## קבצים להגשה

- [ ] `screenshots/` - תיקייה עם צילומי מסך
- [ ] `EXPLORATION.md` - תשובות לשאלות
- [ ] `GsonExample.java` - דוגמה לשימוש ב-Gson
- [ ] `app/build.gradle` - עם ה-dependency שהוספת

---

## קריטריונים להערכה

| קריטריון | ניקוד |
|----------|-------|
| סיור ב-Android Studio | 30 |
| עבודה עם Gradle | 40 |
| ארגון קבצים | 30 |
| **סה"כ** | **100** |

---

## בעיות נפוצות

**בעיה:** Gradle sync נכשל
**פתרון:** ודא שיש לך חיבור לאינטרנט. נסה File → Invalidate Caches → Restart

**בעיה:** לא רואה את התיקייה res
**פתרון:** שנה את התצוגה מ-Project ל-Android בחלון Project



---

## משאבים

- [Android Developer Docs - Project Structure](https://developer.android.com/studio/projects)
- [Gradle Build Configuration](https://developer.android.com/build)

---

בהצלחה! 🚀
