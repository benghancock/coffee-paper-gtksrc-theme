# Coffee Paper Theme

## About

"Coffee Paper" is a light theme for graphical Linux text editors using 
[GTKSourceView](https://wiki.gnome.org/Projects/GtkSourceView/)
for syntax higlighting, such as XFCE's 
[Mousepad](https://docs.xfce.org/apps/mousepad/start). 
It aims to use a minimal palette that is easy on the eyes, 
and imitate the experience of writing on paper. This theme
draws inspiration from Yorick Peterse's
[Vim Paper](https://gitlab.com/yorickpeterse/vim-paper)
and the
[Pen Paper Coffee](https://github.com/nylki/pen-paper-coffee-vscode)
theme for VS Code. Its minimal approach to highlighting is
inspired by
[Alabaster](https://github.com/tonsky/vscode-theme-alabaster).

## Installation

Clone the repo anywhere in your home directory. Then create
a symlink to the `coffee-paper.xml` file in the directory
`$HOME/.local/share/gtksourceview-4/styles`.

Example:

```shell
$ cd $HOME/src
$ git clone git@github.com:benghancock/coffee-paper-gtksrc-theme.git
$ cd $HOME/.local/share/gtksourceview-4/styles
$ ln -s $HOME/src/coffee-paper-gtksrc-theme/coffee-paper.xml coffee-paper.xml
```

After doing that, you should see "Coffee Paper" as an option
when selecting a color scheme in your editor. (In Mousepad,
choose "View" from the menu bar, then "Color Scheme -> Coffee Paper").
