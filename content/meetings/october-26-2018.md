+++
title = "October 26 2018"

date = 2018-12-05T13:51:56-08:00
# lastmod = 2018-09-09T00:00:00

draft = false  # Is this a draft? true/false
toc = true  # Show table of contents? true/false
type = "docs"  # Do not modify.

# Add menu entry to sidebar.
linktitle = "October 26 2018"
[menu.meetings]
  parent = "Meeting Notes"
  weight = 3
+++

**Bay Delta In-person Meeting October 26, 2018**

**Participants**
 
Jim Peterson, 
Erin McCreless, 
Darcy Austin, 
Denise Reed, 
Jim Hobbs, 
Mike Hendrick, 
Sam Luoma, 
Scott Hamilton, 
Mike Beakes, 
Corey Phillis, 
Ben Geske, 
Kevin Clark, 
Matt Reeve, 
Brad Cavallo, 
Emanuel Rodriguez, 
Mike Urkov, 
JD Wikert, 
Shawn Acuna, 
Lauren Adams, 
Javier Miranda, 
Anke Mueller-Solger, 
Rod Wittler, 
Steve Zeug, 
Javier Miranda, 
Rene Henery, 
Gabrielle Boisrame, 
Denise Reed, 
Josh Israel
 
**Scheduling notes**

Conference call November 9, 9-11am

No November or December in-person meetings.

Conference calls Nov. 30, Dec. 14, and Jan. 11.

In-person meeting Jan. 25

Updates from Ben on flood risk and ag revenue

Flood risk

- Ben has talked to Erin Mullin at Delta Science Council, who has been involved with the Delta Levee Investment Strategy. She provided background about what the DLIS tool has been used for.
- We may be able to use DLIS tools and approaches (R code, Access database) for quantifying flood risk and visualizing results for this project.
- In the coming weeks we will set up a meeting with Erin Mullin and FlowWest to discuss the possibility of modifying the DLIS approach for the metrics being considered in the SDM project. We will update the group in one of the upcoming conference calls and get feedback on whether people think this is a good approach to addressing flood risk for our purposes.

Ag revenue

- We have identified tools we can use, but time constraints may prevent us from including ag revenue in this phase of the project
- We will keep working on this; if the approaches are straightforward, we will try to include in rapid prototyping. If it&#39;s too involved and time-consuming, we won&#39;t include in rapid prototyping but will keep working on it and making progress so it can be incorporated in future stages.
- We will schedule meetings with the ag revenue subgroup and FlowWest to discuss next steps, and will update the group in a future conference call.

Water availability – CalSim updates from Lauren Adams (BOR) (See attached file &quot;OMR\_Studyv5.pdf&quot; for figures and summaries)

- Four scenarios have been completed in CalSim: X2 74 km May-June, 81 km July-Aug; X2 81 km May-Aug; OMR flows no more negative than -1250cfs; OMR flows no more negative than -5000
- Lauren presented the results of the OMR simulations for Delta outflow, south of delta exports, reservoir storage, and OMR flows
- CalSim is a hypothetical projection based on historic conditions in the system
- Figures 1-2 show how each scenario would change Delta outflow relative to the baseline. The baseline uses current regulations and applies them to the historical system – 82 years of hydrology, land use, population, etc.
- Figure 2 shows that Delta outflow would be higher with the more stringent -1250 scenario and lower with the -5000 scenario
- Figure 4 shows that SOD exports would be higher under the -5000 scenario and lower under the -1250 scenario
- The next step is to feed these results into the Chinook models to assess the impacts of these actions on fish

Water quality

- May not be able to include fingerprinting and residence time in this phase of the project due to time constraints, as calculating these in CalSim/DSM2 is tricky
- Will query CEDEN database for contaminant loads in major tributaries and calculate relative input to San Joaquin and Sacramento Rivers based on the flow from each trib

Chinook models - Routing

- North Delta
- Yolo entrainment, Sutter/Steamboat, Delta Cross Channel (open/closed), and Georgiana Slough ~ _f_(discharge at Freeport)
- South Delta
- Head of Old River ~ _f_(physical barrier, discharge at Vernalis)
- Turner Cut ~ _f_(discharge at Stockton)
- SWP entrainment ~ _f_(exports)
- CVP entrainment ~ _f_(pumps operating)

Chinook models – Survival – region-specific

- North Delta ~ _f_(discharge at Freeport, DCC open, FL)
- South Delta ~ _f_(discharge and temperature at Vernalis)
- CVP ~ _f_(number of pumps operating)
- SWP ~ constant

Modifications for some Chinook scenarios

Scenario: Install bioacoustic fish fence, floating fish guidance structure, and infrasound fish fence at Steamboat and Sutter Sloughs to divert outmigrating salmon into Sutter and Steamboat Slough

_Unresolved issue: % entrained?_

- Depends on type and orientation of barrier
- Barrier would be less effective at Sutter/Steamboat because it would force fish to move at a right angle. A barrier at Georgiana Slough would be more effective.
- Agreement that a range of 5-10% entrainment seems reasonable.

Scenario: introduce sediment into the Sacramento River to increase turbidity Jan-May (for salmon)

_Unresolved issue: how much and where?_

- Increase turbidity 10 NTU Red Bluff to Freeport (upper mid Sac) – can evaluate and vary this with sensitivity analysis
- Question: is this action actually feasible? Would we need the water quality control board to approve it? Comment: We shouldn&#39;t rule this action out at this stage; should model it to see what the effect would be.
- Need to consider type(s) of turbidity that would be added.
- Would probably need to inject sediments in several different places.

Scenario: Trap juvenile salmonids upstream HOR, transport to western Delta (Dec-May). Trap fish above Vernalis in Dry and below normal years

_Unresolved issue: Need % trapped, where returned, survival during transport_

- Brad suggests doing this in the San Joaquin; 50% of fish trapped; 90% survival. Can choose a location for returning into western Delta based on how the regions are defined.
- Rene: It&#39;s hard to do this in the Central Valley. Some issues: debris can affect trapping; there are size-specific differences in trapping efficiency; there can be a lot of predation in and around traps. Estimating 50% of fish trapped may be a good starting point but there is probably a lot of variability.
- Also need to think about survival at ocean entry. Transport affects survival to adulthood in many ways – the size and structure of the outmigrating cohort, the size of trapped individuals, rearing time in the Delta. Can probably make some assumptions to include these factors in modeling, but there will be a high degree of uncertainty.
- Jim: What about adding differential survival for released fish relative to fish that make it there on their own?
- Rene: maybe could apply size-specific mortality percentage for different size classes, then apply size- and timing-specific ocean survival criteria for those that make it
- Keep in mind that this would be a work-intensive and expensive project. We should look into how it worked in the San Joaquin; ask Don Ports (?) about this.
- JD: In the San Joaquin, during dry years water hyacinth can reduce the ability to trap/sample juvenile fish, so trapping may only be possible in wet years
- For estimating the % trapped, in the rapid prototyping phase we should just test a wide range of values and see how much it matters. If it doesn&#39;t matter much, we won&#39;t need to invest more time in studying it.
- In some cases, even if many fish (e.g. 50%) are trapped, only 1-2% make it to the ocean
- Need to consider not just how many fish get to Chipps Island, but also how well they&#39;ll be able to survive in the ocean. Smaller fish may have lower survival. Ultimately what matters is the number of adults returning.
- Something to consider in future stages of modeling is the possibility of holding and feeding fish
- Jim: Rather than doing the action from Dec-May, could consider just doing some months. JD suggests February and April.

Delta smelt

Modifications to the Rose/Smith model

- Rose/Smith model has incomplete life cycle (June-Jan), no spawning or recruitment mechanisms, monthly time step
- Modifications:
- Adding spawning in Feb-March – ~50% spawning Feb, 50% March (averages from SKT)
- Identifying spawning regions – upper Sac, lower Sac/SJ, Suisun Marsh
- Fecundity based on body size (Bennett 2005)
- Egg-postlarvae (Rose et al.) – post larvae size 15 mm
- Post-larvae April-May distribution based on 20 mm survey occupancy models (Peterson and Barajas)
- June-Jan dynamics – Smith modification

Unresolved issue: How to quantify habitat in the South Delta

- In the SIT, Mark Tompkins looked at habitat per unit area in the North Delta, then applied that value to the South Delta. We could try this, but they may not be equivalent.
- The South Delta gets warmer, this may be an issue
- Could compare levees in the North vs. South Delta (is there a GIS layer for this?)
- Water clarity is important to consider
- South Delta tends to have more flooded island habitat

Spawning

- Scott Hamilton&#39;s model doesn&#39;t break down spawning by region, so the modified Rose/Smith model is a good complement to his
- Scott: beach seine data suggest that fish move out of channels and into spawning habitat in April-May. Scott can make graphs of this.
- Shawn: could we have variable spawning based on temperature? e.g., the 2011 class may have benefited from colder temperatures; spawning occurred in April. Jim: we can do this if there are data to guide it. Shawn suggests looking at the Kodiak trawl data, and considering April for spawning if temperatures are in the right range (12-20C).
- Bennett used a 12-20 degree spawning window; Scott H used monthly spawning window that was based on daily temps
- In wet years, fish may migrate and be ready to spawn based on cold temperatures, but not in dry years.

Modifications for some Delta smelt scenarios

Scenario: Augment flow in the Yolo Bypass by closing Knights Landing Outfall Gates and route water from Colusa Basin into Yolo Bypass. Pulse flow (300 to 500 cfs) through the Yolo Bypass in July and September

_Modification:_ Estimate increase in primary production, proportionally increase zooplankton abundance in region of influence

Scenario: Conservation hatchery for Delta Smelt - add adults Nov

_Modifications:_

- Add adults proportionally to the regions where they tend to congregate based on FMWT
- Survival of stocked individuals 0.75 of naturally produced fish for 1 time step (month) then equal (sensitivity analysis will evaluate)
- Scott suggests adding adults to regions with higher turbidity; food supply is also important. Could use survey data to identify regions with high turbidity and food, then add fish there.
- Question: how would this action actually be done? It would likely be based on similar actions for other species. Studies are being planned to figure this out.
- Question: Would adding adults in November inflate the FMWT index? If so, would it be better to add eggs instead? This would be an argument for clipping fins (though this may be too stressful for fish). For now let&#39;s assume added fish would be identifiable, and details can be worked out later.

Scenario: Conservation hatchery for Delta Smelt - add fertilized eggs

_Modifications_:

- Add all eggs Feb to regions proportionally based on SKT catch Feb/March (for Rose/Smith model)
- Scott&#39;s model is regional for food but not for recruitment, so in his model this would be an increase in overall recruitment
- Egg-postlarvae survival/development 75% of naturally produced eggs (sensitivity analysis will evaluate)
- Suggestion to add eggs where mature fish are found. But, this could be problematic because fish are still staging.
- Generally focus on Cache, Deepwater Ship Channel, Suisun near Decker Island
- Need to consider what life stage is most important to propagate/release
- We expect there would be a difference in performance between propagated and wild fish
- For egg mats, it&#39;s important to add a protective barrier to keep silversides out until eggs have hatched; this would increase survival to hatching and growth

Using DSM2 output in Delta smelt models

- Scott can use the raw DSM2 data in his model
- In the Rose/Smith model we will summarize values by region, then treat each region as homogenous

Data visualization

- For Chinook, could map each routing spot and indicate survival at each point.
- Could map food distribution and habitat availability throughout the Delta. Could also map the difference between habitat needed and habitat available.
- Food data for Delta smelt goes back to 1972; Scott&#39;s model starts in 1975.
- A good timescale for the visualizations would be the most recent 20 years. We may also want to model the next 20 years to account for climate change. It&#39;s important to illustrate a period that includes both wet and dry years. It might be good to focus on a time series of post-clam invasion (post-1988).
- We need to narrow down results and relationships to the few that are most important and can be easily understood, to avoid overwhelming people.
- The group wants to visualize baseline operations (e.g., water flows) and then translate these into outcomes for outcomes of interest (Chinook routing and survival, Delta smelt, etc.)
- End users will also want to see costs
- We could create an interactive tool that allows people to change one factor at a time, to see how each factor changes outcomes. Also include text descriptions of each action. This will especially help people who are new to the process.
- We want to be able to visualize tradeoffs, e.g., for different species.
- Managers will want to know not just the effects of a single action, but also the synergistic effects of many scenarios run simultaneously.

Grading models

- One thing to consider in models is the opportunity to learn. We should identify parameters that are guesses vs. those based on solid data; this will identify learning opportunities.
- Mike B suggests transforming confidence metrics into a continuous rather than categorical framework.
- How to manage situations where people have different opinions or confidence levels in the models? Jim says there are rarely big disagreements. JD suggests that experts can provide guidance in these situations.
- We can do what was done in the SIT – create a table with attributes that affect model grades. Rod has used this kind of table to explain the process to decision makers. Some of these attributes would require a short statement about what it is and how it would be achieved.
- Relative confidence in the model (empirical basis)
- Improvement
- Future action
- Opportunity to learn or improve
- Degree of influence
- Improvement and opportunity to learn are used to track progress, rather than to demonstrate confidence in the model, data, or results

The ranking criteria used in DRERIP might be a good starting place:

_High_

Recent (i.e., within the last 10 years) and robust (e.g., multiple years spanning wet and dry conditions) agency data on the system for the stressor/variable of interest; or More than one peer-reviewed paper of conditions on the system from within the last 20 years generally support the score.

_Medium_

There are agency data on the system for the stressor/variable of interest, but the data are not as recent and/or not as abundant/robust as described for the high score; or One peer-reviewed paper from the scientific literature and/or grey literature reports on the system from multiple disparate sources (i.e., different projects, not periodic interim reports from the same project) from within the last 20 years generally support the score.

_Low_

No recent or robust data are available and score is supported by one scientific grey literature report on the system from within the last 20 years.

- The group generally agreed with these definitions.

- Josh is concerned about using agency data that hasn&#39;t been published. Maybe we should modify our definitions to say &quot;publicly available&quot; agency data. JD said that DRERIP used data from CDEC and other publicly available sources. There&#39;s a lot of data in CDEC, but it&#39;s not always quality controlled. Can we define a ground-truthing or validation process that would make agency data more robust for our purposes? One approach is to check the metadata to see when the data were collected, by whom, and for what purpose. Using only published data, which is different than publicly available, might also be a good approach. In general it is important to capture data quality when assessing confidence.
- If no data are available, this should also factor into the confidence level.
- We&#39;re interested in both the quality of data going into a model, and the quality of the model itself
- How do we decide what is the best information available? For example, DSM2 doesn&#39;t perform well against observed data, but it is probably the best available. The best available data isn&#39;t necessarily high quality. We need to be transparent about how decisions were made related to data quality.
- The DRERIP criteria for high confidence are 10 years of data and 20 years of publications. However, the appropriate timeframe of data will depend on the parameter; for example, fecundity doesn&#39;t need to be measured every year. We can take this into account in our process and explain in the text why we made certain decisions.
- Shawn suggests a weighted evidence approach. For each parameter that goes into a model, we could use multiple lines of criteria to describe what defines a robust measurement, then sum the different criteria to get a measure of overall robustness for that parameter. However, this scoring/weighting process might be too much to include in rapid prototyping.
- The goal is to communicate to users how believable the models are. For example, models based mostly on expert opinion will be less believable than those based on high quality empirical data.