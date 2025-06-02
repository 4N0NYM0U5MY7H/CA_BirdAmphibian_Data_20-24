# CA Threatened Bird and Amphibian Data 2020-2024
This dataset contains data sourced from iNaturalist on threatened bird and amphibian species in California during breeding and nesting seasons from 2020-2024.

## iNaturalist Queries (retrieved 2024-11-23)
### Observation Data
* [2020](iNaturalist/CA_BirdAmphib_MarAug20.csv)
* [2021](iNaturalist/CA_BirdAmphib_MarAug21.csv)
* [2022](iNaturalist/CA_BirdAmphib_MarAug22.csv)
* [2023](iNaturalist/CA_BirdAmphib_MarAug23.csv)
* [2024](iNaturalist/CA_BirdAmphib_MarAug24.csv)

### Query
* https://www.inaturalist.org/observations?quality_grade=research&identifications=any&iconic_taxa[]=Aves&iconic_taxa[]=Amphibia&place_id=14&threatened=true&introduced=false&native=true&d1=2020-03-01&d2=2020-08-31&spam=false
* https://www.inaturalist.org/observations?quality_grade=research&identifications=any&iconic_taxa[]=Aves&iconic_taxa[]=Amphibia&place_id=14&threatened=true&introduced=false&native=true&d1=2021-03-01&d2=2021-08-31&spam=false
* https://www.inaturalist.org/observations?quality_grade=research&identifications=any&iconic_taxa[]=Aves&iconic_taxa[]=Amphibia&place_id=14&threatened=true&introduced=false&native=true&d1=2022-03-01&d2=2022-08-31&spam=false
* https://www.inaturalist.org/observations?quality_grade=research&identifications=any&iconic_taxa[]=Aves&iconic_taxa[]=Amphibia&place_id=14&threatened=true&introduced=false&native=true&d1=2023-03-01&d2=2023-08-31&spam=false
* https://www.inaturalist.org/observations?quality_grade=research&identifications=any&iconic_taxa[]=Aves&iconic_taxa[]=Amphibia&place_id=14&threatened=true&introduced=false&native=true&d1=2024-03-01&d2=2024-08-31&spam=false

### Columns
* `observed_on`: Normalized date of observation
* `time_observed_at`: Normalized datetime of observation
* `quality_grade`: Quality grade of this observation. See Help section for details on what this means. See https://help.inaturalist.org/support/solutions/articles/151000169936
* `latitude`: Publicly visible latitude from the observation location
* `longitude`: Publicly visible longitude from the observation location
* `positional_accuracy`: Coordinate precision (yeah, yeah, accuracy != precision, poor choice of names)
* `private_latitude`: Private latitude, set if observation private or obscured
* `private_longitude`: Private longitude, set if observation private or obscured
* `public_positional_accuracy`: Maximum horizontal positional uncertainty in meters; includes uncertainty added by coordinate obscuration
* `scientific_name`: Scientific name of the observed taxon according to iNaturalist
* `common_name`: Common or vernacular name of the observed taxon according to iNaturalist

For more information about column headers, see https://www.inaturalist.org/terminology

## Contibutors
* **August Frisk** - Data Curation, Analysis, and Documentation
* iNaturalist Contributors - Data Collection, Identification, and Validation
    
    |Observers|Identifiers|
    |---|---|
    |[2020](https://www.inaturalist.org/observations?d1=2020-03-01&d2=2020-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=observers)|[2020](https://www.inaturalist.org/observations?d1=2020-03-01&d2=2020-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=identifiers)|
    |[2021](https://www.inaturalist.org/observations?d1=2021-03-01&d2=2021-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=observers)|[2021](https://www.inaturalist.org/observations?d1=2021-03-01&d2=2021-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=identifiers)|
    |[2022](https://www.inaturalist.org/observations?d1=2022-03-01&d2=2022-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=observers)|[2022](https://www.inaturalist.org/observations?d1=2022-03-01&d2=2022-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=identifiers)|
    |[2023](https://www.inaturalist.org/observations?d1=2023-03-01&d2=2023-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=observers)|[2023](https://www.inaturalist.org/observations?d1=2023-03-01&d2=2023-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=identifiers)|
    |[2024](https://www.inaturalist.org/observations?d1=2024-03-01&d2=2024-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=observers)|[2024](https://www.inaturalist.org/observations?d1=2024-03-01&d2=2024-08-31&introduced=false&native=true&place_id=14&quality_grade=research&threatened=true&view=identifiers)| 

## Acknowledgements
This project is a derived work of Madison Carlson and Darko Gojsic's [Species mapping in ArcGIS Pro](https://storymaps.arcgis.com/stories/a09723cb2d7d4187bbec43466cbdb920).
