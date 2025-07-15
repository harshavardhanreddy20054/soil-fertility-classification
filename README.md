# soil-fertility-classification

This project presents a machine learning-based solution for soil analysis and micronutrient classification, designed for IoT-enabled automated farms. It analyzes soil sample data to predict the presence of essential micronutrients using various machine learning models. The project is built as a Django-based web application to provide a user-friendly interface for real-time soil monitoring and prediction.

---

## 📌 Features

- Soil dataset analysis using ML algorithms.
- Classification of essential micronutrients like Iron (Fe), Zinc (Zn), and Copper (Cu).
- Comparison of multiple machine learning models.
- Web interface using Django framework.
- Designed for integration with IoT-enabled farm systems.
- Visualization of model performance and results.

---

## 🛠️ Technologies Used

- Python 3.x
- Django Framework
- Pandas, NumPy
- Scikit-Learn
- Matplotlib
- HTML, CSS (for frontend)

---

## 📊 Machine Learning Algorithms Used

- Random Forest Classifier
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression

---

## 📂 Project Structure


SoilFertility/
├── manage.py
├── requirements.txt
├── README.md
├── Dataset/
│   ├── soil\_fertitlity\_dataset.csv
│   └── testData.csv
├── Soil/
│   └── Django project configuration files
├── SoilApp/
│   ├── Machine learning implementation
│   ├── Views and templates (HTML)
│   ├── Static files (CSS, images)
├── models/ (optional - saved models)
└── images/ (optional - graphs and results)

````



## ⚙️ Installation Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/soil-fertility-classification.git
   cd soil-fertility-classification
````

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Django Application:**

   ```bash
   python manage.py runserver
   ```

4. **Access Web Application:**
   Open your browser and go to `http://127.0.0.1:8000/`

---

## 📈 Dataset

* Soil sample datasets with attributes like:

  * pH
  * Electrical Conductivity (EC)
  * Organic Carbon (OC)
  * Micronutrient contents (Fe, Zn, Cu, etc.)

Stored inside the `/Dataset` folder in CSV format.

---

## 🎯 Output

* Predicted soil fertility status.
* Classification of micronutrient presence.
* Model accuracy reports and confusion matrices.
* Visualization graphs for model performance.

---

## 🤖 IoT Integration

Although IoT devices are not implemented directly, the trained machine learning models are designed to integrate with IoT-based sensors and automated systems for real-time soil data analysis.

---

## 📄 License

This project is open-source and licensed under the MIT License.

---

## 📬 Contribution & Feedback

Feel free to open issues or submit pull requests for improvements.

```
