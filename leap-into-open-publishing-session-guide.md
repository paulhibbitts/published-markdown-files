# Leap into Open Publishing with Docsify&#8209;This

**Follow along • Try challenges • Share results • Ask questions**

---

## 📍 Session Outline

| What We're Doing | Join In |
|------------------|-------------|
| 📝 Markdown Basics | Brief overview |
| ▶️ Get Started | Experience the magic |
| 🎨 Challenge 1: Style Lab | DESIGN a page! |
| ⚡️ Power Tip: URL Parameters | Learn a shortcut |
| 🔍 Challenge 2: Style Detective | DECODE a design! |
| 🎯 Next Steps + Common Questions | Get answers |

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
 <picture>
  <source srcset="https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-this-v1-10-7-web-page-builder-dark.png" media="(prefers-color-scheme: dark)">
  <img src="https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-this-v1-10-7-web-page-builder.png" alt="Docsify-This Web Page Builder interface showing URL input field, page layout options, styling controls, and publish button">
 </picture>
</p>

</details>

---

## ▶️ Get Started

Turn an online Markdown file into a styled web page in 3 simple steps.

### The 3-Step Process

**1. Get Your Markdown file URL**

- [GitHub](https://github.com) ↗, [Codeberg](https://codeberg.org) ↗, or any public location:  
  View file › Copy URL
- Or use this example file:
  - [github.com/paulhibbitts/demo-markdown-file/blob/main/README.md](https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md  ':target=_blank') ↗ <button type="button" class="copy-link" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

**2. Visit the Docsify-This Web Page Builder**

- [Open Docsify-This.net](https://docsify-this.net#/ ':target=_blank') ↗

**3. Paste › Style › Publish!**

- Paste Markdown file URL into Web Page Builder
- Choose page layout (Content Only / ToC / Sidebar)
- Click **Publish as a Web Page** button

> [!TIP]
> After publishing, take a look at the resulting URL in your browser's address bar - notice how your Web Page Builder choices appear as URL parameters on the generated page.

---

## 🎨 Challenge 1: Style Lab

### Your Mission

Publish and style this online Markdown file YOUR way:  

[https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md](https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md) ↗ <button type="button" class="copy-link" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

Paste the above URL into the [Docsify-This.net](https://docsify-this.net ':target=_blank') ↗ Web Page Builder you just visited! To view additional styling possibilities tap the **Show More Page Appearance Options »** link.

### Consider These Style Types

**Simple Page**

```
☐ Page layout: Content only
☐ Font: Merriweather
☐ Font size: 16px
```

**Presentation Style**

```
☐ Page layout: Content only
☐ Large font (32-36px)
☐ Headers font weight: Semi Bold
☐ Dark mode: On
☐ Max width: 80%
```

**LMS Embedding Style**

```
☐ Page layout: Content only or Table of Contents
☐ Font: Match your LMS
☐ Font size: 16-18px
☐ Link color: Visually match or find out hex color
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

Feel free to post your Docsify-This URL in the session chat and describe your design choice!

---

## ⚡ Level Up Tip: URL Parameters

### Skip the Clicks

Instead of using the Web Page Builder every time, you can also **edit URL parameters directly** when viewing a published page!

### Example URL Breakdown

URL parameters are chained together using `&` (ampersand):

```
https://docsify-this.net?basePath=...
&homepage=home.md
&sidebar=true              ← Change this! (true/false)
&font-family=Merriweather  ← Or this! (font name)
&max-width=80              ← Or this! (percentage width)
```

### Try It Yourself!

**Ready to experiment?** 

1. Return to the styled Docsify-This page you created in Challenge 1
2. Look at the URL in your browser's address bar
3. Find a parameter to change (like `sidebar=false`) or add a new one (like `&font-size=20px`)
4. Edit it directly in the URL
5. Hit the **Enter** key to reload the page and see the change!

> [!NOTE]
> Parameters with default values (like `font-size=18px`) don't appear in the URL unless you change them. To adjust a default, just add it with `&parameter=value`!

### Some Other Commonly Added or Adjusted Parameters

| Parameter | Options | Example |
|-----------|---------|---------|
| `sidebar` or `toc` | true/false | `&sidebar=true` |
| `link-color` | 6-digit color code | `&link-color=cc0000` (red) or `&link-color=0000cc` (blue)|
| `maxLevel` | 1-6 (Sidebar header depth) | `&maxLevel=3` |
| `header-weight` | 400-700 | `&header-weight=600` |
| `dark-mode` | on/auto/off | `&dark-mode=auto` |

> [!TIP]
> Looking for a certain link color? Try this [color picker](https://www.w3schools.com/colors/colors_picker.asp) ↗ to find color codes (use just the 6 digits, no #).

### Why This Matters

✅ **Quickly refine** styled pages  
✅ **Batch-style** multiple pages  
✅ **Share recipes** as plain text  
✅ **Create configurations** for reuse  

---

## ⏸️ Quick Pause

**Questions or observations before we continue?**

Challenge 2 will further explore URL parameters - a powerful shortcut for styling pages!

---

## 🔍 Challenge 2: Style Detective

### Your Mission

**Decode this Docsify-This URL!** Examine the Docsify-This page URL posted in the session chat and figure out what styling choices were made by analyzing the URL parameters.

<details>
<summary>Can't find the URL in chat? Click here for the challenge URL</summary>

```
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&edit-link=https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md&edit-link-text=Suggest_an_Edit&edit-link-top=true&sidebar=true&maxLevel=3&font-family=Merriweather,Georgia,serif&font-size=16px&link-color=cc0000&header-weight=600&max-width=65ch&dark-mode=auto
```

</details>

### Your Detective Work

Analyze the URL and identify one or more of these styling choices:

```
☐ Page layout:
☐ Font family:
☐ Font size:
☐ Link color:
☐ Headers weight:
☐ ...and what else can you discover?
```

### Bonus Challenge

Try to recreate the same styling using the Web Page Builder instead of URL parameters!

### Hints Along the Way

Watch the session chat for hints if you get stuck decoding any parameters!

### Share Your Findings

Feel free to post your decoded styling list in the session chat and share if any parameters were unexpected or gave you ideas for your own styling!

---

## 🎯 Next Steps + Common Questions

**Before You Leave**

- [ ] Bookmark this guide (reclaimopen2025.docsify-this.net)!
- [ ] Save your Challenge 1 URL

**After Today's Session**

- [ ] Consider trying the [Level Up Challenge](#%E2%9A%A1%EF%B8%8F-level-up-challenge-on-your-own)
- [ ] Try a ready-made [Markdown template](#some-of-the-ready-to-use-templates)
- [ ] Share a Docsify-This page URL

### Frequently Asked Questions

**Q: Do I need to install anything?**  
A: No! 100% web-based. Just paste and go.

**Q: Where is my content stored?**  
A: On YOUR GitHub/Codeberg/server account. You keep full control.

**Q: Can I use private GitHub repos?**  
A: Yes! Enable GitHub Pages, then use those raw URLs.

**Q: Will Google index my pages?**  
A: No (due to client-side rendering).

**Q: Is there a cost?**  
A: No, Docsify-This is free and open source!

**Q: Can I customize more?**  
A: Yes! Advanced URL parameters are available, and in addition to supported Markdown CSS classes custom CSS is also possible. Still not enough? Host your own instance!

---

## ⚡️ Level Up Challenge: On Your Own

### Your Mission

**Ready to go further?** Create and host your own Markdown file, then publish it with Docsify-This!

> [!NOTE]
> This challenge is perfect for after the session, where you move from styling existing Markdown content to creating your own!

### GitHub or Codeberg 

#### Step 1: Create a New Repository

1. **Log in** or **Sign up** to [GitHub](https://github.com) ↗ or [Codeberg](https://codeberg.org) ↗
2. **Create a new repository**:
   - Tap the **+** icon and select **New Repository**
   - Fill in the repository details:
     - Choose a **Repository Name** for your repository (e.g., `docsify-this-demo`)
     - Confirm that the **Visibility** is **Public**
   - Tap **Create Repository**

#### Step 2: Create Your Markdown Content

1. **Go to your new repository**, tap **Add File** and then choose **New File**
2. **Name your file** and use the `.md` extension (e.g., `demo.md`)
3. Enter your **Markdown content**. For example:
```markdown
   # Welcome!
   
   This is my sample Markdown file.
```

#### Step 3: View as Docsify-This Web Page

1. On your new repository, **view the Markdown file**
2. **Copy the file URL** (just the regular URL - a raw URL is not required)
3. Go to [Docsify-This.net](https://docsify-this.net ':target=_blank') ↗
4. **Paste** the copied URL into the **Markdown file URL** field
5. Tap the **Publish as Web Page** button

### What's Next?

Congratulations, you've now published your own Markdown content with Docsify-This! 

> [!TIP]
> You can also upload existing Markdown files by using **Add File › Upload files** in your repository, or use an app such as **[GitHub Desktop](https://github.com/apps/desktop)** ↗ to quickly synchronize files between your desktop and a GitHub or Codeberg repository.

---

## 📚 Additional Resources

> [!NOTE]
> All external links below open in a new browser tab.

### All About Markdown

- Markdown Format
  - [What Is Markdown, and How Do You Use It?](https://www.howtogeek.com/448323/what-is-markdown-and-how-do-you-use-it/)
  - [Markdown Guide](http://markdownguide.org)
  - [Markdown Cheatsheet](http://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Accessibility
  - [Improving The Accessibility Of Your Markdown](https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown/)
- Creating and Editing Markdown on GitHub
  - [Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
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

**Don't start from scratch!** Use these Docsify-This Markdown templates:

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
| **Markdown Publishing Guide** | [publishing.docsify-this.net](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&searchbox=true&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&maxLevel=3&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&header-weight=600&dark-mode=auto&code-copy=true#/) |
| **Full Documentation** | [readme.docsify-this.net](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this/main&homepage=README.md&edit-link=https://github.com/hibbitts-design/docsify-this/blob/main/README.md&sidebar=true&searchbox=true&browser-tab-title=Docsify-This%20ReadMe&edit-link-text=Suggest%20an%20Edit%20on%20GitHub&maxLevel=4&header-weight=600&zoom-images=true&dark-mode=auto&code-copy=true&page-copy-button=true#/) |
| **Templates** | [github.com/hibbitts-design](https://github.com/hibbitts-design) |
| **Discord Community** | [discord.gg/docsify](https://discord.gg/docsify) |
| **GitHub Repository** | [github.com/hibbitts-design/docsify-this](https://github.com/hibbitts-design/docsify-this) |

---

**Session:** Leap into Open Publishing with Docsify-This!  
**Presenter:** [Paul Hibbitts](https://www.hibbittsdesign.org/)

---

**Remember:** Your content, your control, zero hassle. 🚀
