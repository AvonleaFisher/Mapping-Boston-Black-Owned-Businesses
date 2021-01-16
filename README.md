# Mapping Boston Black-Owned Businesses

## Data
Business names and addresses included in this project were accessed via a [crowd-sourced spreadsheet](https://docs.google.com/spreadsheets/d/1_wvyIj3w5F8XJn0leuGD5M9sAmaBKT8N2j0fEV0Df5I/edit?fbclid=IwAR3xpEGS_VBryR5oSIDE91aXE6KaSpLeD37t-s6eEF2Q4GRKwIU1ygNU_7Q#gid=778167218) of Black-owned businesses in and around Boston, Massachusetts. The store, restaurant, and services sheets were downloaded as CSV files and read into separate pandas data frames.   

## Methods
The data frames contained either a column with full addresses or a combination of street, city, and zipcode columns whose contents could be concatenated into full addresses. After formatting the full address columns as needed, geographic coordinates were obtained for new columns using [GeoPy](https://geopy.readthedocs.io/en/stable/). Data for the name, address, website, and coordinates of businesses were used with [Folium](https://pypi.org/project/folium/0.1.5/#:~:text=Concept,as%20markers%20on%20the%20map) to design interactive maps.  

## Marker Icon Key

| Restaurants | Stores | Architects | Cleaning and <br>Waste<br>Management | Computer Software,<br>Programming,<br>Training<br>and Support | Education, <br>Advocacy, <br>and Care <br>Non-Profits | Home building,<br>Improvement<br>and Demolition | Health Care<br>Services<br>and Consultants |
| --- | --- | --- | --- | --- | --- | --- | --- | 
| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/cutlery.png' width="80" height="80" alt="Restaurants"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/stores_dollar.png' width="80" height="80" alt="Stores"></a> | <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/building.png' width="80" height="80" alt="Architects"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/trash.png' width="80" height="80" alt="Trash"></a> | <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/laptop.png' width="117" height="90" alt="Laptop"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/heart.png' width="80" height="80" alt="Heart"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/home.png' width="80" height="80" alt="Home"></a> | <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/stethoscope.png' width="80" height="80" alt="Health"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/stores_dollar.png' width="80" height="80" alt="Stores"></a> || git diff | Show file differences that haven't been staged |

## Interactive Map
* [Businesses Map](https://avonleafisher.github.io/Mapping-Boston-Black-Owned-Stores-and-Restaurants/): Map of Black-owned businesses, which includes both confirmed and unconfirmed entries from the above spreadsheet. Businesses with missing addresses whose geographic coordinates could not be obtained with GeoPy have not yet been added to the map.

<img src="https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/boston.gif"></a>

