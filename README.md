# Coding Quiz - M6 Challenge Project

This application is a coding quiz which offers timed multiple choice questions.
This app runs in a browser and feature dynamically updated HTML and CSS powered by JavaScript code. It also features a clean and polished user interface and is responsive, ensuring that it adapts to multiple screen sizes.

## Objective
AS A coding bootcamp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers

## Acceptance criteria
* GIVEN I am taking a code quiz
* WHEN I click the start button
* THEN a timer starts and I am presented with a question
* WHEN I answer a question
* THEN I am presented with another question
* WHEN I answer a question incorrectly
* THEN time is subtracted from the clock
* WHEN all questions are answered or the timer reaches 0
* THEN the game is over
* WHEN the game is over
* THEN I can save my initials and score

## Additional features
* Timer changes color. At 10 second interval it turns green, and at 5 seconds it turns red.
* Pauses timer when user selects choice before advancing to next question
* When the timer is paused, if the user has a wrong choice it is highlighted in red and the correct answer is highlighted in green. If the choice is correct it is just highlighted in green.
* Admin page is provided so users can customize the application
* Users can customize the counter seconds in the admin page
* Users can add additional questions in the admin page
* All admin customizations are stored in localStorage
* The order for choices are always randomly shuffled

## Files included
|File|Relative Path|Description|
|---|---|---|
|index.html|index.html|Home page|
|admin.html|admin.html|Admin page|
|leaderboard.html|leaderboard.html|High scores page|
|quiz.html|quiz.html|Quiz page|
|style.css|assets/css/style.css|Main stylesheet|
|admin.js|assets/js/admin.js|JavaScript for Admin page|
|leaderboard.js|assets/js/leaderboard.js|JavaScript for high scores page|
|quiz.js|assets/js/quiz.js|JavaScript for quiz page|

## Accessing the site
Please visit the [site](https://phil13131.github.io/M6_Code_Quiz/) hosted on GitHub Pages.

## Screenshots
![Screenshot 1](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_1.PNG)
![Screenshot 2](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_2.PNG)
![Screenshot 3](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_3.PNG)
![Screenshot 4](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_4.PNG)
![Screenshot 5](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_5.PNG)
![Screenshot 6](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_6.PNG)
![Screenshot 7](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_7.PNG)
![Screenshot 8](https://github.com/phil13131/M6_Coding_Quiz/blob/main/Screenshot_8.PNG)

https://github.com/phil13131/M6_Code_Quiz/blob/eadfa85c6164d0f2408c97dae37f773c077732c6/Screenshot_20230117_094837.png
## License
This project uses the MIT license.

## Tools used
* [GitHub](https://github.com/) - Code repository and page hosting via GitHub Pages
* [Visual Studio Code](https://code.visualstudio.com/) - For editing and authoring code
* [Prettier](https://prettier.io/) - For opinionated code formatting
* [Chrome Devtools](https://developers.google.com/web/tools/chrome-devtools) - For editing pages on the fly and diagnosing problems
