## Listings of functions used

To determine where to focus early development efforts, we are collecting informatin on which functions from the affected libraries (libxml2, expact, Xerces) are used.

The files in this directory are named in the form library.source.project.list (for example libxml2.ubuntu.squid.list), and contain a list of the functions used, one functon per line.

An example of how to obtain this data by dumping the dymanic symbol tables from ELF binaries is available in a [gist](https://gist.github.com/decodableminion/a5597ba9efe5fd4a68f81192550dc343)

While the usage of functions within open source software is easy to find, the use in internal applications may differ, so please contribute lists from applications which are using these libraries, with organisation names anonymised if you'd prefer.
