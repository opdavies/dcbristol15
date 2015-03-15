drupalcampbristol
=================

A version of the initial [DrupalCamp Bristol](http://2015.drupalcampbristol.co.uk) website, built on [Sculpin](http://sculpin.io).

Originally forked from the [sculpin-minimal](https://github.com/opdavies/sculpin-minimal) repository.

Build
-----

### If You Already Have Sculpin

    sculpin install
    sculpin generate --watch --server

Your newly generated clone of the site is now accessible at `http://localhost:8000/`.

### If You Need Sculpin

    curl -O https://download.sculpin.io/sculpin.phar
    php sculpin.phar install
    php sculpin.phar generate --watch --server