# 🚀 מדריך מהיר - Google Analytics ב-5 דקות

## צעד 1: קבל את ה-ID שלך

1. לך ל: **https://analytics.google.com**
2. לחץ **"Start for free"** (או התחבר אם יש לך חשבון)
3. צור Property חדש:
   - שם: `PagePal Landing`
   - אזור זמן: `Jerusalem`
4. בחר **"Web"** platform
5. הזן URL: `https://maorgabay222.github.io/pagepal-landing/`
6. **העתק את ה-Measurement ID** (נראה כמו: `G-1234567890`)

---

## צעד 2: החלף ב-index.html

פתח `index.html` וחפש:

```html
id=G-XXXXXXXXXX
```

(יש 2 מקומות!)

החלף ל-ID שלך:

```html
id=G-1234567890
```

---

## צעד 3: העלה ל-GitHub

```bash
cd /Users/maor.gabay/pagepal-landing
git add index.html
git commit -m "add Google Analytics ID"
git push origin main
```

---

## צעד 4: בדוק שעובד

לך ל: **https://analytics.google.com**
→ **Reports** → **Realtime**

פתח את האתר שלך בטאב אחר:
**https://maorgabay222.github.io/pagepal-landing/**

אמור לראות **"1 user active now"** 🎉

---

## מה תראה אחרי 24 שעות:

```
👥 Users: כמה אנשים נכנסו
📊 Sessions: כמה כניסות
⏱️ Avg time: כמה זמן הם נשארו
🌍 Countries: מאיפה הם
📱 Devices: Mobile vs Desktop
🔗 Sources: WhatsApp, LinkedIn, Direct
```

---

**זהו! פשוט ככה** ✨

מדריך מפורט: [ANALYTICS_SETUP.md](./ANALYTICS_SETUP.md)
