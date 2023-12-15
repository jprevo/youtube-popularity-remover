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

m.youtube.com##span.small-text.ytm-badge-and-byline-item-byline:nth-of-type(3)
m.youtube.com##span.ytm-badge-and-byline-separator:nth-of-type(4)
m.youtube.com##.modern-panel-with-inline-badge-subtitle > .secondary-text > .yt-core-attributed-string
m.youtube.com##.subhead
m.youtube.com##.slim-video-action-bar-actions > .smartimation--enable-masking.smartimation > .smartimation__content
m.youtube.com##ytm-badge-and-byline-renderer:nth-of-type(2)
m.youtube.com##.slim-video-information-title-and-badges > div > .secondary-text
m.youtube.com##.comments-entry-point-header-count
m.youtube.com##div.comment-icons:nth-of-type(1)
m.youtube.com##div.comment-icons:nth-of-type(2)
m.youtube.com##.typography-body-2a.engagement-panel-section-list-header-context
m.youtube.com##ytm-sentiment-factoid-renderer
m.youtube.com##ytm-factoid-renderer:nth-of-type(1)
m.youtube.com##.ytm-video-description-infocards-section-subtitle
m.youtube.com##span.c4-tabbed-header-page-header-metadata-item:nth-of-type(2)
m.youtube.com##.c4-tabbed-header-page-header-metadata-item-delimiter
m.youtube.com##div.about-channel-section:has(.channel-detail-value)
```

### Licence
MIT
