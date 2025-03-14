# Smart India Hackathon Workshop
# Date:14.03.2025
## Register Number: 212224230096
## Name: Iniya E
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Applicant Portal
User Registration/Login: Applicants create an account with personal details, qualifications, and skills.
Profile Management: Users upload resumes, certificates, and portfolios.
Application Submission: Applicants can apply for different programs/jobs/contests.
Skill Assessments: AI-driven tests to evaluate skills based on predefined criteria.
Simulation Challenges: Real-life problem-solving scenarios where applicants must showcase abilities.

2. Selector Panel (Evaluators)
Dashboard for Shortlisting: AI-assisted filtering based on applicant scores.
Automated Scoring & Ranking: Uses AI/ML to evaluate applications.
Live Interviews: Integrated video conferencing for real-time interviews.
Decision Analytics: Provides insights into applicant strengths and weaknesses.

3. Simulation & AI Integration
AI-Powered Selection Criteria: Adjusts selection parameters dynamically.
Gamification of Selection: Uses simulation-based tests instead of traditional MCQs.
Behavioral Analysis: AI evaluates body language, tone, and responses in interviews.

4. Admin Control & Security
Role-Based Access: Different access levels for applicants, selectors, and admins.
Data Encryption & Privacy: Secure storage of applicant data.
Report Generation: Exportable analytics on applicants' performance.

## Proposed Solution / Architecture Diagram
![Screenshot 2025-03-14 082725](https://github.com/user-attachments/assets/aa4bea63-4b6b-4086-8a77-b713fdbaefe7)


## Use Cases
![Screenshot 2025-03-14 082959](https://github.com/user-attachments/assets/de5d900c-8dc5-4ea9-855c-5dade3838bea)


## Technology Stack
1️⃣ Frontend (User Interface)
📌 Frameworks & Libraries

React.js / Angular / Vue.js → Modern, scalable UI
Tailwind CSS / Bootstrap → Responsive design
Redux / Context API → State management
WebRTC / Jitsi / Zoom API → Video interviews
📌 Features
✅ User registration & authentication
✅ Application forms & document uploads
✅ Live interviews & AI-assisted assessments

2️⃣ Backend (Application Logic)
📌 Languages & Frameworks

Node.js (Express.js) / Django (Python) / Flask (Python)
GraphQL / REST API for communication
📌 Features
✅ Business logic processing
✅ API management
✅ Secure authentication

3️⃣ Database & Storage
📌 Databases

PostgreSQL / MySQL → Structured data storage
MongoDB → NoSQL for flexible storage
📌 File Storage

AWS S3 / Firebase Storage → Resumes, certificates, and documents
📌 Features
✅ Secure storage of user data
✅ Fast retrieval & indexing

4️⃣ AI/ML Integration (Automated Evaluation & Selection)
📌 AI/ML Frameworks

TensorFlow / PyTorch → AI-driven skill assessments
OpenAI APIs / NLP models → Behavioral analysis
Scikit-learn → Ranking & recommendation engine
📌 Features
✅ AI-powered scoring & ranking
✅ Resume parsing & keyword extraction
✅ Behavioral analysis in interviews

5️⃣ Security & Authentication
📌 Security Tools

JWT (JSON Web Tokens) / OAuth 2.0 → Secure authentication
Role-Based Access Control (RBAC) → Restrict permissions
SSL/TLS Encryption → Secure data transmission
📌 Features
✅ User authentication & role management
✅ Data encryption & privacy compliance

6️⃣ Hosting & Deployment
📌 Cloud Platforms

AWS / Google Cloud / Firebase → Scalable deployment
Docker & Kubernetes → Containerized deployment
📌 CI/CD (Continuous Integration/Delivery)

GitHub Actions / Jenkins → Automated deployments
📌 Features
✅ High availability & scalability
✅ Automated updates & monitoring

## Dependencies
1️⃣ Frontend Dependencies (React.js / Angular / Vue.js)
📌 For UI Development:

react / angular / vue → Core frontend framework
tailwindcss / bootstrap → Styling framework
react-router-dom → Frontend routing (React)
axios → API communication
redux / vuex / ngrx → State management
framer-motion → Animations
📌 For Video & Live Interviews:

webrtc → Peer-to-peer video communication
jitsi-meet / zoom-sdk → Embedded video calls
📌 For Form Handling & Validation:

formik + yup → Form handling & validation
react-hook-form → Lightweight form handling
2️⃣ Backend Dependencies (Node.js / Django / Flask)
📌 For API & Web Server:

express (Node.js) → Lightweight backend framework
django / flask (Python) → Full-stack backend framework
cors → Cross-Origin Resource Sharing
📌 For Authentication & Security:

jsonwebtoken (JWT) → Token-based authentication
bcryptjs → Password hashing
helmet → Security middleware
passport → User authentication
📌 For Database Management:

mongoose → MongoDB ORM
sequelize → SQL ORM (PostgreSQL/MySQL)
pg / mysql2 → PostgreSQL/MySQL driver
📌 For AI Integration:

openai → AI-based resume screening
tensorflow / pytorch → AI/ML model execution
nltk / spacy → Natural Language Processing (NLP)
scikit-learn → Machine Learning (ML) algorithms
3️⃣ Database Dependencies
📌 For Relational Databases (SQL-based):

postgresql → PostgreSQL database
mysql2 → MySQL database
sqlite3 → Local development database
📌 For NoSQL Databases:

mongodb → NoSQL document database
redis → Caching for fast responses
📌 For ORM (Object-Relational Mapping):

mongoose (MongoDB)
sequelize (PostgreSQL/MySQL)
SQLAlchemy (Python ORM for SQL databases)
