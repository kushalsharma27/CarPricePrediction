# Car Price Predictor (Mini Project)

This project is a **web-based car price prediction application** built using **Python, Flask, Pandas**, and **a pre-trained Linear Regression model**. It allows users to estimate the resale value of a car based on key attributes like the company, model, year, fuel type, and kilometers driven.

---

## Tools and Technologies Used

* **Python 3.11**
* **Flask** - Web framework
* **HTML/CSS (Jinja Templates)** - Frontend
* **Pandas / NumPy** - Data manipulation
* **Scikit-learn** - Machine Learning (Linear Regression)
* **Pickle** - Model serialization
* **CSV/XLS** - Data source (Cleaned car data)
* **Postman / Browser** - For testing API & UI

---

## Project Structure

```
.
├── application.py                # Flask app to serve the model
├── Cleaned_Car_data.csv          # Dataset used for prediction
├── LinearRegressionModel.pkl     # Trained model file
├── MINI PROJECT.ipynb            # Jupyter notebook used for model training
├── templates/
│   └── index.html                # Web page template for user input
├── misc.xml, modules.xml, etc.  # IDE config files (optional)
```

---

## How to Run the Project

1. **Clone the repository** or copy the files to your local system.

2. **Install dependencies**:

   ```bash
   pip install flask pandas numpy scikit-learn
   ```

3. **Run the application**:

   ```bash
   python application.py
   ```

4. **Open your browser** and navigate to:

   ```
   http://127.0.0.1:5000/
   ```

---

##  How It Works

1. The user selects:

   * Company
   * Car model
   * Year of purchase
   * Fuel type
   * Kilometers driven

2. The data is passed to the server, where a trained **Linear Regression** model predicts the car's price.

3. The prediction is returned and displayed on the web page.

---

##  Model Details

* **Model**: Linear Regression
* **Training Notebook**: See `MINI PROJECT.ipynb`
* **Target Variable**: Selling price
* **Features Used**: `name`, `company`, `year`, `kms_driven`, `fuel_type`

---

##  Future Improvements

* Use more advanced models (e.g., XGBoost, Random Forest).
* Add user authentication.
* Improve UI with better styling (CSS/Bootstrap).
* Deploy on Heroku or Render.

---
