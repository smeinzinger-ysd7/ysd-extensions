# ysd-extensions

Self-hosted distribution point for Chrome extensions developed internally by Yakima School District (YSD7) IT. The packaged extensions (`.crx`) and their update manifest (`update.xml`) in this repository are served over GitHub Pages, where district-managed Chrome browsers check for installs and updates.

## Extensions

### DocuSign Security Banner

Adds a phishing-awareness banner in Gmail on messages that claim to be from DocuSign, reminding staff to verify the sender before clicking any links. DocuSign-themed phishing is one of the most common credential-theft lures aimed at school districts; the banner gives staff a moment of pause on exactly the messages most likely to be spoofed.

## Deployment

Extensions in this repository are force-installed only on district-managed devices through the Google Admin Console. The files here are distribution artifacts — there is nothing to install manually, and the extensions are not published on the Chrome Web Store.

## Questions

Contact YSD7 IT.
