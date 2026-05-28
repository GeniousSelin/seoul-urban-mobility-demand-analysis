In this project, I analyzed a dataset with over 8,700 hourly records to understand what actually drives bike rental demand in Seoul. My goal was to see how weather, seasons, and holidays work together so that city operators can better manage their bike fleets.

### Technical Stack & Instruments Used:
- **Environment:** Jupyter Notebook / Anaconda python environment.
- **Data Manipulation:** `Pandas` (used for indexing, slicing, handling missing values, and data filtering) and `NumPy` (for array and statistical operations).
- **Time-Series Analysis:** Extracted and parsed temporal components (Hours, Seasons, Holidays) to group data and find exact peak usage trends.
- **Statistical Analytics:** Explored feature relations to see how multiple variables (Temperature, Humidity, Wind Speed, Visibility, Solar Radiation) interact and compound together.

### Step-by-Step Implementation:
1. **Data Cleaning:** Imported the raw CSV data into a Pandas DataFrame. Audited the dataset for anomalies, adjusted data types, and filtered out non-operational hours to keep the data organic.
2. **Feature Grouping & EDA:** Grouped the dataset by specific hours and days of the week. This helped isolate regular commuting patterns (rush hours) from leisure activities.
3. **Correlation Analysis:** Analyzed how weather variables work together. Instead of looking at temperature alone, I mapped out how high solar radiation interacts with mid-range temperatures, and how high humidity drops rental numbers.

### Key Results & Business Insights:
- **Multi-Variable Analytics:** You cannot predict urban mobility demand based on temperature alone. A combination of factors, like high humidity or strong winds, can completely drop rental numbers even on a warm day.
- **The Summer Peak:** Summer weekdays turned out to be the absolute peak for bike rentals in Seoul, proving that bikes are a real part of the city's commuting infrastructure, not just a weekend hobby.
- **Fleet Optimization:** Using multi-variable data helps city services predict demand spikes accurately. This prevents situations where stations are empty during rush hours or overflowing when nobody is riding.
