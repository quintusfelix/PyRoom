PyRoom Project
==============

PyRoom is a fullscreen simple text editor, without a toolbar, a menubar or
anything that would distract the user from his most important task: writing.

Dependencies
------------

PyRoom depends on Python 3, PyGi and XDG bindings for Python (python3-xdg). Please
refer to your system documentation for information on how to install these
modules if they're not currently available.

Optional dependencies
---------------------

In order to use GNOME default fonts in PyRoom, gconf bindings (python-gconf)
are recommended.

If you're installing manually from our tarball and want to use PyRoom in your
own language, you'll need to install gettext.

Installing and Running 
----------------------

PyRoom is available as a distutils enabled package. Installation procedures
for those are easy:

Either unpack the tarball 
    
    $ tar xvfz pyroom*.tar.gz

or check out our git repo for a development version (we try to keep those
unbroken and ready for production use)
    
    $ git clone https://github.com/fheinle/PyRoom

From there, you can either run pyroom from commandline

    $ cd pyroom/
    $ ./pyroom

Or install it system wide

    $ cd pyroom
    $ python3 setup.py install # as root
    $ pyroom

Usage 
-----

### Running PyRoom

To run pyroom and instruct it to load some existing files, type:

    $ pyroom /path/to/file1 /other/path/to/file2

### Example Usage

For example, to load PyRoom and instruct it to load the files `article.txt` and
`blogpost.txt`, type the following:

    $ pyroom article.txt blog.txt

### Key Bindings

There are a few keys allowing you to perform a few useful commands:

* Control-H: Show help in a new buffer
* Control-I: Show buffer information
* Control-M: Minimize buffer
* Control-N: Create a new buffer
* Control-O: Open a file in a new buffer
* Control-Q: Quit
* Control-S: Save current buffer
* Control-Shift-S: Save current buffer as
* Control-W: Close buffer and exit if it was the last buffer
* Control-Y: Redo last typing
* Control-Z: Undo last typing
* Control-Page Up: Switch to previous buffer
* Control-Page Down: Switch to next buffer

## Want to know more?

* PyRoom Website: http://pyroom.org
* PyRoom project page on github: https://github.com/fheinle/PyRoom
* PyRoom IRC-Channel: irc://irc.freenode.net/pyroom - #pyroom on FreeNode
