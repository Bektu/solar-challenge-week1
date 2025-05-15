# solar-challenge-week1
KAIM Week 0 Challenge 
# 🌞 Solar Challenge Week 1

## 📌 Challenge Overview

This week’s challenge is focused on understanding, exploring, and analyzing solar farm data found in **Benin**, **Sierra Leone**, and **Togo**.
- Data Engineering (DE)
- Financial Analytics (FA)
- Machine Learning Engineering (MLE)

## 💼 Business Objective

As an **Analytics Engineer at MoonLight Energy Solutions**, the task is to:
- Analyze environmental sensor data
- Translate findings into a strategic recommendation
- Focus on identifying **high-potential regions** for solar installation
- Align insights with MoonLight's long-term sustainability goals

## 🧾 Dataset Overview

The dataset consists of measurements related to solar radiation and environmental factors:

- **Timestamps**
- **Irradiance** (GHI, DNI, DHI)
- **Module Readings** (ModA, ModB)
- **Temperature** (Ambient, Module A & B)
- **Humidity**
- **Wind** (Speed, Gust, Direction)
- **Cleaning Events**
- **Precipitation**
- **Barometric Pressure**
- **Comments**

## ⚙️ Reproduce the Environment

### Using Conda:
```bash
conda create --name solar-env python=3.11
conda activate solar-env
pip install -r requirements.txt

## Folder Structure 

├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
├── scripts/
│   ├── __init__.py
│   └── README.md
├── app/
│   ├── __init__.py
│   ├── main.py
│   └── utils.py