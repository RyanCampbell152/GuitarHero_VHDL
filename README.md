# GuitarHero_VHDL
The purpose of this project is to recreate the guitar hero video game in an FPGA using
VHDL. This will be done by using VGA to display the game, and using the four buttons
on the DE2-115 board to control the game. The actual game will consist of 4 rows of
notes approaching the bottom middle of the screen, corresponding to the four buttons on
the DE2-115 board. When the user starts the game by pressing any button, different notes
will scroll down the screen in sync with music, and the user must press the corresponding
buttons at the same time as when the note crosses a certain threshold. If the player hits the
note correctly, the game will give visual feedback while also increasing the score of the
player. This score will be displayed on the liquid crystal display while the game is going
along, showing your final score at the end. The final score will also be displayed along
with an amount of stars at the end, ranging from 1-5, to show how well you did. 
