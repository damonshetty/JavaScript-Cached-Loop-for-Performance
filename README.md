Increase looping performance by caching the length of the array.
This means accessing the length of the array only once, as opposed to every iteration.

//optimised for loop
for (var i = 0; lengthofarray = array.length; i < lengthofarray; i++)
	{
		
	}


//non-optimised for loop
for (var i = 0; i < array.length; i++)
	{
		
	}


