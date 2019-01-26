[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/paypalme/rbtylee)

# Launcher Spell checker

This is a plugin for [Moksha's](https://github.com/JeffHoogland/moksha) Quick Launcher to check the spelling of words using aspell as a backend.

It is a resurrection of the old e17 [everything-aspell module](https://git.enlightenment.org/legacy/subversion-history.git/tree/trunk/E-MODULES-EXTRA/everything-aspell). With enough demand, support and time willing I plan on taking over maintaining this module as it is currently unmaintained but rather cool.

<p align="center">
  <img src="https://i.imgur.com/WSQErOl.png" alt="Screen Shot">
</p>

# Dependencies

* [Moksha](https://github.com/JeffHoogland/moksha)
* [aspell](http://aspell.net/)
* aspell-en (optional)

**Note:** 
>The default aspell dictinary is english (aspell-en). You can, of course, use other dictionaries with this module.
>However before they are available you need to change the dictionary in the module settings. You must have at least one dictionary installed to use the spell checking functionality.

# Installation

It is recommended Bodhi users install from Bodhi's repo:

```
sudo apt update
sudo apt install moksha-module-spellcheck
```

Other users need to compile the code:

```
./autogen.sh
make
sudo make install
```

# Credits

Full credit for the orginal code of this module go the enlightenment developers:
* Gustavo Barbieri
* Hannes Janetzek
and any others than may committed on this module.
