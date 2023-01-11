# Random Movie Generator

This project presents a simple web page that allows you to play a "Random Movie Generator" game. 

## How to Play

1. Click the "Fetch a random movie" button to fetch a random popular movie title from The Movie Database (TMDb) API. The movie title will be displayed as emoji on the page.

2. Guess the movie title by typing it into the input field and clicking the "Check" button.

3. If your guess matches the movie title, an alert box will display "Correct! The actual movie name is [movie title]." If your guess does not match the movie title, an alert box will display "Incorrect! Try again."

## Technologies Used
- HTML: for defining the structure and content of the web page
- CSS: for defining the visual styling of the page elements
- JavaScript: for defining the behavior of the page elements and handling the communication with the TMDb and OpenAI API

## API Used
- The Movie Database (TMDb) API: to fetch the list of popular movies
- OpenAI API: to convert movie title to an Emoji 

## How to run

To run the game on your local machine, you will need to have a web server installed, you can use [http-server](https://www.npmjs.com/package/http-server) for this.

1. Clone the repository

```git clone https://github.com/lettaz/MovieEmoji.git```

2. Navigate to the project directory

```cd MovieEmoji```

3. Open Index.html with your web browser


5. Click on the "Fetch a random movie" button to start playing the game

## Note
The code uses `apiKey` variable to interact with TMDb API, this variable is set to `######MYAPIKEY######`, which is an example key and may not work in this code. It would be recommended to use your own key which you can get by signing up on [TMDb website](https://www.themoviedb.org/account/signup) and OPEN AI

## Conclusion
This code is a simple game that allows the user to guess a movie title and check their answer, The use of API from TMDb and OpenAI to get a random movie title, and convert it to an emoji, makes the game more interactive. The user can run it on local machine and interact with it by providing input in the given field.
