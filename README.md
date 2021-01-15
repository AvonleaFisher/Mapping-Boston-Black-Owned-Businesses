# Mapping-Boston-Black-Owned-Businesses

## Data
Business names and addresses included in this project were accessed via a [crowd-sourced spreadsheet](https://docs.google.com/spreadsheets/d/1_wvyIj3w5F8XJn0leuGD5M9sAmaBKT8N2j0fEV0Df5I/edit?fbclid=IwAR3xpEGS_VBryR5oSIDE91aXE6KaSpLeD37t-s6eEF2Q4GRKwIU1ygNU_7Q#gid=778167218) of Black-owned businesses in and around Boston, Massachusetts. The stores, restaurants, and services sheets were downloaded as CSV files and read into separate pandas data frames.   

## Methods
Each data frame contained either a column with full addresses or a combination of street, city, and zipcode columns whose contents could be concatenated into full addresses. After formatting the full address columns as needed, geographic coordinates were obtained for new columns using [GeoPy](https://geopy.readthedocs.io/en/stable/). Data for the name, address, website, and coordinates of businesses were used with [Folium](https://pypi.org/project/folium/0.1.5/#:~:text=Concept,as%20markers%20on%20the%20map) to design interactive maps.  

## Maps
* [Stores and Restaurants](https://avonleafisher.github.io/Mapping-Boston-Black-Owned-Businesses/): Map of Black-owned stores and restaurants, which includes both confirmed and unconfirmed entries from the above spreadsheet. Businesses with missing addresses whose geographic coordinates could not be obtained with GeoPy have not yet been added to the map.

<img src="https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/boston.gif"></a>

