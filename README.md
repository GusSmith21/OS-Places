#OS Places API Demos

This repo contains working examples of how to use the Ordnance Survey Places API, a RESTful API based on the [OS AddressBase Premium](https://www.ordnancesurvey.co.uk/business-and-government/products/addressbase-premium.html) datasets. The API returns queries to the service in either XML or JSON, and through a ['find'](https://apidocs.os.uk/docs/os-places-find) resource enables rapid searches of AddressBase Premium to drill down and isolate ambiguous addressing details. The ['match'](https://apidocs.os.uk/docs/os-places-match) resource is for more granular matching and cleansing of existing address databases. Neither features needs any database management of AddressBase Premium. ['Postcode'](https://apidocs.os.uk/docs/os-places-match) searches need the area and district integers as a minimum. There are JavaScript examples using [Leaflet](http://leafletjs.com/) and [typeahead.js](https://twitter.github.io/typeahead.js/), as well as an example of making calls to the API in Python 3.0.

Register for an API key of OS Places API [here](https://developer.ordnancesurvey.co.uk/user/register).

Full documentation for the OS Places API can be found [here](https://apidocs.os.uk/docs/os-places-overview), while service terms for OS Places API can be found [here](https://developer.ordnancesurvey.co.uk/sites/default/files/OS_Places_v2-1.pdf).

##AddressBase Premium

AddressBase Premium provides the most detailed view of an address and its life cycle. It has more records than other AddressBase products as it provides all the information relating to an address or property from creation to retirement.
It contains local authority, Ordnance Survey and Royal Mail® addresses, current addresses, and alternatives for current addresses, provisional addresses (such as planning developments) and historic information, plus OWPAs and cross references to the OS MasterMap® TOIDs®.

AddressBase Premium is made up of -

•	Up to date cross references to our large-scale data, such as OS MasterMap Topography Layer and Integrated Transport Network Layer via the TOID – but also references to objects that don’t have postal addresses, as well as coordinates that have been verified via our surveyors.
•	Data from the Local Land and Property Gazetteer and One Scotland Gazetteer, which includes information captured under statutory obligation through the SNN process.
•	The Royal Mail’s data, providing a Postcode Address File (PAF) containing the UDPRN and the delivery point address record.
•	The Valuation Office Agency (VOA), which provides cross references to council tax and non-domestic rates data.
Our specification will extend the Infrastructure for Spatial Information in the European Community (INSPIRE) Geographical Names theme to ensure it’s compliant with European open data initiatives.

##License

These demos are released under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html)

