# Project-2
### Required Language: C or C++
### Description:
#### In this game, The user will be shown a number between 1 and 13 and they will have to guess what the next card will be either higher or  lower. If the user guesses correctly they will be awarded with a prize and if they guess incorrectly then the game will end.

### User Storys:
  
 #### As the user I want to be able to choose higher or lower 
 #### As the user I want to be able to see when I win or lose
 #### As the user I want to be able to see my score 
 #### As the user I want to be able to see the randomly drawn card
 #### As the user I want to be able to keep on playing till my score runs out

### Flow Chart:
![flowchart p2](https://user-images.githubusercontent.com/31927415/32719636-f9d91864-c858-11e7-8c81-34974b31c6e7.JPG)

### TimeLine Of Progress
![capture](https://user-images.githubusercontent.com/31927415/33025223-4e1cf2cc-ce05-11e7-84cc-089e5ae35428.JPG)

### The language that i used was C++
#### The main reason that i used C++ for my High Low game is because Firstly it is the language that i have the most experience in so i felt the most confident using it. Secondly it upports functions of high level programming languages, such as scripting for software applications. C++ can be used for many differnet things so growing my knowleadge now with basic code in the langauge will help me later on down the road.

### The IDE That i Used Was Repl.it
#### Repl.it is a online IDE that has a live preview of the outcome of the code that i have written so i an see any errors in present time and it also helps with this high low game because the game needs a input to continue so i can also enter that to find any errors or to complete the game in live time. 
#### It also saves your code to the cloud so you can access it at any time and you can also save it to your PC or GitHub aswell. 

### Implementation Of An Algorithm 
![gfdsfb](https://user-images.githubusercontent.com/31927415/33656786-0cbd9554-da6f-11e7-815c-681f1639654e.JPG) 
##### In This screen shot of ths start of the flow chart you can see that the first thing we need to do is shuffle the cards. The code that i used to do this was:   

    int PickCard() { // The function that generates a random number between 1 and 13
  
      int x; // Placehodler int to hold the card value
      x = (rand()%13)+1; // The random number generator
  
  
      return x; // Returns the result of the random number generator
  
      } 

![ghm](https://user-images.githubusercontent.com/31927415/33656952-b62a733c-da6f-11e7-8e2f-72790e6603a9.JPG)
##### In this sceen shot it is when the first card has been drawn and the user my picker higher or lower. The code used to make this work was: 
      cout << card1 << "\n"; // Prints value of card1
    
    	cout <<1 for Higher, 2 for Lower" << "\n"; 
    


### Debugging Process
#### With the help of the live view on Repl.it i managed to debug my code while i was doing line by line so that if i ran into any problems i was able to quickly fix them. One Example of a Error i had was i forgot to end a line of code with ';' and i didnt no what the problem was but i knew it was in my latest line of code as i had just typed it and by looking over my previous lines of code i saw the error quickly.

### Evaluation 
#### Overall the second project went alot better than the first project but i still had alot of problems with errors but with the debugging system in Repl.it i managed to get the program working in the end. It was my first time using a web based IDE. I liked using Repl.it alot as it had a live preview of your code on the right hand side and it would also tell you where the error has occurred which helped alot with the debugging of the code. I think that overall my game has met all the standerds set out from the start and has ticked all the boxes. It was also complete on time
