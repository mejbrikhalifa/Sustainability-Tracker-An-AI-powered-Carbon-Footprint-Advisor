# **Sustainability-Tracker-An-AI-powered-Carbon-Footprint-Advisor**

### **Days 2 & 3 – Environment Setup, Core Modules & API Integration**
This project is part of the Decoding Data Science AI App Challenge. The Sustainability Tracker helps users log daily activities (energy, transport, meals) and calculates their CO₂ footprint, provides AI-generated eco-tips, and awards badges for sustainable progress.

### **Features**
* **CO₂ Engine (co2_engine.py)**
Calculates emissions using predefined factors for energy, transport, and meals.

* **AI Tips Generator (ai_tips.py)**
Integrates with OpenAI GPT API to suggest daily eco-friendly actions.
Includes error handling & fallback to local tips when API fails.

* **Utilities (utils.py)**
Helper functions for formatting emissions, calculating percentage change, and generating feedback messages.

* **Streamlit App (app.py)**
Interactive UI for entering activities, viewing CO₂ results, AI tips, progress streaks, and earning badges.

### 📂 **Project Structure**

📦 Sustainability-Tracker
 ┣ 📜 app.py              # Streamlit UI
 ┣ 📜 co2_engine.py       # CO₂ calculation engine
 ┣ 📜 ai_tips.py          # AI eco-tips generator
 ┣ 📜 utils.py            # Helper utilities
 ┣ 📜 test_co2_engine.py  # Unit tests for CO₂ engine
 ┣ 📜 test_ai_tips.py     # Unit tests for AI tips
 ┣ 📜 test_utils.py       # Unit tests for utils
 ┣ 📜 test_app_module.py  # Tests for app logic
 ┗ 📜 history.csv         # User activity history (auto-generated)

### **Tech Stack**
* **Python 3.12+**
* **Streamlit** – UI framework
* **Pandas** – Data handling
* **OpenAI API** – AI tips integration
* **Pytest** – Testing framework

### **Progress (Days 2 & 3)**
* Environment setup with dependencies and API keys
* Implemented and tested CO₂ calculation engine
* Developed AI eco-tip generator with error handling
* Created utilities for formatting and percentage tracking
* Built initial Streamlit app with inputs, KPIs, and eco-tips
* Added gamification badges & activity history logging
* Expanded tests (all modules tested and passing ✅)

### **Screenshots**
* Streamlit app with activity inputs, CO₂ results, eco-tip, and badges
* Terminal showing passing unit tests
 
### **Requirements**

#### Core dependencies
streamlit==1.26.0
pandas==2.1.1

#### AI API integration
openai==1.32.0

#### Testing
pytest==7.4.4
anyio==4.2.0

#### Optional helpers
python-dotenv==1.0.0   # If you plan to store API keys in a .env file



