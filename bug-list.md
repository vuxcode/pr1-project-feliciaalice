# Bug List

1. Started out wanting to create a quiz where the user could pick from many different choices, that would include many more functions. Figured out a program like that would be too complicated for my skill level, so I chose to focus the quiz on only one study field, and one "startQuiz" function. Then a function for every "step" of the quiz. 

2. Had to figure out how to properly get the quiz to be displayed in the "quiz container". Solution: document.getElementById('quiz-container') to display the quiz/options/answers etc. 

3. Had a logic bug when adding all options to the if-statements. The questions wouldn't change from the first option (cariology questions). Solution: Figured out that I've just forgotten to write "else if", I only wrote "if". Had many small spelling mistakes while writing the program, that ruined it. 

4. When I continued coding all the quiz functions to show the quiz & check the answers, I knew there was an error in the code since when I tried running the program nothing happend when I tried to pick the option "Endodontics". My solution: Checked my code for errors & saw that I had written "Endodontics" for functions, when it should have been "Endo". When I fixed the bug, the program is running perfectly.

5. The hardest challenge so far was to change the correct/incorrect results from the questions to a simple alert(""); to my idea that I wanted the correct answers to be green & the incorrect ones to be red. I did my research to find out how to do it. My solution:

6. I needed to have the end result to show for each different fields. Solution:  
