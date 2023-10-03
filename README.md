# Code Quiz

The application will start once the user clicks the start button. Once started the user will be timed as they take the quiz, with bonus time being given with every correct answer, and time penalties with every wrong answer. Once the user has finished the quiz, the remaining time will be used as their score and the user will be allowed to submit their initials. Once they submit their score, the data will be collected and placed on a scoreboard where they will be ranked based on their score. 

## Link to website

[Code Quiz](https://h3yj4yy.github.io/Coding-Quiz/quiz.html) 



## Preview

```bas
startButton.addEventListener("click", startQuiz);
    saveScoreButton.addEventListener("click", saveScore);

    function startQuiz() {
        startContainer.style.display = "none";
        quizContainer.style.display = "block";
        quizStarted = true;
        startTimer();
        displayQuestion(currentQuestionIndex);
    }class="quizInstructions">
```

