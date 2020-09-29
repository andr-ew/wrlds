```

k2 screens
menu -> microscript -> sandbox ->

menu/selected

name

  0.0  (ext in)
* 0.0  (k2 + e)
+ 0.5  (e, k1 fine)

menu/grid

e1, e2 select

lp  1 0 f r l p o t m m m m
    2 A f r l p o t m m m m
    3 ; f r l p o t m m m m
    4 ~ f r l p o t m m m m

(e - k3)
- buff/enable
- w: w[0 - ascii] -> off/st/end
- r: oct -> oct / fine / slew
- f: frq -> slew / q / cf
- lvl/slew
- pan/slew
- r/pre
- pl/fade time
- mx: (mix matrix)

(arc - e - k3) 
- e1: scroll
- e2: rotate
- e3: k3 select (in lp, col 5-9 are full select)

controls managed by preset are configurable

mainly abt interacting with existing objects in the ecosystem (like connecting crow and nest, or sending a random operator somewhere)

scenes

no wrlds/wrlds.lua, instead the script ships with a handful of scene.lua scripts as examples loaded via SELECT. users are encouraged to add scenes which include `lib/wrlds` and share them on lines. to facilitate reloading the 
entire wrlds script state including live softcut buffers is saved between loads

crow

include a bowery folder + add facilities to load scripts from norns. scenes by default load a blank script to crow but can define crow scripts to load from the bowery

```
