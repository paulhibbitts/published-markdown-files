# Leap into Open Publishing with Docsify-This!

**Follow along during the session • Try the challenges • Share results • Ask questions**

---

## 📍 Session Outline

| What We're Doing | Join In |
|------------------|-------------|
| Intro | Experience the magic! |
| Web Page Builder Demo | View the workflow |
| 🎨 Challenge 1: Style Lab | PUBLISH a page! |
| Power Tip: URL Parameters | Learn a shortcut |
| 🔍 Challenge 2: Style Detective | MATCH a design! |
| Next Steps + Q&A | Ask questions! |

---

## 🚀 Quick Start

### The 3-Step Process

**1. Get Your Markdown file URL**
- GitHub or Codeberg: View file → Copy URL
- Or use either example:
  - [github.com/paulhibbitts/demo-markdown-file/blob/main/README.md](https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md)
  - [codeberg.org/paulhibbitts/demo-markdown-file/src/branch/main/README.md](https://codeberg.org/paulhibbitts/demo-markdown-file/src/branch/main/README.md)

**2. Visit the Docsify-This Web Page Builder**
```
https://docsify-this.net
```

**3. Paste → Style → Publish!**
- Paste Markdown file URL into Web Page Builder
- Choose page layout (Content Only / ToC / Sidebar)
- Tap **Show More Page Appearance Options »** link for more styling options
- Click **Publish as a Web Page** button

---

## 🎨 Challenge 1: Style Lab

### Your Mission
Transform this Markdown file YOUR way:
```
https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/README.md
```

### Try These Styles

**Presentation Style**
```
☐ Page layout: Content only
☐ Large font (32-36px)
☐ Dark mode: On
☐ Max width: 80%
```

**LMS Embedding Style**
```
☐ Page layout: Content only
☐ Font: Match your LMS
☐ Size: 16-18px
☐ Link color: Visually match or find out HexCode
☐ Max width: 100%
```

**Project Documentation Style**
```
☐ Page layout: Table of Contents or Sidebar
☐ Font: Sans serif
☐ Size: 18px
☐ Max width: 65ch
```

**Your Way!**
```
☐ Page layout: ???
☐ Font family: ???
☐ Font size: ???
☐ Link color: ???
☐ Headers font weight: ???
☐ Max width: ???
☐ Dark theme: ???
☐ And who knows!
```

### Share Your Results!
Post your Docsify-This URL in Discord and describe your design choice!

---

## ⚡ Power Tip: URL Parameters

### The Pro Shortcut
Instead of using the Web Page Builder every time, you can also **edit URL parameters directly** when viewing the published page!

### Example URL Breakdown
```
https://docsify-this.net?basePath=...
&homepage=home.md
&font-size=18px          ← Change this!
&link-color=0374B5       ← Or this!
&max-width=80%           ← Or this!
```

You can also add an URL parameter if one is not present (and a default value is being used).

### Some Other Commonly Adjusted Parameters

| Parameter | Options | Example |
|-----------|---------|---------|
| `dark-mode` | false/auto/on | `&dark-mode=auto` |
| `sidebar` or `toc` | true/false | `&sidebar=true` |
| `header-weight` | 400-700 | `&header-weight=600` |

### Why This Matters
✅ **Quickly refine** styled pages  
✅ **Batch-style** multiple pages  
✅ **Share recipes** as plain text  
✅ **Create configurations** for reuse  

---

## 🔍 Challenge 2: Style Detective

### Your Mission
**Match the target design!** Look at the Docsify-This page screenshot posted in Discord.

### Starting Point (Unstyled)
```
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md
```

### Aspects to Consider
```
☐ Page layout:
☐ Font family:
☐ Font size:
☐ Link color:
☐ Headers weight:
☐ Width:
☐ Sidebar header level:
```

### Hints Along the Way
Watch Discord for hints if you get stuck!

### Share Your Results!
Post your Docsify-This URL in Discord and share your style guesses!

---

## 🎯 Next Steps + Q&A

**Before You Leave**
- [ ] Save both your challenge URLs
- [ ] Bookmark [Docsify-This.net](https://docsify-this.net)
- [ ] Join Discord #Docsify-This channel

**Next Week**
- [ ] Publish your own Markdown file
- [ ] Try a ready-made template
- [ ] Share a Docsify-This page URL

### Frequently Asked Questions

**Q: Do I need to install anything?**  
A: No! 100% web-based. Just paste and go.

**Q: Where is my content stored?**  
A: On YOUR GitHub/Codeberg/server account. You keep full control.

**Q: Can I use private repos?**  
A: Yes! Enable GitHub Pages, then use those raw URLs

**Q: Will Google index my pages?**  
A: No (due to client-side rendering).

**Q: Is there a cost?**  
A: No, Docsify-This is free and open source!

**Q: Can I customize more?**  
A: Yes! Advanced URL parameters are available, and custom CSS is supported. Still not enough? Host your own instance!

---

## 📚 Additional Resources

### All About Markdown 

* Markdown Format
  * [What Is Markdown, and How Do You Use It?](https://www.howtogeek.com/448323/what-is-markdown-and-how-do-you-use-it/)
  * [Markdown Guide](http://markdownguide.org)
  * [Markdown Cheatsheet](http://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Accessibility
  * [Improving The Accessibility Of Your Markdown](https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown/)
* Creating and Editing Markdown on GitHub
  * [Quickstart for writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
  * [Authoring With Markdown](https://ucsbcarpentry.github.io/2022-01-31-ucsb-webpub-online/02-markdown/)
* Markdown Desktop Editors
  * [VSCode](https://code.visualstudio.com/)
  * [Pulsar (was Atom.io)](https://pulsar-edit.dev/)
  * [Typora](https://typora.io/)

### Docsify-This Presets & Templates

#### Load-and-Go Presets
Pre-configured styling for common needs:

- Basic Presentation: [present.docsify-this.net](http://present.docsify-this.net)
- Presentation with Docsify Sidebar (auto-closes):  [present-nav.docsify-this.net](http://present-nav.docsify-this.net)
- Canvas LMS: [canvas.docsify-this.net](http://canvas.docsify-this.net)
- Moodle LMS: [moodle.docsify-this.net](http://moodle.docsify-this.net)
- Brightspace: [brightspace.docsify-this.net](http://brightspace.docsify-this.net)
- Sakai LMS: [sakai.docsify-this.net](http://sakai.docsify-this.net)

Just paste your Markdown URL and go!

#### Some of the Ready-to-Use Templates
**Don't start from scratch!** Use these GitHub templates:

- Single article/document: [github.com/hibbitts-design/docsify-this-one-page-article](https://github.com/hibbitts-design/docsify-this-one-page-article)
- Course module page: [github.com/hibbitts-design/docsify-this-one-page-course](https://github.com/hibbitts-design/docsify-this-one-page-course)
- Multi-page website: [github.com/hibbitts-design/docsify-this-multiple-page-site](https://github.com/hibbitts-design/docsify-this-multiple-page-site)
- Blog-style website: [github.com/hibbitts-design/docsify-this-multiple-page-blog-style-site](https://github.com/hibbitts-design/docsify-this-multiple-page-blog-style-site)

**To use:** Click "Use this template" → Create repo → Edit → Publish!

---

### Essential Docsify-This Project Links

| Resource | URL |
|----------|-----|
| **Web Page Builder** | [docsify-this.net](https://docsify-this.net) |
| **Full Documentation** | [readme.docsify-this.net](http://readme.docsify-this.net) |
| **Templates** | [github.com/hibbitts-design](https://github.com/hibbitts-design) |
| **Discord Community** | [discord.gg/docsify](https://discord.gg/docsify) |
| **GitHub Repository** | [github.com/hibbitts-design/docsify-this](https://github.com/hibbitts-design/docsify-this) |

---

**Session:** Leap into Open Publishing with Docsify-This!  
**Presenter:** Paul Hibbitts  

---

**Remember:** Your content, your control, zero hassle. 🚀
