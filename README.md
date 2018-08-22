# DDWlib Plugin Installer Recommendations

## What it does?

A library class to to tweak the results of the WordPress Plugins API with custom plugin recommendations. Via a filter existing recommendations can be removed or tweaked and new ones added. There is a class check included so it is only loaded once no matter how many plugins have included it. Also the instantiating function/hook is pluggable so you can instantiate yourself if needed.


## Why was it built?

By default the WordPress plugin installer displays always the same results on the "Featured" tab - which are not helpful or useful at all. Also, how the tabs "Popular" and "Recommended" are curated or "queried" is unclear and not transparent. This class here let's you change that: for all three tabs you can hook in your own results.

That is the reason I built it because I wanted that for all my plugins to give the user more relevant results - for the target user group of my plugins. At the same time I wanted to use the default WordPress installer - which the users are used to.


## Contributions?

Any contribution is welcome, especially code-wise. Please contact me - open an Issue and/ or a Pull request here in the repo.


## License?

The library is licensed under GPLv2 or later like WordPress itself.


## Author/ Developer?

* David Decker from Chemnitz, Germany
* https://deckerweb.de/
* https://toolbarextras.com/


## Copyright

(c) 2018 by David Decker - DECKERWEB