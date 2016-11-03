# latexBadges
Generate beautiful badges for any event with this easy LaTeX file &amp; csv.



# HOW TO :
* Your participant's detailed list should be in a file named "inscriptions.csv" at the same level as this file
 The cvs first line is supposed to match the following :

Name, Type, Red, Blue, Green, Yellow

* The icons used are stored in the current directory :

red.png, blue.png, green.png, yellow.png



* The background image is stored in background.png; it represent the full badge pin (1063px*591px)
it is currently set to be slightly cropped on the side, and set to 75% opacity
 
* You want to modify the name, place and date of the event  by modifying  the lines :

\put( 7, 8){\scriptsize \color{myColor}Festival\color{black}}

\put( 7, 5){\scriptsize \color{myColor}Where? \color{black}}

\put( 7, 2){\scriptsize \color{myColor}dd/mm/yy\color{black}}


* You can modify the event color my entering the RGB value in the line :

\definecolor{myColor}{rgb}{1, 0.322, 0}

it is currently set to a dark orange.

# References :
* LaTeX modified from https://tex.stackexchange.com/questions/94582/automating-the-creation-of-name-badges-for-an-event
* Icons and background made with Gimp.
* Data generated with http://www.generatedata.com/
