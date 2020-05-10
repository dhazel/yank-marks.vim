yank-marks.vim
==============

Yank all lines marked (with [a-z] / {marks} marks) into
the default register / {register} (in the order of the
marks).

Note: This plugin is largely unnecessary if you know how to append yanks to a
register. To learn about that, see `:help quote_alpha`.

Usage
-----

    :YankMarks [{marks}] [{register}]

Examples
--------

Yank all marks in alphabetical order into the `"` register

    :YankMarks

Yank marks `a`, `c`, and `b`  into the `"` register

    :YankMarks acb

Yank marks `a`, `c`, and `b`  into the `a` register

    :YankMarks acb a

Inspired By
-----------

  * http://stackoverflow.com/a/16325468/564406
