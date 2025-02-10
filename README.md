# Incorrect Word Count in Tcl

This repository demonstrates a common error in Tcl when counting words in a string that contains multiple spaces between words. The `split` command in Tcl, by default, treats consecutive spaces as a single delimiter, leading to an incorrect word count when multiple spaces are present.

The `bug.tcl` file contains the buggy code, while `bugSolution.tcl` provides the corrected implementation using regular expressions to accurately count words regardless of the number of spaces between them.  This is a concise example illustrating a subtle but significant issue in Tcl string manipulation.
