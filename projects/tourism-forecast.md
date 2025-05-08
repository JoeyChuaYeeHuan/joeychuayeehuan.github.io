---
layout: page
title: Tourism Forecasting with R
permalink: /projects/tourism-forecast/
---

<h1>✈️ Forecasting International Tourism in Europe & Central Asia (ECA)</h1>

<p>This project analyzed and forecasted international tourism arrivals in the ECA region, with a focus on understanding the disruptions caused by the COVID-19 pandemic and estimating the recovery trajectory through 2024.</p>

<hr>

<h2>🎯 Objective</h2>
<p>
  To evaluate tourism trends and generate short-term forecasts using time series modeling, supporting post-pandemic planning and policy development.
</p>

<h2>🧪 Methodology</h2>
<p>
  A range of statistical models were applied:
  <ul>
    <li><strong>Moving Average (MA)</strong> – for trend smoothing</li>
    <li><strong>Simple, Holt, and Holt-Winters Exponential Smoothing (SES, DES, TES)</strong> – to capture level, trend, and seasonality</li>
    <li><strong>ARIMA</strong> – for autoregressive behavior and differenced trends</li>
    <li><strong>Linear Regression</strong> – as a comparative baseline</li>
  </ul>
</p>

<p>Model diagnostics included:</p>
<ul>
  <li><strong>Stationarity tests</strong> (ADF)</li>
  <li><strong>Residual analysis</strong> (Ljung-Box test, residual plots)</li>
  <li><strong>Forecast accuracy metrics:</strong> MAPE, MAD, MSD, AIC</li>
</ul>

<h2>📈 Key Findings</h2>
<ul>
  <li><strong>ARIMA</strong> and <strong>Holt-Winters (TES)</strong> delivered the most accurate and robust forecasts.</li>
  <li>The ETS model effectively captured <strong>seasonal patterns</strong> in tourism arrivals.</li>
  <li>Forecasts for 2023 and 2024 indicated a <strong>slow but steady recovery</strong>, though still below pre-pandemic levels.</li>
  <li>Residual diagnostics confirmed <strong>model reliability and well-behaved errors</strong>.</li>
</ul>

<h2>✅ Conclusion</h2>
<p>
  Time series forecasting provided valuable insights for understanding and predicting tourism flows in the post-COVID era. The analysis supports
  <strong>evidence-based decision-making</strong> for governments and tourism stakeholders in Europe and Central Asia.
</p>
