# Single Site Android Browser

הפרויקט מאפשר לך ליצור אפליקצייה לאנדרואיד עבור כל אתר אינטרנט עם הגבלה על רשימת האתרים המותרים באמצעות רשימה לבנה.

### תכונות:

* מאפשר רשימה לבנה לא מוגבלת
* מאפשר לציין כתובת ייחודית שתהיה נקודת ההתחלה (אם לא צויין יתחיל בכתובת הראשונה ברשימה הלבנה)
* טיפול בURI מותאם של tel, mailto וwhatsapp.
* כפיית מצב תצוגה
* חסימת מדיה
* מצב no ssl
* הסתרת הבאנר של נטפרי
* טעינה מחדש של הדף בהחלקה ללמטה בשליש העליון של המסך

## Configuration - קונפיגרציה

ניתן לערוך את ההגדרות ישירות [`app/build.gradle`](./app/build.gradle) (או לטעון באמצעות קובץ env שממוקם בתיקיית app).

לאחר ביצוע השינויים יש לבצע הידור מחדש של הפרויקט בשביל לסנכרן את השינויים.

יש לארוז כרגיל

האפשרויות בenv:

ALLOWED_DOMAINS=example.com // כתובות דומיין שיאופשרו באפליקצייה
STARTUP_URL=example.com // כתובת האתר שבו תתחיל האפליקציה
VIEW_MODE=AUTO // מצב תצוגה (אפשרי: AUTO, PORTRAIT, LANDSCAPE)
BLOCK_MEDIA=false
BLOCK_ADS=true
NO_SSL=false
APP_NAME=my app
APPLICATION_ID=com.myapp.webapp
VERSION=1.0.0
HIDE_NETFREE=true // הסתרת הבאנר של נטפרי

## License - רישיון

This application is distributed under the GNU General Public License version 3 (GNU GPL-3.0). See the [LICENSE](LICENSE) file for more details.

## Disclaimer - כתב ויתור

לידיעתך, אינני עורך דין ואין לראות במידע הניתן כאן ייעוץ משפטי. חשוב להתייעץ עם גורם משפטי מוסמך כדי להבטיח עמידה בכל דרישות הרישוי הרלוונטיות וחובות.

Please note that I am not a lawyer and the information provided here should not be considered legal advice. It is important to consult with a qualified legal professional to ensure compliance with all relevant licensing requirements and obligations.
