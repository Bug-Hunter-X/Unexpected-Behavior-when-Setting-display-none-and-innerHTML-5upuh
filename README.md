# Uncommon HTML Bug: display:none and innerHTML

This repository demonstrates a subtle issue related to manipulating HTML elements' styles and content.  The `bug.html` file shows the problem, while `solution.html` provides a corrected version.

The bug arises when trying to modify the `innerHTML` of an element after setting its `display` style to `none`. The changes to `innerHTML` are made, but they won't visually appear until the display style is changed back. This can lead to unexpected behavior and make debugging difficult.

The solution focuses on ensuring that the element's display is set to visible before making changes to its `innerHTML` in the javascript.  See `solution.html` for the implementation.