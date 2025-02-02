# Uncommon HTML Error: Using innerHTML with Undefined Variable

This repository demonstrates an uncommon HTML error that can be easily overlooked.  The error involves using the `innerHTML` property with a variable that has not been defined.  This leads to a silent failure where the intended content isn't displayed, leaving developers puzzled.

The `bug.html` file showcases the erroneous code. The `bugSolution.html` file provides a corrected version.

## Problem

The problem lies in the JavaScript code within `bug.html`. We try to assign the value of an undefined variable `myUndefinedVar` to the `innerHTML` of a div. This doesn't throw an error, but also does not add anything to the div.