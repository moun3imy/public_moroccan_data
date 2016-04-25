# public_moroccan_data
## will contain specification about the formats of the different data files
### Specification for moroccan_cities.json, the spec will be written with the [json-generator](http://www.json-generator.com/) style (read their help for full details) : 
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
