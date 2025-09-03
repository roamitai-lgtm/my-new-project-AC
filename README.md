## AI-AC-Optimizer


---


### Data and AI techniques
**Data sources include:**
- Indoor sensors: temperature, humidity, occupancy
- User preferences: comfort ranges, budget caps
- Electricity pricing: real-time tariffs and peak times
- Weather forecast data: temperature and humidity outlooks
- AC systems: supported modes, energy draw profiles


**AI techniques:**
- Supervised learning for comfort modeling
- Reinforcement learning for adaptive control within constraints
- Time-series forecasting for weather and energy pricing
- Constraint programming for respecting budget limits
- Clustering for user-type identification and personalization


**Technologies:**
- Python, Scikit-learn, TensorFlow
- OpenWeatherMap API
- Octopus Energy API


---


### How is it used
**Users:**
- Residential users with smart thermostats
- Smart home platforms
- Energy-conscious consumers
- Property managers


**Interfaces:**
- Web dashboard or mobile app
- Budget input fields
- Real-time notifications
- Feedback buttons ("Too cold", "Perfect", etc.)


**Usage:**
- System collects data continuously
- Predicts indoor needs based on weather
- Optimizes runtime to meet comfort and cost goals
- Adjusts settings autonomously or prompts user to confirm


---


### Challenges
- Requires reliable weather and electricity APIs
- Older AC units may lack compatibility
- Users need time to train the system with feedback
- Budget limits may override comfort temporarily


---


### What next
- Add CO2 impact monitoring and sustainability rewards
- Support multiple AC units in shared housing
- Extend to heating and ventilation
- Offer firmware integration for manufacturers
- Integrate with smart assistants (Alexa, Google Home)


---


### Acknowledgments
Inspired by the [Building AI](https://github.com/ivicam/buildingai) course and GitHub community projects.
Special thanks to:
- OpenWeatherMap API
- Octopus Energy API
- Open-source reinforcement learning libraries



> 
