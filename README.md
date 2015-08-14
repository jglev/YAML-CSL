This CSL file is an adaptation of APA 6th ed. by Kornblith et al. to create [YAML](https://en.wikipedia.org/wiki/YAML "Wikipedia: 'YAML'")-style metadata from a citation (in place of in-text citation; this CSL file has no Bibliography section definition). Like the file on which it is based, this CSL file is released under a [Creative Commons Attribution-ShareAlike 3.0 License](https://creativecommons.org/licenses/by-sa/3.0/ "CC-BY-SA") license. Adding my name to the list of contributors, the file has copyright 2015 Jacob G. Levernier; portions copyright 2015 Simon Kornblith, Bruce D'Arcus, Curtis M. Humphrey, Richard Karnesky, and Sebastian Karcher.

Using this style definition, the reference

`Alfano, M. (2013). Character as moral fiction. Cambridge: Cambridge University Press. Retrieved from http://public.eblib.com/choice/publicfullrecord.aspx?p=1099907`

...would look like this:

```
INSTRUCTIONS: Use your text editor to find-and-replace all instances of (without the spaces) '| | |' with '\r\n' (this means 'new line' in most text editors). Then delete this line.||||||---|||Author: Alfano, M.|||Issued: 2013|||Title: Character as moral fiction|||Publisher-place: Cambridge|||Publisher: Cambridge University Press|||URL: http://public.eblib.com/choice/publicfullrecord.aspx?p=1099907|||---||||||
```

...which, when the instructions are followed, becomes this:

```
---
Author: Alfano, M.
Issued: 2013
Title: Character as moral fiction
Publisher-place: Cambridge
Publisher: Cambridge University Press
URL: http://public.eblib.com/choice/publicfullrecord.aspx?p=1099907
---
```

(The `|||` line delimiters are a workaround to allow use of the [CSL Visual Editor](http://editor.citationstyles.org/ "CSL Visual Editor"), which I've found deletes XML linebreaks when used to edit a CSL file.)

This CSL file is especially useful for cases in which a user wants to take plaintext notes on a reference in a standalone file.

This code can be validated using [csl-validator.js](https://simonster.github.io/csl-validator.js/ "csl-validator.js").
