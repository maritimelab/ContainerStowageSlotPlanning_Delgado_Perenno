The instances whose name starts by Instance are the instances used in the paper:

Delgado, A,. Jensen, R.M, Janstrup, K., Rose, T.H, Andersen, K.H.: A constraint
programming model for fast optimal stowage of container vessel bays,European
Journal of Operational Research, 220(1),251–261, (2012)

The 476 instances are those used in:

Grasp for the slot planning problem
Francisco Parreño*, Dario Pacino+, and Ramón Alvarez-Valdés

In each sentence you can read:


//In the first line:
#POD #conToLoad #contLoaded #stacks #cells  #locations #tiers

//#POD number of discharge ports
//#conToLoad number of containers to load
//#contLoaded number of container already loaded
//#stacks number of stacks
//#cells number of cells
//#locations number of locations (always 1)
//#tiers number of tiers

//Line
#LOCATIONS
IDLoaction

//Line of PODs 
#PODS
Possibledischargeports

//An integer of the different discharge ports

//Each line of container already loaded and to load
#CONTAINERS_TOLOAD
#CONTAINER_LOADED

IDstack IDcell IDfor Weight Height Length DischargePort Refer IdLocation IMOcategory


	
//Each line of stack 
#STACKS
MaxWeight MaxHeight Idlocation

//Each line of cells 
#CELLS
IDcell ForeReefer AftReefer ForeFeasible AftFeasible 40Feasible IdLocation

//Weight and Height has two decimals.
//Reefer 1 is TRUE 0 FALSE

