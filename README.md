#Organizing at the Zoo

The Bronx Zoo wants to organize all of their animals using a file tree. They have begun the process, but have some more sorting to do.

Open the `Animals` file and see what sort of organization they have set up so far.

Inside `Animals` you'll see an `Unsorted` directory. Let's help the zoo sort some of these animals.

`Sparrow` is one of the unsorted animals. We know that it belongs in the `Bird` directory. Let's move it there. We will use a new command `mv` which stands for move.

`mv` works like this:

	mv [file name to be moved] [directory to be moved to]

Make sure you're in the `Unsorted` file before you begin.

	[11:07:55] Unsorted
	// ♥ mv sparrow ../Birds

Here we take `sparrow` from the `Unsorted` directory, and we move it outside of `Unsorted` (using `..`) and then back into the `Birds` directory.

If we `cd` out of `Unsorted` and into `Birds` now, we will see that our file has moved.

	[11:08:18] Unsorted
	// ♥ cd ..
	[11:11:08] Animals
	// ♥ cd Birds
	[11:11:11] Birds
	// ♥ ls
	hummingbird	owl		penguin		sparrow

One animal sorted! Now it's your turn to sort the rest. 		
Hint: Some of the animals listed don't belong in any of the categories. Use your command line skills to create a new folder so that we end with an empty `Unsorted` folder.

Stretch: Break down these categories even further! Shelled vs. non-shelled reptiles? Winged insects vs legged? Help the zoo out and get even more specific with your organization. Add as many animals as you see fit!
