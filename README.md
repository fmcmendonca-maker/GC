Aerohub Flight Cost Calculator — Changelog v4.09 (27 Oct 2025)

New / Fixed in v4.09:

Fuel Price Input

Now visible by default instead of hidden.

Toggle functionality retained (“Change” link) for switching between base price info and editable input.

ACMI Input

Visible by default.

Fixed broken HTML in infoBaseAcmi section; “Change” link now works correctly.

Button and Layout Fixes

Corrected Query Again button inline styles.

Removed stray/misplaced text for cleaner layout.

HTML and Semantic Cleanup

Fixed broken <span>/<a> tags and invalid attributes.

Ensured proper accessibility and semantic structure.

Usability Improvements

Default inputs active on page load (useBaseFuelPrice and useDefaultAcmiRate set to false).

Toggle logic remains fully functional.

Internal Versioning

Updated footer to reflect v4.09.



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


