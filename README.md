# Pascal language support in Atom (HGB Style Guidlines)

Forked from the original implementation from > _Originally [converted](https://github.com/alefragnani/atom-language-pascal)Alessandro Fragnani._

This forks purpose is mainly to fit the style guidlines.

## Syntax Highlighting
Syntax Highlighting:
![sl](https://github.com/eisenwinter/atom-language-pascal-hgb/blob/master/images/syntax.png)

## Snippets

*programb*
~~~
{
NameOFPrg
@author(Name <x@y.at>)
@abstract(a short description)
@created(2017-03-06)
a large description
@lastmod(2017-03-06)
}
PROGRAM NameOfPrg


BEGIN
END.
~~~

*whileb*
~~~
WHILE (conidtion) DO BEGIN

END; (* /while *)
~~~

*ptrrec*
~~~
RecNamePtr = ^RecName
RecName = RECORD

END;
~~~

*unitb*
~~~
{
Unitname
@author(Name <x@y.at>)
@abstract(a short description)
@created(2017-03-06)
a large description
@lastmod(2017-03-06)
}
UNIT Unitname;

INTERFACE

IMPLEMENTATION


END.
~~~

*ifb*
~~~
IF conidition THEN
BEGIN

END; (* / if *)
~~~

*begin*
~~~
BEGIN

END;
~~~

... and more


## File Symbols

Navigate to any method inside Pascal files:

![file-symbols](https://github.com/eisenwinter/atom-language-pascal-hgb/blob/master/images/atom-pascal-file-symbols.png)



[MIT](LICENSE.md)
