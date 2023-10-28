# dragInputClickjacking
Demo of using draggable elements in a clickjacking PoC to "type" user inputs. 
<br>
Video demonstration can be seen here:<br>
https://www.youtube.com/watch?v=VIEZ1aByFvU

Start a quick web server in the directory with the .html files:
python3 -m http.server 80

Then open:<br>
http://127.0.0.1/clickjackPoc.html

Follow the instructions, you'll see the PoC will walk you through doing<br>
a paycheck adjustment of $10,000,000 in the example app. 

This requires having the user click a button like any other clickjack attack,
but a number value has to be "typed". This is possible through a drag and drop.<br>

The browser considers this a user initiated action, so the text attached to the draggable<br>
image is "typed" into the hidden/iframed field. 

Credit to Hacktricks for the idea:
https://book.hacktricks.xyz/pentesting-web/clickjacking<br>
Hacktricks Author: https://www.linkedin.com/in/carlos-polop-martin/

<br>

My contact info:<br>
@hoodoer<br>
hoodoer@bitwisemunitions.dev
