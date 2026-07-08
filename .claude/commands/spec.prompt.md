This is the specification for a SPA (Single Page Application).
The whole application is in a single HTML file named index.html, and it uses JavaScript to dynamically update the content without reloading the page. 

It is a fun game that shows a random flag of a US state. It should randomly select and display a flag from the 50 US states.

Once a flag is displayed, start a timer for 30 seconds. After 30 seconds, the screen pauses until the user touches the screen. When the user touches the screen, the application should display the name of the state corresponding to the flag that was shown.

The flags are shown in landscape orientation. Swiping to the left shows the next random flag and swiping to the right shows the previously shown flag. The application should keep track of the flags that have been shown and not repeat them until all 50 flags have been displayed.

There are 3 players in the game. After the 30-second timer and the user touches the screen to reveal the state name, show each user and a way to input if they guessed the state correctly or not.

The game is played on one device only. So, one user will input each player's right/wrong option. After all players' guesses are submitted, the application should display the scores for each player and then move on to the next random flag.

On the top left of the screen, display the current score for each player. The scores should be updated in real-time as players submit their guesses.

Also show a counter of how many flags have been shown out of the total 50 flags.
The application is reset only on page reload. There is no need to implement a reset button or functionality.

Keep the UI minimalistic and user-friendly, focusing on the flag display and player interaction. Use clear and legible fonts, and ensure that the touch interactions are responsive and intuitive.

The screen shows only the flag during the 30-second timer. After the timer ends and the user touches the screen, display the state name along with input options for each player to indicate if they guessed correctly or not.

Get flags form the internet using a public API or a reliable source of US state flags. Ensure that the images are optimized for quick loading and display. The flags should be realistic and high-quality images to enhance the gaming experience.

The game will be loaded from a URL on a web browser in iPhone 16 Pro Max. Ensure that the application is responsive and works well on this device, taking into account the screen size and touch interactions.