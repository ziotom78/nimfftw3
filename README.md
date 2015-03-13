# Nim bindings to the FFTW3 library.

I generated these bindings in a hurry because I needed them for a
project of mine. Only the functions that use `double` values have been
implemented (no `float` or `long double` functions, sorry -- by the
way, at the time of writing, the `long double` type is not yet
supported by Nim).

# Examples

A very short example is provided at the end of
[fftw3.nim](https://github.com/ziotom78/nimfftw3/blob/master/fftw3.nim).

# License

These bindings are released under a MIT license, but since the FFTW
library is covered by a GPL license, any program you'll write which
use these bindings will need to be released under GPL, as this link
explains: http://www.gnu.org/licenses/gpl-faq.html#GPLWrapper.
