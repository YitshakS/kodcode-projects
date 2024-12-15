# Kodcode projects


## 🚀 Name: אמ"ן הקטן

### 📝 Description
מערכת מודיעין, המקבלת נתונים ממספר מקורות מידע, מנטרת ומסווגת מקורות חשודים, ומנתבת את האיומים לזירות הטיפול המתאימות לכל אחד מהם.

מקורות המידע:

* זיהוי מספרי רישוי (בהדגמה באמצעות מצלמת ארדואינו): לכידה בזמן אמת. במקרה של מספר חשוד, שליחת הזמן, המקום והתמונה שנלכדו.
* מעקב אחר קבוצות טלגרם ערביות: האזנה בזמן אמת לרשימת קבוצות. כאשר הודעה מתקבלת היא נשלחת לשרת עם הנתונים: זמן הודעה, פרטי שולח, הודעה מקורית, הודעה מתורגמת לעברית.
* מעקב אחרי מיילים: (בהינתן מייל וסיסמה) האזנה בזמן אמת לתיבת מייל ותפיסת מייל חשוד / שליפת כל המיילים / שליפת כמות נבחרת. ההודעות נשלחות לשרת עם הנתונים: זמן המייל, שולח, מקבל, כותרת, תוכן.

הנתונים הגולמיים המתקבלים בשרת נשמרים בבסיס הנתונים, המיילים בפוסטגרס והטלגרם במונגו. לאחר מכן כל נתון נשלח בקפקא לטופיק ראשי, עובר אנליזה ונקבע האם הוא מסוכן ואם כן לאיזה זירה הוא שייך. אם כן הוא נשלח לטופיק של הזירה הרלוונטית ומשם נשמר במונגו בטבלה של אותה זירה.

### 🛠️ Installation
```bash
  python -m venv .venv
  .\.venv\Scripts\activate
  pip install -r requirements.txt
  python corrects_the_six_error.py
  docker-compose up -d
```

### 💻 Screenshots
![Placeholder Image](https://via.placeholder.com/150)
![Placeholder Image](https://via.placeholder.com/150)
![Placeholder Image](https://via.placeholder.com/150)

## Technologies
![Docker](https://img.shields.io/badge/Docker-20.10.8-blue?style=flat&logo=docker)
![Flask](https://img.shields.io/badge/Flask-2.0.2-lightgray?style=flat&logo=flask)
![Git](https://img.shields.io/badge/Git-2.34-orange?style=flat&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Enterprise-black?style=flat&logo=github)
![Kafka](https://img.shields.io/badge/Kafka-2.8.0-blue?style=flat&logo=apache-kafka)
![MongoDB](https://img.shields.io/badge/MongoDB-4.4.6-green?style=flat&logo=mongodb)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-purple?style=flat&logo=pandas)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13.3-blue?style=flat&logo=postgresql)
![Python](https://img.shields.io/badge/Python-3.9-blue?style=flat&logo=python)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1.4.23-red?style=flat&logo=sqlalchemy)

### 👨🏻‍💻 Code

Github פרויקט ראשי: https://github.com/RafiGedge/amanhakatan.git
<br />
Github זיהוי לוחיות רישוי (בשלבי איחוד לפרויקט הראשי): https://github.com/RafiGedge/image_analysis.git

### Team members
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/yosi-miller?v=4&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="יוסי מילר" />](https://github.com/yosi-miller)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/benioren1?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="בנימין אורנשטיין" />](https://github.com/benioren1)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/RafiGedge?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="רפאל גדז'" />](https://github.com/RafiGedge)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/deltaforce26?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="אהרון ברלינסקי" />](https://github.com/deltaforce26)














## הצוות שלנו:



***

## 🚀 project title
description

### 🛠️ Installation
```bash
  docker-compose
  pip instal ...
```
### 💻 Screenshots
![Placeholder Image](https://via.placeholder.com/150)
![Placeholder Image](https://via.placeholder.com/150)
![Placeholder Image](https://via.placeholder.com/150)

## Technologies
[Python]: https://img.shields.io/badge/Python-3.9-blue?style=flat&logo=python
![Flask](https://img.shields.io/badge/Flask-2.0.2-lightgray?style=flat&logo=flask)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13.3-blue?style=flat&logo=postgresql)
![MongoDB](https://img.shields.io/badge/MongoDB-4.4.6-green?style=flat&logo=mongodb)
![GraphQL](https://img.shields.io/badge/GraphQL-15.5.0-e10098?style=flat&logo=graphql)
![Kafka](https://img.shields.io/badge/Kafka-2.8.0-blue?style=flat&logo=apache-kafka)
![Neo4j](https://img.shields.io/badge/Neo4j-4.4.0-green?style=flat&logo=neo4j)

### 👨🏻‍💻 Code

Github: https://github.com/...
<br />
Replit: https://replit.com/...

### Team members
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/yosi-miller?v=4&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="יוסי מילר" />](https://github.com/yosi-miller)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/benioren1?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="בנימין אורנשטיין" />](https://github.com/benioren1)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/RafiGedge?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="רפאל גדז'" />](https://github.com/RafiGedge)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/deltaforce26?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="אהרון ברלינסקי" />](https://github.com/deltaforce26)
