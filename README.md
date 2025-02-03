# Uncommon HTML Error: Invalid Attribute Name

This repository demonstrates an uncommon error in HTML: using an attribute name that is syntactically invalid within a standard HTML element.

## The Bug

The issue lies in the use of the `data-invalid-attribute` custom attribute.  While custom attributes are generally allowed and useful for storing data directly within elements, there are limitations on their naming and values. In this specific case, using an invalid attribute name causes unexpected behavior or may result in the attribute being ignored by the browser.

## The Solution

The solution involves correcting the attribute name to conform to standard naming conventions.  This usually means avoiding any special characters (besides hyphens and underscores) and ensuring the attribute name starts with a letter.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the lack of expected behavior or that attribute may be completely ignored.
4. Open `solution.html` to see the corrected version.
