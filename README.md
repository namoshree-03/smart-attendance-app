# Smart Attendance App ⚡

Smart Attendance App is an **AI-powered classroom attendance system** that replaces traditional registers. By combining **facial recognition, cloud storage, and real-time reporting**, it ensures accuracy, efficiency, and security in student tracking.

---

## 📂 Project Details 

- Automates attendance using **face recognition**
- Provides **real-time attendance reports** to teachers & admins
- Prevents **proxy attendance & manual errors**
- Scalable to integrate with **LMS/ERP systems**

---

## 🛠️ How to Set up the Project

### 1. Clone the Repository

Clone the project locally and navigate into the application directory.

```bash
git clone https://github.com/namoshree-03/smart-attendance-app.git
cd smart-attendance-app
```

### 2. Install Dependencies

For the frontend (Flutter), navigate to the project root and get the necessary packages:

```bash
flutter pub get
```
### 3. Set up Firebase

- Enable Firestore Database
- Enable Firebase Authentication
- Add your google-services.json (`for Android`) or GoogleService-Info.plist (`for iOS`).
### 4. Run the App
```bash
flutter run
```
---

🚀 How to Use

- Teacher/admin uploads student faces during enrollment.
- In class, teacher clicks “Take Attendance” → app captures classroom photo.
- Face Recognition Model identifies students and marks attendance automatically.
- Attendance records are stored in Firebase and available instantly.

---

🛠 Tech Stack

- Frontend: Flutter, HTML
- Backend: Firebase, Google Cloud
- AI/ML: Face Recognition (ML Kit / Cloud Vision)

---

🤖 Models Used

- Face Detection Model – detects multiple faces in classroom photo.
- Face Recognition Model – matches detected faces with enrolled students.
- Attendance Mapping Logic – marks attendance and syncs with cloud.





