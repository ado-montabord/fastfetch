

Install My Fastfetch Configuration

To install my Fastfetch configuration, simply copy/paste my .config file as well as the logo (ASCII art or image) of your choice into the following folder:
~/.config/fastfetch
Make sure the folder exists; if not, create it with:

mkdir -p ~/.config/fastfetch

Then place:

the configuration file config.jsonc (or .conf, depending on your version),

and your custom logo (for example an ASCII or image file)

into ~/.config/fastfetch.

If you want to use another logo, you can simply replace the existing file in the folder and update its path inside your .config file (usually in the logo or custom section depending on your setup).

Once everything is done, run:

fastfetch
