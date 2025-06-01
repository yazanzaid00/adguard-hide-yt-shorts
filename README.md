# Hide YouTube Shorts (AdGuard)

An AdGuard-compatible filter list to hide all traces of YouTube Shorts videos (desktop & mobile).

This filter list is specifically tailored for AdGuard but may work with other content blockers.

Copy the link below, open AdGuard Custom Filters, and paste it under “Add a filter list by URL” or “Import…”:

- `https://raw.githubusercontent.com/yazanzaid00/adguard-hide-yt-shorts/master/adguard-youtube-shorts-hide.txt`


---

**Extra Tip:** Redirect a Shorts URL to a standard video URL using this regex:
```
/^(https?:\/\/(?:[^\/]+\.)?youtube\.com)\/shorts\/([^\/\?\&]+)(.*)$/
```
Replace with:
```
$1/watch?v=$2$3
```

## License

See [LICENSE.md](https://github.com/yazanzaid00/adguard-hide-yt-shorts/blob/master/LICENSE.md)
