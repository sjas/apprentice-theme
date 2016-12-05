# apprentice-theme

spacemacs custom theme based on the vim-apprentice color scheme.

# install

* Clone the repo into `~/.emacs.d/private/`

```
cd ~/.emacs.d/private
git clone -v --progress https://github.com/sjas/apprentice-theme
```

* Add this into your `.spacemacs` (at `dotspacemacs/user-config`)

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/private/apprentice-theme/")
(load-theme 'apprentice)
```

and change under `dotspacemacs/init()`

```
dotspacemacs-themes '(apprentice ... )
```

such that `apprentice` becomes the first entry.
