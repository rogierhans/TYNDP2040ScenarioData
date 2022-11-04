# TYNDP2040ScenarioData
TYNDP2040ScenarioData

TYNDP-2020-Scenario-Datafile.xlsx contains the original capacity scenarios of the TYNDP2020 from ENTSO-E.
TYNDPGen.csv is a generator characteristics file from ENTSO-E with added generator capacity size for individual generators (ETRI 2014) and with additional ramping limits from the paper “Unit commitment constraints in long-term planning models” (Poncelet et al. 2020). 
In the folder DE_2040, GA _2030, GA_2040:
•	Demand.csv contains the base demand for every scenario provided by ENTSO-E.
•	GC.csv contains the generator capacity of each bidding zone for this scenario coming from TYNDP-2020-Scenario-Datafile.xlsx
•	Hydro.csv contains the hydro capacities from PHS open, PHS closed and STO units coming from TYNDP2020_Scenario_data_internal.xlsx.
•	NTC.csv contains the NTC capacity between bidding zones coming from TYNDP-2020-Scenario-Datafile.xlsx.  It is the “Export Capacity” from “Reference Grid”  plus the “Expanded Grid”.
•	RES.csv contains the RES capacity coming from TYNDP-2020-Scenario-Datafile.xlsx
GA_2040_1982.uc is an example UC instance of 1 weather year and 1 capacity scenario.

References:
ETRI, E. (2014). Energy technology reference indicator projections for 2010–2050. Joint research centre (JRC), European Commission (EC).174
Poncelet, K., Delarue, E., & D’haeseleer, W. (2020). Unit commitment constraints in long-term planning models: Relevance, pitfalls and the role of assumptions on flexibility. Applied Energy, 258 , 113843. Retrieved from https://www.sciencedirect.com/science/article/pii/S0306261919315302 doi:https://doi.org/10.1016/j.apenergy.2019.113843
