This is my keyboard layout originally designed for Levinson, a split 40% ortholinear board.
But it should work fine with non-split 40% ortholinear boards as well.

This keyboard layout is designed for software development and some gaming in mind.

## Goals
#### Easy Transition
The layout is designed to be similar to a regular keyboard, at least for the base layer.
The numbers and the special characters had to be put into layers due to size limitations.

In order to help with memorizing the extra layers, every left/right side of layer has a dedicated theme.

#### Ergonomics
The layout is designed to reduce the finger movement.
Most keys are placed on the center columns where the fingers rest, and all the layer buttons can be reached with a thumbs.

Another consideration was compatibility with application shortcuts.
Application shortcuts usually involve a modifier and a button, which is fine, except when the button is on another layer.
Since the modifiers are all on the left side of the board, there could be times when the left hand may need to press the modifier, layer key, and a button simultaneously.
This kind of finger gymnastics can force all fingers out of the home position, and should be minimized.
This is done by placing keys that may be part of a hotkey on the right side of the board for the non-default layers.

#### Gaming
Gaming on a keyboard has different requirements than a keyboard.
Video games often provide means to map actions to keys, so having the most mappable keys available is more important than being able to type all characters or a sensible layout.
Therefore, a separate gaming mode was added to address this specific use case.

## Standard Layout
#### Base Layer
```
,-----------------------------------------------------------------------------------.
| Tab  |   Q  |   W  |   E  |   R  |   T  |   Y  |   U  |   I  |   O  |   P  | Bksp |
|------+------+------+------+------+-------------+------+------+------+------+------|
| Esc  |   A  |   S  |   D  |   F  |   G  |   H  |   J  |   K  |   L  |   ;  |Enter |
|------+------+------+------+------+------|------+------+------+------+------+------|
| Shift|   Z  |   X  |   C  |   V  |   B  |   N  |   M  |   ,  |   .  |   /  |Shift |
|------+------+------+------+------+------+------+------+------+------+------+------|
| Ctrl | Win  | Alt  | FUNC | NUMS |Space |Space | SYMS | Left | Down |  Up  |Right |
`-----------------------------------------------------------------------------------'
```
The base layer is mostly similar to the standard QWERTY layout.
Due to the ortholinear layout, it is missing some symbolic alpha keys which are moved to the symbol layer.
Caps Lock and some of the redundant modifiers on the right side have been removed to fit the Escape and the arrow keys.

#### Number Layer
```
,-----------------------------------------------------------------------------------.
|      |   !  |   @  |   #  |   $  |      |      |   7  |   8  |   9  |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   %  |   ^  |   &  |   *  |      |      |   4  |   5  |   6  |      |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |      |      |   +  |   _  |      |      |   1  |   2  |   3  |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |   0  |   0  |      |      |      |      |
`-----------------------------------------------------------------------------------'
```
This layer can be used to input all the numbers, as well as the symbols available on the number row (except the equal sign).
The number keys are laid out numpad style, and the number symbols are placed in left-to-right, top-to-bottom on the finger-resting columns.

#### Symbols Layer
```
,-----------------------------------------------------------------------------------.
|      |      |      |      |   ~  |      |      |   "  |   '  |      |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |      |      |   (  |   )  |      |      |   {  |   }  |   [  |   ]  |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |      |      |   \  |   |  |      |      |   =  |   -  |   `  |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      |      |
`-----------------------------------------------------------------------------------'
```
This layer contains all the symbols that could not fit in the other layers.
The home row contains the three brackets, and most keys are placed.

#### Function Layer
```
,-----------------------------------------------------------------------------------.
|      |Print | Ins  | Home | PgUp |      |      |  F1  |  F2  |  F3  |  F4  |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      | Next | Del  | End  | PgDn |      |      |  F6  |  F7  |  F8  |  F9  |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      | Prev | Mute | Vol+ | Vol- |      |      |  F9  |  F10 |  F11 |  F12 |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      | WASD |
----------------------------------------------------------------------------------'
```
The right half contains the F keys.
The left half contains the navigation keys and the media keys.

At the bottom-right is the toggle key for switching to the gaming mode.
This button needs to be tapped twice, to prevent accidental activation.

## Gaming Layout: WASD Mode

This mode is designed to be used with only the left half of the board, and comes with its own set of base, number and function layers.
WASD keys are standard movement keys in gaming, so they are kept constant throughout all layers.
This allows layers to be switched without interrupting in-game movement.

The Windows key is a nuisance when gaming, therefore it is turned into a mappable key in this mode.

All in all, the user has access to the three modifiers, tab, escape, WASD, and 12 hotkeys per modifier/layer. This is 6 * 12 mappable keys on half of a keyboard.

## More Ideas
- More intuitive vim support: Some hotkeys are not intuitive to transition into, such as ^ and $.
- Redue reliance on pinky finger: Pinky fingers can probably be used less for special layers, since there are many keys not being used.
- Add mode for non-WASD gaming (e.g. StarCraft 2).
- Map the three Lock keys and the Pause key to be complete.
- Claiming the right half of the board in gaming mode for something useful.
