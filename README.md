# Unexpected Horizontal Repetition of Background Image with `background-repeat: repeat-y;`

This repository demonstrates an issue where the `background-repeat: repeat-y;` property in CSS unexpectedly causes horizontal repetition of a background image instead of the intended vertical repetition.  The bug.css file contains the problematic code, while bugSolution.css provides a corrected version.

## Bug Description
The CSS code attempts to set a background image and repeat it vertically using `background-repeat: repeat-y;`. However, the image repeats horizontally.  This might be due to other CSS properties interfering with or overriding the `background-repeat` property.