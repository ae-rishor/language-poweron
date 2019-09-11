# PowerOn language package

This language package is designed to enable the use of the PowerOn language in Atom for repgen writing.  I have created several PowerOn
syntaxes that work best for correct highlighting, but if you would like to make your own here is how the grammar is defined.

Comments:	.syntax--comment
Strings:	.syntax--string	.syntax--punctuation     &.syntax--definition &.syntax--string
Special System Variables (SYSTEMDATE, etc):	.syntax--support &.syntax--constant
Record Types:	.syntax--support &.syntax--type
Functions:	.syntax--support &.syntax--function
Field Names:	.syntax--constant
Keywords (IF, THEN, ANY, TOTAL, etc):	.syntax--keyword 	.syntax--keyword &.syntax--other
Operators (AND, OR, =, <, etc):	.syntax--keyword &.syntax--operator


The use of field names and mnemonics should be mostly complete, but please let me know if something isn't highlighting.

If there are words in comments that aren't the right color it's caused by a different package, language-todo or a similar one.
