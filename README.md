# mastodon_advance_web_interface_fix
CSS tweak to fix Mastodon's advanced web interface for large resolutions.

Causes all columns to scale, using up the full width of the screen, with the second and fourth columns scaling more than the others.

Instructions for Firefox:
1. Edit (or create)  the file `[Firefox profile path]/chrome/userContent.css`. Add the following to it: `@import "./mastodonfix.css";`
2. Download mastodonfix.css into the `[Firefox profile path]/chrome/` directory.
3. Edit line 1 of mastodonfix.css to the domain of your mastodon instance.

If someone wants to contribute instructions for other browsers besides Firefox, please open an issue or pull request.
