# README-File
Tick Tack Toe Project Guide
## Installation

To set up and run a Tic Tac Toe on a new PC Follow these steps:

1.	Install Visual Studio: Download and install the latest version of Visual Studio from the official Microsoft website. Make sure to select the "Desktop development with C++" workload during the installation process.

<img width="917" alt="Screenshot 2023-12-08 214239" src="https://github.com/Afaf-yunas11/Project-23-l0745-23-l0523/assets/147866906/3dd961c9-cc3a-4f18-9e78-b30fa82e89ef">




2. Choose the edition: Visual Studio offers different editions depending on your needs. You can choose between the Community (free), Professional, and Enterprise editions. Click on the "Download" button for the edition you prefer. Community edition is preferred to run this game

 ## Project Set Up

 
1.    After Visual Studio has been dowloaded perform these steps.
2.		Create a new project: Open Visual Studio and go to "File" -> "New" -> "Project" to create a new project for your game. Choose “Empty Project”.
 <img width="473" alt="Screenshot 2023-12-08 214523" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/a8dd5a4f-8fb7-452e-8d0e-60f098a00d32">

3.	Add your game code: Open the source file ( with a .cpp extension) where you want to add the game code. You can either create a new file or modify the existing one. Write or paste your C++ code into the file and save it. Open ticktacktoe.cpp.

 <img width="575" alt="Screenshot 2023-12-08 214623" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/48f6719d-6842-4ff9-896d-b679e4373cf9">

 

4.	Build your project: Click on the "Build" menu and select "Build Solution" to compile your project. Visual Studio will check for any errors in your code and generate the corresponding executable file.
 
<img width="829" alt="Screenshot 2023-12-08 214725" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/261fdc8f-2cd3-418a-8091-f7fa48490a8e">


5.	Run your game: After the build process completes successfully, you can run your game by clicking on the "Start Debugging" button (usually a green play button) or by pressing the F5 key. If everything is set up correctly, your game should start running within Visual Studio's debugging environment.
   
 <img width="960" alt="Screenshot 2023-12-08 214901" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/1d29f6a4-f261-4ea5-88b0-fd9587b7b42a">
 
6.	Now the game will start and following will be displayed:

<img width="935" alt="Screenshot 2023-12-12 190107" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/dead9934-1720-4d01-bb37-4b4bb8474629">

## Project Purpose

• It’s a game that can be easily learnt and therefore, can be played by people of all ages. The rules are easy to comprehend and involve a few concepts and moves.

• Despite being simple, it requires strategic thinking and planning. Players are supposed to analyze the ongoing situation and then make profound decisions that increase their chances of winning.

• It helps individuals to develop critical thinking by encouraging to think out of the box and to implement logical reasoning, pattern recognition and problem solving abilities to find the best move in order to win.

• This game also provides a vital opportunity for players to interact, to develop a bonding and consider it a friendly competition. It can be a fun and an engaging game to spend time with friends, family members etc.

• Additionally, tic-tac-toe is an enjoyable and an entertaining game which can be played by players regardless of their age. It no doubt offers a break from daily routine and can help relax the mind while still engaging it.

## Prerequisites

There are no such prerequisites but the players should be well aware of the rules and how the game works. The players, one by one, mark their symbols in the squares. The main objective is to win by making either a horizontal, vertical or diagonal pattern of your symbol before the other player does. The players take alternate turns and the winner is announced the moment the player succeeds in forming a pattern as mentioned before.


## Troubleshooting Common Issues

The implementation of the Tic Tac Toe game in C++ encountered several problems during testing and use. The following troubleshooting steps were followed to identify and resolve these issues.

### Problems found:

1.	Win Condition Bug: The game was not correctly identifying victory conditions, resulting in incorrect declarations of winners or ties.
2.	Input validation failure: Invalid user input was not handled properly, causing unexpected behavior.
3.	User Interface Update: The User Interface was not updating consistently to reflect the current state of the game.

### Troubleshooting steps taken:
Code Review: The game logic was thoroughly reviewed to identify any discrepancies in the victory condition verification algorithm. A logical error was found in the win condition verification and was fixed by adjusting the verification mechanism to correctly identify winning combinations.

Improved input validation: Implemented improved input validation to handle out-of-range inputs and already occupied cells. Users are now prompted to re-enter their move by providing invalid input.

User Interface Restructure: Updated the User Interface refresh features to ensure the screen accurately reflects the current state of the game board. Modifications were made to ensure proper representation of the game board after each move.

### Testing and validation:

Extensive testing was performed after each troubleshooting step to ensure that the implemented changes resolved the identified issues. Test cases covering various motion sequences, edge cases, and invalid inputs were run to verify the correctness of the solutions.

### Resolution:

After implementing and validating the troubleshooting steps, the Tic Tac Toe game now works as expected, accurately identifying victory conditions, correctly handling user input, and updating the UI consistently to reflect the status. current game

## Key Functionalities via ScreenShots



1.	Players get to enter their names to avoid confusion while taking turns later:

   <img width="929" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/b6ab2f32-28fb-485e-8e56-003278819013">
 

3.	A tic tac toe board is shown with box numbers for the ease of the players:
(separate variables declared for coordinate of each box number)

 <img width="930" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/d140eac4-62f9-4660-91f1-9a5b36c92554">


4.	Each player gets to choose his own symbol from a variety of given symbols:
(functions)
 
<img width="535" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/7b35ccdc-4a1b-45ba-bc54-b9ccbee3d84f">

5.	The box number entered by the user is replaced with the user’s symbol on the board side by side:
(functions)

 <img width="439" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/07257f14-c448-42c5-9e52-692997657bcc">

6.	Each player gets a turn after the other player:
(loops)
 
<img width="564" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/795026e6-3d13-4896-a7b5-db1cff785a1d">

7.	Winner after each round is announced and scores are updated side by side:
(functions)
 
<img width="787" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/426bf8b4-d809-41aa-9d0b-3f6ab381e4ee">

8.	A draw message displays if no one wins:
(If -else statements)
 
<img width="269" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/93cfff9d-6752-4d41-8955-95aca9f49c10">

9.	An extra gift feature has been added for the final winner after three rounds:
(If -else statements)
 
<img width="864" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/631c2340-7b87-4a25-b44b-290f26ece0c7">

10.	A list of dares appear if the user chooses dares, links appear for games and a list of facts appear for facts:
(file handling)
 
<img width="937" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/c975d286-a589-4ef8-9ac7-243a90b7d0f1">

11.	The gift feature doesn’t appear if the overall game is a draw:
(If -else statements)
 
<img width="489" alt="image" src="https://github.com/Afaf-yunas11/README-File/assets/147866906/4cf710cf-c1e3-4f9a-9585-62e64eb04d3c">

## Github Repository Link

[https://github.com/Afaf-yunas11/23l-0745-23l-0523](https://github.com/Afaf-yunas11/Project-23-l0745-23-l0523)

## Cloning Repository

### Install GitHub Desktop:

Download and install GitHub Desktop from the official GitHub Desktop website: GitHub Desktop.
Follow the installation instructions for your operating system.
### Log in to GitHub Desktop:

Open GitHub Desktop and sign in with your GitHub account credentials.
### Clone a Repository:

Click on the "File" menu at the top left corner of the GitHub Desktop window.
Select "Clone Repository" from the dropdown menu.
In the "Clone a Repository" window, you'll see a list of your GitHub repositories. If the repository you want to clone will not be  listed so , click on the "URL" tab and paste the repository URL into the "URL" field  which is [ https://github.com/Afaf-yunas11/23l-0745-23l-0523](https://github.com/Afaf-yunas11/Project-23-l0745-23-l0523)

Choose the local path where you want to clone the repository.
Click "Clone" to start the cloning process.

## Accessing Cloned Repository:

Once the cloning process is complete, you'll have a local copy of the repository on your computer.
You can navigate to this repository within GitHub Desktop to view its files and manage it.





