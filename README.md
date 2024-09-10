**Vegan Cocktail Checker**

**1. Data Feature Overview:**
For vegans and those who are curious, this tool allows you to check whether your favorite cocktail is vegan-friendly. The feature collects a list of ingredients from the cocktail you specify and checks whether each ingredient is vegan or not using a combination of APIs. If one or more ingredients are not vegan, the cocktail will be marked as non-vegan. If all ingredients are vegan, you can enjoy your cocktail with peace of mind.

**2. APIs Used:**
TheCocktailDB API:
URL: https://www.thecocktaildb.com/api.php
Purpose: Fetches the list of ingredients from your favorite cocktail.
Why Chosen: It has a vast database of cocktails and their ingredients, making it easy to retrieve mixed drink recipes.

Edamam Nutrition API:
URL: https://developer.edamam.com/edamam-docs-nutrition-api
Purpose: Checks the nutritional information of each ingredient and determines whether it is vegan.
Why Chosen: The Edamam API provides detailed ingredient analysis, including health labels (e.g., vegan, gluten-free), which allows us to determine the vegan status of each ingredient.

**3. Instructions:**
**Setup:**

-Ensure you have an internet connection.
-You'll need API keys for both TheCocktailDB and Edamam APIs (so far they are included in the program already):

    -TheCocktailDB: Register for free here (thecocktaildb.com) to get your API key.
    -Edamam: Register for free here (developer.edamam.com) to get your API key and App ID.
      
**How to Use the Feature:**
  1. When prompted, enter the name of your favorite cocktail (e.g., "Margarita").
  2. The program will fetch the list of ingredients from TheCocktailDB API.
  3. Each ingredient will be checked against the Edamam Nutrition API to determine if it's vegan.
  4. The program will display the vegan status of each ingredient.
  5. If all ingredients are vegan, the program will confirm that the cocktail is vegan-friendly.
  6. If one or more ingredients are not vegan, the program will indicate that the cocktail is not vegan.
  7. You can check multiple cocktails by continuing to enter cocktail names when prompted.
  8. To quit the program, simply enter -1.
