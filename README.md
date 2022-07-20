<p><pre align="center">
<strong>Eric Gebhart /</strong> <a href="https://www.ericgebhart.com">Homepage</a> / <a href="https://tangobreath.com">Tango Home page</a> / <a href="https://github.com/ericgebhart">GitHub</a> / <a href="https://exercism.org/profiles/EricGebhart">Exercism</a> / <a href="https://short-edition.com/fr/auteur/ericag">Short Edition</a>
</pre></p>


I´ve worked in many domains over the decades. I´ve designed and built
many systems, most of which are proprietary. My strongest languages are
C, python, clojure, elisp. I have done a lot of object oriented work in
C derived languages and python. My favorite is clojure and functional
programming which I am likely to do in any language. If you really want
to know who I am, the best place to start is my website which is also
my resumé should you decide to print it. 

I´ve been an Arch linux, Xmonad user/programmer for many years and I´ve written
a lot of Emacs lisp.


#### Natural Languages
I am very interested in learning natural languages. I developed my
own pedagogy in order to learn french, and I am now working to refine 
and automate that process in order to learn others.
I´ve done some plugins for Anki in the past. I also write, so my 
emacs is setup with a variety of tools to enable that, input methods, 
language-tool, dictionaries, synonyms, etc.  My QMK keyboard firmware also 
supports multiple languages.


#### My old book - ODS Markup: Tagsets by Example.
If you are a user of SAS ODS and Tagsets, you may be interested in the
book I wrote many years ago on my Tagset language. It was slated to be
published by SAS Press but never was. So I give it here for free.
Installing LateX and compiling it to pdf is on my todo list.


#### Code tests
You might notice I have a few code tests, some of these have come to
me in interview processes. I am not a fan of code tests as part of an
interview process, I feel they are too narrow in mindset and too full
of unexpressed expectations which bias the results in a negative way. 
I do enjoy a good code puzzle, or doing code to learn something.
But that is something else altogether. Even a code puzzle is no longer
a puzzle when in the guise of a code test.

My current solution is to either refuse a code test or apply
the minimum effort and time to the code test which gives the results
expected. It is throw away code anyway. It is the discussion which
is important, not the code. The code test is, in my mind, a waste of my time.

I have a ton of experience, I know where the parenthesis go, I have a 
working programming environment for many languages and I can read. 
If you need help I can give it.

I generally code using a combination of TDD (Test Driven Development) and 
RDD (REPL Driven Development) in the languages that support that.

<br/>

### Some projects that might be insightful here.

_Note: My activity in 2021 was quite low because I had very poor vision for most of the year from cataracts which have now been corrected._

Of the work I´ve done, here are my favorite projects, which may show some of my skills.
My Arch linux is setup stable and only requires maintenance as packages come and go.
It is interesting because it uses a combination of _Make_, _Arch Packages_, _github_ and 
the Arch AUR via Yay to do it´s job.

Every so often I go through an update of my system, Arch, emacs and xmonad setups to 
drop old ways and adopt new ones.

My current favorite projects over all others are _SPR_, _Plysp_,
_Word-Search_, _Bike-Gear-Calculator_, and *QMK_firmware*/_MyQMK_.
My _QMK_, _Xmonad_ and _Emacs_ setups are always getting tweaks. I have
not been doing 3D work lately, but when I do, I use _scad-clj_.

My _dfs-clj/DFS datastore library_ does make it very easy to create
immutable, partitioned/sliced no sql databases with hadoop, which can be
quite fun to play with. Ironically I feel that Cascalog integrates with
Clojure much more nicely than Datomic´s datalog which I find verbose
and ugly. The pail-manager needs a redesign, but dfs-clj has worked
admirably with a variety of big data sources over extended periods.

<br/>

- **[Arch linux packages](https://github.com/EricGebhart/arch-pkgs/)** - This uses _Make_ to create nice repeatable installation of packages. 
- **[Arch linux install](https://github.com/EricGebhart/Arch-Setup/)** My Arch linux installation script. 
- **[SPR - Simple Process Repl](https://github.com/EricGebhart/Simple_Process_REPL)** - A very cool stackless, auto-binding, self-documenting language at this point. [SPR Wiki](https://github.com/EricGebhart/Simple_Process_REPL/wiki)
- **[Plysp](https://github.com/EricGebhart/plysp)** A simple lisp after clojure. [~90% complete] - SPR has been too fun.
- **[My Xmonad](https://github.com/EricGebhart/xmonad-setup/)** window manager. A fairly extensive custom configuration/executable.
- **[My Emacs Setup](https://github.com/EricGebhart/emacs-setup/)** - It´s home grown since 1995, so this shows my way of organizing emacs.
- **[scad-clj](https://github.com/EricGebhart/scad-clj/)** Coding Open SCAD with clojure, I contributed significantly in it´s beginnings.
- **[clojure cli extension](https://github.com/EricGebhart/clj-cli-ext/)** A library to make the creation of command line interfaces in clojure easier and more robust.
- **[datetime data](https://github.com/EricGebhart/datetime-data/)** A Clojure datetime library for normalizing dates.
- **[file access](https://github.com/EricGebhart/file-access/)** A Clojure file-access library to which creates a consistent API for various types of files. 
- **[dfs-clj](https://github.com/EricGebhart/dfs-clj/)** - This is the core layer above hadoop to manage pails, data partitioning, and tapping into data with Cascalog. After _Nathan Marz_´s Lambda Architecture.
- **[Pail-Schema-Example](https://github.com/EricGebhart/Pail-Schema-Example/)** - This is an example project that shows how to use pails and schema with hadoop and cascalog. This is using dfs-clj before dfs-clj came about. See my __[post Here.](https://www.ericgebhart.com/blog/clojure/2014-03-06-Using-prismatic-schema-with-fressian-pail-and-cascalog/)__ And another __[post here.](https://www.ericgebhart.com/blog/clojure/2014-01-23-Using-pail-with-a-graph-schema/)__
- **[Word search](https://github.com/EricGebhart/word-search/)** - Something I wrote from my own motivations. A meta data collector for words. I have plans for it.
- **[bike gear calculator](https://github.com/EricGebhart/bike-gear-calc/)** - I wanted a nice one, and I wanted to learn clojure/spec.
- **[flickr-fetcher](https://github.com/EricGebhart/flickr-fetcher)** - A code test, turned into a design test. It won a job for me and solved their troubles.
- **[ODS Markup: Tagsets by Example](https://github.com/EricGebhart/Tagsets-by-example)** - A book I wrote about ODS Markup, never published, for forgotten reasons.
- **[SAS-Papers](https://github.com/EricGebhart/SAS-Papers)** - My papers which will show my writing and give some insight into SAS ODS for which I was a significant contributor.

### Programming, tools, utilities

- **[MyQMK](https://github.com/EricGebhart/MyQMK/tree/Main/users/ericgebhart)** A sparse tree of my QMK keyboard user space and the keyboards I have keymaps for.
- **[Emacs](https://github.com/EricGebhart/emacs-setup/)** My old school, from scratch emacs setup. 
- **[Xmonad](https://github.com/EricGebhart/xmonad-setup/)** My Xmonad window manager. 
- **[Arch linux install](https://github.com/EricGebhart/Arch-Setup/)** My Arch linux installation script. 
- **[Arch linux packages](https://github.com/EricGebhart/arch-pkgs/)** My Arch linux Meta packages, as well as a fair bit of code. 
- **[Onboard keyboards](https://github.com/EricGebhart/onboard-keyboards/)** Dvorak and Qwerty Ortho-linear keyboards for the Onboard on screen keyboard. 
- **[view-attachment](https://github.com/EricGebhart/view-attachment/)** Mutt and OS X integration script, written many years ago. 
- **[xmonad-log-applet](https://github.com/EricGebhart/xmonad-log-applet/)** Getting Xmonad to talk over DBus to a toolbar, an orphaned project which I brought back to life. 
- **[Hunspell Dictionaries](https://github.com/EricGebhart/hunspell-dictionaries/)** A collection of Hunspell dictionaries for use with emacs, or whatever else. 
- **[bc-extensions](https://github.com/EricGebhart/bc-extensions/)** A collection of extensions for use with the bc unix calculator.

### Python projects
- **[SPR - Simple Process Repl](https://github.com/EricGebhart/Simple_Process_REPL)** A simple lisp like programming language and Application framework . 
    [SPR Wiki](https://github.com/EricGebhart/Simple_Process_REPL/wiki)
- **[PBR - Particle Board Repl](https://github.com/EricGebhart/Particle_Board_REPL)** The precursor to SPR. A simple lisp like programming language and Application framework for working with Particle.io boards. 
- **[Plysp](https://github.com/EricGebhart/plysp)** A simple lisp after clojure using a BNR grammar, It works but falls short of complete. The plan is to turn the core into Cython when it is time for performance enhancement. It does not yet have tail call recursion or a complete implementation of macros among other things.  
- **[Bar QR code](https://github.com/EricGebhart/barqrcode)** A simple program to print bar and qr codes. Written one afternoon according to the desires of a client. Not my style,
but there it is. 
[I rewrote this in SPR as an example, that one is nicer.](https://github.com/EricGebhart/Simple_Process_REPL/blob/main/examples/print-codes/print_codes.spr)

### Clojure projects
- **[Word search](https://github.com/EricGebhart/word-search/)** Collect meta data and create conjugaison trees from words in wiktionary.
- **[bike gear calc](https://github.com/EricGebhart/bike-gear-calc/)** A bike gear calculator for fixed gear, internal gear and deraileur gear bikes which uses Schema.
- **[bike gear calc UI](https://github.com/EricGebhart/bgc-ui/)** The beginning of a clojurescript/ReFrame UI for the bike gear calculator.

#### Libraries that I created and used within the Applications I created for Yeti Data.
- **[clojure cli extension](https://github.com/EricGebhart/clj-cli-ext/)** A library to make the creation of command line interfaces in clojure easier and more robust.
- **[datetime data](https://github.com/EricGebhart/datetime-data/)** A datetime library for normalizing dates.
- **[file access](https://github.com/EricGebhart/file-access/)** A file-access library which creates a consistent API for various types of files, S3, SFTP, Github. 

#### Dfs datastores, These libraries were inspired by _Nathan Marz_, his book _Big Data_ and the Lambda Architecture. Pre Clojure/Schema. Uses Prismatic Schema and Fressian.
- **[dfs-clj](https://github.com/EricGebhart/dfs-clj/)** A library which combines all of the dfs libraries into one, for managing dfs datastores with cascalog on hadoop.
  **The following libraries are all embodied in dfs-clj.**
  - **[pail-graph](https://github.com/EricGebhart/pail-graph/)** Extension library to streamline the use of Graph Schema thrift objects with Pail and Cascalog.
  - **[pail-schema](https://github.com/EricGebhart/pail-schema/)** Dfs-datastores Pail infrastructure using Prismatic Schema and Fressian.
  - **[clj-pail-tap](https://github.com/EricGebhart/clj-pail-tap/)** Extension library to enable easier tapping of pails.
  - **[Pail-Fressian](https://github.com/EricGebhart/Pail-Fressian/)** Pail structure, serializer and partitioners using Fressian.
  - **[Pail-Schema-Example](https://github.com/EricGebhart/pail-schema-example/)** Example of using pail-schema to validate, coerce, and write data to a pail, then query it with cascalog.
  - **[clj-thrift](https://github.com/EricGebhart/clj-thrift/)** A Clojure abstraction for Thrift.
  - **[clj-pail](https://github.com/EricGebhart/clj-pail/)** A Clojure abstraction for working with Pail.
  - **[pail-thrift](https://github.com/EricGebhart/pail-thrift/)** Serialization and partitioning strategies for using Thrift with clj-pail.
  - **[pail-cascalog](https://github.com/EricGebhart/pail-thrift/)** A Clojure library for working with Pail within Cascalog.
  - **[thrift-pail-cascalog-example](https://github.com/EricGebhart/thrift-pail-cascalog-example/)** An example of using graph schema, thrift, pail and cascalog..

### Code tests and explorations

- **[Exercism](https://exercism.org/profiles/EricGebhart)** Clojure, Haskell, scheme, python. The exercises I´ve done over the years in Exercism. 
- **[flickr-fetcher](https://github.com/EricGebhart/flickr-fetcher)** Clojure/Design. A design for a not so simple http endpoint to give recent images from flickr. This solved the enterprise´s problems with scalability, image size and quality, while allowing
compromises and staging of the implementation according to resource availability.
- **[Suduku validator](https://github.com/EricGebhart/sudoku-validator)** Clojure: A calculator to validate a suduku board. A nicer solution to a code test I did in python. 
- **[Poker](https://github.com/EricGebhart/poker/)** Clojure: A game of poker from the Asheville Coders League Day of Code challenge.  
- **[Swapp](https://github.com/EricGebhart/swapp/)** Clojure: A simple example to understand clojurescript and figwheel.  
- **[Product Inventory Server](https://github.com/EricGebhart/product-inventory/)** Python & flask, A product inventory server.  A code test.
- **[Product Inventory UI](https://github.com/EricGebhart/prod-inv-ui/)** A clojurescript/ReFrame/React front end for a product inventory control system.

### SAS related projects, papers, etc.

- **[ODS Markup: Tagsets by Example](https://github.com/EricGebhart/Tagsets-by-example)** - A book I wrote many years ago about ODS Markup and tagsets.
- **[SAS-Papers](https://github.com/EricGebhart/SAS-Papers)** The various papers I wrote and presented during my time at SAS. 
- **[SAS-Examples](https://github.com/EricGebhart/SAS-Examples)** The Example code to go with all of the papers. 
- **[SAS-Tagsets](https://github.com/EricGebhart/SAS-Tagsets)** The Source for all the official ODS Markup Tagsets as of 2013. 
- **[SAS-Vim](https://github.com/EricGebhart/SAS-Vim/)** Vim extensions for programming with Vim. - As an emacs/evil user I do not use this, apparently many people do. 

### Contributions
- **[QMK Firmware](https://github.com/EricGebhart/qmk_firmware/)** QMK firmware for custom keyboards.
- **[Open SCAD clj](https://github.com/EricGebhart/scad-clj/)** A clojure wrapper for Open-scad so that scad can be programmed from clojure.
- **[Golden Ratio](https://github.com/EricGebhart/golden-ratio.el)** Emacs package which automatically resizes windows in an intelligent way. 
- **[cider](https://github.com/EricGebhart/cider)** Clojure environment for emacs. 
