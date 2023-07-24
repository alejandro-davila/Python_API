<h1 align="center">Weather Analysis</h1>


<p align="center">
<img width="1000" height="400" alt="TempVLat" src=https://github.com/alejandro-davila/python-api-challenge/assets/135288005/f4ec9f5c-1b14-497a-9798-54f6c7129e13>

<p align="center">
* PART 1: WeatherPy - Analysis on monthly Profit/Loss data &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;* PART 2: VacationPy - Analysis on election result

<h2 align="center"> Background </h2>

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

<h1 align="center">PART 1: WeatherPy</h1>

<h2 align="center"> Requirement 1: </h2>

<p align="center"> 
Create Plots to Showcase the Relationship Between Weather Variables and Latitude

<h1 align="center">Latitude vs. Temperature</h1>

<p align="center">
<img width="586" alt="TempVLat" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/793058e5-b686-4faa-acda-b4269b9ad0dd">


<h1 align="center">Latitude vs. Humidity</h1>

<p align="center">
<img width="586" alt="Lat v Hum" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/57a7fdcb-b807-43ed-9ffa-400482165fc7">


<h1 align="center">Latitude vs. Cloudiness</h1>

<p align="center">
<img width="598" alt="Lat v Cloud" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/c5c8c810-0ae3-484a-ac40-0f813d32dac4">


<h1 align="center">Latitude vs. Wind Speed</h1>

<p align="center">
<img width="574" alt="Lat v Wind" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/52a12396-020f-405f-a8dc-809e7d7ed3df">


<h2 align="center"> Requirement 2: </h2>

<p align="center"> 
Compute Linear Regression for Each Relationship

<h1 align="center">Northern Hemisphere: Temperature vs. Latitude</h1>

In the Northern Hemisphere, the statement indicates that there is a relatively strong negative correlation between temperature and latitude with a correlation coefficient of -0.599. A negative correlation means that as you move closer to the North Pole (increasing latitude), the temperature tends to decrease. This is a common observation, as regions closer to the poles generally experience colder temperatures.

<p align="center">
<img width="596" alt="Temp v NLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/f1493a12-66e6-4949-9603-477afb39853b">


<h1 align="center">Southern Hemisphere: Temperature vs. Latitude</h1>

The statement suggests that there is a fairly strong positive correlation between temperature and latitude in the Southern Hemisphere. The correlation coefficient is given as 0.8518. A positive correlation indicates that as you move closer to the equator (increasing latitude from the south pole), the temperature tends to increase. This also aligns with the general understanding that areas closer to the equator experience warmer temperatures.

These statements highlight the general temperature patterns as you move towards different latitudes in both hemispheres. The negative correlation in the Northern Hemisphere and positive correlation in the Southern Hemisphere are well-established climatic trends.

<p align="center">
<img width="581" alt="Temp v SLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/45571f53-cdad-4d05-ad7d-6e7c003911bb">


<h1 align="center">Northern Hemisphere: Humidity vs. Latitude</h1>

The relationship between humidity and latitude exhibits distinct patterns in both hemispheres. In the Northern Hemisphere, there is a relatively strong positive correlation between humidity and latitude, with a correlation coefficient of -0.6252. This suggests that as one moves further north from the equator, humidity tends to increase.


<p align="center">
<img width="588" alt="Hum v NLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/f28961f2-d9d5-4c86-86f6-25894ec2d797">

<h1 align="center">Southern Hemisphere: Humidity vs. Latitude</h1>

On the other hand, in the Southern Hemisphere, there is also a relatively strong positive correlation between humidity and latitude, but with a correlation coefficient of 0.8598. This indicates that as one moves closer to the South Pole, humidity tends to increase. These findings underscore the different moisture trends associated with varying latitudinal positions in both hemispheres.


<p align="center">
<img width="581" alt="Hum v SLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/ad36ef80-9ded-4c10-87bc-b1be0344b029">

<h1 align="center">Northern Hemisphere: Cloudiness vs. Latitude</h1>

The association between cloudiness and latitude demonstrates different strengths in the Northern and Southern Hemispheres. In the Northern Hemisphere, there exists a weak negative correlation with a coefficient of -0.0517. This suggests that cloudiness tends to slightly decrease as one moves north from the equator. The data reflects an immaterial change which can be concluded that there is no strong relationship between latitude and cloudiness in the north.

<p align="center">
<img width="591" alt="Cloud v NLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/0a02934d-1bda-41fc-b5f2-2375c5f8d3d9">

<h1 align="center">Southern Hemisphere: Cloudiness vs. Latitude</h1>

The same can be said about the Southern Hemisphere, there is a relatively weak negative correlation with a coefficient of -0.0642. This indicates that cloudiness is more likely to increase as one moves closer to the South Pole. These contrasting results highlight the varying cloud patterns relative to latitude in each hemisphere.The data reflects an immaterial change which can be concluded that there is no strong relationship between latitude and cloudiness in the south.

<p align="center">
<img width="594" alt="Cloud v SLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/3052ef46-9770-429c-936d-c928359b50d4">


<h1 align="center">Northern Hemisphere: Wind Speed vs. Latitude</h1>

The association between wind speeds and latitude demonstrates different strengths in the Northern and Southern Hemispheres. In the Northern Hemisphere, there exists a semi-weak negative correlation with a coefficient of -0.2286. This suggests that wind speeds tends to slightly decrease as one moves north from the equator.

<p align="center">
<img width="574" alt="Wind v NLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/07bc9623-a4de-419d-b7a2-36814e3e7477">

<h1 align="center">Southern Hemisphere: Wind Speed vs. Latitude</h1>

The Southern Hemisphere, there is a weak negative correlation with a coefficient of -0.0642. This indicates that wind speeds is more likely to increase as one moves closer to the South Pole. These contrasting results highlight the varying wind speed patterns relative to latitude in each hemisphere.The data reflects an immaterial change which can be concluded that there is no strong relationship between latitude and cloudiness in the south.

<p align="center">
<img width="594" alt="Wind v SLR" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/a3d64ef9-1441-43ce-b025-1c7ed4cb3814">


<h1 align="center">PART 2: VacationPy</h1>

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

* Create `city map` that displays a point for every city in the `city_data_df` DataFrame using data in `output_data/cities.csv`. The size of the point is determined by the humidity level in each city.

<p align="center">
<img width="856" alt="Screenshot 2023-07-23 at 11 50 08 PM" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/eed45c4d-51a1-4d03-aa94-ef83a52c58ec">

* Narrow down cities that fit the criteria and drop any results with null values, the criteria are listed below:
<p align="center">
<img width="522" alt="Screenshot 2023-07-23 at 11 56 22 PM" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/e7768453-5f6f-401d-a82e-e7f281ebaa28">

<p align="center">
<img width="701" alt="Screenshot 2023-07-23 at 11 55 10 PM" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/2c9bf3db-fb87-402b-a29e-586fb4b74a1a">

* Create a new DataFrame called `hotel_df` which contains columns: `City`, `Country`, `Lat`, `Lng`, `Humidity`, and `Hotel Name`. For each city, use the **Geoapify API** to find the first hotel located within 10,000 metres of each city and append the results to `hotel df` in a column called `Hotel Name'.

<p align="center">
<img width="422" alt="Screenshot 2023-07-23 at 11 51 15 PM" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/23033ae3-5e3d-4979-b727-e1cf1de929aa">


* Add the hotel name and the country as additional information in the hover message for each city in `hotel map`

<p align="center">
<img width="814" alt="Screenshot 2023-07-23 at 11 50 35 PM" src="https://github.com/alejandro-davila/python-api-challenge/assets/135288005/ae024462-8644-4445-954b-7460c920af24">

***

<h1 align="center">References</h1>

SOFTWARE/TOOLS/LIBRARIES

Anaconda, Jupyter Lab, Pandas, PythonData environment using Python 3.6

