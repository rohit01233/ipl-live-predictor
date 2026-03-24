# 🏏 IPL Live Match Win Predictor

A machine learning web app that predicts the winning probability of an IPL match in real-time based on current match conditions.

---

## 🚀 Live Demo

🔗 [https://ipl-predictor.onrender.com](https://ipl-live-predictor.onrender.com/)

---

## 📌 Features

* 📊 Predicts win probability of both teams
* ⚡ Real-time match situation input
* 🧠 Machine Learning model (Scikit-learn)
* 🌐 Interactive UI using Streamlit
* 🚀 Deployed on Render

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy

---

## 📂 Project Structure

```
ipl-live-predictor/
│
├── app.py              # Main Streamlit app
├── pipe.pkl           # Trained ML model
├── requirements.txt   # Dependencies
├── start.sh           # Start script for deployment
└── README.md
```

---

## ⚙️ How it Works

1. User inputs:

   * Batting team
   * Bowling team
   * City
   * Target
   * Current score
   * Overs completed
   * Wickets fallen

2. The model calculates:

   * Required Run Rate
   * Current Run Rate

3. The trained ML pipeline predicts:

   * 🟢 Probability of batting team winning
   * 🔴 Probability of bowling team winning

---

## 🧪 Run Locally

### 1. Clone the repo

```
git clone https://github.com/your-username/ipl-live-predictor.git
cd ipl-live-predictor
```

### 2. Create virtual environment

```
python -m venv venv
source venv/bin/activate   # Mac/Linux
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run app

```
streamlit run app.py
```

---

## 🌐 Deployment

This project is deployed on Render.

### Steps:

* Connect GitHub repo to Render
* Set build command:

  ```
  pip install -r requirements.txt
  ```
* Set start command:

  ```
  bash start.sh
  ```

---

## 📸 Screenshots

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/ccf6e8c7-4d06-46f0-894c-e3b3a78421d1" />



---

## 🔥 Future Improvements

* 📡 Live match API integration
* 📈 Better model accuracy
* 🎨 Improved UI/UX
* 📊 Graph-based insights

---

## 🙌 Acknowledgements

* IPL dataset sources
* Scikit-learn documentation
* Streamlit community

---

## 📧 Contact

If you liked this project or have suggestions:

* GitHub: https://github.com/rohit01233

---

⭐ If you found this useful, give it a star!
