SET mystNumb = 5
SEND 'please guess the mystNumber' TO DISPLAY
RECIEVE mystNumber FROM KEYBROAD
IF guessNumber >10 THEN 
SEND 'Too high! Your guess must be between 1 and 10.'
Else SEND 'please guess the mystNumber' TO DISPLAY
IF guessNumber = 5 THEN
SEND 'Well done! You guessed correctly.'
Else SEND 'Bad luck! The correct number is 5"
