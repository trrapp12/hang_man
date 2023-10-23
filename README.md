# hang_man

#### Contributors: Trevor Rapp, David Wise, Bob Ziroll

*Completed as part of the [Coding Campus](https://vschool.io/), now V-School, curriculum*

<br/>

---

<br>

![hangman](https://cloud.githubusercontent.com/assets/11747875/8296599/8e007646-190f-11e5-83ce-64c7a3ef2ee2.jpg)

<br/>

---

<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
<img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />

<br>

---

### Description:

This is a simple game of hangman done completely in Python.  The program asks if the user wants to have the rules explained or if they want to play.  When it comes time to play the program chooses a random word from a list of words.  The program then displays the number of spaces in the word and the player is left to guess a letter.  The program checks the letter guessed and filters out case issues or non alphabetic characters and returns an error message if there is one.  If the input is valid, then the program checks if and where the character is contained in the word and displays which empty space is now filled in.  If the guess is incorrect the computer chooses from a list of disparaging remarks to taunt the player and displays how much of the person is "drawn." The player wins if all letters are guessed correctly in under 5 guesses.
<br/>
<br/>



### Instructions on how to launch:
---

1. Make sure you have a Python interpreter installed: 
  - on a Mac type &#8984;  + `space`
  - type "terminal"
  - press `Enter`
  - in the shell command line type 
 
 ```
 \\Check the system Python version
$ python --version

\\Check the Python 2 version
$ python2 --version

\\Check the Python 3 version
$ python3 --version

```

2. This will show you if you have Python installed already and which version you have installed. 
 
3. If you need to, install Python
  - From your browser navigate to Python.org
  - On the Python.org page, find the links to download the file.  Versions are available for Mac or Windows.  However, I found the Mac version worked more consistently for me. 
  <br/>
  <br/>
  
  ![image](https://user-images.githubusercontent.com/11747875/129993191-4912f7c9-edeb-40ad-b73f-96a35f4dc884.png)
  
  <br/>
  <br/>

4. Create a Folder to hold the program
  - in the terminal type `mkdir Hangman` or whatever other name you want to call it. 
  - navigate into the folder by typing `cd Hangman`
  - clone the program into the Hangman folder you just created by typing: 
 
 ```
 git clone https://github.com/trrapp12/hang_man.git
 ```
  
5. Make sure you are still in the Hangman folder
6. You should be able to see a program named 'hangman.py'.  If not, navigate back into the Hangman folder.  
7. Type `python hangman.py` to run the program from the terminal
8. The program runs from prompts in the Command Line, so watch for prompts and respond accordingly. 
9. Enjoy!
<br/>
<br/>

### This project demonstrates the following:
---

- [x] Correct use of functions, conditionals, loops, arrays.
- [x] Properly sequence Python statements.
- [x] Select a random word from a dictionary of words.
- [x] Display all guesses on the user's screen so the user knows what letters he/she has already guessed.
- [x] Display a visual indication for each letter in the word.
- [x] Display the number of turns remaining.
- [x] Decrement the number of turns remaining.
- [x] Display letters guessed in the position that they are contained in the word.

<br/>
<br/>

### More Information:
---

\**For more information see my [LinkedIn](https://www.linkedin.com/in/trevor-rapp-042a1037) or return to my [Github](https://github.com/trrapp12)*
