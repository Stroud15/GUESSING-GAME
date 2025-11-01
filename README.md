# Project Title: Guessing game algorithm

# Project Author: DADA MORUF OLAWALE


## 👩‍💻 Peer Reviewer

# Project Description
This project is a simple number guessing game algorithm.
The program randomly selects a secret number between 1 and 10,
and the user must guess it. The program uses decision control
to tell if the guess is too high, too low, or correct. It keeps asking
until the user guesses correctly.



##  Algorithm

   BEGIN
    secret_number ← RANDOM(1, 10)
    REPEAT
        OUTPUT "Guess the number (between 1 and 10): "
        INPUT guess

        IF guess < secret_number THEN
            OUTPUT "Too low! Try again."
        ELSE IF guess > secret_number THEN
            OUTPUT "Too high! Try again."
        ELSE
            OUTPUT "Congratulations! You guessed correctly!"
        ENDIF
    UNTIL guess = secret_number
END


