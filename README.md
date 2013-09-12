# Snippet

Wrap a block of test in the tag pair. The plugin will strip the tags and return a preview of the block with the 
total number of characters as set by the 'total' parameter. If the original text was longer than the total ellipsis will
be added. 

{exp:snippet total="100" word="true" ellipsis="..."}

The block of text that you want to snippet. 

{/exp:snippet}

Parameters: 

* {total} = default 500

* {word} = Tells the plugin if you want it to end the snippet on the last full word. Set to "true" by default.

* {ellipsis} = Set to '...' by default. You can pass any text that you want appended to the end of the snippet.
