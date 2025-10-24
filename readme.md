
this is an experiment, not to be useed for any live or real scenario
All the values are a very crude apèroximation to real numbers


The work done so far on the HTML flight cost calculator routine includes:

    Developed a multi-leg flight cost calculator that calculates distances, flight time, block time, fuel burn/cost, and ACMI costs using an external JSON file for aircraft data.

    Included a comprehensive JSON aircraft data file containing all major commercial aircraft with key parameters (cruise speed, max range, fuel burn rates, ACMI hourly rates).

    Added input validation for aircraft codes ensuring 3-4 uppercase alphanumeric characters matching the loaded aircraft data.

    Implemented fetching airport distances via Airport Gap API and mapping the route visually using Leaflet.

    Provided toggles to use fixed base fuel price (from IATA fuel price monitor) or user-entered values, and similarly for ACMI hourly rates.

    Identified and addressed common issues with loading external JSON files

    All other variable costs are next steps that are still not implemented 
    
At this stage, there is a modular modular HTML/JS app structure focusing on flight cost parameters derived from external aircraft JSON data with validation and route visualization. Next steps include:


methodology next implementations costs 

V0  Distance calculator             Airport API 
V1  ACMI                            40–50%	Covers basic operating capability
                                    based on very crude oindustri averages
V2  Fuel	                        25–35%	Varies heavily with distance & price of Jet A-1
                                    Iatan fuel monitor - to be updated with more real market numbers
V3  Use of separate files for integration with othre apps 
V4  Airport & Navigation Fees	    10–15%	Includes landing + overflight charges
V5  Ground Handling / Catering	    5–10%	Depends on airport & service level
V6  Crew Hotels / Travel	        2–5%	If multi-day or long-haul
V7  Miscellaneous               	1–3%	Variable


