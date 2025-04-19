# firefox-profile
Documentation on creating pre-configured Firefox profiles to skip Firefox’s onboarding process.

## Why?
Firefox out of the box isn't the most privacy conscious and faces the issue of users having to remove and customize their settings to get their desired setup. Instead of going through a setup process, you can setup your usual profile settings and back it up to a general profile template, so whenever you want to make a new profile you can start with the defaults that you want.

## Explanation of files/folders

| File/Folder        | Description                                                                                                                                         |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| /chrome            | CSS and other files that customize the chrome, any visible aspect of a browser aside from the webpages themselves (e.g., toolbars, menu bar, tabs). |
| /extensions        | Stores extensions and some settings.                                                                                                                |
| places.sqlite      | Stores bookmarks and search history.                                                                                                                |
| search.json.mozlz4 | Stores search engines in the settings. You have to set it up in the settings and export                                                             |
| prefs.js           | Stores settings like toolbar configuration and other settings.                                                                                      |
| user.js            | Stores settings that will override prefs.js                                                                                                         |
