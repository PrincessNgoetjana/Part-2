# Part-2
# 1
A recipe is represented by the Recipe class, which has attributes like Name and Ingredients.
With qualities like Name, Calories, and FoodGroup, the Ingredient class serves as a representation of an ingredient.
A delegate RecipeCaloriesExceededHandler and an event CaloriesExceeded are also included in the Recipe class. This enables the use of delegates to alert the user when a recipe contains more calories than 300.
The primary program logic is included in the Program class.
# 2
The user's recipes are all stored in the recipes list, a general collection.
The user can add a new recipe using the AddRecipe method. The name of the dish is first requested, and then questions about the ingredients' names, calories, and food groups follow. The associated recipe's Ingredients list receives the addition of the Ingredient objects.
Following the addition of a new recipe, the recipes list is sorted using the Sort technique in alphabetical order by name.
# 3 
The DisplayRecipes function just shows the user a list of recipe names.
The SelectRecipe method requests that the user enter the name of the recipe they wish to select. It uses a case-insensitive comparison to find the recipe in the recipes list. If the recipe is identified, it calculates and displays the total calories by adding the calories of all the ingredients. If the total calories surpass 300, a warning message is displayed and the CaloriesExceeded event is triggered.
# 4
The Main method executes an infinite loop to display the menu selections to the user indefinitely. The user can choose between adding a recipe, showing recipes, selecting a recipe, and closing the software.
