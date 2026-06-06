# SOLAR-IRRADIANCE-PREDICTION
The dataset is sourced from the National Solar Radiation Database (NSRDB) and contains hourly solar irradiance and weather data collected over multiple years. It includes measured and satellite-derived observations, enabling accurate solar radiation forecasting by capturing daily, seasonal, and long-term weather patterns.
SOLAR-IRRADIANCE-MICROGRID OPERATION:
Dataset Description (Solar Irradiance Forecasting)
The dataset utilized in this study is derived from the National Solar Radiation Database (NSRDB), a comprehensive and high-resolution dataset developed to support solar energy research and forecasting applications. The NSRDB provides long-term historical solar radiation and meteorological data across multiple geographic locations, making it one of the most reliable sources for solar energy analysis.
The dataset contains time-series observations of solar irradiance and weather-related parameters, typically recorded at intervals of 30 minutes or 60 minutes. For this project, the data has been processed into an hourly format to ensure consistency and compatibility with forecasting models.
The NSRDB dataset includes both measured and satellite-derived data, ensuring high accuracy and coverage even in regions where ground-based measurements are limited. It captures variations in solar radiation caused by atmospheric conditions such as cloud cover, temperature, and humidity.
The dataset used in this project spans multiple years, allowing the model to learn seasonal patterns, daily cycles, and long-term trends in solar irradiance. This temporal richness is essential for building robust and reliable forecasting models.
Key Features (Attributes)
The dataset consists of several important attributes that directly or indirectly influence solar irradiance levels. These features are used as input variables for training machine learning and deep learning models.
1. Global Horizontal Irradiance (GHI)
GHI represents the total amount of solar radiation received on a horizontal surface. It is the primary target variable in solar forecasting and includes both direct and diffuse radiation components.
2. Direct Normal Irradiance (DNI)
DNI measures the solar radiation received directly from the sun without atmospheric scattering. It is particularly important for concentrated solar power systems.
3. Diffuse Horizontal Irradiance (DHI)
DHI represents the scattered solar radiation reaching the Earth's surface. It helps capture the effect of clouds and atmospheric particles.
4. Temperature
Ambient temperature affects atmospheric conditions and influences solar radiation levels. It is also important for photovoltaic system performance.
5. Relative Humidity
Humidity impacts cloud formation and atmospheric transparency, indirectly affecting solar irradiance.
6. Wind Speed
Wind speed influences temperature distribution and atmospheric conditions, contributing to variations in solar radiation.
7. Solar Zenith Angle
This parameter represents the angle between the sun and the vertical direction. It plays a crucial role in determining the intensity of solar radiation received.
8. Cloud Cover / Sky Condition
Cloud presence significantly affects solar irradiance by blocking or scattering sunlight.
9. Timestamp (Date and Time)
Time-based features such as hour, day, month, and season are essential for capturing periodic patterns in solar radiation.
Data Characteristics
The NSRDB dataset exhibits several important characteristics that make it suitable for solar irradiance forecasting:
1. Time-Series Nature
The dataset is sequential and time-dependent, where each data point is linked to a specific timestamp. This allows models to learn temporal dependencies and trends.
2. High Resolution
Data is available at fine time intervals (30-minute or hourly), enabling detailed analysis of solar radiation patterns throughout the day.
3. Seasonal and Daily Patterns
Solar irradiance follows predictable patterns based on the time of day and season. The dataset captures these variations effectively.
4. Non-Linearity
The relationship between input features and solar irradiance is highly non-linear due to complex atmospheric interactions. This makes advanced models such as LSTM and deep learning approaches more suitable.
5. Missing and Noisy Data
Like most real-world datasets, NSRDB may contain missing values or noise due to measurement errors or environmental factors. Data preprocessing techniques are applied to handle these issues.
6. Large Dataset Size
The dataset contains a significant amount of data spanning multiple years, which is beneficial for training robust machine learning models.
Relevance to Solar Forecasting
The NSRDB dataset is highly relevant for solar irradiance forecasting due to its comprehensive coverage and high-quality data. It provides all the necessary parameters required to model solar energy generation accurately.
Solar forecasting is essential for:
 Renewable energy planning
 Grid stability and load balancing
 Energy storage optimization
 Smart grid management
The dataset captures both direct and indirect factors affecting solar radiation, allowing models to learn complex relationships between environmental conditions and solar output.
Its time-series structure makes it particularly suitable for deep learning models such as Long Short-Term Memory (LSTM) networks, which are designed to handle sequential data.
Usage in This Project
In this project, the NSRDB dataset is used to develop and evaluate machine learning and deep learning models for predicting solar irradiance, specifically Global Horizontal Irradiance (GHI).
The dataset undergoes several preprocessing steps before being used for model training:
 Data cleaning to remove missing or inconsistent values
 Feature selection to identify the most relevant variables
 Normalization to scale data for better model performance
 Time-based feature extraction (hour, day, month)
The processed dataset is then divided into training and testing sets. Multiple models, including traditional machine learning algorithms and deep learning models such as LSTM, are trained on the dataset.
The objective is to predict future solar irradiance values based on historical data and environmental conditions. The performance of each model is evaluated using standard metrics such as Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R² score.
The insights obtained from this analysis help improve forecasting accuracy and support efficient solar energy management.
DATASET:
NSRDB (National Solar Radiation Database) - 1998-2023 Dataset Dataset Website Link- https://nsrdb.nlr.gov/
Dataset Used Link- https://s3.us-west-2.amazonaws.com/nsrdb-data.stratus.nlr.gov/7cef467de3abbddf649ee4c766c2ddc1.zip
