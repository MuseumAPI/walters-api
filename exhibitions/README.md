Walters Art Museum Collections API 
===============================================================================

## Exhibitions 

An exhibition is an organized presentation and display of a selection of museum objects. Exhibitions occur within the Walters Art Museum, but can also be held at other museums, galleries, etc. For each exhibition, the associated museum objects listed will be from the Walters collection. Although exhibitions frequently include objects from other institutions, those are not listed by the API. In addition to this API, [exhibition catalog publications and other museum publications](http://www.worldcat.org/search?q=au%3AWalters+Art+Museum+%28Baltimore%2C+Md.%29&qt=hot_author) are also useful resources for studying Walters' exhibitions.


## Requests

There are 2 requests you can use to get museum collections:
- [GET v1/exhibitions](exhibitions-get.md) Get museum objects via a number of parameters.
- [GET v1/exhibitions/{id}/objects](exhibitions-objects.md) Get museum objects that are/were featured within an exhibition by referencing an exhibition id.

