*FETCHING API


The main purpose for this project was demonstatrate how javaScript interact with API through asynchronous operations. 

The project starts by creating an input box along with a button to trigger searching for the information regarding pokemon's name or id.

Next step involves checking if provided URL can be fetched by using  fetch function 'console.log(fech(url))'. The function returns a pending status because a fech function return a Promise as it is asynchronous function by default. However, since the goal  was return a successfulL or Failed promise from the url, next step has to follow.

The next step involves creating async function() to transform any javaScript function into a asynchronous function. Also, await() is used to wrap given url to make sure a Promise resolves successfully or get rejected.

Try and catch are also used to make sure that once a Promise is rejected, the error is  displayed in the console or if it is resolved successfully, the requested information will be displayed.

DOM elements were used to display requested data such as image, id, type, and name of the pokemon on the webpage in case there was no error or displaye a certain message in the browser in case of errors.

In case the user try to enter a pokemon name with a capital letters, DOM elements were used to convert any input in forms of letters to the lowerCaase. 


Other DOM elements were used to change styles of elements of the information from back end while css were used to change styles of elements on the front end.




