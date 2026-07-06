# script

The included headers are:

<iostream> — cin, cout, cerr, endl (this is the main one, and what the sample code uses)
<cstdio> — partial (basic I/O)
<cstdlib> — partial (things like malloc/free, atoi, etc.)
<cstring> — partial (strcpy and similar)
<cmath> — partial (trig, sqrt, pow, etc.)
<cctype> — character classification (isdigit, isalpha, etc.)
<ctime> — partial
<iomanip> — basic output formatting

Notably missing: no <vector>, <string> (the C++ class), <map>, or other STL containers/templates — JSCPP is a C-with-some-C++-syntax interpreter, not a real C++ compiler, so templates and most of the STL aren't there. Plain C-style arrays, structs, and pointers work fine though.
If you write something using a header it doesn't support, you'll get a clear parse/include error rather than a silent failure — so it's easy to tell right away if something's missing. Want me to update the C sample code to show off one of these headers (like <cmath> or <cstring>) instead of just iostream?
Claude is AI and can make mistakes. Please double-che
