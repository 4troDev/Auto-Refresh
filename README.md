- simple HTML page with an iframe and use Javascript to auto-reload.

`<iframe src="http://site.com"></iframe>
<script>setTimeout("location.reload(true);", 3000);</script>`

Some of you guys may be thinking that HTML is a little bit on the “dangerous side”, but here’s the secret – HTML is actually nothing more than plain text. We don’t need to install any complicated code editors nor developer tools… HTML files can be created and edited using just the default Windows Notepad or Mac TextEdit.

First download or clone <a href="https://github.com/VoltDevelopment/Auto-Refresh/blob/main/AutoRefresh.html" target="_blank" rel="noopener noreferrer">dummy reload page in a zip file</a>
open up the above dummy HTML page in your preferred text editor.
Change `<iframe src="http://site.com">` to your preferred website address.
Change `setTimeout("location.reload(true);", 3000)` to your preferred refresh time – This is set to 3000 milliseconds (3 seconds).
Save the update (Don't be like me)
Finally, just open this HTML file in your web browser.
