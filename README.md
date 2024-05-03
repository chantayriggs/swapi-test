# Practice Coding Test

The objective of this task is to develop a code that retrieves data from the [SWAPI](https://swapi.dev/) (Star Wars API). The requirements are as follows:
1. Retrieve and display a list of characters using the "/people" endpoint.
2. Implement pagination to display characters from each individual page.
3. Include two buttons to navigate between pages: a previous button and a next button.
4. Disable the buttons when there is no additional data available through pagination.
5. For each character retrieved from the SWAPI, render a button alongside their name that initially reads "See home world". Upon clicking this button, it should reveal information about the character's home planet, including its name and climate.
6. Once the "See home world" button is clicked, it should dynamically change to "Hide home world". Clicking on this button again should hide the displayed information about the character's home planet.
7. The rendering of character information and home planet information should be handled by separate components. You should have a `Person` component responsible for rendering each character's details and a `Homeworld` component responsible for displaying information about the character's home planet.

   
Note: Implement the logic in such a way that it optimizes rendering performance. For example, ensure that unnecessary re-renders are avoided, especially when toggling the visibility of home planet information.


## Requirements
1. It is preferable to use React and either JavaScript or TypeScript.
2. The focus of this task is on the code that interacts with the API; CSS styling is not necessary.

## Method
Can either use [CodeSandbox](http://codesandbox.io/) and develop your solution there, or you can fork this repo and open a PR to submit your solution.
