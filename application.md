Finec Team ("Final Crew") submission 
====================================

We are a collaborative team, anchored at MGIMO Finance and Economics Department in Odintsovo, Russia. The team is led by Evgeniy Pogrebnyak, FinEc-MGIMO dean, formerly a leader for macroeconomic analysis at a national development bank - VEB. Sergey Korolev is a young data scientist at Sberbank St Petersburg and a member of ‘Ostrov-2035’ learning network. Also from St Petersburg – Maria Markueva, a risk management and data modelling professional, who will be teaching at European University in St Petersburg starting this fall. Maria is qualified as a yacht crew member and passionate about sailing in the Baltic Sea. She is a hands-on user of AIS via MarineTraffic.
Two MGIMO students volunteered for the project – Timur Alikhodjaev, from MGIMO Tashkent campus (Uzbekistan) and Artem Reva, from our linguistics bachelor program.
Our team analyzed the possible uses of this AIS information and identified the following research opportunities:

1. We can design a family of "ports and straits" indices for transport activity monitoring, including COVID lockdowns/traffic demand downturn in 2020.
We hope to calculate the number and total tonnage of ship arrivals and departures per day and a similar indicator for vessel crossings of key straights/channels area (eg gross transit volume per day in Suez Canal, Cape Agulhas in South Africa and similar). Port locations can be pre-defined or derived by clustering stops.
There might be a difference in transport activity by type of location – diversified 'hub' ports will be less affected by economic downturn compared to 'sourcing' ports where energy or agro commodities originate.

2. Route information will supplement our arrival-departure analysis:
- calculate gross tonnage of ships in transit between most common or most reflective start-destination ports, contrast with port activity index above
- look at scope and causes of deviations from optimal or most commonly used routes between ports
- compare Arctic shipping route from Europe to Asia with traditional alternatives (travel time, window and modes of operation, development of ports along the route).

3. There are highly meaningful tasks that we want to explore, but fear lack of necessary data:
- Do we see accidents in the data? Can we assess factors that were common for the accidents? Can we predict or prevent marine accidents? What factors should insurers account for from AIS dataset?
- Ships account for over 18% of air pollution, so we are interested to analyze vessel emissions around the world. Beyond that, we can try to assess the impact of ships on marine animals.

4. There are a few a tasks that seem fun to work on, yet have no immediate impact. The dataset will likely to have ship names, flag, may be year of construction. From social studies, we know giving names to children follows patterns and cycles, maybe ship names do too? Such task can be an entertaining exercise for “breaking the ice” for first-time uses of dataset and non-maritime specialists. On a more serious note, we can dig into patterns of vessel ownership and ship secondary market activity if data permits.

5. We see a special task in lowering a barrier for AIS data usage for beginners and students. Under this part of work we can develop:

- open source codebook for AIS data access
- set of composable utilities for AIS data transformation (proposed by A.Reva)
- API proposals/prototypes for more convenient data access
- document skill and knowledge gaps that can be addressed through learning programs
- micro-exercises and building blocks of working with AIS and similar data
- a sample of easily generated visualizations (with higher overall visual effect per line of code per chart)

While looking at opportunities we also see a few risks for the team, but hope to manage them:

- too much time on data cleaning, slow to test the actual ideas
- not enough programming competences and team communication skills
- lack of domain-specific knowledge in maritime business 
- dispersion of effort between many tasks
- no actionable results after analysis is done
- discontinuity in access to data, research results not reproducible after hackathon.
