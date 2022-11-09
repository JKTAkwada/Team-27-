# Team-27-
 Retail Trade Area Analysis


Description/Overview:

-	Retail trade area analysis is the process of locating and describing the target market for physical locations. This enables users to answer questions about consumer spatial behavior, delineating trade areas, determining site suitability, analyzing market performance, simulating different market scenarios and forecasting sales.
-	Select a city in South Africa you would like to target as a start.

Deliverables:

-	Implement a workflow for defining retail trade areas (a first version could focus on some version of the Huff Model e.g. see this simple interactive example https://gis.jackforsyth.com/).
-	The team can determine details about their data such as the study area to use and type of retail store to consider.
-	It would be useful to show how the solution enables a user to answer a specific business question, for example if a competitor opens a store at location X with properties Y+Z, how does it impact the trade areas of our nearby stores.
-	Written report of the Project, Jupyter notebook containing the codes, Powerpoint presentation of findings
-	Recommended next steps for this project
Data Source:
-	Suggested proof of concept on RSA data for a selected city:
-	road network - Open Street Map - used for calculating distances along the road or we could use a routing API like https://openrouteservice.org/ or even Google’s API
-	census data (linked to enumeration polygons) - StatsSA
Use-Case and things to think about:
-	Development of a set of tooling that enables interactive retail trade area analysis that we can market as a solution for businesses
-	A user should be able to enter data that represents the following:
-	competitors or existing store locations
-	potential store locations to evaluate
-	a measurement of attractiveness per store (e.g. store size)
-	sales potential (socio-demographic data - typically derived from census data)
-	distance decay function (often the perception of distance to a store is a non-linear deterrent of movement)
-	maximum expected travel distance (used in calculating distance along road networks to the centroids of the polygon census data)
-	The output that the user can then interrogate represents predicted catchment areas per store which indicates expected market share of all stores included in the analysis.
-	With anonymised trip data derived from sources such as cell phone tower data the analysis could be extended to also include a time component. This could present an opportunity to partner with a telco to make future iterations of the analysis more detailed.
-	Here’s a simple step-by-step example to illustrate the basic concept: https://gis.jackforsyth.com/
Things to think about and look out for:
-	How can you frame what the solution could look like to add tangible business value?
-	Ensuring what is developed clearly answers critical business questions
-	Summarize findings for EXPLORE data scientists and clients (potential workshop)
To get more info:
○	https://en.wikipedia.org/wiki/Reilly's_law_of_retail_gravitation
○	https://en.wikipedia.org/wiki/Huff_model
NB: 
-	If you need access to the cloud (AWS), please let me know :)

