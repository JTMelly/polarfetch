# polarfetch

### A polar-themed *fastfetch* configuration that nobody wanted or asked for.
(Yes, it is basically just a *fastfetch* config file.)

![Antarctica](/images/Antarctica.png)

Steps:

1) install a *Nerdfont*
2) install *fastfetch*
3) save configuration and text files

## *Nerdfont*

Download a *Nerdfont* from [https://www.nerdfonts.com/#home](https://www.nerdfonts.com/#home). This is needed for glyphs and emojis. Also a mono version will probably help avoid some problems later. Install however you install fonts on your system.

## *fastfetch*

Install *fastfetch* according to the instructions at [https://github.com/fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch). Your usual package manager may provide *fastfetch*. *Homebrew* and *linuxbrew* are also good options for Mac and Linux.

## Configuration

Copy the *config.jsonc* and *.txt* (*ascii* art) files into your `~/.config/fastfetch/` directory. Using a text editor uncomment one and only one of the "`source`" lines near the top of the file. This will select a *polarfetch* "flavor" from among the three options (Antarctica, Corbassière, Svalbard). Run by entering `fastfetch` in your terminal emulator. Optionally, modify your *.bashrc* (or other terminal emulator) to run on launch.