I've totally isolated a browser bug in Chrome for Mac that occurs only when the "Show scroll bars" system preference is "When scrolling" or "Automatically based on mouse or trackpad" and the user does not have a mouse with a physical scroll wheel plugged in.

To replicate the bug, click the "Add content" button and close the modal until there is enough content on the screen that you'll need to scroll. If scrolling appears to be "stuck" you can use the arrow keys to scroll or resize the browser window to get normal scrolling back.

I found a workaround which is available in the `workaround` branch.