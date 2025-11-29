# CAVI_Web_App 
# Hemodialysis Prognostic Estimator (twCAVI)
Haemodialysis Prognostic Estimator Risk assessment using Time-Weighted Cardio-Ankle Vascular Index

This repository contains a static single-page web application that implements a Cox proportional hazards–based risk estimator for hemodialysis patients using the time-weighted Cardio-Ankle Vascular Index (twCAVI).

> **Important:** This tool is intended **only** for research, experimental, and educational use.  
> It is **not** a medical device and must not be used for clinical decision-making.

---

## Features

- Single-page React application loaded via CDN (no build step required)
- Cox proportional hazards model for risk estimation
- Interactive form for patient parameters
- twCAVI calculation from CAVI value and time (months from hemodialysis initiation to CAVI measurement)
- Adjustable time horizon (months) with slider
- All computation is performed client-side in the browser

---

## Usage

### Run from GitHub Pages or any static hosting

1. Deploy this repository as a static site (e.g. GitHub Pages).
2. Open `index.html` in your browser.
3. Enter patient parameters, CAVI value and time, adjust the time horizon, then click **“Calculate Risk”**.

### Run locally

You can also open `index.html` directly in your browser, or serve the folder with any simple HTTP static server (optional but recommended).

---

## Privacy & Cookies

This static application does not set its own cookies or store personal data.  
GitHub Pages and external content providers (such as **unpkg** and **cdn.tailwindcss.com**) may use technical cookies under their own privacy policies.

No patient identifiers should be entered into this tool. Only de-identified or synthetic data should be used.

---

## Medical Disclaimer

This software is designed for research, experimental, and educational purposes.  
It has **not** been validated for clinical use and is **not** intended to be a substitute for professional medical advice, diagnosis, or treatment.

The risk estimates provided are based on statistical models and should **not** be used for clinical decision-making.  
The authors and developers assume no liability for any direct or indirect consequences arising from the use of this application.

---

## License

This project is released under the **MIT License**.  
See the [`LICENSE`](LICENSE) file for details.
