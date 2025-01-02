# Tcl String Comparison Bug

This repository demonstrates a common error in Tcl string comparisons and provides a solution.  The bug arises from using the `==` operator without proper consideration for string normalization. This can lead to unexpected behavior when comparing strings that may differ only in whitespace or case.