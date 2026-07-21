# 🧮 Prevailing Interest Calculator

A simple and intuitive Streamlit web app to calculate the estimated interest earned from a **High Yield Savings Plus Account** based on user-inputted deposit amount and duration.

## 📌 Project Overview

This calculator helps users estimate their interest earnings over a specified time period using tiered interest rates:

- **First $50,000** → 1.5% p.a.
- **Next $25,000** → 1.6% p.a.
- **Next $25,000** → 1.8% p.a.
- **Amount over $100,000** → 2.0% p.a.

The app computes the interest based on the number of days between a user-specified start and end date.

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HJJ1981/interest_calculator_app.git
   cd interest_calculator_app
   ```

2. **Create a new conda environment**:
   ```bash
   conda env create -f environment.yml
   conda activate streamlit
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

---

## 🧪 Example

Enter:
- A deposit amount (e.g., `$120,000`)
- A start and end date (e.g., `2026-01-01` to `2026-12-31`)

You will receive:
- Number of days (e.g., `365`)
- Estimated interest earned (e.g., `$2,010.68`)

---

## 📂 Project Structure

```
interest-calculator-app/
├── app.py               # Main dashboard script
├── environment.yml      # Conda environment file     
├── requirements.txt     # Python dependencies
```

---

## 🛠️ Tech Stack

- Python
- [Streamlit](https://streamlit.io/)
- datetime module

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Hu Jian Jin

GitHub:
https://github.com/HJJ1981

LinkedIn:
https://www.linkedin.com/in/jian-jin-hu-69951243/

---

If you found this project useful, consider giving it a ⭐ on GitHub.