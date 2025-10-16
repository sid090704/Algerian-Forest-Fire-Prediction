# 🔥 Algerian Forest Fire Prediction 🔥

A machine learning web application to predict the Fire Weather Index (FWI) based on meteorological data from two regions in Algeria.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://algerian-forest-fire-prediction-knjb.onrender.com)

---

## 📝 Overview

This project is a web-based tool that uses a machine learning model to predict the likelihood of forest fires. It provides a user-friendly interface to input weather conditions and receive a real-time prediction of the Fire Weather Index (FWI), a key indicator of fire risk.

The application is built with a Flask backend to serve a Ridge Regression model and a clean, responsive HTML/CSS front-end for user interaction.

---

## 📊 About the Dataset

The prediction model was trained on the **Algerian Forest Fires Dataset** from the UCI Machine Learning Repository.

-   **Location:** The data was collected from two regions in Algeria: the Bejaia region and the Sidi Bel-Abbes region.
-   **Time Period:** The dataset covers the fire season from June 2012 to September 2012.
-   **Features:** It includes daily meteorological observations such as:
    -   Temperature
    -   Relative Humidity (RH)
    -   Wind Speed (Ws)
    -   Rain
    -   And various components of the Canadian Forest Fire Weather Index (FWI) System (FFMC, DMC, ISI).
-   **Target:** The model is trained to predict the **Fire Weather Index (FWI)**, which is a numerical rating of fire intensity.

---

## ✨ Features

-   **Interactive Prediction Form:** Users can easily input values for temperature, humidity, wind speed, and other factors.
-   **Real-time Predictions:** The backend model processes the inputs and instantly returns the predicted FWI value.
-   **Responsive Design:** The user interface is designed to work seamlessly on both desktop and mobile devices.
-   **Two Algerian Regions:** The model accounts for data from both the Bejaia and Sidi-Bel Abbes regions.

---

## 🛠️ Technology Stack

-   **Backend:** Python, Flask
-   **Machine Learning:** Scikit-learn, Pandas, NumPy
-   **Frontend:** HTML, CSS
-   **Deployment:** Render, Gunicorn

---

## 🚀 How to Run Locally

To set up and run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-directory>
    ```

2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    python application.py
    ```

5.  Open your web browser and go to `http://127.0.0.1:8080`.

---

## ☁️ Deployment

This application is deployed on **Render** using a `Procfile` to run a Gunicorn web server. Continuous deployment is set up to automatically update the live application whenever new changes are pushed to the main branch on GitHub.

---

## 🙏 Acknowledgements

-   This project uses the [Algerian Forest Fires Dataset](https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset) from the UCI Machine Learning Repository.

## 🙏 Acknowledgements

-   This project uses the [Algerian Forest Fires Dataset](https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset) from the UCI Machine Learning Repository.
