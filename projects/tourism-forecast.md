---
layout: page
title: Tourism Forecasting with R
permalink: /projects/tourism-forecast/
---

<h1>✈️ Forecasting International Tourism in Europe & Central Asia </h1>

<p>This project was conducted as part of the ANL557 module. This assignment analyzed and forecasted international tourism arrivals in the Europe and Central Asia region, with a focus on understanding the disruptions caused by the COVID-19 pandemic and estimating the recovery trajectory through 2024.</p>

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

<h3>1. Moving Average Forecast</h3>
<img src="{{ site.baseurl }}/assets/images/Rplot%209.png" alt="Moving Average Forecast" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<h3>2. ETS (SES, DES and Winters') Forecast</h3>
<img src="{{ site.baseurl }}/assets/images/Rplot%2010.png" alt="SES Forecast" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">
<img src="{{ site.baseurl }}/assets/images/Rplot%2012.png" alt="DES Forecast" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<h3>3. Auto-ARIMA Forecast</h3>
<img src="{{ site.baseurl }}/assets/images/Rplot%2014.png" alt="ARIMA Residuals" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<h3>4. Model Accuracy Comparison</h3>
<img src="{{ site.baseurl }}/assets/images/Rplot%2022.png" alt="Time Series Plot of SES Residuals" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">
<img src="{{ site.baseurl }}/assets/images/Rplot%2030.png" alt="Time Series Plot of DES Residuals" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">
<img src="{{ site.baseurl }}/assets/images/Rplot%2038.png" alt="Time Series Plot of Auto ARIMA Residuals" style="width:100%; max-width:800px; margin-bottom:20px; border: 1px solid #ccc; border-radius: 8px;">

<hr>

<h2>📈 Key Findings</h2>
<ul>
  <li><strong>ARIMA</strong> delivered the most accurate forecasts.</li>
  <li>Forecasts for 2023 and 2024 show a <strong>gradual recovery</strong> in tourism numbers.</li>
  <li>Residual diagnostics confirmed <strong>statistical reliability</strong> of the models.</li>
</ul>

<h2>📌 Summary of Results</h2>
<ul>
  <li><strong>ARIMA (1,2,1)</strong> was the best-performing model, achieving the lowest MAPE (1.44%) and AIC (1462.36), making it the most accurate and efficient choice for short-term forecasting.</li>
  <li><strong>DES (Double Exponential Smoothing)</strong> handled both level and trend effectively, with a MAPE of 1.58% and AIC of 1578.13. It forecasted 1.22B and 1.24B arrivals for 2023 and 2024 respectively.</li>
  <li><strong>SES (Simple Exponential Smoothing)</strong> performed well in terms of short-term level tracking (MAPE = 1.96%) but failed to account for long-term upward trends, producing flat forecasts.</li>
  <li>All three models were evaluated using residual diagnostics (ACF/PACF, QQ plots, Ljung-Box, Shapiro-Wilk), confirming that ARIMA had the most well-behaved residuals with minimal autocorrelation.</li>
  <li>2023 forecast accuracy was strong across all models when compared with actual data:
    <ul>
      <li><strong>SES:</strong> 0% APE (predicted 2023 exactly due to flat trend assumption)</li>
      <li><strong>DES:</strong> 1.66% APE</li>
      <li><strong>ARIMA:</strong> 1.00% APE</li>
    </ul>
  </li>
</ul>

<h2>✅ Conclusion</h2>
<p>
  The project illustrates the strength of time series forecasting in real-world applications, particularly in helping stakeholders anticipate recovery trends in tourism. Auto ARIMA outperformed other models in forecasting accuracy, capturing both level and trend components while adapting to residual structures. DES was a close second and preferable when interpretability is prioritized. SES, while easy to implement, lacked the complexity needed for a strongly trending series.
</p>

<p>
  <a href="{{ site.baseurl }}/projects/" style="display:inline-block; margin-top:30px; background-color:#007bff; color:white; padding:10px 20px; border-radius:6px; text-decoration:none;">⬅ Back to Projects</a>
</p>

