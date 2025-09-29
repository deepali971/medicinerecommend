# Medicine Recommendation System

A simple **content-based recommendation system** that suggests medicines based on user input and a dataset of ailments.  
The project is implemented in **Python** with support for both Jupyter Notebook exploration and a Flask web app interface.

---

## 📂 Project Structure

- `app.py` – Flask application for running the web app.
- `medicine-recommend.ipynb` – Jupyter notebook with data preprocessing, feature extraction, and recommendation logic.
- `medicine.csv` – Dataset containing medicines and related ailments/features.
- `medicine_dict.pkl` – Preprocessed dictionary (pickle file) used for faster lookups.
- `.gitignore` – Git ignore file.

---

## 🚀 Features

- Content-based filtering for recommending medicines.
- Preprocessed dataset (`medicine.csv`) used for accurate recommendations.
- Flask-based web app for user-friendly interaction.
- Notebook version available for experimentation and learning.

---

## 🛠️ Tech Stack

- **Python**  
- **Pandas**, **Scikit-learn**  
- **Flask** (for web app)  
- **Pickle** (for model/data storage)  
- **Jupyter Notebook** (for analysis & development)

---

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/deepali971/medicinerecommend.git
   cd medicinerecommend
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:

   ```bash
   python app.py
   ```

4. Open your browser and go to:

   ```
   http://127.0.0.1:5000/
   ```

---

## 📊 Example Workflow

* Input: User provides ailment/symptom name.
* Processing: The system matches input against dataset using similarity measures.
* Output: Recommended list of medicines.

---

## 📌 Future Improvements

* Add symptom-to-medicine mapping with NLP.
* Enhance dataset with dosage, side effects, and interactions.
* Deploy on cloud (Heroku / Render).
* Improve UI/UX of the web app.

---

## 👩‍💻 Author

Developed by [Deepali Malik](https://github.com/deepali971)

