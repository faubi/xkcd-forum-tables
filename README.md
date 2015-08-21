# xkcd-forum-tables
This userscript adds table support to the [xkcd forums](http://forums.xkcd.com).

It adds a `[table][tr][td][/td][/tr][/table]` bbcode that can be used in the editor to add tables. The syntanx works like HTML tables.
It also adds a `[csvtable][/csvtable]`  that creates a table using csv data.

If the viewer has this script, the tables will be displayed using html. If not, they will display by default as aligned monospace text using a code block. Because of this, table cells can only contain plain text, not images, links, or other rich content.

The top row of the table is a header row by default, but that can be disabled with `[table={"header":false}]`. This also applies to csv tables.

If something doesn't work right, please let me know so I can try to fix it. This has only been tested in the latest version of Chrome, so I don't guarantee it will work in other browsers, though it hopefully should.
