
using conda and activate python2 env
- conda activate py2

Run: python jemdoc -c mysite.conf xx.jemdoc

http://dubisheng.com/www/jemdocinstall.html

For inserting the image
~~~
{}{img_left}{zhao.jpeg}{alt text}{}{12%}{} <!-- 302.4px 403.2 px-->
~~~

{}{img_left}{zhao.jpeg}{alt text}{161}{183}{}  % this one works

Regarding Link
For example, [mathjax.html] opens in a new web broswer tab, but [/mathjax.html] opens in the current web browser tab. The link opening in a new tab is useful for linking an external website (like http://www.google.com), whereas the link opening in the current tab is useful for liking your jemdoc page (such as the page linked as a jemdoc menu item on the left panel).

Unlike the link in the main text, a jemdoc menu item link on the left panel opens in the current tab by default, because you want to stay in the same tab while navigating menu items. However, you can override this default behavior and make it open in a new tab by putting a backslash (\) character in the beginning of the link of the menu item. This is useful when putting an external website as a menu item. See this usage in “Open in New Tab” menu item on the left panel, which is defined in MENU file.