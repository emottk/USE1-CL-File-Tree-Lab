#Organizing at the Grocery Store

Your local grocery store wants to organize all of their foods using a file tree. They have begun the process, but have some more sorting to do.

Open the `Food_Groups` file and see what sort of organization they have set up so far.

Inside `Food_Groups` you'll see an `unsorted` directory. Let's help them sort some of these foods.

`cabbage` is one of the unsorted foods. We know that it belongs in the `vegetables` directory. Let's move it there. We will use a new command `mv` which stands for move.

`mv` works like this:

	mv [file name to be moved] [directory to be moved to]

Make sure you're in the `unsorted` file before you begin.

	[11:07:55] unsorted
	// ♥ mv cabbage ../vegetables

Here we take `cabbage` from the `unsorted` directory, and we move it outside of `unsorted` (using `..`) and then back into the `vegetables` directory.

If we `cd` out of `unsorted` and into `vegetables` now, we will see that our file has moved.

	[11:08:18] unsorted
	// ♥ cd ..
	[11:11:08] Food_Groups
	// ♥ cd vegetables
	[11:11:11] vegetables
	// ♥ ls
	cabbage	carrot	celery	kale

One food sorted! Now it's your turn to sort the rest. 		
Hint: Some of the foods listed don't belong in any of the categories. Use your command line skills to create a new folder so that we end with an empty `unsorted` folder.

Stretch: Break down these categories even further! Root vs vine vegetables? Fat vs non-fat? Get even more specific with your organization. Add as many foods as you see fit!
