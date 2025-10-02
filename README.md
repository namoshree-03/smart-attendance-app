# Smart Attendance System ⚡

Smart Attendance App is an **AI-powered classroom attendance system** that replaces traditional registers. It is a facial recognition + cloud-based system that marks attendance from a single classroom photo.

---

## 📂 Project Details 

- Automates attendance in one click using **face recognition**
- Provides **real-time attendance reports** to teachers & admins
- Prevents **proxy attendance & manual errors**
- Scalable to integrate with **LMS/ERP systems**

---

## 🌐 Live Demo & Deployment

The Smart Attendance App web interface is hosted using GitHub Pages.

**🔗 [View Live Application Here](https://namoshree-03.github.io/smart-attendance-app/)**

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

- Frontend: Flutter, HTML, CSS
- Backend: Python, Firebase, Google Cloud
- AI/ML: Face Recognition (ML Kit / Cloud Vision)

---

🤖 Models Used

- Face Detection Model – detects multiple faces in classroom photo.
- Face Recognition Model – matches detected faces with enrolled students.
- Attendance Mapping Logic – marks attendance and syncs with cloud.

---





