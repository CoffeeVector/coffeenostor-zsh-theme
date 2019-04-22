# coffeenostor-zsh-theme

## coffeenostor.zsh-theme
A theme file (should be placed in ~/.oh-my-zsh/themes).
This is practically identical to agnoster, but has a right-prompt for vi-mode.
Notice, that it requires my version of vi-mode (vi-mode-coffeevector) to use all of the features.
The new feature includes a right-prompt that has --INSERT-- and --NORMAL-- come at respective times, while also complying with the powerline look

## vi-mode-coffeevector
This is also practically identical to the default vi-mode from oh-my-zsh, but it replaces $MODE_INDICATOR with $INSERT_MODE_INDICATOR and $NORMAL_MODE_INDICATOR.
This allows for the right-prompt to show something while in normal mode and in insert mode.
If this can be achieved without an entirely new plugin, these files should be removed (cause it's annoying to switch a new plugin ya know).
