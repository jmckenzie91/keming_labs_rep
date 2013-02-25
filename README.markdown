# Nanoc-based static site

The Ruby programming language is required to build the site.
If you're running Mac OS X, you already have Ruby installed.
Otherwise, go find and install it.
Then install the necessary bits to compile the site by running

    gem install bundle
    bundle install

Then running

    nanoc autocompile

will start the site at `http://localhost:3000`.
Changing any of the source files will automatically recompile, so all you neeed to is refresh the page.
