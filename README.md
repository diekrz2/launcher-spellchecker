[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/paypalme/rbtylee)

# Launcher Spell checker

This is a plugin for [Moksha's](https://github.com/JeffHoogland/moksha) Quick Launcher to check the spelling of words using aspell as a backend.

It is a resurrection of the old e17 [*everything-aspell module*](https://git.enlightenment.org/legacy/subversion-history.git/tree/trunk/E-MODULES-EXTRA/everything-aspell) *with only minor [Bodhi](https://www.bodhilinux.com/) specific changes*. With enough demand, support and time willing I plan on taking over maintaining this module as it is currently unmaintained but rather cool.


<p align="center">
  <img src="https://i.imgur.com/WSQErOl.png" alt="Screen Shot">
</p>

# Dependencies

* The usual build tools, autopoint libtool intltool pkg-config  autotools-dev
* [EFL](https://www.enlightenment.org/download)
* [Moksha](https://github.com/JeffHoogland/moksha)
* [aspell](http://aspell.net/)
* aspell-en (optional)

**Note:** 
>The default aspell dictinary is english (aspell-en). You can, of course, use other dictionaries with this module.
>However before they are available you need to change the dictionary in the module settings. You must have at least one dictionary installed to use the spell checking functionality.

# Usage

First one must load the module. Now assuming one has aspell installed and an aspell dictionary, then usage should be as simple as opening Mokshas Quick Launcher and typing 's ' without the single quote marks. Note: one must type the blank following the s. The prompt will change to a colon and now type a word one wishes to check the spelling of. A list as pictured above will be displayed.

For a detailed explantaion of how to use this module complete with pictures see the wiki:

>https://github.com/rbtylee/launcher-spellchecker/wiki/Usage

# Installation

It is recommended Bodhi users install from Bodhi's repo:

```ShellSession
sudo apt update
sudo apt install moksha-module-spellcheck
```

Other users need to compile the code:

First install all the needed dependencies. Note this includes not only EFL but the EFL header files as well as the [e_dbus](https://git.enlightenment.org/legacy/e_dbus.git/) header files. If you have compiled and installed EFL, e_dbus and Moksha from source code this should be no problem. 

Then the usual:

```ShellSession
./autogen.sh
make
sudo make install
```

# Reporting bugs

Please use the GitHub issue tracker for any bugs or feature suggestions:

https://github.com/rbtylee/launcher-spellchecker/issues

# Contributing

Please submit patches to code or documentation as GitHub pull requests!

Contributions must be licensed under this projects copyright (see COPYING). 

# Support This Project

*Coming soon*

# Credits

Full credit for the original code of this module go the enlightenment developers:
* Gustavo Barbieri
* Hannes Janetzek

and any others than may have committed on this module.

<p align="center">
  <i>I Stand on the shoulders of giants.</a>
</p>
