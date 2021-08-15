# Auto popcat for Chrome
:white_check_mark: Mobile Compatible :iphone: \
:white_check_mark: No Devtools
## No-brainer Guide :memo:
1. Go to [popcat.click][1]
2. Insert the following code in the url.
*(Note: Do not hit enter yet)*
<pre><code>:document.cookie="bot= ";const event = new KeyboardEvent('keydown', { key: 'a', ctrlKey: true });const timegap = 1 / (780 / (30 * 1000));setInterval(() => {document.dispatchEvent(event);}, timegap);</pre></code>
3. Manually insert `javascript` in the beginning of the url and hit enter
4. There you have it :tada:

Credit to [Tommy Wong][2] for providing the script.

[1]: https://popcat.click/
[2]: https://www.facebook.com/permalink.php?story_fbid=1973975986101742&id=100004680791150
