# Adventure:

Create an adventure game for web.

## Backend

Record the adventure in a database as a series of 'rooms'.
Each room has:
	* A description
	* A list of exits, not given a description unless in the room description.
	* a list of items in the room that can be interacted with.

Each item has:
	* A description ( examine item )
	* if this can be picked up or not
	* what item(s) it can interact with....
	* what happens when it interacts with 'item'


Each Adventure will have:
	* An 'owner' - main author
		* Only the owner can 'delete' an adventure
		* Only the owner can give or revoke 'authorship' to others.
	* A set of authors
	* Availability status
	* A starting point
	* A 'winning' condition


A guest (identified by what ever ip/machine name I can get),


