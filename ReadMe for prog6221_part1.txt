Here is a brief explanation on how my console application works:

The Recipe class represents a recipe, with properties for the name, ingredients, units of measurement, and steps.
Each of these properties is a list of strings, except for the name which is a single string.
In the Main method, i have created a list of Recipe objects to store all the recipes.
The application enters a loop where it prompts the user to enter a recipe name. 
If the user enters ‘exit’, the application breaks out of the loop and ends.
For each recipe, the application enters two more loops to prompt the user to enter the ingredients and their units of measurement, and the steps. 
If the user enters ‘proceed’, the application breaks out of the current loop and moves on to the next step.
After all the information for a recipe has been entered, the recipe is added to the list of recipes.
Finally, after all recipes have been entered, the application loops through the list of recipes and prints out each one, including the name, ingredients (with unit of measurement), and steps.