# Linkding addon

##  What is it ? (shamelessly from [Here](https://github.com/sissbruecker/linkding?tab=readme-ov-file#introduction))

linkding is a bookmark manager designed be to be minimal, fast, and easy to set up using Docker.

The name comes from:
- *link* which is often used as a synonym for URLs and bookmarks in common language
- *Ding* which is German for thing
- ...so basically something for managing your links

**Feature Overview:**
- Clean UI optimized for readability
- Organize bookmarks with tags
- Bulk editing, Markdown notes, read it later functionality
- Share bookmarks with other users or guests
- Automatically provides titles, descriptions and icons of bookmarked websites
- Automatically archive websites, either as local HTML file or on Internet Archive
- Import and export bookmarks in Netscape HTML format
- Installable as a Progressive Web App (PWA)
- Extensions for [Firefox](https://addons.mozilla.org/firefox/addon/linkding-extension/) and [Chrome](https://chrome.google.com/webstore/detail/linkding-extension/beakmhbijpdhipnjhnclmhgjlddhidpe), as well as a bookmarklet
- SSO support via OIDC or authentication proxies
- REST API for developing 3rd party apps
- Admin panel for user self-service and raw data access

## About

This addon is based on *alpine* docker image made by https://github.com/sissbruecker/linkding
It provides admin user configuration, no need to launch docker commands to create admin.
I didn't expose all other settings, let's see if it is needed at some point.

Happy bookmarking !

## Installation

1. [Add my Linkding add-on repository](https://github.com/diyanei/hassio-linkding.git) to your Home Assistant instance.
1. Install this add-on.
1. Fill in an admin username and password, click the `Save` button to store your configuration.
1. Start the add-on.
1. Check the logs of the add-on to see if everything went well.
1. Use the `Open Web interface` button to access the instance.
1. Enjoy