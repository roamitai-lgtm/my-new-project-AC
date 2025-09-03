# SmartClimate: AI-Powered Personalized AC Optimization
**Building AI course project**

## Summary
SmartClimate is an AI system that dynamically adjusts air conditioning settings based on user preferences, monthly budget limits, electricity efficiency, program schedules, and real-time weather forecasts. By learning from behavior and optimizing consumption, it helps reduce costs while maintaining comfort.
**Building AI course project**

## Background
Managing indoor temperature efficiently is a growing challenge in both residential and commercial settings. Many users suffer from high electricity bills, discomfort due to poor scheduling, or both. This problem becomes more common as global temperatures rise and energy costs fluctuate. My personal frustration with rigid AC systems and ballooning utility bills led me to create a smarter solution.

The idea behind SmartClimate is to enhance traditional thermostat systems with AI intelligence that adapts to each user's lifestyle, financial constraints, and environmental conditions. This project matters because energy efficiency isn't just a personal win—it's a societal necessity.

## Data and AI Techniques
SmartClimate integrates multiple data sources:
- **User Preferences**: Comfort ranges, preferred temperature at different times of day.
- **Monthly Budget Input**: A self-defined cap on electricity spending.
- **Real-time Weather Forecasts**: Sourced via APIs such as OpenWeather.
- **Electricity Tariffs**: To identify cost-effective cooling periods.
- **Smart Meter Data**: For real-time consumption tracking.
- **Daily Schedules**: User activity patterns and occupancy schedules.

### AI Techniques:
- **Supervised Learning** for consumption prediction.
- **Reinforcement Learning** to adjust settings dynamically and optimize for comfort/cost trade-offs.
- **Constraint Optimization** to respect budget and comfort bounds.
- **Clustering** to learn similar user profiles and propose better settings.

## How It Is Used
SmartClimate is designed to integrate with existing smart home ecosystems. Users interact via a mobile or web dashboard where they:
- Set monthly electricity budget.
- Input comfort preferences and work schedule.
- View forecasts, usage predictions, and receive suggestions.

End users include:
- Households looking to save on utility bills.
- Smart building managers seeking automated efficiency.
- Environmentally conscious users reducing energy footprint.

## Challenges
- Requires reliable weather and tariff APIs.
- Needs integration with smart meters and thermostats.
- Might not fully optimize for extreme or unpredictable weather.
- Privacy concerns when handling personal preferences and schedules.

## What Next
- Expand support to heating and multi-zone buildings.
- Incorporate solar power availability predictions.
- Add ML-based anomaly detection for HVAC faults.
- Build an open API for smart-home developers to plug into the engine.

## Acknowledgments
This project is inspired by the "Building AI" course by the University of Helsinki and utilizes open weather APIs and concept references from smart energy communities.

Special thanks to the open-source community for contributions to energy and IoT data modeling tools.
