# qx_Find_Change_Lists

A collection of csv files for GREP find/change with Quark Xpress

## remove_extra_spaces.csv
Fixes the following:

- double spaces (  ) => single space ( )
- space-colon ( :) => colon (:)
- space-question ( ?) => question mark (?)
- space-exclamatory ( !) => exclamatory (!)
- space-equals ( =) => equals (=)
- space-full stop ( .) = full stop (.) 



## en_dashes.csv
Fixes the following (just need to make it first):

- space - space ( - ) => en-dash ( – )
- nummber-number ([0-9]-[0-9]) => number-en-dash-number ([0-9]–[0-9])
- - text (starts with -) => – text (starts with –)
