# GitHub userscripts [![tag](https://img.shields.io/github/tag/Mottie/GitHub-userscripts.svg)](https://github.com/Mottie/GitHub-userscripts/tags)

Userscripts to add functionality to GitHub.

## Installation

1. Make sure you have user scripts enabled in your browser (these instructions refer to the latest versions of the browser):

  * Firefox - install [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/).
  * Chrome - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=chrome) or [NinjaKit](https://chrome.google.com/webstore/detail/gpbepnljaakggeobkclonlkhbdgccfek).
  * Opera - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=opera) or [Violent Monkey](https://addons.opera.com/en/extensions/details/violent-monkey/).
  * Safari - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=safari) or [NinjaKit](http://ss-o.net/safari/extension/NinjaKit.safariextz).
  * Dolphin - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=dolphin).
  * UC Browser - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=ucweb).

2. Get more information about the userscript by clicking on the named link. Or install it directly or from the GreasyFork site:

  | Userscript Wiki                        | Ext | Direct Install     | GreasyFork     | Created    | Updated    |
  |----------------------------------------|:---:|:------------------:|:--------------:|:----------:|:----------:|
  | [GitHub code colors][ccs-wiki]         |     | [install][ccs-raw] | [site][ccs-gf] | 03/20/2016 | 03/25/2016 |
  | [GitHub collapse in comment][cic-wiki] |  *  | [install][cic-raw] | [site][cic-gf] | 06/27/2016 | 06/27/2016 |
  | [GitHub collapse markdown][cmd-wiki]   |  *  | [install][cmd-raw] | [site][cmd-gf] | 06/27/2016 | 07/05/2016 |
  | [GitHub custom hotkeys][chk-wiki]      |     | [install][chk-raw] | [site][chk-gf] | 04/10/2016 | 07/11/2016 |
  | [GitHub custom navigation][cnv-wiki]   |     | [install][cnv-raw] | [site][cnv-gf] | 06/22/2016 | 06/25/2016 |
  | [GitHub font preview][fpv-wiki]        |     | [install][fpv-raw] | [site][fpv-gf] | 06/11/2016 | 07/21/2016 |
  | [GitHub image preview][ipv-wiki]       |     | [install][ipv-raw] | [site][ipv-gf] | 05/17/2016 | 06/07/2016 |
  | [GitHub issue comments][ic1-wiki]      |     | [install][ic1-raw] | [site][ic1-gf] | 04/04/2016 | 07/17/2016 |
  | [GitHub issue counts][ic2-wiki]        |     | [install][ic2-raw] | [site][ic2-gf] | 01/16/2012 | 05/25/2016 |
  | [GitHub issue highlighter][gih-wiki]   |     | [install][gih-raw] | [site][gih-gf] | 05/21/2016 | 05/21/2016 |
  | [GitHub remove diff signs][rds-wiki]   |     | [install][rds-raw] | [site][rds-gf] | 04/05/2016 | 06/06/2016 |
  | [GitHub rtl comments][rtl-wiki]        |     | [install][rtl-raw] | [site][rtl-gf] | 06/13/2016 | 06/24/2016 |
  | [GitHub sort content][srt-wiki]        |     | [install][srt-raw] | [site][srt-gf] | 07/13/2016 | 07/21/2016 |
  | [GitHub table of contents][toc-wiki]   |     | [install][toc-raw] | [site][toc-gf] | 03/28/2016 | 07/05/2016 |
  | [GitHub title notification][tbn-wiki]  |     | [install][tbn-raw] | [site][tbn-gf] | 03/24/2016 | 03/24/2016 |
  | [GitHub toggle wiki sidebar][tws-wiki] |     | [install][tws-raw] | [site][tws-gf] | 04/01/2016 | 05/18/2016 |
  | [Gist to dabblet][g2d-wiki]            |     | [install][g2d-raw] | [site][g2d-gf] | 01/26/2012 | 04/07/2016 |

\* "Ext" column indicates that the userscript has been included in the [Octopatcher](https://github.com/Mottie/Octopatcher) browser extension/addon.

[ccs-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-code-colors
[cic-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-collapse-in-comment
[cmd-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-collapse-markdown
[chk-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-custom-hotkeys
[cnv-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-custom-navigation
[fpv-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-font-preview
[ipv-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-image-preview
[ic1-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-issue-comments
[ic2-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-issue-counts
[gih-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-issue-highlighter
[rds-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-remove-diff-signs
[rtl-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-rtl-comments
[srt-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-sort-content
[toc-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-table-of-contents
[tbn-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-title-notification
[tws-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-toggle-wiki-sidebar
[g2d-wiki]: https://github.com/Mottie/GitHub-userscripts/wiki/Gist-to-dabblet

[ccs-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-code-colors.user.js
[cic-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-collapse-in-comment.user.js
[cmd-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-collapse-markdown.user.js
[chk-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-custom-hotkeys.user.js
[cnv-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-custom-navigation.user.js
[fpv-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-font-preview.user.js
[ipv-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-image-preview.user.js
[ic1-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-issue-comments.user.js
[ic2-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-issue-counts.user.js
[gih-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-issue-highlighter.user.js
[rds-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-remove-diff-signs.user.js
[rtl-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-rtl-comments.user.js
[srt-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-sort-content.user.js
[toc-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-toc.user.js
[tbn-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-title-notification.user.js
[tws-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/github-toggle-wiki-sidebar.user.js
[g2d-raw]: https://raw.githubusercontent.com/Mottie/GitHub-userscripts/master/gist-to-dabblet.user.js

[ccs-gf]: https://greasyfork.org/en/scripts/18141-github-code-colors
[cic-gf]: https://greasyfork.org/en/scripts/20973-github-collapse-in-comment
[cmd-gf]: https://greasyfork.org/en/scripts/20974-github-collapse-markdown
[chk-gf]: https://greasyfork.org/en/scripts/18675-github-custom-hotkeys
[cnv-gf]: https://greasyfork.org/en/scripts/20830-github-custom-navigation
[fpv-gf]: https://greasyfork.org/en/scripts/20479-github-font-preview
[ipv-gf]: https://greasyfork.org/en/scripts/19773-github-image-preview
[ic1-gf]: https://greasyfork.org/en/scripts/18503-github-toggle-issue-comments
[ic2-gf]: https://greasyfork.org/en/scripts/15560-github-show-repo-issues
[gih-gf]: https://greasyfork.org/en/scripts/19867-github-issue-highlighter
[rds-gf]: https://greasyfork.org/en/scripts/18520-github-remove-diff-signs
[rtl-gf]: https://greasyfork.org/en/scripts/20542-github-rtl-comment-blocks
[srt-gf]: https://greasyfork.org/en/scripts/21373-github-sort-content
[toc-gf]: https://greasyfork.org/en/scripts/18344-github-toc
[tbn-gf]: https://greasyfork.org/en/scripts/18253-github-title-notification
[tws-gf]: https://greasyfork.org/en/scripts/18433-github-toggle-wiki-sidebar
[g2d-gf]: https://greasyfork.org/en/scripts/18254-gist-to-dabblet

## Other userscripts not hosted here:

* [GitHub Dark Script](https://github.com/StylishThemes/GitHub-Dark-Script)
  * [Github Monospace Font Toggle](https://greasyfork.org/en/scripts/18787-github-monospace-font-toggle) (also part of GitHub Dark Script)
  * [GitHub Diff File Toggle](https://greasyfork.org/en/scripts/18788-github-diff-file-toggle) (also part of GitHub Dark Script)
  * [GitHub Toggle Code Wrap](https://greasyfork.org/en/scripts/18789-github-toggle-code-wrap) (also part of GitHub Dark Script)
* [GitHub Custom Emojis](https://github.com/StylishThemes/GitHub-Custom-Emojis)
* [ZenHub Sort Issues](https://github.com/Mottie/ZenHub-userscripts#zenhub-sort-issues)
* [ZenHub Toggle Meta](https://github.com/Mottie/ZenHub-userscripts#zenhub-toggle-meta)
