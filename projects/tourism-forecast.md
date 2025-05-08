---
layout: page
title: Tourism Forecasting with R
permalink: /projects/tourism-forecast/
---

<h1>✈️ Forecasting International Tourism in Europe & Central Asia </h1>

<p>This project analyzed and forecasted international tourism arrivals in the Europe and Central Asia region, with a focus on understanding the disruptions caused by the COVID-19 pandemic and estimating the recovery trajectory through 2024.</p>

<hr>

<h2>🎯 Objective</h2>
<p>
  To evaluate tourism trends and generate short-term forecasts using time series modeling, supporting post-pandemic planning and policy development.
</p>

<h2>🧪 Methodology</h2>
<p>
  A range of statistical models were applied:
</p>
<ul>
  <li><strong>Moving Average (MA)</strong> – for trend smoothing</li>
  <li><strong>Simple, Double, and Holt-Winters' Exponential Smoothing (SES, DES, Winters')</strong> – to capture level, trend, and seasonality</li>
  <li><strong>ARIMA</strong> – for autoregressive behavior and differenced trends</li>
  <li><strong>Linear Regression</strong> – as a comparative baseline</li>
</ul>

<p>Model diagnostics included stationarity tests (ADF), residual plots, and accuracy metrics such as MAPE, MAD, MSD, and AIC.</p>

<hr>

<h2>📊 Key Visualizations</h2>

<h3>1. ETS (Holt-Winters) Forecast</h3>
<img src="{{ site.baseurl }}/assets/images/ets_forecast.png" alt="ETS Forecast" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<h3>2. Auto-ARIMA Residual Diagnostics</h3>
<img src="{{ site.baseurl }}/assets/images/arima_residuals.png" alt="ARIMA Residuals" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<h3>3. Model Accuracy Comparison</h3>
<img src="{{ site.baseurl }}/assets/images/model_accuracy.png" alt="Model Accuracy Comparison" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<hr>

<h2>📈 Key Findings</h2>
<ul>
  <li><strong>ARIMA</strong> delivered the most accurate forecasts.</li>
  <li>Forecasts for 2023 and 2024 show a <strong>gradual recovery</strong> in tourism numbers.</li>
  <li>Residual diagnostics confirmed <strong>statistical reliability</strong> of the models.</li>
</ul>

<h2>✅ Conclusion</h2>
<p>
  The project illustrates the strength of time series forecasting in real-world applications, particularly in helping stakeholders anticipate recovery trends in tourism. It supports evidence-based planning in the post-COVID context for Europe and Central Asia.
</p>

<p>
  <a href="{{ site.baseurl }}/projects/" style="display:inline-block; margin-top:30px; background-color:#007bff; color:white; padding:10px 20px; border-radius:6px; text-decoration:none;">⬅ Back to Projects</a>
</p>
