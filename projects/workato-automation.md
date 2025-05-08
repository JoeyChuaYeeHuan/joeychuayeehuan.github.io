---
layout: page
title: "Workato Automation: Telco Fault Alerts"
permalink: /projects/workato-automation/
---

<h1>📡 Telco Fault Alert Automation with Workato</h1>

<p>
This project was developed as part of the <strong>ANL555 Data Integration for Enterprise Automation</strong> course. 
It demonstrates a complete automation of telco fault detection and proactive customer notifications using 
<strong>Workato, Google Sheets, JSON processing, and Telegram messaging</strong>. The group scored <strong>90/100</strong> for this assignment.
</p>

<hr>

<h2>🎯 Objective</h2>
<p>
To improve customer satisfaction by automating fault detection and alert notifications using an iPaaS (Workato).
The solution consolidates siloed CRM data, interprets network faults, and sends real-time alerts to impacted customers.
</p>

<h2>🔧 Tools Used</h2>
<ul>
  <li>Workato (iPaaS) – Recipe-based low-code automation</li>
  <li>Google Sheets – Simulated data lake and CRM source</li>
  <li>JSON file – Simulated Juniper network service data</li>
  <li>Telegram – Simulated SMS notification for broadband issues</li>
  <li>Email – Notification channel for mobile network issues</li>
  <li>Mistral (GenAI) – Automated message generation</li>
</ul>

<hr>

<h2>🧪 Solution Architecture Overview</h2>
<p>
The solution integrates five modular Workato recipes to process incoming network fault data, cross-reference impacted customers,
and notify them in real-time through appropriate channels. CRM data from Salesforce and Amdocs is combined into a unified customer view.
</p>

<h3>📁 Workato Recipe Breakdown</h3>
<ul>
  <li><strong>Recipe 1:</strong> Parses a JSON file with network status data and stores it in Sheet 4 (Service Status)</li>
  <li><strong>Recipe 2:</strong> Identifies impacted customers based on failed locations and logs them in Sheet 6</li>
  <li><strong>Recipe 3:</strong> Sends email (for mobile faults) or Telegram (for broadband faults) alerts using Mistral-generated content</li>
  <li><strong>Recipe 4 & 5:</strong> Combine Salesforce and Amdocs CRM records into a consolidated customer data lake (Sheet 5)</li>
</ul>

<img src="{{ site.baseurl }}/assets/images/Workato%20Workflow.png" alt="Recipe Flow" style="width:100%; max-width:900px; margin-bottom:20px; border-radius: 8px;">

<hr>

<h2>📸 Workato Alert Showcase</h2>
<p>A visual walkthrough of our fault alert generation, powered by AI-driven message prompts and automated delivery.</p>

<h3>1. Mistral AI Prompt – Broadband Fault Alert (Telegram)</h3>
<img src="{{ site.baseurl }}/assets/images/Content1.png" alt="Broadband alert prompt" style="width:100%; max-width:800px; margin-bottom:20px; border-radius: 8px; border: 1px solid #ccc;">

<h3>2. Mistral AI Prompt – Mobile Fault Alert (Email)</h3>
<img src="{{ site.baseurl }}/assets/images/Content2.png" alt="Mobile alert prompt" style="width:100%; max-width:800px; margin-bottom:20px; border-radius: 8px; border: 1px solid #ccc;">

<h3>3. Workato-Generated Email Preview</h3>
<img src="{{ site.baseurl }}/assets/images/Email%20Alert.png" alt="Email preview" style="width:100%; max-width:800px; margin-bottom:20px; border-radius: 8px; border: 1px solid #ccc;">

<h3>4. Received Email – Mobile Disruption</h3>
<img src="{{ site.baseurl }}/assets/images/Email%20Received.png" alt="Received email" style="width:100%; max-width:800px; margin-bottom:20px; border-radius: 8px; border: 1px solid #ccc;">

<h3>5. Telegram Alert – Broadband Disruption</h3>
<img src="{{ site.baseurl }}/assets/images/Telegram%20Alert.png" alt="Telegram alert" style="width:100%; max-width:800px; margin-bottom:20px; border-radius: 8px; border: 1px solid #ccc;">

<hr>

<h2>📊 Key Features</h2>
<ul>
  <li>🔁 <strong>Real-time parsing</strong> of service fault JSON from Google Drive</li>
  <li>🔍 <strong>Customer-impact matching</strong> using location cross-reference</li>
  <li>📬 <strong>Targeted communication</strong> using Telegram and Email</li>
  <li>⚡ <strong>Auto-generated messages</strong> powered by Mistral GenAI</li>
  <li>🔒 <strong>OAuth 2.0</strong> authentication and privacy safeguards implemented</li>
</ul>

<h2>📈 Measured Outcomes</h2>
<ul>
  <li>💡 Automated alerts reduced notification time to <strong>under 3 minutes</strong></li>
  <li>📉 Expected reduction in customer complaint volume</li>
  <li>📊 Improved data accuracy and traceability via timestamped logs</li>
  <li>🧠 Frees internal teams from manual Excel matching and scripting</li>
</ul>

<p><em>*Live links to recipes and demo data available upon request. All triggers and jobs ran successfully during testing.*</em></p>

<p>
  <a href="{{ site.baseurl }}/projects/" style="display:inline-block; margin-top:30px; background-color:#007bff; color:white; padding:10px 20px; border-radius:6px; text-decoration:none;">⬅ Back to Projects</a>
</p>
