# Mapping Boston Black-Owned Businesses

## About
The aim of this project is to develop a publicly accessible, interactive map of Black-owned businesses in and around Boston, Massachusetts. The map is intended for use by Boston residents and visitors seeking to support Black-owned businesses to help narrow the racial wealth gap and strengthen local economies. This project may also serve as a resource for individuals and organizations interested in developing similar maps for other geographic regions. 

## Data
Business names and addresses included in this project were accessed via a [crowd-sourced spreadsheet](https://docs.google.com/spreadsheets/d/1_wvyIj3w5F8XJn0leuGD5M9sAmaBKT8N2j0fEV0Df5I/edit?fbclid=IwAR3xpEGS_VBryR5oSIDE91aXE6KaSpLeD37t-s6eEF2Q4GRKwIU1ygNU_7Q#gid=778167218) of Black-owned businesses in and around Boston. The store, restaurant, and services sheets were downloaded as CSV files and read into separate pandas data frames. A restaurant-specific map was previously developed with data from this document, and can be accessed on the restaurant sheet.

## Methods
The data frames contained either a column with full addresses or a combination of street, city, and zipcode columns whose contents could be concatenated into full addresses. After formatting the full address columns as needed, geographic coordinates were obtained for new columns using [GeoPy](https://geopy.readthedocs.io/en/stable/). Data for the name, address, website, and coordinates of businesses were used with [Folium](https://pypi.org/project/folium/0.1.5/#:~:text=Concept,as%20markers%20on%20the%20map) to design the map.  

## Marker Icon Key

| Restaurants | Stores | Architects | Cleaning and <br>Waste<br>Management | Computer Software,<br>Programming,<br>Training<br>and Support | Education, <br>Advocacy, <br>Shelter and Care Nonprofits | Home Building,<br>Improvement<br>and Demolition | Health Care<br>Services<br>and Consultants | Marketing |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | 
| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/cutlery.png' width="80" height="80" alt="Restaurants"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/stores_dollar.png' width="70" height="80" alt="Stores"></a> | <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/building.png' width="80" height="80" alt="Architects"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/trash.png' width="80" height="80" alt="Trash"></a> | <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/laptop.png' width="127" height="100" alt="Laptop"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/heart.png' width="155" height="80" alt="Heart"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/home.png' width="110" height="80" alt="Home"></a> | <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/stethoscope.png' width="110" height="80" alt="Health"></a>| <img src ='https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/bullhorn.png' width="110" height="80" alt="Marketing"></a>|| git diff | Show file differences that haven't been staged |

## Interactive Map
[Businesses Map](https://avonleafisher.github.io/Mapping-Boston-Black-Owned-Businesses/): Map of Black-owned businesses in the Greater Boston Area, which includes both confirmed and unconfirmed entries from the above spreadsheet. Businesses with missing addresses whose geographic coordinates could not be obtained with GeoPy have not yet been added to the map.

<img src="https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/blob/main/Images/preview.gif"></a>

## Further Information and Resources

Please feel free to contact me at [fisheravonlea@gmail.com](mailto:fisheravonlea@gmail.com) or via my [LinkedIn profile](https://www.linkedin.com/in/avonlea-fisher/) with any comments or inquiries regarding this project.

Black Lives Matter is working to deveop a website, [Backing Black Business](https://www.backingblackbusiness.com/), that will include Black-owned businesses across the United States. If you are a Black business owner or know someone who is, owners can submit information about their business via [this form](https://docs.google.com/forms/d/e/1FAIpQLSfTlalteGhMVi9fQsSgnFpwnR-lNyPCf1CFxQGokc9nZfFPAQ/viewform).
