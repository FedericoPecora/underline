# The `underline` package

This LaTeX package provides a robust command for underlining text. It combines the following features:

* underlining is interrupted so as to not intersect descenders;
* underlining works across line breaks, page breaks, and hyphenation;
* underlined can be combined with other common formatting, such as `\textit`, `\textbf`, `\em`, and `\bf`;
* underlining works both within and around math mode.

The implementation derives form a solution originally posted by Peter Grill which builds on the `soul` package (see the thread ["Using soul with indirect formatting applied" on StackExchange](https://tex.stackexchange.com/questions/125219/using-soul-with-indirect-formatting-applied)).
