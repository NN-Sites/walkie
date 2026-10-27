# Walkie – האתר הרשמי

- `index.html` – דף הבית עם קישור ל-Google Play.
- `t/index.html` – יעד קישורי "שיתוף נסיעה בלייב": מנסה לפתוח את Walkie (`walkie://t/<מזהה>`), ואם היא לא מותקנת מציג
  "סליחה, אבל Walkie לא מותקנת אצלך." וכפתור הורדה מ-Google Play.

הקישור שהאפליקציה שולחת: `https://nn-sites.github.io/walkie/t/?id=<מזהה>` (`OPEN_BASE` ב-`walkie/public/js/config.js`).
