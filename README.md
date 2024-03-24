# Furniture Science

A turn-based block-pushing puzzle game which is also a bit of a homage. Made in [Puzzle Script Next](https://david-pfx.github.io/PuzzleScriptNext/)


![preview](https://raw.githubusercontent.com/vexorian/furniture-science/main/furniturepreview.gif)

You can go play the game at [https://vexorian.itch.io/furniture-science](https://vexorian.itch.io/furniture-science).

## Talking about the game

  Once there was an attempt to make an open source sequel to the game Kye,
I'm talking stone age stuff, back when sourceforge was a thing. This was written
in visual basic. Kye 3.0 wasn't that interesting. It allowed to push stuff 
diagonally. I dunno what made them thinkg this was a good idea. But as is 
tradition, unofficial Kye sequels come with new objects. In this case, there
was a teleporter block. The teleporter block had some janky logic for when it was
possible to use it to teleport, but it was pushable and pretty interesting.

  Ever since then I've been thinking about puzzles that involve moving teleporters
around. To the point that when *I* made my own version of the bad idea of making
Kye sequels, I copied those teleporters. Even so, a couple of years ago, during
the pandemic, when I started getting into puzzle script, my first puzzle script
game "Clone Cleanup" also copied those teleporter blocks.

  But the puzzles I kept thinking about were actually getting more ridiculous
than that. After playing Portal and Gateways. I kept imagining adding a new kind
of teleporter block, instead of requiring the teleporters to be lining up, they
would be color based and always be active. More so, their angles would allow you
to rotate stuff. Many objects in Xye are direction specific, so that felt interesting. One thing in Xye are the 'Large Blocks' which are just rigid blocks
composed of multiple cells. So one of the idea was rotating these large blocks
using the teleporter blocks. Huh but this stuff was long after I stopped updating
Xye, I was kind of over game dev by then. 

  Back to a couple of years ago, Puzzle script was one of my pandemic hobbies and
I played with it quite a bit. After making 2 or 3 games I was really playing with
it. I wanted to make a new game and was playing around trying to come up with
rigid blocks. All while ignoring the fact that Puzzle script had a very throughout
documentation about how to do rigid blocks. Including an explanation of the
rigid keyword and that sort of thing. Nevertheless, I found out about
startloop/endloop so I was actually managing to do things. I was going to make
some sort of game involving rigid blocks and water and making bridges. But this
startloop/endloop stuff started looking really interesting. I suddenly thought,
since the movement logic is so custom, maybe I can actually do things
like portals... And that's how I figured I had a chance to actually make those
puzzles I was thinking about for so long.

  It was actually a bad idea, because in order to get it to work, I really had to
get used to copy pasting the same rule 4 or 8 or even 16 times and rewriting it
to cover all the variations of each case. The code was a real mess to deal with.
Worse still, many of the things I wanted to do weren't really doable with my ps
skills. But I did manage to get something that ressembled a game with some levels.

  To be honest, I thought the mechanics were cool, but was never really happy
with the levels. Specially the last ones. Maintaining it was also a bit of a
nightmare due to the overly complex code. I eventually stopped relaly doing
puzzle script for a while.

  Which brings me to 2024. My new hobby was "retro" handheld consoles. It's small,
cheap, often Chinese devices that look like a Gameboy or like a Nintendo Switch but
are really designed to play emulators, mostly. I was playing around with some
of them and always felt like I wanted to play puzzlescript. Eventually, a
puzzle script core for retroarch was made and it was added to the custom OS of
one of my favorite devices, the Miyoo mini+. Would this means I would actually
be able to play my own games in a tiny console like that? Not really. It turns out
even my most simple puzzle script games abuse rules so much that they were really slow and glitchy in the Retroarch Puzzlescript core. But nevertheless, this 
insipired me to go back to playing aroudn with Puzzlescript.

  Furniture Science was always my favorite of the puzzlescript games I made back
in 2021. So I would sometimes open it and play it. Or get ideas for new objects.
Many of those ideas were not very good. Some might work but are too much work.
kind of boring and long to solve considering it doesn't even have portals in it.
So I started modifying Furniture Science. I learned about Puzzlescript Next, which
had some parts of Puzzlescript+ which was very useful when making Kye.ps. So I
gave it a try. The real magic of the new features tunred out to be the tags. The
code is so much cleaner now, and I feel it is readable. I was able to optimize the
code quite a bit AND add features AND make it more readable, it's all thanks to
the Pattern:script features. It's not perfect, but the amount of repetition you
usually have to deal with when making stuff in puzzlscript is really one of the
worst things about it, and Pattern:script really tackles it. Then we also have
all the other features from the other forks. This makes making games a lot more
viable. Original puzzle script is sort of optimized for fast prototyping and it's
really good at that. But there's always a lot of friction when it comes to making
games that you might actually want to make available for people to play even though
many might actually have the opinion that you shouldn't use puzzlescript for making
actual non-prototype games. But Puzzlescript Next can really cover a lot of those
deficiencies. 

## Playtest

The latest version is being playtested before adding it to itch.io , you can play it here: https://vexorian.github.io/furniture-science/


