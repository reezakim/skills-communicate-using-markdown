# Daily Learning
## Morning Planning
- [ ] Check Out The [github blog](https://github.blog/) for topic ideas.
- [ ] Learn About [Github Pages](https://skills.github.com/first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
Convert an image or video from dark mode to Light mode using [ffmped](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
