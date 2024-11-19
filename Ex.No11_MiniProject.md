# Ex.No: 11  Mini Project 
### DATE:                                                                            
### REGISTER NUMBER : 212222240009
### AIM: 
To write a python program to simulate the Zombie hunter game.
### Algorithm:
```
1.Word Selection: A word is randomly chosen from the list word_list using 
random.choice()

2.Hidden Word: The chosen word is represented as underscores (_), and the 
player guesses letters to reveal the hidden word.

3.Guessing Logic: The player enters a letter using input().
 If the letter exists in the word, the program reveals the letter in the correct 
positions.

 If the guess is incorrect, the number of attempts is reduced by 1.
4.Game Loop: The loop continues until the player either guesses the word or runs out 
of attempts.

5.Win/Loss Condition: The player wins if they guess the word before 
running out of attempts. If they run out of attempts, the game ends and the
correct word is revealed.

6.This game helps users practice string manipulation, loops, and conditionals while 
enjoying the challenge of guessing word.

```

### Program:
# HTML:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" href="https://cryptogunner.online/wp-content/uploads/2023/03/Logotipo_Token2.png" type="image/x-icon">
<link rel="stylesheet" href="./style.css">
  <title>zombie hunt</title>
  </head>
<body>
    <div class="container">
      <div class="container-game-info">
        <div class="container-bullets">
          <h2 id="bullets"></h2><!-- Fetch --><h2 id="bullets-num"></h2>
        </div>
        <divclass="container-timer">
          <h2 id="timer"></h2><!-- Fetch --><h2 id="timer-num"></h2>
        </div>
        <divclass="container-score">
          <h2 id="score"></h2><!-- Fetch --><h2 id="score-num"></h2>        
        </div>      
      </div>
  <buttontype="button" class="button">START</button>
      <div class="start-timer">
        <h1 id="start-timer"></h1>
      </div>
<divclass="game-rules">
          <h3>The Undead army is comming...</h3>
          <p>"he face of darkness. Your destiny awaits, young Gunner, may your path be guided by courage and skill." - With my respect, The Officer.</p>
          <h3>Game Rules:</h3>
          <ul>
              <li>Each NFT rarity have different amount of Bullets, Time and Max Score.</li>
              <li>Highest rarity NFTs will earn more than low rarity ones.</li>
              <li>If your BULLETS goes to zero, game over.</li>
              <li>If your TIME goes to zero, game over.</li>
              <li>If your MAX SCORE is reached, game over.</li>
              
              <li>Have fun, and good luck!</li>
          </ul>
      </div>
  
      <div class="container-button-start">
      </div>
      <img
        src="https://clipart-library.com/img1/37366.gif"
        alt="Crosshair"
        class="cursor"
      />
      <img
        src="https://clipart-library.com/images_k/bullet-hole-transparent/bullet-hole-transparent-19.png"
        alt="Bullet Hole"
        class="bulletHole"
      />
      <img
        src="https://clipart-library.com/images/Lcd5A9bbi.png"
        alt="Blood Spot"
        class="bloodSpot"
      />

    </div>
    <script src="./java.js"></script>
  </body>
  </html>
  
  ### Output:
![image](https://github.com/user-attachments/assets/9e1846a1-f7b8-4047-8cbc-14019e53d8f0)


### Result:
Thus the simple  game was implemented using web development.
