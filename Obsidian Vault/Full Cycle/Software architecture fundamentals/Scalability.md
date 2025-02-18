> _Capacity of the system to support growth of workloads, for a higher or lower price cost_


Types being of [[Computational power]]
- #Vertical_scale 
	- One centralized server scales
- #Horizontal_scale 
	- Aims to decentralize
		- Disk needs to be ephemeral ( data could be lost )
		- Apps servers and Assets servers ( provides static files )
		- Centralized cache on specific cache server
		- Centralized sessions on specific session server
		- Improves throughput
- For #Databases_scale
	- Distribute read and write on different db's
	- Can be scaled onto horizontal scale 
	- Serveless ( cloud )
	- Optimizations and telemetry, APM on queries
	- Indexes
	- CQRS READ and WRITE 
	