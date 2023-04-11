# RF: A Reddit Frontend

<p align="center">
<img width="200" src="doc/logo.png">
</p>

RF is a portable Reddit frontend distributed as a single HTML file. Try it [here](https://rf.alexkoen.com/#/r/eyebleach+programming) or download it to your device.

# Screenshots

<p align="center">
<img width="80%" src="doc/home.png">
</p>

---

<p align="center">
<img width="80%" src="doc/post.png">
</p>

# Features
- [x] Bundled as a single HTML file
- [x] Multireddit support
- [x] HN-style comment navigation
- [x] Inline media preview
- [x] Optional link preview with 12ft.io (disabled by default)
- [x] PWA support

# Redirecting from Reddit.com

RF supports handling standard Reddit URLs as location hashes. You can therefore use the [Redirector](https://github.com/einaregilsson/Redirector) browser extension to route all Reddit links to RF.

![](doc/redirect.png)

# Notes

- Because RF does not provide its own backend it's limited by CORS policies. You may need to disable your browser's "enhanced tracking protection" for this site for it to work.
- Although Add to Home Screen is supported on most browsers, the experience on mobile is subjectively better as a normal site as external links display in new tabs.
