# bigrep
Bigrep - pronounced 'bi-grep'. 

Maybe it means binary grep, maybe it means big grep........

-------------------------------------------------------------------------------

Bigrep allows the searching of large (it's been tested on a 120Gb file) binary
files using regular expressions in which characters of the regex may be
expressed in hexadecimal in addition to the usual means. It's primary purpose was
carve out timestamps from whole-disk forensic images but should be useful in
any situation where you need to search for binary data in a large file.


Bigrep is *not* a true member of the grep family in that it does not (yet!)
support the common options/switches that you might expect of a 'grep'.


Like other members of the grep family it returns 0 (no error) in the case of a
match otherwise it returns non-zero.

#####-----
