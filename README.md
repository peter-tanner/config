# config
Configurations

## Windows 10
### Manually install
| Link | Description |
|-|-
|[mifi/lossless-cut](https://github.com/mifi/lossless-cut/releases/latest)| GUI lossless video editor
|[peter-tanner/numlock-indicator](https://github.com/peter-tanner/numlock-indicator)|my laptop does not have a numlock light

### Packages

```powershell
vssadmin resize shadowstorage /for=C: /on=C: /maxsize=20G

winget source remove msstore
winget install -e --id TortoiseSVN.TortoiseSVN
#winget install usbipd

wsl --set-default-version 2
wsl --set-version Ubuntu-20.04 2

choco install make ext2fsd mboxviewer kitty simple-sticky-notes sharex czkawka rufus googledrive powertoys imagemagick pdftk-server syncthing rpi-imager zotero wslgit win32diskimager vcxsrv mediainfo winscp handbrake audacity yed barrier dotnetcore-runtime hwinfo windows-sdk-10-version-2004-all adobereader sqlitebrowser docker-desktop linkshellextension inkscape python altium-designer crystaldisinfo paint.net notepadplusplus wsltty vlc vscode adoptopenjdk16 7zip obs-studio prismlauncher discord
```

### WSL

```bash
sudo add-apt-repository ppa:swi-prolog/stable
sudo apt-get update
sudo apt install cifs-utils git-lfs vbindiff subversion ocrmypdf ncdu pandoc swi-prolog texlive-extra-utils openjdk-17-jdk-headless graphviz pdfcrack bibutils ffmpeg ruby-dev xvfb libxi6 libgconf-2-4 chromium-chromedriver ruby sqlite rename texlive-latex-recommended latexmk pdftk-java jq npm tree gdb libgd-dev taskwarrior make gcc imagemagick-6.q16 python3-pip python3-venv lrzip net-tools

# yt-dlp with dislikes plugin
python3 -m pip install -U https://github.com/pukkandan/yt-dlp-ReturnYoutubeDislike/archive/master.zip yt-dlp

# For blackboard scraper
sudo gem install solargraph selenium-webdriver rubyzip nokogiri ruby-debug-ide
```


## Intel/Altera Quartus FPGA IDE dark mode

Run script in [peter-tanner/Intel-Quartus-Dark-Mode-Windows](https://github.com/peter-tanner/Intel-Quartus-Dark-Mode-Windows).

## Firefox

### Extensions

| Name                                         | Extension ID                           | Internal UUID                        | Manifest URL                                                       |
| -------------------------------------------- | -------------------------------------- | ------------------------------------ | ------------------------------------------------------------------ | 
| Address bar math                             | address-bar-math@benc.io               | 3720a3b8-2c04-4c16-a083-b414160bad49 | moz-extension://3720a3b8-2c04-4c16-a083-b414160bad49/manifest.json |
| Annotations Restored for YouTube™            | {0731d555-4732-4047-99f9-38a388ffa044} | 08676a32-4b6f-4e06-a28e-37b9cdf16b22 | moz-extension://08676a32-4b6f-4e06-a28e-37b9cdf16b22/manifest.json |
| Auto Tab Discard                             | {c2c003ee-bd69-42a2-b0e9-6f34222cb046} | 468d8783-e575-40df-a79e-de2c83e07c27 | moz-extension://468d8783-e575-40df-a79e-de2c83e07c27/manifest.json |
| Dark Reader                                  | addon@darkreader.org                   | 365ef68e-c355-4dbb-97e0-2d0241321e0c | moz-extension://365ef68e-c355-4dbb-97e0-2d0241321e0c/manifest.json |
| Link Gopher                                  | linkgopher@oooninja.com                | 9aaaa8e1-d386-4fa2-a0d5-33c8deb658e5 | moz-extension://9aaaa8e1-d386-4fa2-a0d5-33c8deb658e5/manifest.json |
| Redirect Octopart datasheets                 | {01b40f09-337b-4f91-a56a-35319698c584} | a72733d6-03c9-48fa-86bb-a7b559ad4699 | moz-extension://a72733d6-03c9-48fa-86bb-a7b559ad4699/manifest.json |
| Redirector                                   | redirector@einaregilsson.com           | 5851bf3b-e477-41d1-8706-3234660b80ed | moz-extension://5851bf3b-e477-41d1-8706-3234660b80ed/manifest.json |
| Return YouTube Dislike                       | {762f9885-5a13-4abd-9c77-433dcd38b8fd} | 030175ba-21e5-49b5-9c33-ec5910273957 | moz-extension://030175ba-21e5-49b5-9c33-ec5910273957/manifest.json |
| SingleFile                                   | {531906d3-e22f-4a6c-a102-8057b88a1a63} | eea9c060-82a9-4230-91fa-1f090b458267 | moz-extension://eea9c060-82a9-4230-91fa-1f090b458267/manifest.json |
| SponsorBlock for YouTube - Skip Sponsorships | sponsorBlocker@ajay.app                | a991cc7a-3c9d-4cd4-a40b-5de2629d5247 | moz-extension://a991cc7a-3c9d-4cd4-a40b-5de2629d5247/manifest.json | 
| Stylus                                       | {7a7a4a92-a2a0-41d1-9fd7-1e92480d612d} | f1089774-0d28-4e42-af3d-e726182a7051 | moz-extension://f1089774-0d28-4e42-af3d-e726182a7051/manifest.json |
| Tampermonkey                                 | firefox@tampermonkey.net               | 8b80622d-0e22-4874-b6ba-ec9d405ac94a | moz-extension://8b80622d-0e22-4874-b6ba-ec9d405ac94a/manifest.json | 
| uBlacklist                                   | @ublacklist                            | f1cea2fc-3151-49c5-b732-f901753eb9f8 | moz-extension://f1cea2fc-3151-49c5-b732-f901753eb9f8/manifest.json |
| uBlock Origin                                | uBlock0@raymondhill.net                | eb4a66b1-03e8-4d15-ac56-2c87e9914bf4 | moz-extension://eb4a66b1-03e8-4d15-ac56-2c87e9914bf4/manifest.json |
| Wayback Machine                              | wayback_machine@mozilla.org            | c18e7aec-381a-40dd-b3a8-7910f195c28f | moz-extension://c18e7aec-381a-40dd-b3a8-7910f195c28f/manifest.json |
| YouTube Shorts Redirect                      | {cf485034-0bda-470d-a027-794f3214359c} | de111349-1c6e-4ce3-9e41-b38200afd5c8 | moz-extension://de111349-1c6e-4ce3-9e41-b38200afd5c8/manifest.json |
| Zotero Connector                             | zotero@chnm.gmu.edu                    | 637d73c1-2487-43d4-878b-138a92ca0e92 | moz-extension://637d73c1-2487-43d4-878b-138a92ca0e92/manifest.json |

### Redirector redirects

```json
{
    "createdBy": "Redirector v3.5.3",
    "createdAt": "2024-08-12T10:45:11.648Z",
    "redirects": [
        {
            "description": "Example redirect, try going to http://example.com/anywordhere",
            "exampleUrl": "http://example.com/some-word-that-matches-wildcard",
            "exampleResult": "https://google.com/search?q=some-word-that-matches-wildcard",
            "error": null,
            "includePattern": "http://example.com/*",
            "excludePattern": "",
            "patternDesc": "Any word after example.com leads to google search for that word.",
            "redirectUrl": "https://google.com/search?q=$1",
            "patternType": "W",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        },
        {
            "description": "yt shorts",
            "exampleUrl": "https://www.youtube.com/shorts/vOao4HkXnpY",
            "exampleResult": "https://www.youtube.com/watch?v=vOao4HkXnpY",
            "error": null,
            "includePattern": "https://www.youtube.com/shorts/(.*)",
            "excludePattern": "",
            "patternDesc": "",
            "redirectUrl": "https://www.youtube.com/watch?v=$1",
            "patternType": "R",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        },
        {
            "description": "old wikipedia",
            "exampleUrl": "https://en.wikipedia.org/wiki/Free-space_path_loss",
            "exampleResult": "https://en.wikipedia.org/wiki/Free-space_path_loss?&useskin=vector",
            "error": null,
            "includePattern": "^https://(\\w+)([.]m)?.wikipedia.org([^#?]+)(\\?)?([^#]*?)(&useskin=vector)?(#.+)?$",
            "excludePattern": "",
            "patternDesc": "https://old.reddit.com/r/wikipedia/comments/10fc9pn/help_post_wikipedia_changed_to_a_new_interface/j50nkk9/",
            "redirectUrl": "https://$1.wikipedia.org$3?$5&useskin=vector$7",
            "patternType": "R",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        },
        {
            "description": "minecraft.wiki",
            "exampleUrl": "https://minecraft.fandom.com/wiki/Function_(Java_Edition)",
            "exampleResult": "https://minecraft.wiki/w/Function_(Java_Edition)",
            "error": null,
            "includePattern": "https://minecraft.fandom.com/wiki/(.*)",
            "excludePattern": "",
            "patternDesc": "",
            "redirectUrl": "https://minecraft.wiki/w/$1",
            "patternType": "R",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        },
        {
            "description": "",
            "exampleUrl": "https://www.youtube.com/",
            "exampleResult": "localhost",
            "error": null,
            "includePattern": "*youtube.com*",
            "excludePattern": "",
            "patternDesc": "",
            "redirectUrl": "localhost",
            "patternType": "W",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        },
        {
            "description": "twitter",
            "exampleUrl": "https://twitter.com/testhttps://nitter.poast.org$1",
            "exampleResult": "https://xcancel.com/testhttps://nitter.poast.org$1",
            "error": null,
            "includePattern": "https://twitter.com(.*)",
            "excludePattern": "",
            "patternDesc": "",
            "redirectUrl": "https://xcancel.com$1",
            "patternType": "R",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        },
        {
            "description": "twitter",
            "exampleUrl": "https://x.com/test",
            "exampleResult": "https://nitter.poast.org/test",
            "error": null,
            "includePattern": "https://x.com(.*)",
            "excludePattern": "",
            "patternDesc": "",
            "redirectUrl": "https://nitter.poast.org$1",
            "patternType": "R",
            "processMatches": "noProcessing",
            "disabled": false,
            "grouped": false,
            "appliesTo": [
                "main_frame"
            ]
        }
    ]
}
```

### Dark mode PDF reader

You may just use `invert(100%)` but this appears to work better with preserving colors. Adjust the contrast and other parameters as desired.

Credit for the idea: https://github.com/mozilla/pdf.js/issues/2071#issuecomment-830446509

Add this to `userContent.css` (See instructions how to use firefox styles on [userchrome.org](https://www.userchrome.org/how-create-userchrome-css.html)):
```css
/* Dark mode PDF viewer */
#viewerContainer > #viewer > .page {
  filter: invert(64%) contrast(300%) brightness(80%) hue-rotate(180deg);
}

#viewerContainer > #viewer > .page > .textLayer ::selection {
  background-color: yellow;
}
/* END Dark mode PDF viewer */
```