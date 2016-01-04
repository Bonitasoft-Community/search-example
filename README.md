# search-example
An example to demonstrate how to create a search form to search in business data

# Known limitations
As soon as user type in the search input, a REST request to query BDM is sent.
Such approach might create an unnecessary load on the server.

A more efficient alternative would be to create a custom "search button" widget.

Note that "button" widget in Bonita BPM 7.0 - 7.1 does not support GET operation and so cannot be used to implement such feature.
