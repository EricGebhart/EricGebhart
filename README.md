<p><pre align="center">
<strong>Eric Gebhart /</strong> <a href="https://www.ericgebhart.com">Homepage</a> / <a href="https://tangobreath.com">Tango Home page</a> / <a href="https://github.com/ericgebhart">GitHub</a> / <a href="https://exercism.org/profiles/EricGebhart">Exercism</a> / <a href="https://short-edition.com/fr/auteur/ericag">Short Edition</a>
</pre></p>


I´ve been programming a very long time now. More than 40 years. 
A great amount of the code I have written is proprietary and not viewable.
I have written many tools, debuggers, and development tools, etc.
I have designed and built databases, frameworks and the large complex systems 
that need them. At SAS I was responsible for many 100´s of 1000´s of lines of code.
My strongest skills are Architecture and systems design. I´m good at the big picture.
I´ve done all sorts of databases, object oriented programming, functional programming.
I´ve taught programming in various languages including my own.
The last decade I have been programming in functional languages like Clojure
which I love, and Haskell, mostly for my Xmonad configuration.
Recently I wrote the SPR language on top of python as an answer to a problem
I was solving. The end result is a quite nice functional language, which leverages
python libraries directly and simply.
I´ve written a fair amount of lisp, and lisp languages which I find fascinating
to create. I´ve been an Arch linux, Xmonad user for many years and I´ve written
a lot of emacs lisp. Emacs is the best vi emulator anywhere.
<br/>

The projects that might be interesting here, are 
 * MyQMK - It uses macros extensively and is unlike any other user space in QMK.
 * Arch linux packages - This uses make extensively, and contains some utilities. 
 * Arch linux install - A nice script that automates Arch installs.
 * SPR - A very cool language at this point. [SPR Wiki](https://github.com/EricGebhart/Simple_Process_REPL/wiki)
 * Xmonad - Haskell, It doesn´t change much these days.
 * My emacs setup - It´s home grown, so shows my way of organizing emacs.
 * dfs-clj - This is the core layer above hadoop to manage data partitioning and interfacing with Cascalog. The pail manager needs love, but the project died before that happened.
 * SAS papers and examples which will show my writing and give some insight into SAS ODS for which I was a significant contributor.
 * Word Search - Something I wrote from my own motivations. I have plans for it.
 * Bike Gear Calculator - I wanted a nice one, and I wanted to learn clojure/spec.

### Programming, tools, utilities

- **[MyQMK](https://github.com/EricGebhart/MyQMK/tree/Main/users/ericgebhart)** A sparse tree of my QMK keyboard user space and the keyboards I have keymaps for.
- **[Emacs](https://github.com/EricGebhart/xmonad-setup/)** My old school, from scratch emacs setup. 
- **[Xmonad](https://github.com/EricGebhart/xmonad-setup/)** My Xmonad window manager. 
- **[Arch linux install](https://github.com/EricGebhart/Arch-Setup/)** My Arch linux installation script. 
- **[Arch linux packages](https://github.com/EricGebhart/arch-pkgs/)** My Arch linux Meta packages, as well as a fair bit of code. 
- **[Onboard keyboards](https://github.com/EricGebhart/onboard-keyboards/)** Dvorak and Qwerty Ortho-linear keyboards for the Onboard on screen keyboard. 
- **[view-attachment](https://github.com/EricGebhart/view-attachment/)** Mutt and OS X integration script, written many years ago. 
- **[xmonad-log-applet](https://github.com/EricGebhart/xmonad-log-applet/)** Getting Xmonad to talk over DBus to a toolbar. 
- **[Hunspell Dictionaries](https://github.com/EricGebhart/hunspell-dictionaries/)** A collection of Hunspell dictionaries for use with emacs, or whatever else. 
- **[bc-extensions](https://github.com/EricGebhart/bc-extensions/)** A collection of extensions for use with the bc unix calculator.

### Python projects
- **[SPR - Simple Process Repl](https://github.com/EricGebhart/simple-process-repl)** A simple lisp like programming language and Application framework . 
    [SPR Wiki](https://github.com/EricGebhart/Simple_Process_REPL/wiki)
- **[PBR - Particle Board Repl](https://github.com/EricGebhart/particle-board-repl)**The precursor to SPR. A simple lisp like programming language and Application framework for working with Particle.io boards. 
- **[Plysp](https://github.com/EricGebhart/plysp)** A simple lisp using a BNR grammar, works but falls short does not yet have closures or macros. 

### Clojure projects
- **[Word search](https://github.com/EricGebhart/word-search/)** Collect meta data and create conjugaison trees from words in wiktionary.
- **[bike gear calc](https://github.com/EricGebhart/bike-gear-calc/)** A bike gear calculator for differnt types of bikes which uses Schema.
- **[bike gear calc UI](https://github.com/EricGebhart/bgc-ui/)** The beginning of a clojurescript/ReFrame UI for the bike-gear-calculator.

##### These are libraries I created and used within the Applications I created for Yeti Data.
- **[clojure cli extension](https://github.com/EricGebhart/clj-cli-ext/)** A library to make the creation of command line interfaces in clojure easier and more robust.
- **[datetime data](https://github.com/EricGebhart/datetime-data/)** A datetime library for normalizing dates.
- **[file access](https://github.com/EricGebhart/file-access/)** A file-access library to which creates a consistent API for various types of files. 
- **[dfs-clj](https://github.com/EricGebhart/dfs-clj/)** A library which combines all of the dfs libraries into one, for managing dfs datastores for cascalog in hadoop..

##### The folowing are all embodied in dfs-clj, but existed separately before it´s existence.
- **[pail-graph](https://github.com/EricGebhart/pail-graph/)** Extension library to streamline the use of Graph Schema thrift objects with Pail and Cascalog.
- **[pail-schema](https://github.com/EricGebhart/pail-schema/)** Dfs-datastores Pail infrastructure using Prismatic Schema and Fressian.

- **[clj-pail-tap](https://github.com/EricGebhart/clj-pail-tap/)** Extension library to enable easier tapping of pails.
- **[Pail-Fressian](https://github.com/EricGebhart/Pail-Fressian/)** Pail structure, serializer and partitioners using Fressian.
- **[Pail-Schema-Example](https://github.com/EricGebhart/Schema-Example/)** Example of using pail-schema to validate, coerce, and write data to a pail, then query it with cascalog.

- **[clj-thrift](https://github.com/EricGebhart/clj-thrift/)** A Clojure abstraction for Thrift.
- **[clj-pail](https://github.com/EricGebhart/clj-pail/)** A Clojure abstraction for working with Pail.
- **[pail-thrift](https://github.com/EricGebhart/pail-thrift/)** Serialization and partitioning strategies for using Thrift with clj-pail.
- **[pail-cascalog](https://github.com/EricGebhart/pail-thrift/)** A Clojure library for working with Pail within Cascalog.
- **[thrift-pail-cascalog-example](https://github.com/EricGebhart/thrift-pail-cascalog-example/)** An example of using graph schema, thrift, pail and cascalog..

### Code tests and explorations

- **[Exercism](https://exercism.org/profiles/EricGebhart)** The exercises I´ve done over the years in Exercism. 
- **[flickr-fetcher](https://github.com/EricGebhart/flickr-fetcher)** A design for a simple http endpoint to give recent images from flickr. This solved the enterprise´s problems with scalability, image size and quality, while allowing fall backs to simpler choices according to resource availability. 
- **[Suduko validator](https://github.com/EricGebhart/suduko-validator/)**Clojure: A calculator to validate a suduko board. A nicer solution to a code test I did in python. 
- **[Poker](https://github.com/EricGebhart/poker/)**Clojure: A game of poker from the Asheville Coders League Day of Code challenge.  
- **[Swapp](https://github.com/EricGebhart/swapp/)**Clojure: A simple example to understand clojurescript and figwheel.  
- **[Product Inventory Server](https://github.com/EricGebhart/product-inventory/)** A product inventory server written with python and flask.  A code test.
- **[Product Inventory UI](https://github.com/EricGebhart/https://github.com/EricGebhart/prod-inv-ui/)** A clojurescript/ReFrame/React front end for a product inventory control system.

### SAS related projects, papers, etc.

- **[SAS-Papers](https://github.com/EricGebhart/SAS-Papers)** My various papers I wrote and presented during my 17 years at SAS. 
- **[SAS-Examples](https://github.com/EricGebhart/SAS-Examples)** The Example code to go with all of the papers. 
- **[SAS-Tagsets](https://github.com/EricGebhart/SAS-Tagsets)** The Source for all the official SAS Tagsets as of 2013. 
- **[SAS-Vim](https://github.com/EricGebhart/SAS-Vim/)** Vim extensions for programming with Vim. - Do not use this anylonger.. 

### Contributions
- **[QMK Firmware](https://github.com/EricGebhart/qmk_firmware/)** QMK firmware for custom keyboards.
- **[Open SCAD clj](https://github.com/EricGebhart/clj-scad/)** A clojure wrapper for Open-scad so that scad can be programmed from clojure.
- **[Golden Ratio](https://github.com/EricGebhart/golden-ratio.el)** Emacs package which automatically resizes windows in an intelligent way. 
- **[cider](https://github.com/EricGebhart/cider)** . 
