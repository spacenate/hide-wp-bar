# hide-wp-bar
This javascript bookmarklet will hide the WordPress admin bar that appears on a WordPress site while you are logged in. This is useful for doing side-by-side comparisons, for example from a development environment where you may be logged in, to a production environment where you are not.

To use it, first create a new bookmark in your browser, and set this as the location:

    javascript:(function()%7Bdocument.getElementById('wpadminbar').style.display%3D'none'%3Bdocument.body.style.marginTop%3D'-32px'%7D)()

Now you may run this bookmarklet whenever you'd like an unobstructed view of your WordPress site.
