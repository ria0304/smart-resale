# Smart Resale — Real-Time Resale Price Predictor

> Know the fair price of your phone or laptop before you buy or sell.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-orange)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## The problem
Resale pricing on OLX, Cashify, and Amazon Renewed is inconsistent 
and confusing — especially for students and Gen Z buyers on a budget. 
There's no reliable way to know the fair market value of a used device.

## The solution
Smart Resale scrapes real-time listings, processes the data, and uses 
ML to predict a fair resale price — instantly, from just the device specs.

## Pipeline
| Step | What happens |
|------|-------------|
| Scraping | Pulls live listings from OLX, Cashify, Amazon Renewed |
| Preprocessing | Cleans prices, extracts specs, handles missing values |
| EDA | Finds patterns — how brand, RAM, age affect price |
| Modelling | Trains Random Forest, XGBoost, Linear Regression |
| Interface | Streamlit app — enter specs, get predicted price |

## Current status
- [x] Synthesized dataset & baseline ML models
- [x] EDA & feature importance visualisation  
- [ ] Live web scraping (OLX, Cashify)
- [ ] Streamlit UI
- [ ] Deployment

## Quick start
```bash
git clone https://github.com/ria0304/smart-resale
pip install -r requirements.txt
jupyter notebook solution_jupyterlab.ipynb
```

## Tech stack
`Python` `BeautifulSoup` `Selenium` `Pandas` `NumPy`  
`Scikit-learn` `XGBoost` `Matplotlib` `Seaborn` `Streamlit`

## Future scope
- Expand to tablets, smartwatches, gaming consoles
- Image recognition for condition detection from photos
- Real-time demand trends for dynamic pricing

## License
MIT — by [ria0304](https://github.com/ria0304)
