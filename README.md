# tic-tac-toe
# Makefile for web deployment

all: PutHTML

PutHTML:
	cp tictac.html /var/www/html/tic-tac-toe/
	cp tictac.css /var/www/html/tic-tac-toe/
	cp tictac.js /var/www/html/tic-tac-toe/
	
	echo "Current contents of your HTML directory: "
	ls -l /var/www/html/tic-tac-toe/

