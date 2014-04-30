distance_map
============

This one-page web application takes in a list of employees and a list of employers and
calculates commute time to each potential employer. 

It is designed to be run from your local computer, requires a mapquest
developer key, and properly formatted formatted files which can be uploaded
using the ajax interface.

It will geo-code all you addresses, then create an interactive map with everyone displayed.
To reduce requests, it also takes advantage of browser side data storage when possible.

Detailed information for each commute is also displayed in a sortable table.

The table includes, commute time, commute distance and estimated fuel use for each scenario.
