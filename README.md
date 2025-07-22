# Heart-Failure-Prediction
❤️ Heart Failure Prediction App

This is a Machine Learning + Flask web application that predicts whether a patient is at high risk of heart failure based on clinical health records.

🏥 Made for educational & learning purposes.


⸻

🚀 Features

✅ Predicts heart failure risk (High / Low)
✅ User-friendly web form
✅ Trained using real clinical dataset
✅ Built using Python, Flask & Scikit-learn
✅ Beautiful custom CSS & responsive design

⸻

🧠 Dataset Used
	•	Dataset: Heart Failure Clinical Records Dataset
	•	Source: UCI Machine Learning Repository
	•	Features: 12 clinical measurements
	•	Target: DEATH_EVENT (0: survived, 1: died)

⸻

🔧 Tech Stack
	•	Python 3.7+
	•	Flask
	•	Scikit-learn
	•	Pandas
	•	HTML & CSS

⸻

📝 Input Fields

Feature	Type	Description
age	float	Age of the patient
anaemia	binary	Decrease of red blood cells
creatinine_phosphokinase	integer	Enzyme level in blood
diabetes	binary	If the patient has diabetes
ejection_fraction	integer	Percentage of blood leaving the heart
high_blood_pressure	binary	If the patient has hypertension
platelets	float	Platelet count
serum_creatinine	float	Creatinine level in blood
serum_sodium	float	Sodium level in blood
sex	binary	0 = Female, 1 = Male
smoking	binary	Smoking history
time	integer	Duration of follow-up in days


⸻

📂 Project Structure

heart_failure_app/
│
├── app.py                  # Flask app
├── model.pkl               # Trained ML model
├── train_model.py          # (Optional) model training script
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── templates/
    └── index.html          # Frontend UI


⸻

⚙️ How to Run Locally
	1.	Clone this repository:

git clone https://github.com/yourusername/heart-failure-prediction.git
cd heart-failure-prediction


	2.	(Optional) Create & activate virtual environment:

python -m venv .venv
.venv\Scripts\Activate.ps1   # PowerShell


	3.	Install dependencies:

pip install -r requirements.txt


	4.	Run the app:

python app.py


	5.	Open your browser at:

http://127.0.0.1:5000




⸻

✅ Output
	•	⚠️ High risk of heart failure
	•	✅ Low risk of heart failure

Messages are shown in a friendly and easy-to-understand format.

⸻

🙋‍♂️ Author

Made with ❤️ by AYUSH SHRIVASTAV
Feel free to fork, improve, and contribute!

⸻

📄 License

This project is licensed under the MIT License.
Feel free to use for academic, personal, or demo purposes.
