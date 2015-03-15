drupalcampbristol
=================

A version of the initial [DrupalCamp Bristol](http://2015.drupalcampbristol.co.uk) website, built on [Sculpin](http://sculpin.io).

Build
-----

### If You Already Have Sculpin

    sculpin install
    sculpin generate --watch --server

Your newly generated clone of sculpin-blog-skeleton is now
accessible at `http://localhost:8000/`.

### If You Need Sculpin

    curl -O https://download.sculpin.io/sculpin.phar
    php sculpin.phar install
    php sculpin.phar generate --watch --server