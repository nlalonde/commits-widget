### Github Commits Widget

Want to see the latest commits to a github repo on a web page?  Have I got a widget for you!

[Click here for a demo](http://nlalonde.github.com/commits-widget/index.html?owner=discourse&repo=discourse)

It takes the following parameters:

Required:

- <b>owner</b>: (string) The owner of the github repo.
- <b>repo</b>: (string) The name of the repo.

Optional:

- <b>limit</b>: (integer) How many commits to show, starting with the most recent.
- <b>width</b>: (integer) The width in pixels of the widget.
- <b>height</b>: (integer) The height in pixels of the widget.
- <b>heading</b>: (string) The text to use in the header of the widget.

For example, to view this repository's 6 latest commits, I could load the widget in an iframe on a page like this:

```
<iframe src="http://nlalonde.github.com/commits-widget/index.html?owner=nlalonde&repo=nlalonde.github.com&limit=6&width=500&height=200" width="502px" height="202px"></iframe>
```

Easy pickings!

Feel free to fork this code, change it, and host it on your own servers.  As shown in the example, I'm hosting it as a Github page at `http://nlalonde.github.com/commits-widget/index.html`.