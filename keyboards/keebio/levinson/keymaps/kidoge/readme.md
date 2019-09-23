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
Most keys are placed on the center columns where the fingers rest, and all the layer buttons can be reached with a thumb.

Commonly used keys are placed toward the center of the keyboard, so that stronger fingers are used to press them.

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
The right half contains the numpad, with a couple of options for 0.
The right half contains the number symbols are placed in left-to-right, top-to-bottom on the finger-resting columns.
Unshifted - and = can be found on the symbol layer.

#### Symbol Layer
```
,-----------------------------------------------------------------------------------.
|      |      |   ~  |   [  |   ]  |      |      |   "  |   '  |   `  |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |      |   |  |   (  |   )  |      |      |   {  |   }  |   \  |      |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |      |      |      |   |  |      |      |   =  |   -  |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |      |      |      |      |      |
`-----------------------------------------------------------------------------------'
```
This layer contains all the symbols that could not fit in the other layers.

#### Function Layer
```
,-----------------------------------------------------------------------------------.
|      | PrSc | Ins  | Home | PgUp |      |      |  F1  |  F2  |  F3  |  F4  |      |
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

## Gaming Mode
This mode is enabled by double-tapping Fn-WASD.
The same input can be used to exit the gaming mode.

This mode is designed to be used with only the left half of the board, and comes with its own set of base, number and function layers.
WASD keys are standard movement keys in gaming, so they are kept constant throughout all layers.
This allows layers to be switched without interrupting in-game movement.
```
,-----------------------------------------.      .-----------------------------------------.
|      |      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+-------      +------+------+------+------+------|------|
|      |      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------|      +------+------+------+------+------|------|
|      |      |      |      |      |      |      |      |      |      |      |      |      |
|------+------+------+------+------+------+      +------+------+------+------+------|------|
|      |Pause |      |W_FUNC|W_NUMS|      |      |      |      |      |      |      |      |
`-----------------------------------------'      '-----------------------------------------'
```
The Windows key is a nuisance when gaming, therefore it is replace with pause, which can be mapped in-game.
The layer keys now point to gaming counterparts of Number and Function layers
```
,-----------------------------------------------------------------------------------.
|      |   1  |   W  |   2  |   3  |   4  |      |      |      |      |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   A  |   S  |   D  |   5  |   6  |      |      |      |      |      |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |   7  |   8  |   9  |   0  |   -  |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      |   =  |      |      |      |      |      |      |      |      |      |      |
`-----------------------------------------------------------------------------------'
```
The Number layer replaces all non-WASD alphas and the windows key with the number row.
```
,-----------------------------------------------------------------------------------.
|      |  F1  |   W  |  F2  |  F3  |  F4  |      |      |      |      |      |      |
|------+------+------+------+------+-------------+------+------+------+------+------|
|      |   A  |   S  |   D  |  F5  |  F6  |      |      |      |      |      |      |
|------+------+------+------+------+------|------+------+------+------+------+------|
|      |  F7  |  F8  |  F9  |  F10 | F11  |      |      |      |      |      |      |
|------+------+------+------+------+------+------+------+------+------+------+------|
|      | F12  |      |      |      |      |      |      |      |      |      | WASD |
`-----------------------------------------------------------------------------------'
```
The Function layer replaces all non-WASD alphas and the windows key with the F keys.

All in all, the user has access to the three modifiers, tab, escape, WASD, and 12 hotkeys per modifier/layer. This is 72 (6*12) mappable keys on half of a keyboard.

## More Ideas
- More intuitive vim support: Some hotkeys are not intuitive to transition into, such as ^ and $.
- Redue reliance on pinky finger: Pinky fingers can probably be used less for special layers, since there are many keys not being used.
- Add mode for non-WASD gaming (e.g. StarCraft 2).
- Map the three Lock keys and the Pause key to be complete.
- Claiming the right half of the board in gaming mode for something useful.
