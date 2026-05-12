# WEATHER BASED SELLS & STAFFING AUTOMATION SYSTEM

An AI-powered automation workflow that analyzes weather conditions and generates staffing recommendations to help businesses prepare for demand fluctuations automatically.

This project demonstrates how AI automation can transform external real-time data into operational business insights that improve scheduling efficiency and decision-making.

---

## Overview

Businesses that rely on customer traffic are heavily affected by changing weather conditions. Sudden temperature changes, rain, or extreme weather can significantly impact staffing demand, product demand, and promotional planning, making manual operational decisions inefficient and reactive.

This automation system helps businesses make faster operational decisions by monitoring weather data, analyzing conditions with ChatGPT, and generating automated staffing, product, and promotional recommendations based on forecasted weather patterns.

The workflow reduces manual planning while improving operational readiness, response speed, and day-to-day retail decision-making.

---

## Business Problem

Retail and hospitality businesses often struggle to quickly adapt daily operations to changing weather conditions.

This creates several operational challenges:

- Overstaffing during slow weather conditions
- Understaffing during high-traffic weather shifts
- Poor product demand forecasting
- Delayed promotional adjustments
- Manual monitoring of weather forecasts
- Inconsistent operational planning

A scalable automated solution was needed to monitor weather conditions and generate operational recommendations automatically.

---

## Solution

Built an automated workflow that:

- Pulls live weather forecast data using the OpenWeather API
- Processes incoming weather conditions through Zapier automation
- Uses ChatGPT to generate operational recommendations
- Creates staffing suggestions based on forecast conditions
- Generates promotional messaging recommendations
- Sends automated daily operational summary emails
- Triggers severe weather alert notifications when conditions meet predefined thresholds
- Reduces manual forecasting and operational planning effort

---

## Workflow Breakdown

1. Zapier Schedule triggers the workflow automatically every morning at 7:00 AM

2. OpenWeather API retrieves daily weather conditions for Miami, FL

3. Weather data is sent to ChatGPT for operational analysis

4. ChatGPT generates:
   - Product recommendations
   - Staffing suggestions
   - Promotional messaging ideas

5. Zapier Paths evaluates severe weather conditions

6. Gmail automatically sends:
   - Daily operational summary emails
   - Severe weather alert notifications when triggered

---

## Value Added

- Automates weather-based operational planning
- Improves staffing and inventory decision-making
- Helps businesses respond proactively to weather-driven demand changes
- Reduces manual forecasting and planning effort
- Converts live weather data into actionable business insights
- Demonstrates practical AI-powered workflow automation

---

## Tech Stack

- Zapier
- OpenWeather API
- ChatGPT API
- Gmail
- JSON Parsing
- Prompt Engineering
- Workflow Automation
- No-Code Automation

---

## Workflow Screenshots

### Workflow Architecture Diagram

![Workflow Architecture Diagram](images/01-workflow-architecture-diagram.png)

---

### Zapier Workflow Overview

![Zapier Workflow Overview](images/02-zapier-workflow-overview.png)

---

### Schedule Trigger Configuration

![Schedule Trigger](images/03-schedule-trigger.png)

---

### OpenWeather API Request Step

![OpenWeather API Step](images/04-openweather-api-step.png)

---

### ChatGPT Analysis Step

![ChatGPT Analysis Step](images/05-chatgpt-analysis-step.png)

---

### Gmail Daily Summary Email Step

![Gmail Email Step](images/06-gmail-email-step.png)

---

### Severe Weather Conditional Logic

![Severe Weather Logic](images/07-severe-weather-logic.png)

---

### Daily Operational Summary Email

![Daily Summary Email](images/08-daily-summary-email.png)

---

### Severe Weather Alert Email

![Severe Weather Alert Email](images/09-severe-weather-alert-email.png)

---

## Future Improvements

Potential future enhancements include:

- SMS or Slack notification integrations
- Multi-location operational forecasting
- Inventory forecasting automation
- POS system integration
- Historical trend analysis dashboards
- Predictive staffing analytics

---

## Project Status

Completed as a functional AI-powered automation workflow for weather-based operational planning, staffing recommendations, and automated business alerts.
