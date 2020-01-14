# CS3-DR-Unit_Conversions

This library, {lmrlib}, was mostly developed by 2000, as the ICOADS project increasingly recognized the need for a central shared resource of reusable code, containing well documented and thoroughly validated subroutines and functions for historical units conversions and similar requirements encountered during translation of data into the common ICOADS formats.

This library includes a Python implementation of {lmrlib}, which together with its test suite is believed to be functionally equivalent to the original Fortran {lmrlib}.

The name "lmr" refers (in retrospect not the best choice) to the now-obsolete Long Marine Report (binary) format (documentation here), which still however retains some structural characteristics of our current International Maritime Meteorological Archive (IMMA) format (documentation here).

In addition, Philip Brohan (UK Met Office) has begun developing a shared online library for the code he uses for IMMA analysis, which is available at https://github.com/oldweather/IMMA ("pull requests" welcome, ref. http://oss-watch.ac.uk/resources/pullrequest). This library includes a Perl implementation of {lmrlib}, which together with its test suite is believed to be functionally equivalent to the original Fortran {lmrlib}.
