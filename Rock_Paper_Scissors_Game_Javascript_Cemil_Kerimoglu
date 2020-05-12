// ROCK PAPER SCISSORS GAME UNTIL CERTAIN NUMBER OF WINS

function rockPaperScissorsNumberOfWins(numberOfWins) {
    if (numberOfWins > 1) {
      console.log("The one who scores the first " + numberOfWins + " wins is declared the winner of the game. Let's go!");
    }
    else if (numberOfWins == 1) {
      console.log("The one who scores the first win is declared the winner of the game. Let's go!");
    }

    let userWins = 0;
    let computerWins = 0;

    while (computerWins < numberOfWins && userWins < numberOfWins) {

      var userEntry = prompt("Choose rock, scissors or paper");
      let computer = Math.random();
      if (computer <= 0.333) {
        var computerEntry = "rock";
      }
      else if (computer > 0.333 & computer <= 0.666) {
        var computerEntry = "scissors";
      }
      else {
        var computerEntry = "paper";
      }

      if (userEntry == "rock") {
        if (computerEntry == "rock") {
          console.log("Computer and user both chose " + userEntry + ". It is a tie!");
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
        else if (computerEntry == "scissors") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". User wins!");
          userWins++;
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
        else if (computerEntry == "paper") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". Computer wins!");
          computerWins++;
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
      }

      else if (userEntry == "scissors") {
        if (computerEntry == "rock") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". Computer wins!");
          computerWins++;
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
        else if (computerEntry == "scissors") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". It is a tie!");
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
        else if (computerEntry == "paper") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". User wins!");
          userWins++;
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
      }

      else if (userEntry == "paper") {
        if (computerEntry == "rock") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". User wins!");
          userWins++;
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
        else if (computerEntry == "scissors") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". Computer wins!");
          computerWins++;
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
        else if (computerEntry == "paper") {
          console.log("Computer chose " + computerEntry + ", user chose " + userEntry + ". It is a tie!");
          console.log("CURRENT STAND: Computer - User: " + computerWins + " - " + userWins);
        }
      }
    }

    if (userWins > computerWins) {
      console.log("FINAL RESULT: Computer - User: " + computerWins + " - " + userWins + ". User won the game!");
    }
    else if (computerWins > userWins) {
      console.log("FINAL RESULT: Computer - User: " + computerWins + " - " + userWins + ". Computer won the game!");
    }

}
