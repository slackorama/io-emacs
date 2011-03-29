io-mode-inf.el -- Inferior mode for the Io language
==============================================

Install
=======

       $ cd ~/.emacs.d/lisp
       $ git clone git://github.com/slackorama/io-emacs.git

In your emacs config:

       (add-to-list 'load-path "~/.emacs.d/lisp/io-emacs")
       (require 'io-mode-inf)

Functions
=========

        io-run-io - Start up Io interpreter in an Emacs buffer. With a prefix
        argument, it will prompt you for the path to your Io interpreter.
        io-eval-region - Send current region to Io interpreter.
        io-eval-buffer - Send whole buffer to Io interpreter.
        io-load-file - Evaluate the contents of the file in the context of the
        Lobby. See doFile for more information.
        io-switch-to-interpreter - Switch to the Io interpreter buffer.

Confg
=====

Set `io-interpreter` to the path of your Io interpreter if it isn't on your
path.

Info
====

* Code:   `git clone git://github.com/slackorama/io-emacs.git`
* Home:   <http://github.com/slackorama/io-emacs>
* Issues: <http://github.com/slackorama/io-emacs/issues>

Thanks
======
I borrowed large parts of this from the Scala mode for Emacs.
