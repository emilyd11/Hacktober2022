# Hacktober2022

GAME BACKSTORY: 
The year is 2032. Welcome to Pleasantville. This idyllic little town was founded ten years
ago, and became the headquarters of Kohlenstoff Inc., growing quickly into a sprawling
metropolis. But now the city is facing a crisis. Pollution is skyrocketing, residents are getting sick
and moving out, and the government is cracking down on Pleasantville due to the new
environmental policies. Kohlenstoff has no interest in changing their policies, however.
You have just been elected Mayor of Pleasantville. Your work is cut out for you. There’s
only one problem.... Kohlenstoff doesn’t want to leave.

GAME STATS/ORGANIZATION: 

Goal: Clean up the city. 

UI DESIGN PLAN: 
Isometric tilemap
Basic Unity
UI design - allow users to select the buildings and see their building scores

How is pollution measured?/Stats for succeeding in the game:

AQI - air quality index - measures the air pollution level. Starts with randomly generated value between 151 and 200 - this corresponds to red - unhealthy. Goal is to get this value to 50 or lower (this corresponds to green - good air quality). 

Fix this by planting trees. Or building air purifiers but they cost energy to use

Amount of oil in the water - Ppm - starts at 50 ppm. Goal is to get it down to 0. 

Fix this with water purification plants 

Percent of energy from fossil fuels starts at 100% because fossil fuel plant is providing all the power - goal is to get it to 0% 
The percentage can be amount produced by nonrenewable/total energy required for the whole city
Then each building can have an amount produced or an amount required
And if they’re producing energy it needs to be classified as renewable or nonrenewable

Fix this by installing wind turbines/solar panels 

Buildings:

What buildings does the player start with:
Fossil fuels power plant
Three blocks of apartments 
Three mansions
River
Roads

Stats for housing buildings;
Apartment:
Amount of energy required per minute:
Initial Cost:
Money produced per minute:
Mansion:
Amount of energy required per minute:
Initial Cost:
Money produced per minute:
Cottage:
Amount of energy required per minute:
Initial Cost:
Money produced per minute:
Townhouse/Condo:
Amount of energy required per minute:
Initial Cost:
Money produced per minute:

Stats for Energy Production buildings:
The main enemy oil energy producing building:
Amount of energy produced per minute (must be enough to sustain the initial city of three mansions and three apartment blocks)
Amount of oil in water produced per minute:
Amount of air pollution produced per minute:
nonrenewable
Solar farm
    -initial cost
Amount of energy produced per minute
renewable
Wind turbine
-initial cost
-amount of energy produced per minute
-renewable

In real life, wind turbines are more efficient than solar panels, but also more expensive, so our stats should reflect this - we will have the solar panels be cheaper but produce less energy than the wind turbines

Stats for pollution decreasing buildings:
Water purification plant - 
-initial cost
     - ppm of oil in water decrease per minute
-energy required 
Air purifier 
    -initial cost
AQI decrease per minute - better than tree, but this requires energy and trees don’t 
Energy required
Tree
-initial cost
-AQI decrease per minute


