# Precomiled Wheels for some Python Packages

## Hints:
### PyCrypto Installation on Window 7 x64 with Python 3.6

1. Install Visual Studio Community Edition 2017 with **VC++ 2015 native toolset.**
1. Restart your comuter.
1. Run **vcvarsall.bat _x86_amd64_** (x86_amd64 is optional parament depended of your CPU)
1. Run **set VC2015INSTALLDIR=-FI"c:\Program Files (x86)\Microsoft Visual Studio 14.0\VC"**
1. Run **set CL=-FI"%VC2015INSTALLDIR%\include\stdint.h"**
1. pip install pycrypto