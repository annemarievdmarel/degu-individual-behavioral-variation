Code and data for the manuscript titled "Individual behavioral variation does not affect social organization or reproductive success in a cooperative small mammal"

DESCRIPTION We studied the common degu, Octodon degus, a social and group-living rodent, to evaluate whether individual behavioral variation affects i) 
the composition of social groups, and ii) the reproductive success of individuals in groups. 
We identified several social groups in a population in central-north Chile, tested adults in an open field and poke test to quantify individual behavioral variation, 
determined assortment based on individual behavioral differences across social groups, and performed genetic analyses.

CITATION
DOI: 10.5281/zenodo.8156905 
License: CC0

METADATA
We included the code in the Rmarkdown file titled "Rmd_degu_personality_v1.3.Rmd"

The data files can be found in the data folder. 

PokeTestOnlyAll1.csv
- date = date of poke test trial
- id	= unique identifier of adult degu
- obs = trial number
- capture	= number of capture
- burrow = at which burrow the degus was captured
- sex = male or female
- mass	= mass at capture
- poke = binomial poke response (0 = no response, 1 = response)

open_field_test.csv
- trial = total number of trials performed
- date = date of open field test trial
- ID = unique identifier of degu
- video = trial number
- group = unique identifier to which group the degu belonged
- age = age of degu (adult or pup)
- sex = male or female
- weight = mass at capture
- hide_placement	= at which side of the arena the hide was placed
- hide = at which side of the arena the hide was placed
- distance_moved	= total distance moved in arena in cm,
- mean_velocity = average speed the degu was moving during trial
- time_moving_s	= total time spent moving in arena
- time_notmoving_s	= total time spent not moving in arena
- entry_number_arena	= how many times the degu entered the arena from the hide
- time_in_arena = total time spent in arena
- latency_hide = how many seconds it took the degu to leave the arena and enter the arena

  
parentage.csv
- OffspringID	= unique identifier of offsrping
- first_weight_offspring	= mass measured first time capturing
- motherID	= unique identifier of mother
- mother_groupID = to which social group the mother belonged
- fatherID	= unique identifier of father
- father_groupID = to which social group the father belonged


socialgroups2017.csv
- groupID	= identifier of the social group
- ID	= identifier of degu
- sex = male or female



 

