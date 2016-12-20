# YouTube Comment Filter Script
Script that filters unwanted comments.
<BR/>
Enjoy.
<BR/><BR/>
Version <strong>0.0.4</strong>

<A HREF="https://github.com/TomONeill/youtube-comment-filter-script/raw/master/yt-comment-filter-latest.user.js">INSTALL</A>

# Screenshot
<IMG SRC="https://raw.githubusercontent.com/TomONeill/youtube-comment-filter-script/master/screenshots/preview.png" />

# Description
This repository includes a userscript for Greasemonkey and Tampermonkey that tries to find and remove stupid comments like "first" and "I'm early".

# Lots of work left
The script is currently still in development. Code needs to be cleaned out, optimised and lots of additions needs to be included. Still I thought I'd share this script with you, as it does a simple job of cleaning out comments you don't need to be annoyed about.

If you are a developer, don't be ashamed to send out a pull request. I'll review your code, comment on it and include it into the project, since it can't be worse than it is now :p.

# Target goals/how it works
The script does a very simple job by comparing each comment with hardcoded commonly used comments (or commonly used word combinations). It checks every now and then (configurable in the code) for new comments (which means that when you scroll down it will look for comments which weren't there before or after clicking the "Load more comments" button) and filters the annoying ones out.

# Known bugs
- Viewing more replies to comments don't get filtered (might be fixed?).

# Changelog
<A HREF="https://raw.githubusercontent.com/TomONeill/youtube-comment-filter-script/master/changelog.txt">View changelog</A>

# About userscripts
This is a userscript which you can use in combination with a browser extension to inject JavaScript (Greasemonkey, Tampermonkey).
This means new functionality can be added, or bugs can be fixed on (discontinued) websites.<BR />
DO NOT INSTALL USERSCRIPTS YOU DON'T TRUST! Check always for urls like the @domain tag at the top of a script before installation. Sensitive data (like usernames, passwords, or banktransactions even), may be sent to other sources.

# Donate
If you like my work so much you feel like doing something nice for me, a complete stranger of the internet, you can.<BR />
<A HREF="https://www.paypal.me/TomONeill">Donate here</A>.
