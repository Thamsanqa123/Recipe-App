# Recipe App instructions
Zip File: Download and  Exract the zip file and click on the Recipe app file
Open Visual Studio: Launch Visual Studio on your computer.
click file o the top left corner of your VS and then you will click "Open" and then "Open folder".
select the file/project downloaded on your computer
Compile the Project: Click on the "Build" menu and select "Build Solution" to compile the project. Visual Studio will compile the code and generate the executable file.
After successful compilation, you can run the application by clicking on the "Start" button or pressing F5. This will launch the command-line interface of the Recipe App in the Visual Studio console window.
Follow the prompts on the window to interact with the Recipe App. The app will give option to choose from; you can enter the following options **recipe details, display recipes, scale recipes, reset quantities, clear all data, filter and ect the application using the provided options.**
**Exit the Application**: To exit the application, choose the "Exit" option from the menu, or simply close the console window.


Link to my repository:
https://github.com/Thamsanqa123/Recipe-App

#Changes Based on Lecturer's Feedback:
I replaced arrays with generic collections (lists) to store recipes, ingredients, and steps. This change enhances flexibility and ease of use, allowing for dynamic management of recipe data.
Ensured the the list of recipes is displayed in alphabetical order, this was implemented in the "showRecipe" method.
I added a method in my Recipe class which will display total calories, plus a warning is provided if the total calories exceed 300.
the ResetQuantities() method now iterates through each ingredient in the recipe. It then searches for the original quantity of each ingredient from a hypothetical backup list of ingredients (originalIngredients).
updated code includes error handling for user input.
A unit test was implemented to verify the accuracy of the total calorie calculation. 
