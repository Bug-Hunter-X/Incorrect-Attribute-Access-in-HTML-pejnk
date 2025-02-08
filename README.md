# Incorrect Attribute Access in HTML
This repository demonstrates a common error when working with HTML elements and their attributes.  Specifically, it showcases the improper way of accessing and setting attributes, leading to unexpected results. The solution provides the correct methodology using `setAttribute` and `getAttribute`.

## Bug
The original code attempts to directly assign a value to an element's attribute using the syntax `element.attribute = value`. This approach is not supported by HTML's standard DOM manipulation methods.

## Solution
The corrected code uses the standard methods `setAttribute()` and `getAttribute()` to properly set and retrieve custom attributes.