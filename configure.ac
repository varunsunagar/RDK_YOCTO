#Autoconf Requirements

#Intialize, but use more options. Note Parameters brackets and whitespace.
AC_INIT([autohello],[0.01])

#Force Autoconf to be at least this Version Number:
AC_PREREQ([2.68])

#Safety Check - list a source file that wouldnt be in other Directories..
#AC_CONFIG_SRCDIR([hello.c])    

#Put Configuration Results here, so we can easily  #include them:
#AC_CONFIG_HEADERS([config.h])

#put autotools auxiliary files in a subdir, so they dont clutter top dir:

#Enable "automake" to simplify creating makefiles
AM_INIT_AUTOMAKE([1.11])
AC_CONFIG_FILES([Makefile])

# Look for C COmpiler
AC_PROG_CC

#Do Final Output
AC_OUTPUT


