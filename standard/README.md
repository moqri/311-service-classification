# CDO Network 311 Service Classification, an Analysis

### Cities

| City             | # Requests | Top 100 Services |
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

### Top 100 Services by City

![top_services](https://github.com/moqri/311-service-classification/blob/master/images/top_services.PNG)

[full table](https://github.com/moqri/311-service-classification/blob/master/standard/top_service.csv)

### Most Common Keywords 

Most used keywords accorss all 12 cities (after removing stop_words and ambiguous words) are as follows.

Street, Trash, Sign, Graffiti, Tree, Cart, Traffic, Recycling, Sidewalk, Building, Vehicle, Animal, Water, Signal, Parking, Light, Abandoned, Muni, District, Park, Removal, Waste, Dead, Curb, Noise, City, Dumping, General, Pothole, Utility, Weeds, Cleaning, Vacant, Public, Marking, Snow, Pickup, Litter, Permit, Yard, Commercial, Trees, Service, Grass, VAP, DOF, Heat, Collection, Pedestrian, Plumbing

### Extracted Tags

After removing alternative term (e.g. weeds -> grass) and combining terms (e.g. sign, signal, traffic -> traffic), we propose the following standard tags for 311 services.

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
