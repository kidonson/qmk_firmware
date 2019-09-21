# MiniGrid Layout

MiniGrid is a keyboard layout originally designed for Levinson, a split 40% ortholinear board.
But it should work well with non-split 40% ortholinear boards as well.

This keyboard layout is designed for software development and gaming in mind. 

## Goals
- The layout should be similar enough to easily transition into.
- The layout should make logical sense to make memorization easier.
- The layout should minimize finger movement.
- The layout should allow application hotkeys to be input without finger gymnastics.
- The layout should be usable for gaming with just the one of the halves of the split keyboard.

## The Layout
### Base Layer

```
,-----------------------------------------------------------------------------------.
| Tab  |   Q  |   W  |   E  |   R  |   T  |   Y  |   U  |   I  |   O  |   P  | Bksp |
|------+------+------+------+------+-------------+------+------+------+------+------|
| Esc  |   A  |   S  |   D  |   F  |   G  |   H  |   J  |   K  |   L  |   ;  |Enter |
|------+------+------+------+------+------|------+------+------+------+------+------|
| Shift|   Z  |   X  |   C  |   V  |   B  |   N  |   M  |   ,  |   .  |   /  |Shift |
|------+------+------+------+------+------+------+------+------+------+------+------|
| Ctrl | GUI  | Alt  | Func | Nums |Space |Space | Syms | Left | Down |  Up  |Right |
`-----------------------------------------------------------------------------------'
```

The base layer is mostly similar to the standard QWERTY layout.
Due to the ortholinear layout, it is missing some symbolic alpha keys: \`, \, ', [ and ], which are moved to the symbol layer.
Caps Lock and some of the redundant modifiers on the right side have been removed to fit the Escape and the arrow keys.
The arrow keys are laid out in the same order as Vim movement keys.

### Number Layer
```
,-----------------------------------------------------------------------------------.
|      |   !  |   @  |   #  |   $  |      |      |   7  |   8  |   9  |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   %  |   ^  |   &  |   *  |      |      |   4  |   5  |   6  |      |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |      |   +  |   -  |   _  |      |      |   1  |   2  |   3  |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |   0  |   0  |      |      |      |      |
`-----------------------------------------------------------------------------------'
```
This layer can be used to input all the numbers, as well as the symbols available on the number row (except the equal sign).
The number keys are laid out numpad style, and the number symbols are placed in left-to-right, top-to-bottom on the finger-resting columns.

The underscore is placed next to the layer key so that it is easy to locate and press, since it is a symbol that is very often used.

### Symbols Layer
```
,-----------------------------------------------------------------------------------.
|      |      |      |   `  |   ~  |      |      |   "  |   '  |      |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   [  |   ]  |   (  |   )  |      |      |   {  |   }  |      |      |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |      |      |   \  |   |  |      |      |   =  |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      |      |
`-----------------------------------------------------------------------------------'
```
This layer contains all the symbols that could not fit in the other layers.
The brackets are on the home row, since they are used often when programming.
    
The equal sign is also one of the most often used symbols when writing software.
So it is placed right next to the layer key for the same reason as the underscore.

### Function Layer
    
### Gaming: WASD Mode


## TODOs
More intuitive vim support: Some hotkeys are not intuitive to transition into, such as ^ and $.
Redue reliance on pinky finger: Pinky fingers can probably be used less for special layers, since there are many keys not being used. 
Add mode for non-WASD gaming (e.g. StarCraft 2).
Map the three Lock keys and the Pause key to be complete.
