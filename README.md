# Perljam

A port of pdfjam by David Firth written in Perl.

Originally written as a way of using pdfjam on Windows, the main difference is in the configuration files. Unlike pdfjam they are not executed as bash scripts but parsed and by default none are used. If you'd like to enable then you can set the PERLJAMCONFIGFILE environmental variable with the path or paths (separated by semi-colons on Windows, and colons on other systems).

## Dependancies

Perl, Pdflatex, the File::Which cpan module.

## Optional

Ghostscript, Pdfinfo and the Gnu file command.

It requires the File::Which perl module and pdflatex, but may also require ghostscript, pdfinfo and the gnu file command depending on the function being requested. It expects to find all of these in the PATH.

Please consider it alpha software as I've never really had the opportunity to thoroughly test it.