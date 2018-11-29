A port of pdfjam by David Firth written in Perl.

Originally written as a manner of using pdfjam on windows, the main difference is in the configuration files. Unlike pdfjam they are not executed as bash scripts but parsed and by default none are used. If you'd like to enable then you can set the PERLJAMCONFIGFILE environmental variable with the path or paths (separated by colons).

It requires the File::Which perl module and, like pdfjam, pdflatex, but may also require ghostscript, pdfinfo and the gnu file command depending on the function being requested. It expects to find all of these in the PATH.

Please consider it alpha software as I've never really had the opportunity to thoroughly test it.