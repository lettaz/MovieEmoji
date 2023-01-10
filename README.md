# MovieEmoji Game
a simple JavaScript program that uses the axios library to make an API call to the Movie Database (TMDb) to fetch a random popular movie, and then uses the OpenAI API to convert the title of the movie into an emoji representation.

The program defines an event listener for the "Fetch a random movie" button which calls the logTitle function when clicked. logTitle calls the getRandomPopularMovie function, which makes an API request to TMDb's /movie/popular endpoint, and then calls the getEmoji function and passed the random movie title.

The getEmoji function makes a post request to OpenAI API, passing the movie title along with some other parameters in the request body, like the model, prompt, temperature, and stop etc. After receiving the response the API returns movie title in form of emoji representation and it is added to the movie-container div.

The program also includes a form with an input field and a "Check" button, which, when clicked, calls the compareStrings function. This function compares the user-entered text in the input field with the original movie title, checking if any of the words in the user's input are present in the original movie title. If there is a match, the user is alerted that they have guessed correctly, otherwise they are alerted that their guess is incorrect.

It is a simple interactive movie guessing game that uses APIs to generate the random movie name and convert the title in the form of an emoji representation for the user to guess.
