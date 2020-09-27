#READ ME

## Project 1

Noah Jaffe, Rahul Raju, Julia Nguyen, Barrett Williams
_____________________________________________________

### Project overview
 
- The purpose of this project was to advise the company WomenTechWomenYes (WTWY) on placement of volunteers working to attract attendees and donors for the company’s annual gala.
- To formulate these recommendations, we examined passenger traffic data from the New York City subway system, performing various EDA techniques to determine the optimal placement of WTWY volunteers.
- We were specifically interested in maximizing interaction with potential attendees by selecting subway stations with the most throughput as well as with potential donors by selecting subway stations in higher-income neighborhoods. 
Our recommendations were delivered to the client through a short presentation of our findings.

### Data sources
- MTA subway station data: http://web.mta.info/developers/turnstile.html
- MTA data key: http://web.mta.info/developers/resources/nyct/turnstile/ts_Field_Description.tx
- Income data: https://data.cccnewyork.org/data/table/66/median-incomes#66/107/40/a/a
- Map data:  https://data.cityofnewyork.us/

### Basic methodology
- General EDA was a collaborative effort between the four group members and was guided by instruction from our Metis instructors and TAs:
	- Joan Wang
	- Brian McGarry
	- Vinny Senguttuvan
	- Anterra Kennedy
- Data were analyzed using the following Python modules:
	- Pandas
	- Numpy
	- Matplotlib
	- Seaborn
- Project steps were as follows:
	- Download MTA and income datasets
	- Select time frame for MTA data
	- Clean data so that analysis could be performed
	- Visualize data by station, turnstile and passenger traffic
	- Cross-reference MTA data with income data

### Results summary
- Rationale for Mid-March through Mid-June date range:
	- Gives potential attendees significant lead time to incorporate into their schedules
	- Avoids the summer decline in commuter traffic due to extended vacations
- Station Placement & Rationale: Six stations in total
	- Grand Central:  High income, and high traffic particularly from other high income regions\
	- Penn Station, 34 St:  High traffic due to status as tri-state commuter hub
	- Herald Square, 34 St:  High traffic due to proximity to Macy’s as well as NJ commuters
	- 86th St:   High traffic, also considered one of Manhattan’s wealthiest neighborhoods
	- Union Square 14 St:  High income and high traffic due to shops, dining, cafes and a park



