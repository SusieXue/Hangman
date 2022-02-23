# Hangman
## Description
This contains the game codes for hangman and the medias in the codes.
## History of hangman
"The origins of Hangman are obscure meaning not discovered, but it seems to have arisen in Victorian times," says Tony Augarde, author of The Oxford Guide to Word Games. (https://culture.fandom.com/wiki/Hangman_(game))
## How to play
Solo mode: The program will automatically strip some letters in the program according to the difficulty you have chosen, input the letters present in the word. If you have seven incorrect guesses, you lose!
Two people mode: The program will strip some letters in the word the player input. The other player needs to guess the correct letters, and if he or she has seven incorrect guesses, he or she loses.
## Known issues
- Some words are too difficult to guess because the program stripped too many letters.
- If the user doesn't input letters in order, the program will regard that as correct, but the word may be messed up.
- The paths of the medias don't work on someone else's computer because relative path didn't work, so I used absolute path. If you are trying the program on your computer, you need to change the paths in ```playsound```.
- There is a latency with ```playsound``` module, even if ```block=False``` is used.
