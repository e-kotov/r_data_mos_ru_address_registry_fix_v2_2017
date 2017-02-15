# r_data_mos_ru_address_registry_fix_v2_2017
Script and tutorial for extracting spatial data from Excel spreadsheet cells with non-standard text format for spatial data

A little more than a year ago I made a post on fixing the non-compliant JSON/GeoJSON files from data.mos.ru. Brief recap: the JSON/GeoJSON files with building polygons were not compliant with the standard, so they could not be read by default by software that expects standard JSON/GeoJSON. So back then I wrote a parser to fix the data and convert it to CSV with WKT encoded geometry in order to be able to load it into QGIS (or indeed any other GIS).
For a rather long period of time there were no issues and the data set was even fixed on the supplier side. But another problem struck in December 2016. The data was not updated any more. It seemed like a server-side issue, where new data set could not be properly pre-exported into a downloadable CSV/XLSX/JSON/XML file and API returned nothing.

also see the blogpost at http://ekotov.blogspot.com/2017/02/fixing-open-data-with-r-case-of-moscow.html
