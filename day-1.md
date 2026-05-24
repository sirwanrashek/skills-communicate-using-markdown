<h1> # Daily Learning</h1>

<h3> ## Morning Planning </h3>
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.<br>
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).<br>
- [ ] Convert my first blog post into an actual webpage.<br>

<h4> ## Review </h4>

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
