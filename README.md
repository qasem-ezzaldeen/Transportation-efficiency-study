# Transportation-efficiency-study
### Data Collection
To gather the necessary data for this study, I utilized ChatGPT, which provided me with a variety of data sources. After reviewing these, I decided to focus my analysis on car registration data collected across Europe in 2023.


### Data Preprocessing and Cleaning with Python
After downloading the dataset, I loaded it into a pandas DataFrame to begin the preprocessing and cleaning phase. The raw data contained many missing values, especially in important fields like car make and model, which are crucial for the analysis. Additionally, there were several unnecessary columns that did not contribute to the study, so I removed them to streamline the dataset. I handled the missing values by dropping records where essential fields were empty. Once the dataset was cleaned, I exported it to a CSV file for further use in building the dashboard.


### Insights and Summary
#### 1- Cars Registered & CO2 Emissions:
* 10.73M cars are registered in Europe, with an average CO2 emission of 106.67 g/km and fuel consumption of 5.41 g/km.
* Germany, Italy, and France lead in both registrations and CO2 emissions.

#### 2- Fuel Type & Electric Vehicles:
* Petrol cars dominate at 56.03%, followed by diesel (16.98%). Electric cars account for 15.55%, highlighting the need for further growth to reduce emissions.

#### 3- CO2 Emissions by Engine Size & Fuel Consumption:
* Larger engines produce more CO2, and higher fuel consumption correlates with higher emissions. Reducing fuel-hungry vehicles is critical.

#### 4- Supercars vs. Regular Cars:
* Supercars like the Aston Martin Valkyrie and Bugatti Chiron have very high CO2 emissions, averaging over 400 g/km, but they are rare (Valkyrie: 11, Chiron: 1).
* In contrast, everyday cars like the Sandero (223,289 registered) and TROC (177,749 registered) have a much larger presence and contribute heavily to CO2 emissions despite having lower per-car emissions.

#### 5- Electric Conversion Recommendation:
* High-volume, high-emission cars like the Sandero and TROC need to transition to electric models, which produce zero emissions, to reduce the overall environmental impact of transportation.
