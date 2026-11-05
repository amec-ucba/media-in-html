# 📄 CE10: Media

Embed audio, video, and a YouTube player in a web page, and style the page heading with a
Google Font.

**Points:** 10

## 🎯 Overview

Early websites needed browser plug-ins to play sound or video. HTML5 added built-in
`audio` and `video` elements, so media now plays without any extra software.

In this coding exercise you start with a page that is already laid out and styled. Your job is
to fill in the empty sections. You will add a Google Font to the page heading, embed an audio
file with the `audio` element, and embed a video in three file formats with the `video` and
`source` elements. You will also embed a YouTube video with an `iframe`.

The page also shows the old HTML4 way of embedding media: an `object` element that relied on
a plug-in. That player won't work in a modern browser. **That is expected** — it is there to
show you how things used to be done. Leave it alone.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Add a Google Font to a page with a `link` element and a CSS `font-family` rule
- Explain why browsers needed plug-ins for media before HTML5
- Embed audio with the `audio` element
- Embed video with the `video` element
- Offer a video in several file formats (`.mp4`, `.webm`, `.ogv`) with `source` elements
- Use media attributes such as `controls`, `src`, and `type`
- Embed a YouTube video with its `iframe` embed code
- Link to files inside subfolders like `audio/` and `video/`

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. They
walk you through the entire exercise. Watch them **in order** and follow along in Visual
Studio Code. Pause whenever you need time to finish a step. It is normal to pause, rewind,
and rewatch parts of a coding demonstration.

Each video builds on the previous one, so please don't skip ahead.

| Video | What you will do |
| --- | --- |
| **Part 1 — Overview & Fonts** | Tour the starter files, then pick a Google Font and add it to the page heading. The `link` code goes in the `head` of `index.html`. The `font-family` rule goes in the `h1` rule in `styles.css`. |
| **Part 2 — HTML4 Video & HTML5 Audio** | See how the old HTML4 `object` element embedded media with a plug-in. Then add an `audio` element that plays `audio/shatner2.mp3`. |
| **Part 3 — HTML5 Video** | Add a `video` element with three `source` elements so the video plays in every browser: `video/demi.mp4`, `video/demi.webm`, and `video/demi.ogv`. |
| **Part 4 — YouTube Video & Other Media** | Copy the embed code for a YouTube video and paste it into the page. Then look at the links to other kinds of media you can embed. |

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> HTML and CSS, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files:** don't download `media start.zip`. Create your own repo
>   from this template and open it with GitHub Desktop, as described in the
>   [README](README.md#-getting-started).
> - **Submitting:** don't zip your folder or upload a file. Publish your page to GitHub
>   Pages and submit a pull request URL in Canvas, as described in the
>   [README](README.md#-submitting-the-assignment).

> [!NOTE]
> **Two tips from the videos:**
>
> - When you type `video` in VS Code, it auto-completes an opening tag with a `src=""`
>   attribute. You are using `source` elements instead, so **delete `src=""`** from the
>   `video` tag and type `controls="controls"` in its place.
> - **YouTube videos don't play in the VS Code Live Preview window.** Open `index.html` in a
>   real web browser (Chrome, Firefox, Safari, or Edge) to check that your YouTube player
>   works. Once your page is on GitHub Pages, test it on your live site too.

> [!IMPORTANT]
> Open the entire project **folder** in VS Code, not just `index.html`. Keep the `audio`
> and `video` folders next to `index.html`, and don't rename or move the media files. If
> you do, your `src` paths will break and the media won't play.

## 📂 Starter Files

| File / Folder | Purpose |
| --- | --- |
| `index.html` | The page. Add your Google Font `link`, `audio`, `video`, and YouTube embed here. |
| `styles.css` | The page's styles. Add your Google Font `font-family` to the `h1` rule. |
| `reset.css` | Removes the browser's default styles. Don't edit it. |
| `audio/shatner1.mp3` | Used by the HTML4 `object` example. Already in place. Don't change it. |
| `audio/shatner2.mp3` | The song for your `audio` element. |
| `video/demi.mp4`, `video/demi.webm`, `video/demi.ogv` | The same video in three formats, one for each of your `source` elements. |

Comments with arrows mark every spot where your code goes:

```
<!-- ⬇ Paste the HTML for your Google Font below ⬇ -->
<!-- ⬇ Add your <audio> element here ⬇ -->
<!-- ⬇ Add your <video> and <source> elements here ⬇ -->
<!-- ⬇ Add the embed code of a YouTube video here ⬇ -->
/* ⬇Paste the CSS for your Google Font below⬇ */
```

Put your code right below each comment. Leave the comments in place.

## ✅ Before You Submit

Check the following:

- [ ] The Google Font `link` code is in the `head` of `index.html`
- [ ] The `h1` rule in `styles.css` uses your Google Font with `font-family`, and the page heading shows the new font
- [ ] The HTML5 Audio section has an `audio` element with controls that plays `audio/shatner2.mp3`
- [ ] The HTML5 Video section has a `video` element with controls
- [ ] The `video` element has three `source` elements, one each for `demi.mp4`, `demi.webm`, and `demi.ogv`
- [ ] The `video` tag doesn't have a leftover empty `src=""` attribute
- [ ] The YouTube section has a working YouTube embed (tested in a real browser, not VS Code Live Preview)
- [ ] The HTML4 `object` example and the starter text are still on the page
- [ ] The `audio` and `video` folders and all the media files are still in the repo, with their original names
- [ ] You saved both `index.html` and `styles.css`
- [ ] The page is live on GitHub Pages, the audio and video play there, and the URL is in your pull request

## 🧮 Grading

| Criteria | Points |
| --- | --- |
| **Google Font** — the font's `link` is in the `head`, and the `h1` uses it with `font-family` | 2 |
| **HTML5 audio** — an `audio` element with controls plays `audio/shatner2.mp3` | 2 |
| **HTML5 video** — a `video` element with controls and three `source` elements (`.mp4`, `.webm`, `.ogv`) with correct paths | 3 |
| **YouTube embed** — the YouTube `iframe` embed code is in the YouTube section, and the video plays | 2 |
| **Published and submitted** — the page is live on GitHub Pages with working media, and the pull request is filled in and submitted in Canvas | 1 |
| **Total** | **10** |

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save both `index.html` and `styles.css`?
- Do your `src` paths include the folder name? Use `audio/shatner2.mp3`, not just
  `shatner2.mp3`.
- Are the file names spelled exactly right, including the extension and lowercase letters?
  GitHub Pages is case-sensitive, so `Demi.mp4` won't find `demi.mp4`.
- Does your `audio` or `video` element have the `controls` attribute? Without it there is no
  play button.
- Are the `source` elements *inside* the `video` element, between `<video>` and `</video>`?
- Did you delete the empty `src=""` that VS Code added to the `video` tag?
- Is your heading still in the default font? Check that the Google Font `link` is inside the
  `head`, and that the `font-family` name in `styles.css` is spelled exactly as Google Fonts
  shows it.
- Does the YouTube player show "Video Unavailable"? Some videos, often ones with copyrighted
  music, can't be embedded. Pick a different video.
- Does the YouTube player give an error in VS Code? Open the page in a real browser instead.
- The HTML4 `object` player doesn't work. That is expected — modern browsers no longer
  support the plug-in it needs.

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [Google Fonts](https://fonts.google.com/) — pick a font, then click **Get font** →
  **Get embed code**
- [MDN — Video and audio content](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio)
- [MDN — `<audio>`: The Embed Audio element](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/audio)
- [MDN — `<video>`: The Video Embed element](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/video)
- [MDN — `<source>`: The Media or Image Source element](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/source)
- [YouTube Help — Embed videos and playlists](https://support.google.com/youtube/answer/171780)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) — paste your
  HTML in to catch unclosed tags

---

The AI policy and submission instructions are in the [README](README.md).
