# Visual-Novel-Editor
A derivative of my Dialogue Editor. It's purely a visual novel style

It's based on pygame.

You can change npc image and bg.

```
ver 0.2
add command system in input line.
now has one command ':' which can refered which line is what character say.
sample:
player:line
npc:line

you can also use short way:
p:line
n:line

if you don't use ':' to refered character. system will default as npc say.
now npc use black text color. player use red.

and now add line system upgrade. line will add next to the line you chose
in text list box.

edit line system changed.
example-> 'n:hello'
If you only text 'p:' : the line will only change talker -> 'p:hello'
If you only text 'line' : the line will only change text -> 'n:line'
If you text 'p:line' : the line will all change -> 'p:line'
```
