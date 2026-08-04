# Weather-Aware Smart Tourist Recommendation and Itinerary Planning System for Sri Lanka

An AI-powered tourist recommendation and itinerary planning system that generates **dynamic, weather-aware travel itineraries** for Sri Lanka. The system combines **machine learning**, **knowledge-based weather reasoning**, and **constraint-aware search** to recommend attractions and automatically adapt travel plans under different weather conditions.

---

## Project Overview

Traditional itinerary planners generate fixed travel plans that do not adapt to changing weather conditions. This project proposes a hybrid AI approach that combines behavioural learning with expert knowledge to recommend attractions and generate feasible itineraries based on:

- Current weather conditions
- User preferences
- Attraction popularity
- Distance
- Opening hours
- Travel time
- Outdoor safety constraints

The project demonstrates how Artificial Intelligence can improve tourism planning by producing practical, explainable, and adaptive recommendations.

---

## Demo Video

🎥 **Watch the project demonstration**
https://youtu.be/uem6X_zR3H0


Or watch directly:



---

## Features

- Weather-aware itinerary generation
- Hybrid AI recommendation model
- Dynamic weather policy
- Automatic route replanning
- Interactive Folium maps
- Constraint-aware itinerary optimisation
- Risk-aware outdoor activity management
- Scenario-based itinerary comparison
- Interactive Google Colab demo

---

## AI Techniques Used

### Machine Learning
- LightGBM Classifier
- Behaviour prediction
- Classification
- Ranking

### Knowledge Representation
- Rule-based weather policy
- Hybrid suitability scoring
- Weather risk index

### Search & Optimisation
- Greedy insertion search
- Constraint-aware itinerary generation
- Route optimisation

---

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Folium
- Matplotlib
- Joblib
- Open-Meteo API

---

## Dataset

### Behavioural Data

TSMC2014 Foursquare Check-in Dataset

- New York
- Tokyo

The behavioural data is used to train the recommendation model before applying it to Sri Lankan tourist attractions.

### Weather Data

Open-Meteo Historical Weather Archive

Variables include:

- Temperature
- Precipitation
- Humidity
- Wind Speed
- Cloud Cover

---

## Project Workflow

```
Behavioural Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Tourism Category Mapping
        │
        ▼
Historical Weather Integration
        │
        ▼
Feature Engineering
        │
        ▼
LightGBM Model Training
        │
        ▼
Hybrid Suitability Model
        │
        ▼
Dynamic Weather Policy
        │
        ▼
POI Ranking
        │
        ▼
Constraint-aware Search
        │
        ▼
Final Itinerary
        │
        ▼
Interactive Folium Map
```

---

## Repository Structure

```
Weather-Aware-Itinerary-System/

│
├── notebooks/
│   ├── Full_Project.ipynb
│   ├── Demo_Notebook.ipynb
│
├── data/
│   ├── Sri_Lanka_POIs.csv
│   ├── Weather_Data/
│
├── models/
│   ├── weather_pipeline.pkl
│   ├── hybrid_lookup.pkl
│
├── outputs/
│   ├── Figures/
│   ├── Maps/
│   ├── Results/
│
├── docs/
│   ├── demo_thumbnail.png
│   ├── architecture.png
│
├── README.md
│
└── requirements.txt
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

Move into the project

```bash
cd YOUR_REPOSITORY
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Demo

Open

```
Demo_Notebook.ipynb
```

Run the first cell to load the saved model.

Choose:

- City
- Weather Scenario
- Preferred Categories
- Maximum Stops

Click

```
Generate Itinerary
```

The notebook will automatically display:

- Ranked tourist attractions
- Generated itinerary
- Interactive route map

---

## Example Output

The system generates:

- Ranked attractions
- Weather suitability scores
- Dynamic itinerary
- Travel schedule
- Interactive Folium route
- Scenario comparison

---

## Research Contributions

- Hybrid AI framework combining machine learning and symbolic reasoning.
- Weather-aware tourist recommendation.
- Dynamic itinerary replanning.
- Constraint-aware route optimisation.
- Explainable weather-risk policy.
- Interactive tourism decision support.

---

## Future Improvements

- Live weather forecasts
- Google Maps Directions API integration
- Real-time traffic estimation
- Multi-day itinerary planning
- Hotel and restaurant recommendations
- User accounts and personalised preferences
- Mobile application deployment

---

## Author

**Ovara Perera**

MSc Artificial Intelligence

University of Westminster

---

## References

- Yang, D., Zhang, D., Zheng, V.W. and Yu, Z. (2015). *Modeling User Activity Preference by Leveraging User Spatial Temporal Characteristics in LBSNs.*
- Ke, G. et al. (2017). *LightGBM: A Highly Efficient Gradient Boosting Decision Tree.*
- Open-Meteo Historical Weather API
- Foursquare TSMC2014 Dataset

---

## License

This repository is provided for academic and educational purposes.

```
