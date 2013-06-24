# esh-help.el

This library adds the following help features for Eshell:
* run-help functionality inspired by Zsh
* eldoc functionality

To use this package, add these lines to your `.emacs` file:
```elisp
    (require 'esh-help)
    (esh-help-eldoc-setup)  ;; To use eldoc in Eshell
```
And by using `M-x eldoc-mode` in Eshell, you can see help strings
for the pointed command in minibuffer.
And by using `M-x esh-help-run-help`, you can see full help string
for the command.
