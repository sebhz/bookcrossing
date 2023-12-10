# bookcrossing
I like setting books free. So I wrote this script to automate French labels generation.

For information about bookcrossing: http://www.bookcrossing.com/faqs.

Goal is to have one single self-contained script to generate my bookcrossing label... but it is too big to be a Gist.

# dependencies

- uudecode to extract the base PNG image for the script.
- imagemagick to write the BCID at the right location in the image.

# usage

`./fill_bcid.sh BCID0 [BCID1 BCID2 BCID3 ... BCID7]`

One BCID at least is required. No more than 8 are supported.
