Kitty themes :
https://github.com/dexpota/kitty-themes


Themes installation instructions:

    If you want to download and use one of these theme you have two options:
        clone the entire kitty-themes repository:

        git clone --depth 1 https://github.com/dexpota/kitty-themes.git ~/.config/kitty/kitty-themes

or download just one theme:

    THEME=https://raw.githubusercontent.com/dexpota/kitty-themes/master/themes/3024_Day.conf
    wget "$THEME" -P ~/.config/kitty/kitty-themes/themes

Choose a theme and create a symlink:

    cd ~/.config/kitty
    ln -s ./kitty-themes/themes/Floraverse.conf ~/.config/kitty/theme.conf

Add this line to your kitty.conf configuration file:
    
    include ./theme.conf


