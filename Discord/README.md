# CSS-Tweaks for Discord
This repository is where I upload any tweaks I make to a webpage I think people could benefit from.  
I typically create them to fix inconsistencies or general design flaws on a given webpage.

This particular subfolder pertains to all tweaks made to Discord, wether that be via a web browser using stylus for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) or [Chromium](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) based browsers or the desktop client through the use of client modifications like [Vencord](https://vencord.dev) or [BetterDiscord](https://betterdiscord.app).

## Installation of styles for Stylus
1. Navigate into the Stylus folder
2. Find the name of the style you would like to install in the README at the bottom of page and click its link.
3. A new tab should open offering to install or update the Style. (Should Stylus not load, refresh the newly opened tab.)
4. Click install style on the Stylus window that shows.

## Installation of styles for Discord client modifications
1. Navigate into the Client folder
2. Find the style you would like to use in the README and copy the import line for that style.
3. Navigate to the CustomCSS section of your client modification and then add the @import line to the TOP of the file.

NOTE: You MUST add the imports to the top of the file or the styles won't apply, if an import is placed below anything other than another import, it will get ignored and wont be applied. This isn't something I can control. Please don't raise an issue about styles failing to apply if you haven't taken the time to place them in the CustomCSS file correctly.