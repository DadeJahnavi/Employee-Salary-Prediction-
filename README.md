# 💼 Employee Salary Estimation App

The **Employee Salary Estimation App** is an interactive **Streamlit web application** that predicts an employee’s **monthly salary** based on workplace metrics.  
It provides instant insights with clean data visualization, making it useful for HR teams, data enthusiasts, or anyone curious about salary modeling.

Built with **Python, Streamlit, Plotly, and scikit-learn**, this app transforms machine learning predictions into a **friendly, visual experience**.

## 🔥 Features

- 📊 **Salary Prediction** using a trained ML model  
- 📈 **Dynamic Input Visualization** with colorful bar charts  
- 🎉 **Interactive UI** with balloons and status messages  
- 💾 **Scikit-learn Pipeline** with scaling & regression  
- 🌐 **Streamlit Cloud Deployment** for easy access  

## 🧠 How It Works

1. **Input your details**:
   - Years at the company  
   - Satisfaction level (0 to 1)  
   - Average monthly working hours  

2. **Click “Predict Salary”**:
   - Your inputs are scaled using the pre-trained **scaler**  
   - The ML **model predicts** the estimated salary  

3. **Visual Feedback**:
   - Salary prediction is displayed with formatted INR value  
   - Plotly bar chart visualizes your input profile  

## 📁 Project Structure

| File               | Purpose                                             |
|--------------------|-----------------------------------------------------|
| `app.py`           | Main Streamlit app                                  |
| `scaler.pkl`       | Pre-fitted Scikit-learn scaler                      |
| `model.pkl`        | Trained salary prediction model                     |
| `requirements.txt` | Required Python libraries for deployment            |
| `README.md`        | This guide                                          |

---

## 🚀 Run Locally

1. **Clone this repo**  
   ```bash
   git clone https://github.com/DadeJahnavi/Employee-Salary-Prediction-.git
   cd employee-salary-prediction


   ## 🌐 Live Demo

🔗 **Try the App Here:** [Employee Salary Estimation App](https://employee-salary-prediction-dadejahnavi.streamlit.app/)

---

> 💡 *"Data tells the story, and prediction helps you plan."*

🛡 Built with **Python, Streamlit, Plotly, and Scikit-learn**  

