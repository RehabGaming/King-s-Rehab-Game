
# Dynamic Game Description

## מבוך
1.  מה המאפיינים העיקריים של העצמים במשחק המבוך?
חפצים ומשתנים עיקריים:
המבוך:
מבנה דינמי: המבוך משתנה בכל פעם שהשחקן משחק במשחק.
שבילים אסטרטגיים: חלק מהשבילים מובילים לחפצים חיוניים (חפצי המלך), בעוד שאחרים מובילים למבוי סתום.
חפצים:
חפצי המלך : נדרשים לפתיחת היציאה מהמבוך ולהתקדמות לשלבים הבאים.
השחקן:
מאפיינים: השחקן יכול לזוז, לאסוף חפצים, ולפתור את המבוך לאחר שאסף את כל החפצים.
יכולות מיוחדות: ניתן להגביר את מהירות השחקן או להאט אותה (הכוונה למהירות הליכתו) 
2.  איך לקבוע את המאפיינים המספריים כך שהמשחק יהיה מאוזן?
מספר שלבים במבוך:
המבוך יכלול 3  שלבים, עם מבנים מורכבים יותר ככל שמתקדמים(גודל המבוך יגדל והמבוך יבנה באופן רנדומלי).
כל שלב ידרוש מהשחקן למצוא מספר חפצים (ככל שהשחקן יתקדם בשלבים מספר החפצים יגדל רמה ראשונה פריט אחד, רמה שניה 3 פריטים ורמה שלישית 5 פריטים).
רמת קושי עולה:
מורכבות המבוך:
המבוך יגדל בגודל(שלב ראשון המבוך בגודל 9X9 ובשאר השלבים נגדיל את המבוך).
החפצים ימוקמו במקומות קבועים אך המבוך ישתנה ממשחק למשחק.
יציאות המבוך: בשלב הראשון יהיו 2 יציאות מהמבוך ובשאר השלבים רק יציאה אחת.
בדיקות משחק:
Playtesting  עם שחקנים שונים יסייע לקבוע אם מגבלות הזמן והמורכבות מתאימות.
לדוגמה, אם שחקנים נכשלים בשלב הראשון בגלל דרגת הקושי, אפשר לפשט את המבוך.
מהם המיקומים של החפצים העיקריים במשחק המבוך?
חפצי המלך:
מיקום: בכל שלב, החפצים פזורים באזורים קבועים של המבוך. המבוך משתנה בכל פעם שהשחקן משחק.
היגיון: החפצים ממוקמים כך שיאלצו את השחקן לנווט לכל חלקי המבוך ולא רק לעבור בקו ישר לדלת.
יציאות:
מיקום: תמיד בסוף המבוך. השחקן צריך לאסוף את כל החפצים לפני שיוכל לפתוח את היציאה.
איך קבעתם את המיקומים כך שהמשחק יהיה מאוזן ומעניין?
שיקולי אתגר:
המפתחות פזורים כך שהשחקן יצטרך לעבור דרך אזורים מורכבים של המבוך.
הדלת ממוקמת בצורה ברורה אך רחוקה מהמפתחות כדי להוסיף אתגר.
שיקולי עניין:
המבוך נוצר בצורה רנדומלית בכל פעם כדי לשמור על רעננות במשחק.
מפתחות ממוקמים באזורים שמדרבנים את השחקן לחקור את כל המפה.
דוגמה למפה (שלב ראשון במבוך):   מבוך בגודל 9 על 9

![תיאור המבוך](https://raw.githubusercontent.com/RehabGaming/King-s-Rehab-Game/main/maze.png)



3. התנהגויות עיקריות של עצמים ודמויות במשחק המבוך:
חפצי המלך:
מופיעים במיקומים קבועים במבוך שמשתנה רנדומלית בכל משחק.
דורשים חקר של המבוך כדי לאסוף אותם.
יציאות:
נמצאות תמיד בקצוות של המבוך.
נפתחות רק לאחר שכל החפצים נאספו.
תופעות שנוצרות:
חקר: המבוך משתנה ממשחק למשחק מה שנותן לשחקן לחקור בכל משחק מחדש את המבוך.
למידה: השחקן מזהה דפוסים ולומד איך להשלים את המבוך בצורה אופטימלית.
4. אין מערכת כלכלית בתוך המשחק ומחוצה לו.
5. כמה ואיזה מידע יש לשחקן בזמן המשחק?
מידע זמין:
השחקן יכול לראות כמה פריטים חסרים לו כדי לפתוח את הדלת ולהתקדם לשלב הבא.
אופן הצגת המידע:
מספר החפצים: מוצג בפינה העליונה של המסך, מראה כמה חפצים נאספו מתוך סך החפצים הנדרשים.
מה נקודת המבט של השחקן על העולם?
מבט גוף שלישי:
השחקן רואה את הדמות שלו בתנועה במבוך.
מאפשר לשחקן לראות את הסביבה הכוללת, כולל חפצים, דלתות.
הבחירה במבט זה נועדה להקל על ניווט במבוך ולהגביר את תחושת החקר.
מדוע נבחרה נקודת מבט זו?
מבט גוף שלישי מעניק לשחקן ראייה רחבה יותר על הסביבה.
עוזר לשחקן לתכנן את התנועה ולזהות מיקומים אסטרטגיים (חפצים, יציאות, מבויים סתומים וכו').
מבט זה מתאים למשחקים שבהם השחקן נדרש לנווט במרחב מורכב ולנהל אינטראקציות עם אובייקטים שונים.
6. מה שיטת השליטה של השחקן על מצב המשחק?
שיטת השליטה:
במשחק המבוך, השחקן שולט באופן ישיר בדמותו. הוא נע בתוך המבוך בעזרת המקלדת (לדוגמה, מקשי החצים או .(WASD 
השחקן מבצע את הפעולות בזמן אמת כלומר, הוא מגיב מידית לאתגרים ולמבנה המבוך.
כיצד זה עובד?
השחקן נע במבוך, מחפש ואוסף את חפצי המלך שמפוזרים במיקומים שונים.
ברגע שהשחקן אוסף את כל החפצים הנדרשים, הסיציאה נפתחת, והוא יכול לצאת מהמבוך ולהשלים את השלב.
מדוע נבחרה שיטת שליטה זו?
תחושת מעורבות: השליטה הישירה בזמן אמת יוצרת חוויית משחק אינטראקטיבית ומעורבת, שבה השחקן שולט באופן מלא על הפעולות.
אתגר ודינמיות: שיטה זו מוסיפה תחושת דחיפות ואתגר, במיוחד כשיש מגבלת זמן או אויבים פוטנציאליים.
התאמה לסגנון המשחק: משחקי מבוך הם בדרך כלל מבוססי תנועה והתמצאות במרחב, ולכן שליטה ישירה בזמן אמת היא הבחירה הטבעית.
פשטות: שימוש במקלדת מאפשר שליטה קלה ונגישה, שמתאימה לשחקנים מכל רמות הניסיון.
7. אילו אסטרטגיות שחקנים יכולים לנקוט כדי לנצח במשחק?
אסטרטגיית חקר (Exploration):
חקירה שיטתית של המבוך לאיתור כל החפצים הנדרשים. מתאימה לשחקנים זהירים.
אסטרטגיית מהירות (Speedrun):
התמקדות בהגעה מהירה לדלת היציאה תוך איסוף המינימום הנדרש של חפצים.
האם ישנה אסטרטגיה שולטת?
לא, הצלחה תלויה בשילוב אסטרטגיות ובהתאמה למבנה המבוך.
האם ישנה אסטרטגיה נשלטת?
כן, אסטרטגיות לא יעילות, כמו מהירות יתר ללא חקירה מספקת, עלולות להכשיל את השחקן ולגרום לבזבוז זמן.

## סידור הממלכה
1. מה המאפיינים העיקריים של העצמים במשחק?
העצמים המרכזיים:
חפצים בסביבה:
פריטים הנמצאים בשלב הנתון כמו ספר, כרית וכו'.
ממוקמים במערך של פריטים בצד ימין למטה של המסך והשחקן צריך למקם אותם נכון.
מפה או רמז לסידור נכון:
מופיעה במסך ותפקידה להנחות את השחקן כיצד לסדר את הפריטים.
איך לקבוע את המאפיינים המספריים כך שהמשחק יהיה מאוזן?
מספר חפצים:
4 חפצים לשלב ראשון, עם עלייה הדרגתית במספרם בשלבים מתקדמים.
מורכבות סידור:
בתחילה, סידור פשוט עם מעט חפצים.
בשלבים מתקדמים, החפצים יהיו יותר מגוונים ודומים, מה שמאתגר את זיהוי המיקומים.
2. המיקומים של החפצים העיקריים במשחק?
חפצים:
בתחילת השלב, החפצים נמצאים במערך של חפצים ולא במקומם הטבעי בחדר.
מפה להכוונה:
ממוקמת בפינה קבועה במסך, מציגה את התצורה הנכונה לסידור.
איך קבעתם את המיקומים כך שהמשחק יהיה מאוזן ומעניין?
החפצים פזורים בצורה שתדרוש מהשחקן לעבור על כל הפריטים שצריך לשים במקומם בחדר הנתון בשלב.
ככל שהשלבים מתקדמים, המיקומים הופכים למאתגרים יותר, מה שמוסיף עניין.
אנחנו מיקמנו את החפצים שהשחקן צריך להחזיר למקומם במערך בפינה התחתונה של המפה על מנת שלשחקן יהיה נוח לראות אותם בעיניו ולמקם אותם על ידי פעולת גרירה

![סידור הממלכה](https://raw.githubusercontent.com/RehabGaming/King-s-Rehab-Game/main/%D7%A1%D7%99%D7%93%D7%95%D7%A8%20%D7%94%D7%9E%D7%9E%D7%9C%D7%9B%D7%94.png)



3. מה ההתנהגויות העיקריות של העצמים במשחק?
חפצים:
ניתנים להרמה וגרירה באמצעות העכבר.
מתמקמים במקום הנכון כאשר השחקן מזהה את המיקום המתאים לפי המפה.
4. אין מערכת כלכלתי במשחק או חיצונית.
5.  כמה ואיזה מידע יש לשחקן על מצב המשחק?
מידע זמין:
המיקום הנכון של החפצים מוצג במפה (רמז).
6. מה שיטת השליטה של השחקן על מצב המשחק?
שיטת שליטה:
ישירה: השחקן משתמש בעכבר לגרירת החפצים או במקשי ניווט.
בזמן אמת: על השחקן להזיז את החפצים ולמקם אותם תוך כדי תנועה.
7. אילו אסטרטגיות שחקנים יכולים לנקוט כדי לנצח במשחק?
אסטרטגיית זיהוי מהיר:
זיהוי מהיר של החפצים הנדרשים והתאמתם למיקומים במפה.
אסטרטגיית מיון:
תחילה למיין את כל החפצים לפי גודל (למשל, רהיטים וספרים) לפני סידורם ולסדר אותם בהתאם.
האם ישנה אסטרטגיה שולטת?
לא, שתי האסטרטגיות יכולות להצליח, והשחקן יכול לשלב ביניהן לפי סגנונו.
האם ישנה אסטרטגיה נשלטת?
כן, אסטרטגיית חוסר סדר או תנועה אקראית תבזבז זמן ועלולה להכשיל את השחקן.

## הגנה מפני פולשים
1. מה המאפיינים העיקריים של העצמים במשחק?
העצמים המרכזיים:
דמויות (תושבים ופולשים):
תושבים: דמויות חיוביות שהשחקן צריך לזהות ולשלוח ליעד הנכון (הממלכה).
פולשים: דמויות שליליות שהשחקן צריך לסווג ולשלוח ליעד אחר (מחוץ לממלכה).
מד זמן:
מציג את הזמן שנותר לסיווג כל הדמויות בשלב.
איך לקבוע את המאפיינים המספריים כך שהמשחק יהיה מאוזן?
מספר הדמויות:
בשלב ראשון: 4 דמויות להופעה איטית.
בשלבים מתקדמים: עד 6 - 8 דמויות להופעה מהירה יותר.
זמן מוקצב:
שלב ראשון: 60 שניות.
ירידה של 20% בזמן המוקצב בכל שלב מתקדם.
מהירות הופעת הדמויות:
דמויות מופיעות בקצב איטי בתחילה ומתגבר בשלבים מתקדמים.
2.  מהם המיקומים של החפצים העיקריים במשחק?
דמויות:
מופיעות בקצה העליון של המסך ונעות כלפי מטה.
יעדים:
שני צדדים בתחתית המסך:
צד ימין: הממלכה (לתושבים).
צד שמאל: מחוץ לממלכה (לפולשים).
איך קבעתם את המיקומים כך שהמשחק יהיה מאוזן ומעניין?
מיקום הדמויות בקצה העליון נותן לשחקן זמן תגובה לזהות ולשלוח אותן ליעד.
שני יעדים ברורים בתחתית המסך מונעים בלבול ומאפשרים לשחקן להגיב במהירות.
בנינו את המפה כך ששני הצדדים מסווגים לממלכה ומדבר כך שלשחקן יהיה נוח יותר לסווג את הדמויות ואת הדמויות אנחנו מזמנים מהחלק העליון של המסך על מנת שיהיה לשחקן יותר זמן להבין את הסיטואציה ולבחור לאן לסווג את הדמות.

![פולשים](https://raw.githubusercontent.com/RehabGaming/King-s-Rehab-Game/main/%D7%A4%D7%95%D7%9C%D7%A9%D7%99%D7%9D.png)


3.  מה ההתנהגויות העיקריות של העצמים במשחק?
דמויות:
נעות בקצב אחיד (משתנה בשלבים מתקדמים) לכיוון תחתית המסך.
מתאימות יעד בהתאם לפעולת השחקן (ימין או שמאל).
מד הזמן:
סופר לאחור ומגביר את תחושת הדחיפות.
4. אין מערכת כלכלית פנימית או חיצונית במשחק.
5. כמה ואיזה מידע יש לשחקן על מצב המשחק?
מידע זמין:
מספר הפעמים שנותר לשחקן לטעות(סיווג לא נכון).
הזמן שנותר לסיום השלב.
אופן הצגת המידע:
מד ניקוד: ממוקם בפינה העליונה של המסך.
מד זמן: מופיע ליד מד הניקוד.
6.  מה שיטת השליטה של השחקן על מצב המשחק?
שיטת שליטה:
השחקן משתמש במקשי החצים (ימין ושמאל) כדי לשלוח דמויות ליעדים המתאימים.
בזמן אמת: השחקן מגיב מיידית לדמויות שיורדות על המסך.
7. אילו אסטרטגיות שחקנים יכולים לנקוט כדי לנצח במשחק?
אסטרטגיית זיהוי מהיר:
זיהוי מהיר של דמויות לפי תכונותיהן וסיווגן מיד ליעד הנכון.
האם ישנה אסטרטגיה שולטת?
לא, האסטרטגיה אפקטיבית והשחקן יכול לשלב עם אסטרטגיות שונות.
האם ישנה אסטרטגיה נשלטת?
כן, התעלמות או סיווג אקראי יגרמו לשחקן לפספס דמויות, מה שיוריד את הניקוד שלו וימנע את השלמת השלב. (הניקוד במשחק זה כרגע בפיתוח אך עדיין התייחסנו אליו בנושא)
