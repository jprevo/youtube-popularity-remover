# youtube-popularity-remover
uBlock Origin filters to remove all popularity data from YouTube : views, likes and such. You'll be amazed at how your eyes automatically search for this uninteresting information.

Go to uBlock Origin settings, My filters tab, and add the following content: 

```
! YouTube Popularity Remover - github.com/jprevo/youtube-popularity-remover
www.youtube.com##span.ytd-video-meta-block.style-scope.inline-metadata-item:nth-of-type(1)
www.youtube.com##span.ytd-video-meta-block.style-scope.inline-metadata-item::before
www.youtube.com###owner-sub-count
www.youtube.com##.ytd-menu-renderer.style-scope.YtSegmentedLikeDislikeButtonViewModelHost
www.youtube.com###view-count
www.youtube.com##span.yt-formatted-string.style-scope.bold:nth-of-type(1)
www.youtube.com##span.yt-formatted-string.style-scope.bold:nth-of-type(2)
www.youtube.com##.ytd-comments-header-renderer.style-scope.count-text
www.youtube.com###like-button
www.youtube.com###dislike-button
www.youtube.com###vote-count-middle
www.youtube.com##span.ytd-c4-tabbed-header-renderer.style-scope.meta-item:nth-of-type(3)
www.youtube.com##span.ytd-grid-video-renderer.style-scope:nth-of-type(1)
www.youtube.com##span.ytd-grid-video-renderer.style-scope:nth-of-type(2)::before
www.youtube.com###thumbnail-attribution
www.youtube.com##span.yt-formatted-string.style-scope:nth-of-type(1)
www.youtube.com##span.yt-formatted-string.style-scope:nth-of-type(2)
www.youtube.com##yt-formatted-string.ytd-playlist-byline-renderer.style-scope.byline-item:nth-of-type(2)
www.youtube.com##.ytd-c4-tabbed-header-renderer.style-scope.delimiter
```

### Licence
MIT
