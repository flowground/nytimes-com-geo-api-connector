# ![LOGO](logo.png) Geographic **flow**ground Connector

## Description

A generated **flow**ground connector for the Geographic API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/nytimes.com/geo_api/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:20+03:00

## API Description

The Geographic API extends the Semantic API, using a linked data approach to enhance location concepts used in The New York Times' controlled vocabulary and data resources which combine them with the GeoNames database, an authoritative and free to use database of global geographical places, names and features.


## Authorization

Supported authorization schemes:
- API Key
## Actions

### Geographic API

*Tags:* `Events`

#### Input Parameters
* `name` - _optional_ - A displayable name for the specified place.
* `latitude` - _optional_ - The latitude of the specified place.

* `longitude` - _optional_ - The longitude of the specified place.
* `elevation` - _optional_ - The elevation of the specified place, in meters.
* `sw` - _optional_ - Along with ne, forms a bounded box using the longitude and latitude coordinates specified as the southwest corner. The search results are limited to the resulting box. Two float values, separated by a comma `latitude,longitude` <br/> The ne parameter is required to use this parameter.
* `query` - _optional_ - Search keywords to perform a text search on the fields: web_description, event_name and venue_name. 'AND' searches can be performed by wrapping query terms in quotes. If you do not specify a query, all results will be returned.

* `filter` - _optional_ - Filters search results based on the facets provided.  For more information on the values you can filter on, see Facets.

* `date_range` - _optional_ - Start date to end date in the following format- YYYY-MM-DD:YYYY-MM-DD
* `facets` - _optional_ - When facets is set to 1, a count of all facets will be included in the response.
    Possible values: 0, 1.
* `sort` - _optional_ - Sorts your results on the fields specified. <br/> `sort_value1+[asc | desc],sort_value2+[asc|desc],[...]`<br/> Appending +asc to a facet or response will sort results on that value in ascending order. Appending +desc to a facet or response  will sort results in descending order. You can sort on multiple fields. You can sort on any facet. For the list of responses you can sort on, see the Sortable Field column in the Response table. <br/><br/>If you are doing a spatial search with the ll parameter, you can also sort by the distance from the center of the search: dist+[asc | desc] <br/> **Note:** either +asc or +desc is required when using the sort parameter.

* `limit` - _optional_ - Limits the number of results returned
* `offset` - _optional_ - Sets the starting point of the result set

## License

**flow**ground :- Telekom iPaaS / nytimes-com-geo-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
