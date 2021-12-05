# Ukulele-ring-notation-editor
Hello, my name is LaughingAbe the colour coded ukulele teacher from South Africa.
I've been creating a new way to teach music to even young children using a coloured ring notation system. 
So far I have created the notation in a vector graphics editor where each note is drawn with shapes and 
now I want to start automating this time consuming step of converting the tab notation into rainbow filled rings.

For visula examples
https://laughingabecom.wordpress.com/2021/03/08/a-story-of-musical-learning-week-3/

Colour convention:
C = Red
D = Orange
E = Yellow
F = Green
G = Light blue
A = Navy
B = Pink

Each note, played by plucking 1 of the 4 strings, is represented with a coloured ring that can either be filled with a colour or it can be blank (white).

Ring convention:
Navy ring = A0 (String A, fret 0)
Yellow ring = E0 (String E, fret 0)
Red ring = C0
Light blue ring = G0

Fret fill convention
A0 = white; A2 = pink; A3 = red; A5 = orange; A7 = yellow; A8 = green; A10 = light blue; A12 = navy
E0 = white; E1 = green; E3 = light blue;
C0= = white; C2 = orange
G0 = white; G2 = navy

Examples:
A3 = Navy ring + red fill
E1 = Yellow ring + green fill
C2 = Red ring + orange fill

User input = [A3, E1, C2]
Visual output = (Navy ring + red fill); (Yellow ring + green fill); (Red ring + orange fill) 

Future functionality:
Generate score and play sounds in sequence.
Displaying the fretnumbers as well
Ajustable design for rings, fills and colours.
Symbols for 2 strings at the same time
Symbols for chords 
