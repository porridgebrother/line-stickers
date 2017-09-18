# line-stickerbot
A Telegram bot for downloading Line stickers. It takes a URL sent to the bot from a user, downloads the page, and finds the relevant image links. Then, it downloads the images, rescales them to the appropriate size, and sends them all back to the user in a .zip archive.

## How do I use it?
Add [@line_stickerbot](http://telegram.me/line_stickerbot) on Telegram.

Or, if you prefer to run it yourself, replace `<token>` in `main.py` and `imagedl.sh` with the token the Botfather gave you, and run `main.py`.

## Dependencies

This bot uses a few modules to make my life easier. Run `pip install` if you don't have them.

* `bs4` for parsing the HTML of the sticker page.
* `cssutils` for getting the url of the sticker image.
* `wand` for resizing the downloaded images.
