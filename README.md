# Mapping-Boston-Black-Owned-Businesses

## Data
Business names and addresses included in this project were accessed via a [crowd-sourced spreadsheet](https://docs.google.com/spreadsheets/d/1_wvyIj3w5F8XJn0leuGD5M9sAmaBKT8N2j0fEV0Df5I/edit?fbclid=IwAR3xpEGS_VBryR5oSIDE91aXE6KaSpLeD37t-s6eEF2Q4GRKwIU1ygNU_7Q#gid=778167218) of Black-owned businesses in and around Boston, Massachusetts. The stores, restaurants, and services sheets were downloaded as CSV files and read into separate pandas data frames.   

## Methods
Each data frame contained either a column with full addresses or a combination of street, city, and zipcode columns whose contents could be concatenated into full addresses. After formatting the full address columns as needed, geographic coordinates were obtained for new columns using [GeoPy](https://geopy.readthedocs.io/en/stable/). Data for the name, address, website, and coordinates of businesses were used with [Folium](https://pypi.org/project/folium/0.1.5/#:~:text=Concept,as%20markers%20on%20the%20map) to design interactive maps.  

## Marker Icon Key
### Restaurants and Stores 
| Restaurants | Stores |
| --- | --- | 
| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/favpng_font-awesome-cutlery-fork-tableware.png' width="100" height="100" alt="Restaurants"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/stores_dollar.png' width="100" height="100" alt="Stores"></a> || git diff | Show file differences that haven't been staged |

### Services

| Home building,<br>Home Improvement<br>and Demolition  | Cleaning and <br>Waste<br>Management | Computer Software,<br>Programming,<br>Training<br>and Support | Health Care<br>Services<br>and Consultants |
| --- | --- | --- | --- | 
|<img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/home.png?raw=true' width="130" height="100" alt="Home"></a>|<img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/trash.png' width="100" height="100" alt="Trash"></a> |<img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/off.png' width="130" height="100" alt="Off"></a>|<img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/heart.png' width="125" height="100" alt="Heart"></a> || git diff | Show file differences that haven't been staged |

## Interactive Maps
* [Restaurants and Stores](https://avonleafisher.github.io/Mapping-Boston-Black-Owned-Businesses/): Map of Black-owned stores and restaurants, which includes both confirmed and unconfirmed entries from the above spreadsheet. Businesses with missing addresses whose geographic coordinates could not be obtained with GeoPy have not yet been added to the map.

<img src="https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/boston.gif"></a>

