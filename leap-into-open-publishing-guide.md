# Leap into Open Publishing with Docsify-This

**Follow along • Try the challenges • Share results • Ask questions**

---

## 📍 Session Outline

| What We're Doing | Join In |
|------------------|-------------|
| 📝 Markdown Basics | Brief review |
| 🚀 Quickstart | Experience the magic |
| 🎨 Challenge 1: Style Lab | PUBLISH a page! |
| Power Tip: URL Parameters | Learn a shortcut |
| 🔍 Challenge 2: Style Detective | MATCH a design! |
| Next Steps + Q&A | Ask questions! |

## 📝 Markdown Basics

**Before we dive in**, let's quickly review what Markdown is — the simple format that powers everything you'll publish today.

| You Would Type | You Would Get |
|----------|---------|
| `# Heading 1` | Large heading |
| `## Heading 2` | Medium heading |
| `**bold text**` | **bold text** |
| `*italic text*` | *italic text* |
| `[link text](URL)` | Clickable link |
| `![alt text](image.jpg)` | Embedded image |
| `- Item` | • Bulleted list |

**Ready to see it in action?** Let's publish your first page!

<details>
<summary>Show a preview of the Web Page Builder interface</summary>

<p>
  <em>Figure 1. <strong>Docsify-This</strong> Web Page Builder - just paste your Markdown file URL, style and publish!</em>
</p>
<p>
 <picture>
  <source srcset="https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-this-v1-10-7-web-page-builder-dark.png" media="(prefers-color-scheme: dark)">
  <img src="https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-this-v1-10-7-web-page-builder.png" alt="Docsify-This Web Page Builder interface showing URL input field, page layout options, styling controls, and publish button">
 </picture>
</p>

</details>

---

## 🚀 Quickstart

### The 3-Step Process

**1. Get Your Markdown file URL**

- GitHub or Codeberg: View file › Copy URL
- Or use either example:
  - [github.com/paulhibbitts/demo-markdown-file/blob/main/README.md](https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md  ':target=_blank') ↗ <button type="button" class="copy-link" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>
  - [codeberg.org/paulhibbitts/demo-markdown-file/src/branch/main/README.md](https://codeberg.org/paulhibbitts/demo-markdown-file/src/branch/main/README.md ':target=_blank') ↗ <button type="button" class="copy-link" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://codeberg.org/paulhibbitts/demo-markdown-file/src/branch/main/README.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

**2. Visit the Docsify-This Web Page Builder**

- [Open Docsify-This.net](https://docsify-this.net#/ ':target=_blank') ↗

**3. Paste › Style › Publish!**

- Paste Markdown file URL into Web Page Builder
- Choose page layout (Content Only / ToC / Sidebar)
- Tap **Show More Page Appearance Options »** link for more styling options
- Click **Publish as a Web Page** button

> [!TIP]
> After publishing, take a look at the resulting URL in your browser's address bar - notice how your Web Page Builder choices appear as URL parameters on the generated page.

---

## 🎨 Challenge 1: Style Lab

### Your Mission

Transform this Markdown file YOUR way:

[https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md](https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md) ↗ <button type="button" class="copy-link" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

Paste the above URL into the [Docsify-This.net](https://docsify-this.net ':target=_blank') ↗ Web Page Builder you just visited! Don't see the expected styling options? Tap the **Show More Page Appearance Options »** link.

### Consider These Style Types

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
☐ Link color: Visually match or find out hex color code
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

### Share Your Results

Post your Docsify-This URL in the session chat and describe your design choice!

---

## ⚡ Power Tip: URL Parameters

### The Pro Shortcut

Instead of using the Web Page Builder every time, you can also **edit URL parameters directly** when viewing the published page!

### Example URL Breakdown

```
https://docsify-this.net?basePath=...
&homepage=home.md
&font-size=18px      ← Change this! (size in pixels)
&link-color=0374B5   ← Or this! (6-digit hex color, e.g. CC0000)
&max-width=80        ← Or this! (percentage width)
```

You can also add an URL parameter if one is not present (and a default value is being used).

### Some Other Commonly Added or Adjusted Parameters

| Parameter | Options | Example |
|-----------|---------|---------|
| `sidebar` or `toc` | true/false | `&sidebar=true` |
| `maxLevel` | 1-6 (Sidebar header depth) | `&maxLevel=3` |
| `header-weight` | 400-700 | `&header-weight=600` |
| `dark-mode` | on/auto/off | `&dark-mode=auto` |

### Why This Matters

✅ **Quickly refine** styled pages  
✅ **Batch-style** multiple pages  
✅ **Share recipes** as plain text  
✅ **Create configurations** for reuse  

---

## 🔍 Challenge 2: Style Detective

### Your Mission

**Decode this Docsify-This URL!** Examine the Docsify-This page URL posted in the session chat and figure out what styling choices were made by analyzing the URL parameters.

### Your Detective Work

Analyze the URL and identify these styling choices:

```
☐ Page layout:
☐ Navigation header level:
☐ Font family:
☐ Font size:
☐ Headers weight:
☐ Width:
☐ Dark mode setting:
```

### Bonus Challenge

Try to recreate the same styling using the Web Page Builder instead of URL parameters!

### Hints Along the Way

Watch the session chat for hints if you get stuck decoding any parameters!

### Share Your Findings

Post your decoded styling list in the session chat and share if any parameters were unexpected or gave you ideas for your own styling!

---

## Practice Version (Shorter URL)

### Mystery URL to Decode

```
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&font-family=Merriweather,Georgia,serif&link-color=cc0000
```

---

## 🎯 Next Steps + Q&A

> [!NOTE]
> All external links below open in a new browser tab.

**Before You Leave**

- [ ] Save your Challenge 1 URL
- [ ] Bookmark [Docsify-This.net](https://docsify-this.net  ':target=_blank')
- [ ] Join [discord.gg/docsify](https://discord.gg/docsify) #Docsify-This channel

**After Today's Session**

- [ ] Publish your own Markdown file
- [ ] Try a ready-made template
- [ ] Share a Docsify-This page URL

### Frequently Asked Questions

**Q: Do I need to install anything?**  
A: No! 100% web-based. Just paste and go.

**Q: Where is my content stored?**  
A: On YOUR GitHub/Codeberg/server account. You keep full control.

**Q: Can I use private repos?**  
A: Yes! Enable GitHub Pages, then use those raw URLs.

**Q: Will Google index my pages?**  
A: No (due to client-side rendering).

**Q: Is there a cost?**  
A: No, Docsify-This is free and open source!

**Q: Can I customize more?**  
A: Yes! Advanced URL parameters are available, and in addition to supported Markdown CSS classes custom CSS is also possible. Still not enough? Host your own instance!

---

## 📚 Additional Resources

### All About Markdown

- Markdown Format
  - [What Is Markdown, and How Do You Use It?](https://www.howtogeek.com/448323/what-is-markdown-and-how-do-you-use-it/)
  - [Markdown Guide](http://markdownguide.org)
  - [Markdown Cheatsheet](http://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Accessibility
  - [Improving The Accessibility Of Your Markdown](https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown/)
- Creating and Editing Markdown on GitHub
  - [Quickstart for writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
  - [Authoring With Markdown](https://ucsbcarpentry.github.io/2022-01-31-ucsb-webpub-online/02-markdown/)
- Markdown Desktop Editors
  - [VSCode](https://code.visualstudio.com/)
  - [Pulsar (was Atom.io)](https://pulsar-edit.dev/)
  - [Typora](https://typora.io/)

### Docsify-This Presets & Templates

#### Load-and-Go Presets

Pre-configured styling for common needs:

**Presentations:**

- Basic presentation: [present.docsify-this.net](http://present.docsify-this.net)
- With navigation sidebar (auto-closes): [present-nav.docsify-this.net](http://present-nav.docsify-this.net)

**LMS Integration:**

- Canvas: [canvas.docsify-this.net](http://canvas.docsify-this.net)
- Moodle: [moodle.docsify-this.net](http://moodle.docsify-this.net)
- Brightspace: [brightspace.docsify-this.net](http://brightspace.docsify-this.net)
- Sakai: [sakai.docsify-this.net](http://sakai.docsify-this.net)

Just paste your Markdown file URL and go!

#### Some of the Ready-to-Use Templates

**Don't start from scratch!** Use these GitHub templates:

- Single article/document: [github.com/hibbitts-design/docsify-this-one-page-article](https://github.com/hibbitts-design/docsify-this-one-page-article)
- Course module page: [github.com/hibbitts-design/docsify-this-one-page-course](https://github.com/hibbitts-design/docsify-this-one-page-course)
- Multi-page website: [github.com/hibbitts-design/docsify-this-multiple-page-site](https://github.com/hibbitts-design/docsify-this-multiple-page-site)
- Blog-style website: [github.com/hibbitts-design/docsify-this-multiple-page-blog-style-site](https://github.com/hibbitts-design/docsify-this-multiple-page-blog-style-site)

**To use:** Click "Use this template" › Create repo › Edit › Copy `home.md` URL › Paste URL › Publish!

---

### Essential Docsify-This Project Links

| Resource | URL |
|----------|-----|
| **Web Page Builder** | [docsify-this.net](https://docsify-this.net ':target=_blank') |
| **Full Documentation** | [readme.docsify-this.net](http://readme.docsify-this.net) |
| **Templates** | [github.com/hibbitts-design](https://github.com/hibbitts-design) |
| **Discord Community** | [discord.gg/docsify](https://discord.gg/docsify) |
| **GitHub Repository** | [github.com/hibbitts-design/docsify-this](https://github.com/hibbitts-design/docsify-this) |

---

**Session:** Leap into Open Publishing with Docsify-This!  
**Presenter:** Paul Hibbitts  

---

**Remember:** Your content, your control, zero hassle. 🚀
