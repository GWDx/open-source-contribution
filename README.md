记录代码相关的 PR 和 issue

### PR

> https://github.com/pulls?q=is%3Apr+author%3AGWDx
>
> https://invent.kde.org/dashboard/merge_requests?scope=all&state=all&author_username=gwdx
>
> 按照创建时间排序

| id   | organization   | product          | PR (GitLab/GitHub/Phabricator/Gerrit)                        | commit (GitHub) / status                                     |
| ---- | -------------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| P1   | KDE            | Konsole          | [url filter: remove trailing non-URL characters](https://invent.kde.org/utilities/konsole/-/merge_requests/934) | [02ba8ce](https://github.com/KDE/konsole/commit/02ba8cefc763f841e523c77069860253599b2dc0) [1817dd4](https://github.com/KDE/konsole/commit/1817dd40679240ab50ea52891d53802ef15b5723) |
| P2   | KDE            | Okular           | [fix Unicode Normalization: replace NFKC to NFC](https://invent.kde.org/graphics/okular/-/merge_requests/941) | [322fd2d](https://github.com/KDE/okular/commit/322fd2d54e4226f6dbb4fb357a86931a5c790340) |
| P3   | GitHub Desktop | GitHub Desktop   | [Fix extra newline issue when adding to non-existent .gitignore](https://github.com/desktop/desktop/pull/19279) | [aa2f9cc](https://github.com/desktop/desktop/commit/aa2f9cca767ef15e7b85367d02686bdb22ac944f) |
| P4   | KDE            | Akregator        | [Fix extra empty line when adding a new feed to a new folder](https://invent.kde.org/pim/akregator/-/merge_requests/57) | [0c869e0](https://github.com/KDE/akregator/commit/0c869e02caea41421d6a54feb2b03e3ec3aa9030) |
| P5   | Mozilla        | Firefox DevTools | [Fix incomplete text display in Devtools Network Panel search results. r=jdescottes](https://phabricator.services.mozilla.com/D232793) | [474665d](https://github.com/mozilla-firefox/firefox/commit/474665d9931ed106d487f75a1695500e21e031de) |
| P6   | KDE            | KTextEditor      | [Fix scrolling to search results in wrapped long lines](https://invent.kde.org/frameworks/ktexteditor/-/merge_requests/786) | [6a18c18](https://github.com/KDE/ktexteditor/commit/6a18c1818eec5514bff95e93f97b4baf27f9c091) |
| P7   | KDE            | Konsole          | [Fix search wrapping behavior at boundaries](https://invent.kde.org/utilities/konsole/-/merge_requests/1088) | [b83680a](https://github.com/KDE/konsole/commit/b83680a69328eb4fc7d32949406696b2fb00a0dc) |
| P8   | KDE            | Krfb             | [Fix incorrect cursor position under display scaling](https://invent.kde.org/network/krfb/-/merge_requests/86) | [6379e01](https://github.com/KDE/krfb/commit/6379e0169d0e764b6a2855d66cbfda45940f17a3) |
| P9   | KDE            | Krfb             | [Add UTF-8 clipboard support](https://invent.kde.org/network/krfb/-/merge_requests/88) | [c434224](https://github.com/KDE/krfb/commit/c434224d23d1ff8f45c692b329c7101a8c2c04ee) [7e34a75](https://github.com/KDE/krfb/commit/7e34a75b8e4fc9659ee7a2c9b80c6dc512e3a2d5) |
| P10  | KDE            | KRDC             | [VNC: Add UTF-8 clipboard support](https://invent.kde.org/network/krdc/-/merge_requests/182) | [9775af3](https://github.com/KDE/krdc/commit/9775af314f8685cba9c9009af88c107a6d8c401d) [abcda23](https://github.com/KDE/krdc/commit/abcda2356553de20339370d7c13e9bd2f7923d97) |
| P11  | Gitea          | Gitea            | [Fix incorrect divergence cache after switching default branch](https://github.com/go-gitea/gitea/pull/34370) | [71a1187](https://github.com/go-gitea/gitea/commit/71a11872091634f1370374ef123d32798ec0447d) |
| P12  | KDE            | KCharSelect      | [Support copying selected text from detail panel](https://invent.kde.org/utilities/kcharselect/-/merge_requests/30) | Open                                                         |
| P13  | KDE            | Discover         | [Fix use-after-free when closing Discover](https://invent.kde.org/plasma/discover/-/merge_requests/1090) | [82226e8](https://github.com/KDE/discover/commit/82226e8a5cd263d5e9eb2b4c7c48eb32cfae296f) |
| P14  | KDE            | Krita            | [Draft: Windows: Limit detected function keys to F1–F12](https://invent.kde.org/graphics/krita/-/merge_requests/2416) | Closed                                                       |
| P15  | KDE            | Solid            | [Fix garbled product names in USB devices](https://invent.kde.org/frameworks/solid/-/merge_requests/214) | [edae70e](https://github.com/KDE/solid/commit/edae70e96f3459783cd088b636b6044454ffaba6) [561a15b](https://github.com/KDE/solid/commit/561a15b5f438a92709aa9f91b7ccd1873f4cb0a9) |
| P16  | Chromium       | Chromium         | [Fix stuck F22 key state in ForegroundHelper on Windows](https://chromium-review.googlesource.com/c/chromium/src/+/6674454) | [f16e1dd](https://github.com/chromium/chromium/commit/f16e1ddc09c516addedf6d80561d468136e2c4a2) [5eecc16](https://github.com/chromium/chromium/commit/5eecc165cbd32b54ccba16a41966a6c6e2cc4781) |
| P17  | LibreOffice    | LibreOffice      | [Fix incorrect object selection for captioned images](https://gerrit.libreoffice.org/c/core/+/188824) | [f4b53f9](https://github.com/LibreOffice/core/commit/f4b53f9fb513b5238cbefb6a415bbcf2bd8aa238) |
| P18  | Zettlr         | Zettlr           | [Fix WebP images not rendering from relative paths](https://github.com/Zettlr/Zettlr/pull/5843) | [eae605f](https://github.com/Zettlr/Zettlr/commit/eae605fe8de2a1b746994ec9cda8be2186adbb5d) |
| P19  | KDE            | Dolphin          | [Fix duplicated "Internal shared storage" when opening MTP device from sidebar](https://invent.kde.org/system/dolphin/-/merge_requests/1036) | [d0f8985](https://github.com/KDE/dolphin/commit/d0f8985b4c5c790781be6fcd06d299f087e78756) [eeb5251](https://github.com/KDE/dolphin/commit/eeb5251c30c3cbcdff5db59b250286eae30792fb) [051bc36](https://github.com/KDE/dolphin/commit/051bc3665a169e261d57ecab1f70baaa31a4a1ad) |
| P20  | KDE            | KGpg             | [Fix crash when editing a key in terminal the second time](https://invent.kde.org/utilities/kgpg/-/merge_requests/35) | [ab0a524](https://github.com/KDE/kgpg/commit/ab0a5249d9c07f085e27e9243a92b600dccf923d) |
| P21  | KDE            | Konsole          | [HTMLDecoder: fix missing span on subsequent lines](https://invent.kde.org/utilities/konsole/-/merge_requests/1130) | [b04c4ec](https://github.com/KDE/konsole/commit/b04c4ec523fa2c1807dd711d3612b495134f3784) [7919ae7](https://github.com/KDE/konsole/commit/7919ae7f281ba8c03ce17f38aa08a2ed24620a7d) |
| P22  | mathjax        | MathJax-src      | [Allow digits in \operatorname (mathjax/MathJax#2991)](https://github.com/mathjax/MathJax-src/pull/1360) | [859405e](https://github.com/mathjax/MathJax-src/commit/859405e8d57bc8c16b1c90d2f6f33f0b8bcfccc8) |
| P23  | KDE            | Ark              | [Draft: Fix crash when closing while loading large tar.gz archive](https://invent.kde.org/utilities/ark/-/merge_requests/306) | Open                                                         |
| P24  | KDE            | Konsole          | [Draft: Fix crash when handling very long text](https://invent.kde.org/utilities/konsole/-/merge_requests/1137) | Open                                                         |
| P25  | KDE            | Konsole          | [Remove extra character and nulls in HTML export for lines with CJK characters](https://invent.kde.org/utilities/konsole/-/merge_requests/1139) | Open                                                         |



### Issue

> https://github.com/issues/created?q=is%3Aissue%20author%3AGWDx

| id   | organization | product          | Issue (bugzilla/GitHub)                                      | closed by / status |
| ---- | ------------ | ---------------- | ------------------------------------------------------------ | ------------------ |
| I1   | Mozilla      | Firefox DevTools | [Network Panel Search - Incomplete text displayed on the left side panel](https://bugzilla.mozilla.org/show_bug.cgi?id=1938771) | P5                 |
| I2   | Gitea        | Gitea            | [Branches still compare against previous default branch after switch](https://github.com/go-gitea/gitea/issues/34369) | P11                |
| I3   | KDE          | Solid            | [Product name displayed as garbled text for USB devices with non-ASCII characters](https://bugs.kde.org/show_bug.cgi?id=505913) | P15                |
| I4   | Chromium     | Chromium         | [ForegroundHelper sends VK_F22 without key-up event on Windows](https://issues.chromium.org/issues/427778321) | P16                |
| I5   | KDE          | KGpg             | [KGpg crashes when editing a key in terminal the second time](https://bugs.kde.org/show_bug.cgi?id=509767) | P20                |
| I6   | KDE          | Konsole          | [Saving output as HTML cause multi-line text loses style](https://bugs.kde.org/show_bug.cgi?id=509784) | P21                |
| I7   | KDE          | Konsole          | [HTML export adds extra character and nulls for lines with CJK characters](https://bugs.kde.org/show_bug.cgi?id=511323) | P25                |

> https://bugs.kde.org/buglist.cgi?quicksearch=ALL%20commenter%3Agwdx
>
> https://bugs.kde.org/buglist.cgi?quicksearch=ALL%20%22Wendi%20Gan%22
