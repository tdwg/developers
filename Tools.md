# List of tools

_List here reusable tools and libraries for Biodiversity Informatics._

## [Frictionless Darwin Core](https://github.com/frictionlessdata/FrictionlessDarwinCore)

[Frictionless Data Package](https://frictionlessdata.io/) is an emerging data standard similar to [Darwin Core Archive], but domain agnostic. This tool allows converting a [Darwin Core Archive] to a Data Package (from the CLI or Python code), giving access to the Frictionless ecosystem ([goodtables](https://github.com/frictionlessdata/goodtables-py), ...)

Currently in development, but the basic works and contributions are welcome.

## [pygbif](https://pygbif.readthedocs.io/en/latest/)

[GBIF] Python client. Allows exploring GBIF data (occurrences, taxonomic names, maps, datasets, ...) from Python. 

## [pyinaturalist](https://github.com/niconoe/pyinaturalist)

Read-/write Python client for the iNaturalist APIs. Used in production, but the API coverage is not complete yet (allows creating, updating, deleting and searching observations, uploading pictures, setting *observation fields*, ...).

## [python-dwca-reader](https://github.com/BelgianBiodiversityPlatform/python-dwca-reader)

A simple Python package to read and parse [Darwin Core Archive] (DwC-A) files, as produced by the [GBIF] website, the [IPT](https://www.gbif.org/fr/ipt) and many other biodiversity informatics tools.

It intends to be Pythonic and simple to use, support Darwin Core extensions, is quite stable, can deal with large archives and works on Python 2, 3 and Jython on Linux, Mac OS and Windows. 

## [rgbif]

Search and retrieve data from the Global Biodiverity Information Facilty ([GBIF]) rgbif is an [R] package to search and retrieve data from [GBIF]. [rgbif] wraps [R] code around the GBIF API to allow you to talk to GBIF from [R].

[Darwin Core Archive]: https://en.wikipedia.org/wiki/Darwin_Core_Archive
[GBIF]: https://www.gbif.org
[R]: https://www.r-project.org/
[rgbif]: https://github.com/ropensci/rgbif