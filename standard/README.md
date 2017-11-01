# CDO Network 311 Service Classification, an Analysis

### Cities
The following table summarizes the number of service requests and the ratio of the top 100 most commonly used service request for each city in our analysis.

| City             | # Requests | Top 100 Services Ratio|
|------------------|------------|----------|
| Cinciniti        | 555811     | 93%      |
| Philadelphia     | 1659364    | 100%     |
| Louisville       | 102039     | 98%      |
| San Francisco    | 2657709    | 94%      |
| Washington DC    | 771239     | 100%     |
| NYC              | 1329000    | 98%      |
| Los_anglese      | 955815     | 100%     |
| Kansas city (MO) | 1110841    | 100%     |
| Pittsburgh       | 185136     | 92%      |
| Boston           | 1027469    | 89%      |
| San Diego        | 161763     | 100%     |
| New Orleans      | 244338     | 100%     |

Top 100 Service Ratio = Total number of service requests in top 100 request types for that city / Total number of service request for that city (in our data)

### Top 100 Services by City

![top_services](https://github.com/moqri/311-service-classification/blob/master/images/top_services.PNG)

[full table](https://github.com/moqri/311-service-classification/blob/master/standard/top_service.csv)

### Most Common Keywords 

Most common keywords used in a service request name accorss all 12 cities (after removing stop_words and ambiguous words) are as follows.

Street, Trash, Sign, Graffiti, Tree, Cart, Traffic, Recycling, Sidewalk, Building, Vehicle, Animal, Water, Signal, Parking, Light, Abandoned, Muni, District, Park, Removal, Waste, Dead, Curb, Noise, City, Dumping, General, Pothole, Utility, Weeds, Cleaning, Vacant, Public, Marking, Snow, Pickup, Litter, Permit, Yard, Commercial, Trees, Service, Grass, VAP, DOF, Heat, Collection, Pedestrian, Plumbing

### Extracted Tags

After removing alternative term (e.g. weeds -> grass) and combining terms (e.g. sign, signal, traffic -> traffic), we propose the following **standard tags** for 311 services for US cities.

* street 
* light
* traffic 
* sidewalk
* vehicle
* graffiti 
* tree 
* grass
* park
* trash
* recycle 
* building
* district
* animal 
* water 
* noise
* miscellaneous

### Tagging/classification
Mapping of the existing service type (or service category) to these tags (tagging/classification) could be done by is a a CSV or JSON format. For example, a I propose the follwing tagging of the top 50 most common service types for Louisville: 
* [CSV](Louisville.csv)
* [JSON](Louisville.json)

Of course, the cities themeselve could provide a better mapping. 

### Using this taggs for analysis
Given such a tagging dictiorany for any city, its complete 311 data could be automatically tagged. These standardized taggs in addition to tagging dictionaries therefore could be used to perform 311 related analysis accross cities.

Let me know what your think here #1!
