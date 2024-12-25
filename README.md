# Personal Carbon Calculator App ⚠️🌍

Welcome to the **Personal Carbon Calculator App**! 🌱 This web application helps you estimate your personal carbon footprint based on your daily activities. You can calculate your CO2 emissions from **transportation**, **electricity**, **diet**, and **waste** generation, and gain insights into your environmental impact.

## Features ✨
- **🚗 Transportation**: Calculate emissions based on your daily commute distance (in km).
- **💡 Electricity Consumption**: Estimate emissions from your monthly electricity usage (in kWh).
- **🍽️ Diet**: Evaluate the carbon emissions from your daily meals.
- **🗑️ Waste**: Compute emissions based on the weekly waste you generate (in kg).

## How It Works 🧑‍💻
1. **User Input**: 
   - Choose your country (currently supports **India** 🇮🇳).
   - Enter your **daily commute distance** (in km).
   - Enter your **monthly electricity consumption** (in kWh).
   - Input your **weekly waste generation** (in kg).
   - Enter the number of **meals** you consume per day.

2. **Emissions Calculation**: The app uses predefined **emission factors** for each activity:
   - **Transportation**: 0.14 kgCO2/km 🚗
   - **Electricity**: 0.82 kgCO2/kWh 💡
   - **Diet**: 1.25 kgCO2/meal 🍽️
   - **Waste**: 0.1 kgCO2/kg 🗑️

3. **Results**: The app will display:
   - Your **carbon emissions** for each category.
   - Your **total CO2 emissions per year**.

4. **Comparison**: The app compares your emissions with the average **CO2 emissions per capita** in India.

## Requirements 📦
To run the app, you will need:
- `streamlit` (for building the app)
- Python 3.x

### Installation 🛠️
1. Clone this repository or download the source code.
2. Install the required dependencies:
    ```bash
    pip install streamlit
    ```
3. Run the app:
    ```bash
    streamlit run app.py
    ```

## Usage 🎮
1. Open the app in your browser.
2. Select your country (currently only **India** 🇮🇳 is supported).
3. Input your daily commute distance, monthly electricity consumption, weekly waste generation, and number of meals per day.
4. Hit the **"Calculate CO2 Emissions"** button to see your estimated carbon footprint!

## Emission Factors 🔋
The emission factors used in the app are based on typical values for **India**:
- **Transportation**: 0.14 kgCO2 per km 🚗
- **Electricity**: 0.82 kgCO2 per kWh 💡
- **Diet**: 1.25 kgCO2 per meal 🍽️
- **Waste**: 0.1 kgCO2 per kg of waste 🗑️

## Data Insights 📊
- **India's CO2 Emissions (2021)**: In 2021, the average CO2 emissions per capita in India were **1.9 tons** of CO2 per year, a significant increase from **0.39 tons** in 1972.
- This app helps you understand how your daily activities compare to the national average.

## License 📄
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## Contributing 🤝
We welcome contributions! If you have any bug fixes, enhancements, or suggestions, feel free to:
- Open issues
- Submit pull requests

Let's work together to make this app even better! 💪

