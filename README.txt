אסנת אקרמן 315747204
שירה יאיר 315389759

הוראות להרצת tagger1:

	- נדרש הקובץ load_data.py
	- ארגומנטים ל-main:
		1.  path לתיקייה בה שמורים קבצי הדאטה
		2. מספר 1 אם קוראים את POS ו-0 אם קוראים את NER.
דוגמה:
כדי להריץ על קבצי POS, שורת הפקודה תהיה:	python3 tagger1.py ./pos 1
כדי להריץ על קבצי NER, שורת הפקודה תהיה:	 python3 tagger1.py ./ner 0 
(אצלנו תיקיות POS ו-NER נמצאות בתיקייה הנוכחית ממנה מריצים את הקוד)

ההדפסות לקונסול יציינו תחילתו וסופו של אפוק, את אחוזי הדיוק והלוס על סט האימון וסט הבדיקה.
כדי לייצר קובץ פרדיקציות יש לשחרר מההערה את 2 השורות בסוף הפונקציה tagger1.

הוראות להרצת tagger2:

	- נדרש הקובץ load_data.py
	- ארגומנטים ל-main:
		1.  path לתיקייה בה שמורים קבצי הדאטה
		2. מספר 1 אם קוראים את POS ו-0 אם קוראים את NER.
	- נדרשים הקבצים wordVectors.txt, vocab.txt. יש לשים אותם באותה תיקייה ממנה מריצים את הקוד.

הוראות להרצת tagger3:

- נדרש הקובץ load_data.py
	- ארגומנטים ל-main:
		1.  path לתיקייה בה שמורים קבצי הדאטה
		2. מספר 1 אם קוראים את POS ו-0 אם קוראים את NER.
		3. מספר 1 אם רוצים להשתמש בווקטורים מאומנים מראש. 0 אם רוצים ווקטורים מאותחלים אקראית.
	- נדרשים הקבצים wordVectors.txt, vocab.txt. יש לשים אותם באותה תיקייה ממנה מריצים את הקוד.

דוגמה:
כדי להריץ על קבצי POS עם ווקטורים מאמונים מראש, שורת הפקודה תהיה:	python3 tagger1.py ./pos 1 1
כדי להריץ על קבצי NER, בלי ווקטורים מאמונים מראש שורת הפקודה תהיה:	0 python3 tagger1.py ./ner 0 
(אצלנו תיקיות POS ו-NER נמצאות בתיקייה הנוכחית ממנה מריצים את הקוד)