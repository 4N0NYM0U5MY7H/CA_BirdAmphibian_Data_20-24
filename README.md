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
* `observed_on`, `time_observed_at`, `quality_grade`, `latitude`, `longitude`, `positional_accuracy`, `private_latitude`, `private_longitude`, `public_positional_accuracy`, `scientific_name`, `common_name`

## Acknowledgements
This project is a derived work of Madison Carlson and Darko Gojsic's [Species mapping in ArcGIS Pro](https://storymaps.arcgis.com/stories/a09723cb2d7d4187bbec43466cbdb920).
