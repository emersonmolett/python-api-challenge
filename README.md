This is the initial assignment leveraging APIs. The Application Programming Interface (API) are used in combination with Python and JSON, to analyze weather data. </br>

API Querying:
<li>API Key was imported from external script and used as variable</li>
<li>Loops over the list of cities</li>
<li>No errors in the API call loop</li>

</br>

Data Modeling:</br>

A Pandas dataframe was created off the API call. The dataframe contained over 500 cities, with the following information successfully determined via coding: 
<li>City latitude</li>
<li>City longitude</li>
<li>Max temperature</li>
<li>Humidity</li>
<li>Cloud coverage</li>
<li>Wind speed</li>
<li>City country</li>

</br>

Plot Creation: </br>

Using the previous information, a series of plots were created. The plots had axis and title tables. The plots include:
<li>Latitude vs Temperature</li>
<li>Latitude vs Humidity</li>
<li>Latitude vs Cloudiness</li>
<li>Latitude vs Wine Speed</li>

</br>

A linear regression was performed on the plot visuals, to further illustrate the relation between weather and location. This includes:
<li>Northern Hemisphere – Temperature (F) vs Latitude</li>
<li>Southern Hemisphere – Temperature (F) vs Latitude</li>
<li>Northern Hemisphere – Humidity (%) vs Latitude</li>
<li>Southern Hemisphere – Humidity (%) vs Latitude</li>
<li>Northern Hemisphere – Cloudiness (%) vs Latitude</li>
<li>Southern Hemisphere – Cloudiness vs Latitude</li>
<li>Northern Hemisphere – Wind Speed (mph) vs Latitude</li>
<li>Southern Hemisphere – Wind Speed (mph) vs Latitude</li>



