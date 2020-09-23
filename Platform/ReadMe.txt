Hello, folks!

Time ago I found the original version of this program surfing on the
Net (I don't remember where, sorry).
It was unfinished, without sprite animation and with bugs;
so, after a quicky view, I left it to rest in a corner of my hard disk.

But, few weeks ago I downloaded two programs: the Johan Peitz "Happyland
Adventures" and the Carl Warwick "Shaolin Soldier".
The first is written in DJGPP, without source code but with a map editor
to play it, the second is written in Visual Basic, with source code but
with any information about how to build maps and set the characters.

So I rescued this program and I found it very interesting at a second view;
having realized that platform games demo written in visual basic are very
few in the net, I decided to work on it.

Fixed the bugs, maked some modifications at the code, I got Ari Feldman
SpriteLib (my licence number is 156.54.253.2-977991862) to create the
sprites, the tiles and some maps, added sounds, collision detection and
so on.

Well, here is the first playable goal!

Both the programs are in progress:
I think the map editor is on 80% and the engine is on 50%, therefore is
possible you will find some bugs.

Infact, I had thought to create an engine with passing levels from one to
another, but now I get error n. 10 when Redim then Sprite type;
so I am afraid I will have to change the structure of the programs.

Any suggestions for Redim the Sprite Type on fly without restructure this 
programs would help, thanks.

At today you can load different map levels with the batch file included.

Try to create your maps and send them to me; I will include them in the 
final version and you will have a credit.

Send to me your comments, suggestions, bug reports or ideas help by e-mail,
thanks.

Look for the next extensions on this site; 
they will come soon and including:
background and foreground tiles layers, slope tiles, moveable tiles,
graphics effects, more sprites, more music and sounds, speed up graphics
engine and so on.


Goodbye for now and have fun.

Emails are always welcomed: fabiocalvi@yahoo.com


THE GAME (AT TODAY)
--------


CONTROLS

Default keys are as follows:

      Key         Action        

      Left        LEFT          
      Right       RIGHT
      Spacebar    JUMP

      Esc         QUIT


PLAYING

The goal of each level is to complete it and achieve a score as high as
possible collecting the pickups, dodging enemies and bewaring of spikes.

You can't injure the enemies (you are a baby, remember), you can only
jump.

Items you can pickup will only give you points. There are however a
few that give you special powers:

HEART              increases your lives (max 3)
BIG BLUE POTION    increases your health by 10  
SMALL BLUE POTION  increases your health by 5  




MAP EDITOR

Is possible to set the tiles with the left mouse button (after its selection),
cancel it with the right mouse button.

At this moment the position and the set of characters is unchangeable
and undeleted (feature is not included yet).

I think is better to create the platforms with the tiles as first (save), 
then put the items and finally put the characters with player as first
of them (the source code get the first index, "0",  as player).


Enjoy.