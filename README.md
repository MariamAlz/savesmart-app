# SaveSmart App

> **Project:** Senior Design Project (team) · BSc Computer Engineering, Khalifa University · 2nd place in energy efficiency, Solar Decathlon Middle East

Delivery of the final system for the SaveSmart mobile application in Kivy.

This is the team's final repository, kept here as a record of the project. My Xamarin app prototype for SaveSmart is in [MariamAlz/savesmart-prototype](https://github.com/MariamAlz/savesmart-prototype).

## Project structure

```
app/          Kivy (KivyMD) mobile app: main.py, app.kv, fonts, images and icons
model/        LSTM forecasting: AI.py (model), pipeline.py (train and forecast), conf.yml, trained model (lstm_model.h5), output predictions
model/data/   DAYTON_hourly.csv power-use dataset and a sample predictions file
scripts/      HS110.py, reads live power from a TP-Link HS110 smart plug
experiments/  Early Kivy screen tests and a knapsack approach to grouping devices
```

## Configuration

The app reads its logins and paths from a `.env` file. Copy `.env.example` to `.env` and fill in your values; `.env` is ignored by git.
