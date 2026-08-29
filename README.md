# לוח מנויים · הפועל תל אביב כדורסל

דף סטטי ב־GitHub Pages. הנתונים יושבים ב־`data.json` באותו מאגר.

## העלאה
1. מאגר חדש ופומבי, למשל `hapoel-subs`
2. העלה את `index.html`, `data.json`, `README.md` לשורש המאגר
3. Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `root` → Save
4. הכתובת שתתקבל: `https://<owner>.github.io/hapoel-subs/`

## הזנה יומית (רק אתה)
1. פתח `https://<owner>.github.io/hapoel-subs/#admin`
2. GitHub → Settings → Developer settings → Personal access tokens → Fine-grained token
   - Repository access: רק המאגר הזה
   - Permissions → Repository permissions → Contents: **Read and write**
3. הדבק את הטוקן בשדה Access token ולחץ "שמור הגדרות"
4. הדבק את הסיכום היומי → "קרא נתונים" → "שמור יום"

השמירה מבצעת commit ל־`data.json`. הצופים רואים את העדכון תוך כדקה.

## צפייה (סתו, אורן, רועי)
`https://<owner>.github.io/hapoel-subs/` — בלי טוקן, בלי חשבון, קריאה בלבד.

## אבטחה
- הטוקן נשמר ב־localStorage של הדפדפן שלך בלבד, אף פעם לא בקוד האתר
- מאגר פומבי = נתוני המכירות גלויים לכל מי שמגיע לכתובת
- לביטול גישה: מחק את הטוקן ב־GitHub
