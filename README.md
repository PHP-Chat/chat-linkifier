chat-linkifier
==============

Convert PHP identifers to manual links in [StackOverflow PHP chat](http://chat.stackoverflow.com/rooms/11/php) via extensive use of magic.

Should match any of the following usage patterns:

 - Message with function() in it
 - Message with `function()` in it
 - Message with `ClassOrInterfaceName` in it
 - Message with `bookname` in it

Also converts 'Google "term"' to add a link to the Google search results for 'term'.

###Installation

- Right click [this link](https://github.com/PHP-Chat/chat-linkifier/raw/master/chat-linkifier-0.0.0.6.crx) and "Save target as..."
- Open [`chrome://extensions`](chrome://extensions/)
- Drag-and-drop the file onto the page.
