This is a fork of powerline.el which I began while the original
authorship of powerline was unknown.

- Note: Forked from the original emacs port of vim powerline,
Powerline.el by Nicolas Rougier

## Using main-line.el

Add a require to .emacs / init.el

     (require 'main-line)

You can customize the separator graphic by setting the custom variable

     main-line-separator-style
     
e.g.

     (setq main-line-separator-style 'wave)

possible values...

- `wave`
- `zigzag`
- `butt`
- `wave-left`
- `zigzag-left`
- `butt-left`
- `wave-right`
- `zigzag-right`
- `butt-right`
- `chamfer`
- `chamfer14`
- `rounded`
- `arrow`
- `arrow14`
- `slant`
- `slant-left`
- `slant-right`
- `curve`

To customize the modeline - simply override the value of mode-line-format,
see the default at the end of the script, as an example.

You can create your own modeline additions by using the defmain-line macro.

for example,

    (defmain-line row "%4l")

gives you `main-line-row` to use in `mode-line-format`

Note. Using `main-line-percent-xpm` requires 18px separators (use
`main-line-percent` with `arrow14` or `chamfer14`)

A few examples...

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-wave.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-zigzag.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-butt.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-curve.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-chamfer.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-rounded.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-slant.png)

![](https://raw.github.com/jasonm23/emacs-mainline/master/emacs-main-line-arrow.png)


