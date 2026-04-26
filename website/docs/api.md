---
title: Using the API
---

Data is made available to users via an REST API.  

## Filtering

Data can only be filtered by the city, neighborhood, or date. Any additional filtering 
of the data, will have to be done by the consumer.  See 
[Routing](#routing) for more information on how to filter based on the 
previously mentioned criteria.

## Routing

### City Example

The route 

```
/montgomery/crime.json
```

will return all of the crime data for the City of Montgomery.

```
/montgomery/2026/03/crime.json
``` 

will return the crime data for March 2026 for the City of Montgomery.

### Neighborhood Example

The route 

```
/montgomery/cloverdale/crime.json
```

will return all of the crime information for the Cloverdale neighborhood. Similar to the [City Example](#city-example), you can also filter 
by date.

