rkingy-dots
===========

The first example of using the [...](http://github.com/ingydotnet/....git)
system as a social config.

Useful for:

- Setting up pair-programming environments
- Trying out other peoples' configs
- Finding the "just right" place for a script or config snippet (that is,
  having a good place to upstream/downstream pieces)

To Use
------

    git clone git@github.com:ingydotnet/rkingy-dots.git &&
        cd rkingy-dots &&
        ./install &&
        exec bash

After that sequence, all the scripts and configs should be linked into place.

To Set Up Your Own
------------------

We ran these commands to set up this repo:

    git init
    vim README.md
    git add .
    git commit -m 'First draft'
    git remote add origin git@github.com:ingydotnet/rkingy-dots.git
    git push -u origin master
    git submodule add git@github.com:ingydotnet/....git
    git submodule add git@github.com:ingydotnet/boot-dots.git
    git submodule add git@github.com:ingydotnet/ingy-dots_.git
    git submodule add git@github.com:ryanjosephking/rking-dots.git
    git submodule update --init
    git add .
    git commit
    ./install
