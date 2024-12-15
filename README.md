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

## ⚙️ Technologies
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

### 👥 Team members
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/yosi-miller?v=4&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="יוסי מילר" />](https://github.com/yosi-miller)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/benioren1?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="בנימין אורנשטיין" />](https://github.com/benioren1)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/RafiGedge?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="רפאל גדז'" />](https://github.com/RafiGedge)
[<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/deltaforce26?v=4?&h=50&w=50&fit=cover&mask=circle&maxage=7d" title="אהרון ברלינסקי" />](https://github.com/deltaforce26)

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

***

# Maritime Monitoring System

## �� Name: Real-Time Maritime Monitoring

### ��️ Description
A real-time maritime monitoring system that collects, processes, and visualizes data from various sensors to track and evaluate threats posed by maritime objects like ships and submarines. The system calculates dynamic danger levels and displays them interactively on a web-based map interface.

### Data Sources:
* **Kafka Streams:** Aggregates data from radar, sonar, and thermal sensors.
* **MQTT:** Efficient protocol for live updates from maritime sensors.
* **Custom Generators:** Simulated dummy JSON data for testing.

### Process Flow:
1. **Data Collection:** Data streams into Kafka and MQTT from sensors.
2. **Data Processing:** Python processes the raw data using Pandas for analytics and calculates threat levels.
3. **Real-Time Updates:** Flask-SocketIO delivers real-time updates to the front end.
4. **Visualization:** Interactive map using Leaflet.js displays tracked objects with dynamic threat indicators.

### Features:
- **Threat Level Calculation:** Multi-parameter analysis to assess object danger.
- **Interactive Map:** Displays real-time positions and statuses of maritime objects.
- **Alerts:** Highlights hostile and high-risk objects for immediate attention.

---

### �� Installation
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python kafka_listener.py
python flask_server.py
```

### �� Screenshots
![Placeholder Image](https://via.placeholder.com/150)
![Placeholder Image](https://via.placeholder.com/150)
![Placeholder Image](https://via.placeholder.com/150)

---

## Technologies
![Python](https://img.shields.io/badge/Python-3.9-blue?style=flat&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.0.2-lightgray?style=flat&logo=flask)
![Kafka](https://img.shields.io/badge/Kafka-2.8.0-blue?style=flat&logo=apache-kafka)
![MQTT](https://img.shields.io/badge/MQTT-5.0.0-green?style=flat&logo=mqtt)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-purple?style=flat&logo=pandas)
![Socket.IO](https://img.shields.io/badge/Socket.IO-4.5.4-black?style=flat&logo=socket.io)
![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-green?style=flat&logo=leaflet)

---

### ����‍�� Code
- GitHub: [Maritime Monitoring System Repository](https://github.com/example/maritime-monitoring)

---

### Team Members
[<img src="https://via.placeholder.com/50" title="Team Member 1" />](https://github.com/team-member1)
[<img src="https://via.placeholder.com/50" title="Team Member 2" />](https://github.com/team-member2)
[<img src="https://via.placeholder.com/50" title="Team Member 3" />](https://github.com/team-member3)
