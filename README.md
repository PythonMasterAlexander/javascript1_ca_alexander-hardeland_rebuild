Rebuild of CA in JavaScript1 course on Noroff front-end Development

Teacher feedback on the original assignment grade - 9/10

Hello Alexander, thanks for your submission. 

On the index page you have managed to make an API call and loop over the results to render them, which is great. The loader is not working though, this is because you are adding it as a “div” inside a “table” a “div” is not valid as a direct child of a “table” and will be moved outside the “table” in the HTML, you can confirm this by looking at the dev tools. Because of this it will not be part of the “.main__table-container” and will not be removed when you try to empty the “innerHTML”. 

The details page is implemented correctly but does not have a loader while fetching the API data.  

The contact page is also implemented correctly but a note here is that you are using “event” inside the “formValidation” function but, you have not added “event” as an argument to the function. When the “submit” event listeners is triggered “event” is sent to the function you attach to it as the first argument so if you want to use “event” inside the function you should take it in as an argument in your function like this “function formValidation(event) {“. 

Overall though Good work on this assignment!
