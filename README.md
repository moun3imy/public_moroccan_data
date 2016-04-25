# public_moroccan_data
This repository aims at providing useful data about about different sectors and facets of morocco, all in json format.
## will contain specification about the formats of the different data files
### 1.Specification for moroccan_cities.json
moroccan_cities.json contains data about morocco different cities.
the spec will be written with the [json-generator](http://www.json-generator.com/) style (read their help for full details) : 
```js
[
  '{{repeat(number_of_cities)}}',
  {
    City: '',
    Region: '',
    Mayor: '',
    Postal_Code: '',
    Coordinates: '',
    Area: '',
    Highest_Elevation: '',
    Lowest_Elevation: '',
    city_population: '',
    population_density: '',
    population_rank_morocco: '',
    population_metro: '',
    website: '',
    foundation_date: '',
    list_neighborhoods: [
    '{{repeat(number_of_neighborhoods)}}',
    {
    neighborhood:,
    Coordinates:,
    Postal_code :
     }
    
    ]
   
    
  }
]
```
