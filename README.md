# buzzwordbingo
Generates HTML bingo cards from a list of terms. Written for the 2008
University of Washington Genome Sciences Department Retreat.

Usage: `python bingo.py <word file> <number of cards>`

The word file contains one word per line, and can include HTML tags for text 
formatting. The output is an HTML file with the specified number of bingo cards 
populated randomly from the word list. Duplicate cards are possible (and likely
if the word list is small).
