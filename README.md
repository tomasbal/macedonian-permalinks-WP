# Fix WordPress permalinks on Macedonian.

This plugin will fix the permalinks when post is published so they don't look like this:
"%rwe%3432%rwrrw".

That is happening because WordPress is trying to encode the URL, but that is not very human readable.

__What this plugin does is, changing the Post permalinks (if its on Macedonian - Cyrilic) and retype it on Latin.__

So if you have something like Title:"Наслов за новата објава", the url will be like this: "https://websitename.com/%434324%3434324%34" it will be translated to this: "https://websitename.com/naslov-za-novata-objava";


## How to use it?

1. Download the plugin
2. Upload it to WordPress
3. That's it. Next time you create post the permalinks will be changed to latin (without changing the title).

