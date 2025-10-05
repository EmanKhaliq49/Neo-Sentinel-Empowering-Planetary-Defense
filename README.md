# 🚀 NEO-SENTINEL AI ASSISTANT

## The Planetary Defence Hub: Real-Time Asteroid Impact Simulation & Conversational Threat Analysis


-----

## 🌟 Overview

**NEO-SENTINEL** is a Progressive Web App (PWA) designed to bridge the gap between complex orbital mechanics data and public safety communication. Using a **Retro-Futuristic, Neon UI** inspired by classic command centers, this application allows users to simulate the impact of Near-Earth Objects (NEOs) and instantly generate **plain-language, localized threat assessments** via a Generative AI-powered conversational core.

We provide an interactive simulation, a hazard prediction engine, and a mitigation strategy tool, directly addressing the challenge of clear, impactful threat communication.

-----

## ✨ Key Features

  * **Scenario Builder:** Input specific asteroid parameters (diameter, velocity, composition) using live data from NASA APIs to trigger a custom impact scenario.
  * **The Prediction Engine (ML):** A lightweight Machine Learning model that instantly classifies the potential impact as **Low, Medium, or High Risk** and calculates the likely damage radius.
  * **The Conversational Core (Gen AI):** The core AI assistant takes the ML prediction and a target location, generating a clear narrative that describes the consequences (e.g., blast radius, equivalent earthquake magnitude, tsunami risk) and suggests mitigation steps.
  * **Retro-Futuristic PWA Interface:** A fast, mobile-friendly PWA experience featuring a **funky, cool, neon-accented UI** with subtle, animated space backgrounds and interactive HUD-style data panels.
  * **Data Visualization:** Uses Chart.js to render hazard breakdowns (Blast, Thermal, Tsunami Risk) and overlays USGS Elevation Map data to visualize impact zone consequences.

-----

## 🛠️ Technology Stack

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Frontend/PWA** | **Nuxt.js** (Vue) | Building the fast, mobile-first, single-page application shell. |
| **UI/Visualization** | **Chart.js** | Rendering all hazard breakdowns and data visualizations. |
| **Prediction Engine** | **Python / Scikit-learn** | Building a simple classification model for hazard prediction. |
| **Conversational Core** | **Generative AI / Hugging Face** | Providing the plain-language, contextual narrative response. |
| **APIs/Backend** | **Python / Gradio / Streamlit** | Exposing the ML model and AI core as accessible API endpoints. |

-----

## 📡 Data Sources & Attribution

The reliability of our simulation is built upon verified scientific data from leading institutions.

1.  **NASA Near-Earth Object (NEO) Web Service (NeoWs) API:** Provides the core, live asteroid data (size, velocity, orbital elements).
2.  **Small-Body Database Query Tool:** Used for training data to build a mock dataset of Potentially Hazardous Asteroids (PHAs).
3.  **USGS National Map Elevation Data:** Adds high-fidelity, geographical realism for map visualization of impact consequences (e.g., tsunami inundation).
4.  **USGS National Earthquake Information Center (NEIC) Catalog:** Used to correlate the asteroid's kinetic energy to a relatable earthquake magnitude scale for the AI narrative.

-----

## ⚙️ Setup and Installation

Follow these steps to get a local copy of the project up and running for development and testing.

### Prerequisites

  * Node.js (LTS version recommended)
  * Python 3.x
  * Git

### 1\. Clone the repository

```bash
git clone [YOUR_REPO_URL_HERE]
cd neo-sentinel-pwa
```

### 2\. Frontend Setup (Nuxt.js PWA)

```bash
cd frontend
npm install
npm run dev
# The PWA will be available at http://localhost:3000
```

### 3\. Backend Setup (ML/AI Services)

The backend is composed of two main services (Prediction Engine and Conversational Core).

```bash
cd backend
# Create a virtual environment and activate it
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Run the backend services (or the Streamlit/Gradio wrapper)
python api_server.py # (or similar command to start your API endpoints)
```

-----

## 🧑‍💻 Team

This project was built by:

| Role | Name |
| :--- | :--- |
| **Machine Learning / Python** | Waqar Ali |
| **Generative AI / Chatbot** | Muhammad Saad |
| **Frontend / Nuxt.js / PWA** | Eman Khaliq |
| **Frontend / Chart.js** | Saad |

-----

## 📄 License

This project is open-sourced under the **[MIT License / Apache 2.0 License / etc.]** - see the `LICENSE.md` file for details.
