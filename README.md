trac-11975
==========

These are my patches for <http://trac.sagemath.org/sage_trac/ticket/11975>.

To apply them to sage-5.9, start Sage in this directory, then


    sage: [hg_sage.import("trac_11975-part%s.patch"%i) for i in [1..5]]
    sage: quit


    sage -br

    