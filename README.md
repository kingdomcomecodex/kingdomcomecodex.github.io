# kingdomcomecodex.github.io
Kingdom Come: Deliverance Codex online reader (https://kingdomcomecodex.github.io)

* [Reddit link](https://www.reddit.com/r/kingdomcome/comments/83g3l4/kingdom_come_deliverance_codex_online_web/)
* Made by [nachazo](https://github.com/nachazo)
* Link to project php script that generates this website from game xml lang files: [nachazo/kingdomcomecodex-php-generator](https://github.com/nachazo/kingdomcomecodex-php-generator).

### Changelog:
  * **1.5** (23/07/2019):
    * Updated with new lang files version, from the last game update. A few new chapters (thanks @Francys55555).
    * Still no new languages, estonian and ukranian XML files are uncomplete and japanese still no in the game files.
    * Fixed some UI text of polish version (issue #4, thanks @Matik7)
  * **1.4.3** (05/04/2018):
    * Minor improvements in CS language welcome texts.
  * **1.4.2** (16/03/2018):
    * Fixed in german language an error with a text from a modal box.
    * Changed width from bottom advise (to avoid three lines).
  * **1.4.1** (15/03/2018):
    * Added soft animation effect to the plus/minus width.
  * **1.4** (15/03/2018):
    * Added much more entries with links to locate in the game map. Added where it fits for categories, society... Made using the last online map url option changes.
    * Added a window with "beware spoilers" advise for users opening map in some entries.
    * Added in the welcome page an option to delete all cookies of the codex (read marks, position, advises...).
    * Fixed that turkish language not being selected correctly.
  * **1.3** (15/03/2018):
    * Now each entry changes the uri and updates on article change.
    * Add a optional way for help external link with variables in permalinks/url for hide controls (for clean lecture of an entry) and force language. This is the new permalink format: /?entry=ui_codex_demo&lang=en&clean=true
    * Old permalink style still works (the way .../#ui_codex...) but priorized the new one.
    * Temporary changes on the links used on open in map, untils updates to the external links to the map will be made.
  * **1.2.1** (14/03/2018):
    * Links to online map now open a modal window (shows also the link for open in new tab).
    * Fixed the position in mobile of the open in map icon.
    * Fixed small bug with inexistent permalinks.
    * Improved welcome message text in german (thanks @janfo93).
  * **1.2** (14/03/2018):
    * Added link to related location on online map for some articles (locations and a small number of anothers). May include also categories and some other improvements in next updates.
    * Fixed small bug with the "Increase width" button.
    * Added "easter egg" that you can double click the sidebar bottom shield to show all articles at once, for print to PDF purposes (maybe you could convert to epub).
  * **1.1** (13/03/2018):
    * Fixed bug when loading by default ENG languague when non-KCD languague detected from browser.
    * Slightly edited left sidebar (some line breaks and shows ugly) width for ~1024 resolutions.
    * Added a permalink icon in the bottom left, this gives a permanent direct link for each article (maybe relocated anytime in the future).  
  * **1.0** (10/03/2018):
    * Initial release

### About

This project converts the in-game codex feature from [Kingdom Come: Deliverance](https://www.kingdomcomerpg.com) game into a online web. I made because I want to read comfortably in my smartphone (or any web browser) the whole game codex, with so nice historical and KCD world info. Also I wanted practice some web developement things, so this is a good way for it!

Some comments:

- It's made with the game XML language files, so it bundles the 10 languages that the game supports (with 1.3 also with turkish!).
- In sum, I made a script (in php) that transform these xml files to html that you saw, with (hope) nice design. The script source code is also in GitHub, here: [nachazo/kingdomcomecodex-php-generator](https://github.com/nachazo/kingdomcomecodex-php-generator).
- It has all entries unblocked. As only a few are unlocked by default in the game start, I prefer to pull the complete codex. In my opinion, no spoilers where there (you can feedback about).
- Adapted for mobile and pc screens.
- You could mark as read articles (for mark where your last read position, for example). Also the last article viewed and selected width are stored on a cookie :)
- I tried to make somekind of comfortably way to read: search, image zooms, increase-decrease width, etc.

And another ones...:

- Kudos to the online map (is linked): fonts and default background image taken from these.
- As this uses extensively jquery and css3, you need a decent modern browser (tested on Firefox & Chrome).
- Of course probably could be better programmed.
- Also for host in githubio, pages are in one html, bigger than normal websites (one general and one for each language).
- As it's massive export from XML files, could be errors that I've not detected. You can notify that on github: https://github.com/kingdomcomecodex/kingdomcomecodex.github.io/issues
- Of course, feedback, request, etc could be made in the same url.
- The same for some translated texts.
- Game developers are notified of this and no problem :)
- Making that I take account that "ui_tutorial_cont_combat_basic" (basic combat help) are translated only in the english xml file! So "Combat" in part tutorial seems to be only in english (in fact i'm not sure it shows in "Tutorials" tab in the game).

Feedback is welcome, of course.

Hope this helps somebody.
