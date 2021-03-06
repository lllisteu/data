# lllist.eu data

This repository provides data for art museums and art exhibitions in Europe.

The [lllist.eu](https://lllist.eu/) website listed art exhibitions in Europe. It became active in February 2012 and was updated until March 2018. The resulting set of data for 1,022 exhibitions forms the basis of this dataset.

![lllist.eu viewed on an iphone 6](lllist_iphone.png)

## Data

Items are provided as individual .txt files, encoded in UTF-8.

### Exhibition data

Since lllist.eu went on hiatus, exhibition data are amended only infrequently.

Next to the exhibition title, field names are mostly self explanatory:

Field|Description|Wikidata equivalent
---|---|---
uid|Unique identifier|
dt-created|Record creation date/time|
event-dt-begin|Opening date of the exhibition|[P580](https://www.wikidata.org/wiki/Property:P580)
event-dt-end|Closing date of the exhibition|[P582](https://www.wikidata.org/wiki/Property:P582)
event-location|Exhibition venue (museum)|
link|URL of exhibition webpage|

### Museum data

The set of museum data is still growing. Apart from museums, it includes some exhibition venues without a collection (_Kunsthalle_).

Next to the museum name, field names are mostly self explanatory:

Field|Description|Wikidata equivalent
---|---|---
uid|Unique identifier|
dt-created|Record creation date/time|
link|URL of museum webpage|[P856](https://www.wikidata.org/wiki/Property:P856)
tags|Tags|
wikidata_id|Corresponding [Wikidata](https://www.wikidata.org/) item|
wikipedia|Corresponding [Wikipedia](https://en.wikipedia.org/) article|
lat|[Latitude](https://en.wikipedia.org/wiki/Geographic_coordinate_system)|
lon|[Longitude](https://en.wikipedia.org/wiki/Geographic_coordinate_system)|
isa|Object class (usually _museum_)|

## Resources

* Related projects
    * Museum of Modern Art [collection](https://github.com/MuseumofModernArt/collection) and [exhibition](https://github.com/MuseumofModernArt/exhibitions) data
    * [The Tate Collection](https://github.com/tategallery/collection)
* [Europeana Collections](https://www.europeana.eu/)
* [_Unsustainable Museum Data_](https://matthewlincoln.net/2015/01/26/unsustainable-museum-data.html) by Matthew Lincoln

## License

Data is provided “as is”, without warranties of any kind.

This dataset is placed in the public domain using a [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).
