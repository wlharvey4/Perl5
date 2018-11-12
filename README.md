# Perl5

## About This Source File

This document (`Perl5.twjr`) is a *literate* source document. It is designed to
produce an `Info` file (best read from within Emacs, but there is a stand-alone
Info reader  that can be used),  a `Pdf` document (generated  from LaTeX source
code by PDFTeX), an `HTML` web  site, `Docbook` source code, an `XML` document,
and a plain  text document. In addition.  it also produces working  code in any
language (so long as your system  contains the infrastructure to run the code).
For example,  this `README` file  was drafted  within this source  document and
extracted  as a  separate file,  as was  also the  `Makefile`. This  *literate*
document's features are targeted via a custom `Makefile` that is also a part of
this document, and  extracted as a separate  file, and is dynamic  in the sense
that if you  update it, you can produce  a new version with a simple  call to a
`make` target.  It is  designed to  be able  to produce  any number  of working
software  packages  of  any  language  contained at  any  number  of  different
locations on your system, all with  a single or, alternatively, multiple `make`
calls, depending on the granularity you need.

The Github  repository contains this  source document,  a Makefile that  can be
used  to work  with the  project, as  well as  a `Texinfo`  file that  has been
generated from  this `Twjr` file,  this README,  and a `.gitignore`  file. Most
computer systems have or can easily get the `make`, and `texinfo` programs that
are needed to  process the `Texinfo` file into the  various end documents, such
as `Info`,  `Pdf`, `HTML`, etc. Your  system will need, in  addition to `make`,
and `texinfo`, Gnu  AWK (`gawk`), and TexiwebJr to make  changes to this source
document and  process it  into a  `Texinfo` file and  extract its  programs and
files.  Your system  should also  have  the equivalent  of Bash  version 4,  as
version 4  has some parameter capabilities  that earlier versions do  not. Note
that most  versions of Mac OS  have version 3  of Bash installed as  a default.
Version 4 can be added using Homebrew or MacPorts very easily. In the past, Mac
OS has  also shipped with a  version of `texinfo`  that is below 6.5.  You will
also need to update `texinfo` to at least 6.5 if that is the case.

## How It Works

## Resources

* [TexiwebJr](https://github.com/arnoldrobbins/texiwebjr)
* [Texinfo](https://www.gnu.org/software/texinfo/)
* [Gnu AWK (gawk)](https://www.gnu.org/software/gawk/)
* [Gnu Bash](https://www.gnu.org/software/bash/)
* [TeX Live](https://www.tug.org/texlive/)

