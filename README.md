# PHP Silent Array Key Access: Unexpected Null Values

This repository demonstrates a common yet subtle bug in PHP: the silent handling of accessing undefined array keys.  When attempting to access an array element using a non-existent key, PHP returns null without raising an error, potentially causing unexpected behavior.

The `bug.php` file showcases the issue, where accessing a non-existent key leads to unexpected calculations.  The `bugSolution.php` file offers solutions to prevent and handle this situation.