# AquaPredict

AquaPredict is a cloud-based, AI-enabled platform that leverages machine learning, geospatial analysis, and IoT sensors to predict optimal borehole-drilling sites. The platform is designed to assist WASH authorities and NGOs in identifying high-potential groundwater locations, monitoring sustainability, and visualizing predictions through a user-friendly dashboard.

## Key Features
- **Geospatial AI (GeoAI):** Analyzes satellite imagery and historical borehole data to map groundwater potential, considering soil composition, topography, and rainfall patterns.
- **Machine Learning Models:** Predicts borehole yield and water quality using Artificial Neural Networks (ANN) and Support Vector Machines (SVM), trained on hydrogeological and climatic datasets.
- **IoT Sensors:** Integrates low-cost, solar-powered sensors to monitor real-time groundwater levels and quality post-drilling.
- **User Interface:** Provides a mobile-accessible dashboard for data visualization and site prioritization.

## Project Structure

```
AquaPredict/
│
├── backend/
│   ├── api/
│   ├── ml_models/
│   ├── geoai/
│   ├── iot/
│   ├── data/
│   ├── utils/
│   ├── requirements.txt
│   └── Dockerfile
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   ├── package.json
│   └── Dockerfile
│
├── deployment/
│   ├── docker-compose.yml
│   ├── cloud/
│   └── README.md
│
├── docs/
│
├── .env.example
├── README.md
└── LICENSE
```

---

## Getting Started

1. **Backend:** Python (FastAPI) for API, ML, and geospatial processing.
2. **Frontend:** React for dashboard and visualization.
3. **Deployment:** Docker and cloud scripts for scalable deployment.

---

For more details, see the documentation in the `docs/` folder.