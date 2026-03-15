# GigShield – AI Powered Insurance for Delivery Workers

## Problem Statement

Delivery partners working for platforms like Swiggy and Zomato often lose income due to external disruptions such as heavy rain, extreme heat, pollution, or curfews.

Currently there is no insurance protection for their income loss.

## Proposed Solution

GigShield is an AI-powered parametric insurance platform that automatically compensates delivery workers when external disruptions prevent them from working.

## Target Persona

Food Delivery Partners (Swiggy / Zomato)

## Application Workflow

1. Worker registers on the platform  
2. AI calculates weekly premium based on location risk  
3. System monitors weather APIs  
4. If disruption occurs, claim is automatically triggered  
5. Worker receives instant payout  

## Parametric Triggers

- Rainfall > 40mm  
- Temperature > 45°C  
- Pollution AQI > 300  
- City curfew announcements  

## Weekly Premium Model

| Risk Level | Weekly Premium |
|-------------|---------------|
| Low Risk | ₹20 |
| Medium Risk | ₹35 |
| High Risk | ₹50 |

## Tech Stack

Frontend: React  
Backend: Spring Boot  
Database: MySQL  
AI: Python (Scikit-learn)  
APIs: OpenWeather API

## Project Structure

gigshield-ai-insurance  
│  
├── frontend  
├── backend  
├── ai-service  
├── docs  
└── README.md  

## System Architecture

![Architecture](architecture.drawio.png)
## Future Enhancements

- AI fraud detection
- GPS validation for workers
- Dynamic premium pricing
- Real-time weather disruption alerts
