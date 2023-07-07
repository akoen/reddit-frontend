<h3 align="center">RF: A (Working) Reddit Frontend</h3>
<p align="center">
<img width="200" src="doc/logo.png"/>
</p>

RF is a portable Reddit frontend distributed as a single HTML file that **still works** with Reddit's new API policy. Try it [here](https://rf.alexkoen.com/#/r/eyebleach+programming) or download it to your device.

:warning: You may need to disable Firefox's "Enhanced Tracking Protection", which prevents RF from making CORS requests to reddit.com. See [notes](#notes).
# Content
- [Features](#features)  
- [Screenshots](#screenshots)
- [Redirecting from Reddit.com](#redirecting-from-redditcom)
- [Notes](#notes)

# Features
- [x] Bundled as a single HTML file
- [x] Multireddit support
- [x] HN-style comment navigation
- [x] "Instant" post loading
- [x] Inline media preview
- [x] Optional link preview with 12ft.io (disabled by default)
- [x] PWA support

# Screenshots

<p align="center">
<img width="80%" src="doc/home.png">
<br>
<em><a href="https://rf.alexkoen.com/#/r/climbing+linux">Multireddit support with configurable number of posts.</a></em>
</p>

<p align="center">
<img width="80%" src="doc/gallery.png">
<br>
<em><a href="https://rf.alexkoen.com/#/r/climbing/comments/121ogdt/aiguille_de_blaitière_chamonix_night_and_day_oc/">Embedded multimedia preview.</a> Supports images, galleries, videos and more.</em>
</p>

<p align="center">
<img width="80%" src="doc/link-preview.png">
<br>
<em><a href="https://rf.alexkoen.com/#/r/programming/comments/x8el14/how_the_sqlite_virtual_machine_works/">Inline link-preview</a> (enable in settings).</em>
</p>

# Redirecting from Reddit.com

RF supports handling standard Reddit URLs as location hashes. You can therefore use the [Redirector](https://github.com/einaregilsson/Redirector) browser extension to route all Reddit links to RF.

![](doc/redirect.png)

# Notes

- Because RF does not provide its own backend it's limited by CORS policies. You may need to disable your browser's "enhanced tracking protection" for this site for it to work.
  
  ![image](https://github.com/akoen/reddit-frontend/assets/43913902/5383288c-0eea-4a77-ae67-b4ffc1489f89)

- Although Add to Home Screen is supported on most browsers, the experience on mobile is subjectively better as a normal site as external links display in new tabs.
