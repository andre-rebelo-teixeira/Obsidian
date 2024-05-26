## Event
Adding events to the PEC -> priority queue based on the time the event will be fulfilled. This for starter event, Then add the event based on this

Discover how do we decide the time the event will be fulfilled


## Todo list
- [x] Test if the generating random distrubutions of patrols works or not 
- [x] Finish the Event Package and start testing it with hard coded event list
- [x] Create an interface to have and extermination event
- [x] Move reproduction mutation and kill event out of the event package
> This is done since the event package gives us a Generic interface, our event are external to the package can can be create without having to change anything inside the Event package. As long as they are compliant the Generic Event definition. This way the event PEC can still handle them

- [x] Finish the observer in Individual <-> patrol  
- [x] Finish Getting string from the node
- [x] Initialize Priority of individuals
- [x] Seems like the reproduction is not changing the ID of the nodes
- [x] Epidemics are killing everyone
- [x] Clonning of the object is not really clonning, just changing the name 
> Need to create constructors for Patrol, individual, planetary system


## Test to confirm
- [ ] Use predefined test to confirm stuff work -> full application
- [ ] Test Event with only 1 individual and one event to make sure they are doing what they should 
	- [ ] Reproduction Event 
		> Should only create a new individual with a different distributions where the number of changes are specified, and the ID is different
		- [ ] Correct number of changes
		- [ ] Correct ID
	- [ ] Mutation Event
		> Should change the distributuion of the current individual in only one way

	- [ ] Death
		 > Should be kill the Invidual

- [ ] Make sure prints are as they should be
- [ ] Make sure Java doc commenting style exist for all the functions necessary
- [ ] Make sure the observer between individuals <=> population works as it should 
	> A simple print should do the trick to verify it works
- [ ] Check Event counter

## Finish Touches 
- [ ] Create Java docs documentation for all the packages in the code
- [ ] Generate UML for all the packages
- [ ] Generate Test