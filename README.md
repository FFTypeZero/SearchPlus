# SearchPlus
It is a chrome extension project in progress. I intend to privide easy and powerful page search functionality and more.

## Current Features
0. By default, Ctrl+Shift+Enter for popup window.
1. Simple javascript interpreter, capable of manipulating elements of current page. ("/code"+Enter to enter)
   In code mode, shift+enter to execute js code; shift + up/down to scroll over execution history
2. History log (up arrow key to view previous "entered" results, "/clear" to clear history).
3. Highlight functions: match("/normal"+Enter to enter), Multi-highlight("/multi"+Enter to enter), regular expression match("/regex"+Enter)
   Regex mode supports javascript style regular expressions, ignores regexs which accept "".
4. In normal/multi/regex mode, press Enter to scroll over all elements, and Shift+Enter to scroll back. (Currently there maybe some hidden elements not detected as hidden)
5. If current element selected can be clicked, Ctrl+Enter to click it.

