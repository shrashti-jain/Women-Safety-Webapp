# 🛡️ Women Safety Web Application

A full-stack **Django-based women safety web app** built to provide real-time security features for women, enabling quick access to emergency tools and resources.  
This project was developed as part of the **Smart India Hackathon (SIH)**, where our team ranked among the **Top 50 External Teams**.  

🔗 **Live Demo:** [Women Safety WebApp](https://women-safety-webapp-vmhz.onrender.com/)

---

## 🚀 Features

### 🔴 Emergency Tools
- **Fake Call** – Simulates an incoming call to distract or escape risky situations.  
- **Panic Shake** – Shake your phone to instantly send alerts.  
- **Panic Alert** – Sends an SMS with live location to predefined emergency contacts.  

### 🛡️ Self-Defense & Awareness
- **Self-Defense Training Videos** – Learn essential self-defense techniques.  
- **AI-Powered Accuracy Check (Future Scope)** – Analyzes uploaded self-defense practice videos and rewards coins.  

### 📍 Safety & Evidence
- **Safety Route** – Guides the user through the safest path using maps.  
- **Video & Audio Evidence** – Automatically starts recording in emergencies for proof and safety.  

---

## 🖼️ Screenshots

<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/ca2b6a2d-a413-4a73-833d-24a4ee6b2ac3" />
 

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Django (Python)  
- **Database:** SQLite / PostgreSQL  
- **APIs:** Google Maps API, Geolocation, Twilio (for SMS alerts)  
- **Deployment:** Render  

---

## 📂 Project Structure
women-safety-webapp/
│── templates/ # HTML files
│── static/ # CSS, JS, Images
│── safety/ # Django app with features
│── db.sqlite3 # Database
│── manage.py # Django entry point


---

## ⚡ Installation & Setup

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/women-safety-webapp.git
   cd women-safety-webapp

2. Create a virtual environment and activate it
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
  
3. Install dependencies
   ```bash
   pip install -r requirements.txt
   
4. Run migrations and start the server
   ```bash
   python manage.py migrate
   python manage.py runserver

5. Visit the app at
   ```bash
   http://127.0.0.1:8000/


## 📌 Future Enhancements

- AI-based gesture recognition for quick emergency triggers.
- Blockchain-based tamper-proof evidence storage.
- Multilingual support for wider accessibility.

## 👨‍💻 Team & Contribution

- Team Leader: Shrashti Jain
- Contributed as part of Smart India Hackathon.



