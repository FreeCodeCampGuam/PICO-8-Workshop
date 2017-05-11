# Pico-8 workshop(s)

## Day 1
1. install pico-8 and get on our discord
    1. while installing, either explore splore or [8bit hero](https://www.youtube.com/watch?v=M7azf71z0QE) and/or [pocketchip](https://www.youtube.com/watch?v=W3qkdB5bzLY)
    2. use our keys if they don't have
2. Overview of Game Dev, Engines, Tools, and Languages used (ppt?)
    1. What is a video game? duh. but do you know what goes into making one?
    2. Game development spans many expertise and skills, not only coding.
        1. Of course, Programming
        2. But there can also be a lot of Math and Logic depending on the game
        2. No game is complete without Art and Music
        4. And if you are planning on selling your game, you can't leave out Marketing
        5. and all the Legal / Business aspects you'll have to tackle
    3. but you don't have to be an expert in any of those to start making games. Now adays there are many tools that do much of that hard work for you.
        1. Unreal Engine (free) - The engine used by most AAA Studios. Professional and heavy duty. Games like Gears of War, Bioshock, Batman Return to Arkham, Rocket League, and of course Unreal Tournament (which is now open source)
        2. Unity (free) - Popular with Indies. Lots of mobile games like Fallout Shelter, Triple Town, Threes, Temple Run, Angry Birds 2, Pokemon GO, Super Mario Run. As well as games like Battlestar Galactica Online, Guns of Icarus, 7 Days to Die, Deus Ex: The Fall, Gone Home, Robocraft, Shelter, Rust, The Forest, Kerbal Space Program, Ori and the Blind forest
        3. GameMaker ($99 +) - Easy and Indie. Games like Hyper Light Drifter, Crashlands, Spelunky, Savant: Ascent, Hotline Miami, Nidhogg, Undertale, Risk of Rain
    4. We will be using Pico-8 though because it is an easy to use all in one game development tool. Pico-8 was designed with harsh limitations chosen to be fun and challenging to work with while cutting out all all the fat that might get in the way of beginners learning how to program or make games. You'll find that people can do so much with pico-8 despite its limitations and the pico-8 "scene" can become very reminiscent of earlier history in game making
3. overview (with jelpi) - while they are installing
    1. terminal - load jelpi.p8
    2. code editor
    3. sprite - edit a sprite and load the game
    4. map editor - add ground so jelpi can reach 1st platform
    4. sfx - same ^
    5. pattern - same ^
    6. go back to code editor and make jelpi jump higher
4. once they all have installed
    1. terminal
        1. help
        2. install_demos
        3. ls
        4. cd demos
        5. load jelpi.p8
        6. change jelpi 
        7. cd ..
        8. mkdir mygames
        9. cd mygames
        10. save myjelpi
        11. save myjelpi.png
        12. folder
        12. share on discord
5. intro to programming
    5. what is everyone's experience with programming? what do you know about it?
    5. (If people ask) What programming language should you use to make games? It really doesn't matter that much. C++ is used if you want fast / graphically intensive games. C# is used for many Microsoft related products. JavaScript is slow but used for all of the Web, but most popular languages have their own Game Engines now as well including Python and Lua
    5. Pico-8 uses lua - often used in game dev as an embeded scrupting language.
        6. (if they care) minecraft, garry's mod, world of warcraft, the witcher, angry birds, civ V, Dark souls, payday: psychonauts, diner dash, dota 2, don't starve, saints row series, sim city/sims gmaes, fable 2, farcry
    5. hello-world (terminal)
    6. colors on the screen from the guide (in the terminal)
    7. reboot (to get blank file)
    9. cd mygames
    10. make first program
    
### Playing around
```
cls, circ, print
var x/y
line x+/y+
    store in vars 
spr
    spr flipped
if flipped line
else only print
while true t+1 print
    color t
_draw circ 
    r:t/10,t
    %10
    sin ?
        sin t/40
            *10
    x + sin
        cos
    y + sin
        cos
    r: + 5  ?(-1,1)
```

### Breakout walkthrough
```
sprite / map editor
    rotate, copy paste, fill
bg, map, paddle
vars padx/y
special funcs
    vars in _init
    draw in _draw
padx += 1
max(padx, 120)
    - width
if btn, move pad
move left
padspeed
draw centered ball
move ball
    rnd start
pause
draw pause
    centered text
    shadow
    blink
solid/collide functions
 in _update
```


### Outcomes
```
data types
    numbers
    string
    tables (later)
variables
operators
    + - * / % .. (string concat) +=
conditionals
    boolean
    logical operators
        == < > <= >= != not
    if/else
loops
    while
    for
functions
    regular
    built-in
    return
```


4. splore
    5. bbs
    6. twitter?