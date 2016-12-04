# apprentice-theme

spacemacs custom theme based on the vim-apprentice color scheme.

# install

* Clone the repo into `~/.emacs.d/private/`

```
cd ~/.emacs.d/private
git clone https://github.com/sjas/apprentice-theme
```

* Add this into your `.spacemacs` (in your `dotspacemacs/user-config`)

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/private/apprentice-theme/")
```

and

```
dotspacemacs-themes '(apprentice)
```
