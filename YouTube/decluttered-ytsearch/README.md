# Decluttered YouTube Search

[![Userscript Version](https://img.shields.io/badge/version-0.1.0-blue)](https://raw.githubusercontent.com/dv-001/userscripts/YouTube/decluttered-ytsearch/decluttered-ytsearch.user.js)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple UserScript to remove irrelevant items from YouTube search results, giving you a cleaner, more focused experience.

## The Problem

YouTube's search results page has become increasingly cluttered. What was once a straightforward list of videos now includes:
-   Shelves of extraneous and distracting content
-   Large grids of Shorts
-   Individual Shorts embedded in results
-   Videos you've already watched

This script aims to restore the simplicity of YouTube search by putting you in control of what you see.

## Features

-   **Toggleable Menu:** An easy-to-use settings menu, accessible via a gear icon next to the search bar on results pages.
-   **Hide Shelves:** Instantly remove "shelf" elements like, **For You**, **People also watched**, **Watch again**, etc.
-   **Filter Shorts:** Remove both the dedicated grid of YouTube Shorts and individual Shorts that appear within the main video results.
-   **Hide Watched Videos:** Automatically hide videos you've already watched based on a customizable threshold (default: 90%).
-   **Persistent Settings:** Your preferences are saved and automatically applied on future visits.
-   **Lightweight:** Works by injecting a small, efficient stylesheet. No constant page scanning or heavy processing.

## Installation

To use this script, you first need a userscript manager. The most popular ones are:

-   [Tampermonkey](https://www.tampermonkey.net/) (for Chrome, Firefox, Edge, Safari)
-   [Violentmonkey](https://violentmonkey.github.io/) (for Chrome, Firefox, Edge)
-   [Greasemonkey](https://www.greasespot.net/) (for Firefox)

Once you have a userscript manager installed, simply click the link below to install **Decluttered YouTube Search**:

### [➡️ Install Script](https://raw.githubusercontent.com/dv-001/userscripts/master/YouTube/decluttered-ytsearch/decluttered-ytsearch.user.js)

Your userscript manager will open a new tab and ask you to confirm the installation.

## Usage

1.  Navigate to YouTube and perform any search.
2.  On the search results page (`youtube.com/results?...`), a new **gear icon** will appear to the right of the search input box.
3.  Click the gear icon to open the settings panel.
4.  Check or uncheck the boxes to enable or disable features. The page content will update instantly.
5.  To hide watched videos, check the "Hide videos more than" box and set your desired completion percentage (from 1 to 100).
6.  Click anywhere outside the panel to close it. Your settings are saved automatically.

## Support & Contributions

-   Found a bug or have a suggestion? [Please open an issue](https://github.com/dv-001/userscripts/issues).
-   Want to contribute? Pull requests are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.