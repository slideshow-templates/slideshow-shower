# Shower (Ribbon Theme) - Slide Show (S9) Template Pack 

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site »](http://slideshow-s9.github.io)

## Intro

The [Shower](https://github.com/shower/shower) package by Vadim Makeev bundled up into 
a Slide Show (S9) template pack.

Note, the package is configured to use the following headers in `slides.html.erb`:

    author: Your Name Here
    title: Your Slide Show Title Here
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow install shower

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.slideshow/templates
    $ git clone git://github.com/slideshow-s9/slideshow-shower.git

To check if the new template got installed, use the `list` command:

    $ slideshow list

Listing something like:

    Installed templates include:
       shower.txt (~/.slideshow/templates/shower/shower.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow build tutorial -t shower

That's it. 

## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!
