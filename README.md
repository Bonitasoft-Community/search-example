# Search form
An example to demonstrate how to create a search form to search in business data.

Process definition does not include an instantiation form.
After you click on Studio "Run" button, you will need to go to "Task" menu in the Portal in order to access the pending task and associated "search form".

In the form type "test" (without quotes) to get two results, type "first" to get only one result.

Note that the REST API call result (raw JSON) is displayed below submit button.


## Known limitations
As soon as user type in the search input, a REST request to query BDM is sent.
Such approach might create an unnecessary load on the server.
A more efficient alternative would be to create a custom "search button" widget.

Default search value is empty and so no match is reported by default.

Also implementation is case sensitive.

Business Data Model (BDM) has not been optimized with indexes.

Note that "button" widget in Bonita BPM 7.0 - 7.1 does not support GET operation and so cannot be used to implement such feature.

## Compatibility
Example has been create and build using Bonita BPM 7.1.5 Community Edition.
It should be compatible with version 7.1.5 or higher as well as with Subscription Edition.

## Issues
Please report issues and feature requests using GitHub issue tracker.
