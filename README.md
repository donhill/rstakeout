Rstakeout
=========

Ruby script to execute an arbitrary command whenever a file changes.

Installation
------------

    gem install rstakeout
    # Mac users: install `growlnotify` from the Growl DWG to get notifications

Common usage
------------

    # Execute a test everytime any file changes
    rstakeout 'rake test' **/*
    
    # Regenerate some LessCSS files whenever needed
    rstakeout 'lessc %s' **/*.less

Authors
-------

Original by Mike Clark, enhanced by topfunky

Contributors:

* sinefunc
* EdvardM

Copyright
---------

Icons from http://gakuseisean.deviantart.com/art/OSE-PNGs-53752770

License: MIT

