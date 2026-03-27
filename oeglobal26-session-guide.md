#  From Markdown to Open Web: Hacking the Publishing Barrier with Docsify&#8209;This

<h2>OEGlobal26</h2>

**Follow along • Try activities • Share results • Ask questions**

---

**Docsify-This** is an open-source web app that instantly turns online Markdown
text files into styled web pages - no installation, no build process, just paste
a URL and go!

In this hands-on session, you'll learn to publish and style Markdown pages in
minutes.

## 🧭 Learning Objectives

After participating in this session, attendees will be able to:

- Describe the key benefits of Markdown as a system-independent format for open content creation and reuse.
- Use Docsify-This to instantly publish a Markdown file as a standalone, shareable web page with no server or technical infrastructure required.
- Customize the visual appearance of a Docsify-This page using the Web Page Builder or URL parameters.
- Connect Docsify-This features to the 5 Rs of OER and identify how each design principle supports open education values in practice.

## 📍 Session Outline

| What We're Doing | Join In |
|------------------|-------------|
| 📝 Markdown Basics | Brief overview |
| ▶️ Get Started | Experience the magic |
| 🎨 Activity 1: Style Lab | DESIGN a page! |
| ⚡️ Power Tip: URL Parameters | Learn a shortcut |
| 🔄 Activity 2: Docsify-This and the 5 Rs of OER | CONNECT the dots! |
| 🎯 Next Steps + Common Questions | Get answers |

## 📝 Markdown Basics

**Before we dive in**, let's quickly review what Markdown is — the simple format
that powers everything you'll publish today.

| You Would Type | You Would Get |
|----------|---------|
| `# Heading 1` | Large heading |
| `## Heading 2` | Medium heading |
| `**bold text**` | **bold text** |
| `*italic text*` | *italic text* |
| `[link text](URL)` | Clickable link |
| `![alt text](image.jpg)` | Embedded image |
| `- Item` | • Bulleted list |

**Ready to see Docsify-This in action?** Let's publish your first page!

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

> [!NOTE]
> Links with ↗ will automatically open in a new browser tab so this guide
> remains available as you proceed.

### The 3-Step Process

**1. Get Your Markdown file URL**

- [GitHub](https://github.com) ↗, [Codeberg](https://codeberg.org) ↗, or any
  public location:
  View file › Copy URL
- Or use this example file:
  - [github.com/paulhibbitts/demo-markdown-file/blob/main/README.md](https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md ':target=_blank') ↗
<br><button type="button" style="height: 1.8rem; padding: 0 12px; box-sizing: border-box; border: 1px solid #999; border-radius: 8px; background: #f8f8f8; color: #333;" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/paulhibbitts/demo-markdown-file/blob/main/README.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

**2. Visit the Docsify-This Web Page Builder**

- [Open Docsify-This.net](https://docsify-this.net#/ ':target=_blank') ↗

**3. Paste › Style › Publish!**

- Paste Markdown file URL into Web Page Builder
- Choose page layout (Content Only / ToC / Sidebar)
- Click **Publish as a Web Page** button

> [!TIP]
> After publishing, take a look at the resulting URL in your browser's address
> bar - notice how your Web Page Builder choices appear as URL parameters on the
> generated page.

---

## 🎨 Activity 1: Style Lab

**Time estimate:** 3-5 minutes

### Your Mission

Publish and style this online Markdown file YOUR way:

[https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md](https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md) ↗
<br><button type="button" style="height: 1.8rem; padding: 0 12px; box-sizing: border-box; border: 1px solid #999; border-radius: 8px; background: #f8f8f8; color: #333;" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

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

Feel free to post your Docsify-This URL in the session chat and describe your
design choice!

---

## ⚡ Level Up Tip: URL Parameters

### Skip the Clicks

Instead of using the Web Page Builder every time, you can also **edit URL
parameters directly** when viewing a published page!

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
1. Return to the styled Docsify-This page you created in Activity 1
2. Look at the URL in your browser's address bar
3. Find a parameter to change (like `sidebar=false`) or add a new one (like
   `&font-size=20px`)
4. Edit it directly in the URL
5. Hit the **Enter** key to reload the page and see the change!

> [!NOTE]
> Parameters with default values (like `font-size=18px`) don't appear in the
> URL unless you change them. To adjust a default, just add it with
> `&parameter=value`!

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

**What we've covered so far:**
- ✅ Basic Docsify-This publishing
- ✅ Styling options and Web Page Builder
- ✅ URL parameter shortcuts

**Coming up:** Docsify-This and the 5 Rs of OER!

---

## 🔄 Activity 2: Docsify-This and the 5 Rs of OER

**Time estimate:** 3-5 minutes

### Your Mission

Explore how Docsify-This features map directly to the 5 Rs of OER:

| 5 R | How Docsify-This Supports It |
|-----|------------------------------|
| **Retain** | Content stays in your original location — GitHub, Codeberg, or any public server |
| **Reuse** | Any public Markdown URL can be instantly published as a web page |
| **Revise** | Optional "Edit this Page" links enable direct content editing |
| **Remix** | Template repositories provide ready-to-customize starting points |
| **Redistribute** | Share any Docsify-This URL instantly; page copy button lets visitors grab source Markdown |

### Try It: Page Copy Button

Visit this example page and look for the copy button in the top right corner:

[One-Page Article with page copy button enabled](https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&page-copy-button=true) ↗

The **page copy button** gives visitors one-click access to the source Markdown
— putting Reuse and Remix directly in their hands. Tap this button and try the
various options!

### Share Your Thoughts

How might the **page copy button** — or any of the 5 Rs features — open new
possibilities for your own open education work? Feel free to share in the
session chat!

---

## 🎉 Session Wrap-up

**What we've done today:**
- Published your first Docsify-This page
- Explored styling options and URL parameters
- Connected Docsify-This features to the 5 Rs of OER
- Got resources for continued learning

**Keep the momentum going** with the "Continue After the Session" challenges!

---

## 🎯 Next Steps + Common Questions

**Before You Leave**

- [ ] Bookmark this guide!
- [ ] Save your Activity 1 URL

**After Today's Session**

- [ ] Consider trying the [Style Detective Challenge](#-on-your-own-challenge-style-detective)
- [ ] Try a ready-made [Markdown template](#some-of-the-ready-to-use-templates)
- [ ] Share a Docsify-This page URL

### Real-World Examples

Docsify-This in action across disciplines and institutions:

- **[OpenLab Project Documentation](https://docsify-this.net?basePath=https://raw.githubusercontent.com/davidmalawey/openLab/main&homepage=home.md&edit-link=https://github.com/davidmalawey/openLab/blob/main&sidebar=true&browser-tab-title=OpenLab_Project&edit-link-top=true&hide-credits=true&loadFavicon=favicon.png&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&name=OpenLab_Project&searchbox=true&page-title=OpenLab&mergeNavbar=true&zoom-images=true&dark-mode=true)** ↗ — Robotics prototyping lab at Texas A&M University
- **[Digital Literacy Course](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/harlows/TERTL509/main/modules/introduction&homepage=overview.md&browser-tab-title=TERTL509&hide-credits=true&sidebar=true&loadSidebar=_sidebar.md&subMaxLevel=3&loadFooter=_footer.md)** ↗ — Open university course adapting Ontario Extend OER content
- **[Ethics & Management Issues in Information Systems](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/Parsa-Rajabi/CIS-485/main/docs&homepage=home.md&sidebar=true&font-family=Lato%20Extended,Lato,Helvetica%20Neue,Helvetica,Arial,sans-serif&font-size=16px&loadSidebar=_sidebar.md&name=CIS%20485&loadFavicon=assets/favicon/favicon-ufv.ico&dark-mode=auto)** ↗ — Docsify Open Course Starter Kit at the University of the Fraser Valley

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
A: Yes! Advanced URL parameters are available, and in addition to supported
Markdown CSS classes custom CSS is also possible. Still not enough? Host your
own instance!

---

## Continue After the Session

---

## 🔍 On Your Own Challenge: Style Detective

**Time estimate:** 5-10 minutes

### Your Mission

**Decode this Docsify-This URL!** Examine the Docsify-This page URL posted in
the session chat and figure out what styling choices were made by analyzing the
URL parameters.

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

Try to recreate the same styling using the Web Page Builder instead of URL
parameters!

### Need Help?

Refer back to the [URL Parameters reference](#-level-up-tip-url-parameters).

### Share Your Findings

Feel free to post your decoded styling list in the session chat and share if any
parameters were unexpected or gave you ideas for your own styling!

### Reveal the Answer

**Ready to see how you did?** Compare your findings below!

<details>
<summary>Show answer to URL analysis</summary>

  - Page layout: Sidebar
  - Font family: Merriweather
  - Font size: 16 pixels
  - Link color: cc0000 (red)
  - Headers weight: 600 (semi bold)
  - Max width: 65 characters
  - Dark mode: Auto

</details>

---

## 📄 On Your Own Challenge: Create & Publish Online Files

**Difficulty:** ⭐ Intermediate

**Time estimate:** 10-15 minutes

### Your Mission

**Ready to go further?** Create and host your own Markdown file, then publish
and style it with Docsify-This!

### GitHub or Codeberg

> [!NOTE]
> Codeberg Pages may experience loading delays due to infrastructure updates.
> GitHub is recommended for best performance.

#### Step 1: Create a New Repository

1. **Log in** or **Sign up** to [GitHub](https://github.com) ↗ or
   [Codeberg](https://codeberg.org) ↗
2. **Create a new repository**:
   - Tap the **+** icon and select **New Repository**
   - Fill in the repository details:
     - Choose a **Repository Name** for your repository (e.g.,
       `docsify-this-demo`)
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

> [!WARNING]
> If your GitHub URL doesn't work with Docsify-This, make sure:
> - Repository is public
> - You're copying the file view URL (not raw URL)
> - File has `.md` extension

### What's Next?

Congratulations, you've now published your own Markdown content with
Docsify-This!

> [!TIP]
> You can also upload existing Markdown files by using **Add File › Upload
> files** in your repository, or use an app such as **[GitHub
> Desktop](https://github.com/apps/desktop)** ↗ to quickly synchronize files
> between your desktop and a GitHub or Codeberg repository.

---

## 🔄 On Your Own Challenge: Desktop Sync Workflow

**Difficulty:** ⭐⭐ Intermediate+

**Time estimate:** 10-15 minutes

### Your Mission

**Want to edit with your favorite desktop editor?**
Clone your repository with GitHub Desktop, make local edits, and sync changes
back to see them appear instantly in your Docsify-This page!

### What You'll Need
- Your repository from the Create & Publish challenge
- [GitHub Desktop](https://desktop.github.com) ↗ (free download)

### The Desktop Workflow

**Step 1: Get GitHub Desktop**
1. **Download and install** GitHub Desktop
2. **Sign in** with your GitHub account

**Step 2: Clone Your Repository**
1. **Go to your repository** on GitHub.com
2. **Tap the green <> Code button**
3. **Choose "Open with GitHub Desktop"**
4. **Select a local folder** and tap **Clone**

**Step 3: Edit Locally**
1. **Browse** to the downloaded folder
2. **Open your Markdown file** in any text editor you like
3. **Make a change** - add content, fix a typo, whatever you want!
4. **Save** the file

**Step 4: Sync Back to GitHub**
1. **Return to GitHub Desktop** - your changes appear automatically
2. **Add a summary** in the commit message if you want (e.g., "Added new
   content")
3. **Tap "Commit to main"**
4. **Tap "Push origin"** to sync changes back

**Step 5: See the Magic**
1. **Wait 5-10 seconds** for sync
2. **Refresh your Docsify-This page** - your edits appear instantly!

> [!TIP]
> Now you can use VS Code, Typora, or any desktop editor while keeping the
> publishing power of Docsify-This! Perfect for larger editing sessions or when
> working offline.

### Challenge Review
- [ ] Downloaded and set up GitHub Desktop
- [ ] Cloned repository to your computer
- [ ] Made local edits and synced changes
- [ ] Verified updates appear in your Docsify-This page

**Congratulations - you're now using an optimized Markdown publishing
workflow!** 🚀

---

## 🚀 On Your Own Challenge: Template Jumpstart

**Difficulty:** ⭐⭐ Intermediate+

**Time estimate:** 10-20 minutes

### Your Mission

**Skip the setup, start with style!** Use a Docsify-This Markdown template as
your foundation, customize it with your own content, and publish a polished page
in minutes.

### What You'll Need
- A GitHub account (free)
- Your choice of template goal (article, course, or project site)

### Choose Your Template Adventure

Pick an example template to try out below (more available at
[Docsify-This.net](https://docsify-this.net/#/?id=ready-to-use-docsify-this-markdown-templates)
↗):

**📰 Article**
- Template: [One-Page Article](https://github.com/hibbitts-design/docsify-this-one-page-article) ↗
- Great for: Blog posts, tutorials, documentation pages
- Features: Clean layout, responsive design

**🎓 Course Site**
- Template: [Multiple Page Course Site Template](https://github.com/hibbitts-design/docsify-this-multiple-page-course-site) ↗
- Great for: Lessons, training materials, educational content
- Features: Learning modules, resource pages

**🌐 Project Documentation Site**
- Template: [Multiple Page Open Publishing Site Template](https://github.com/hibbitts-design/docsify-this-multiple-page-open-publishing-site) ↗
- Great for: Project sites, portfolios, small websites
- Features: Custom Sidebar, custom Navbar, multiple linked pages

> [!TIP]
> **Template Exploration:** Each template repository includes example content
> and a README with specific instructions. Don't skip reading these - they
> contain valuable customization tips!

### The Template Workflow

**Step 1: Choose Your Template**
1. **Visit your chosen template** repository (links above)
2. **Tap the green "Use this template"** button (upper-right)
3. **Choose "Create a new repository"**
4. **Name your repository** (e.g., `my-docsify-this-course`) and tap **Create
   repository**

**Step 2: Explore the Structure**
1. **Browse the files** in your new repository
2. **Look for `home.md`** - this is usually the main content or home page file
3. **Check other `.md` files** - notice how they're named and organized
4. **Peek at any example content** to understand the template's style

**Step 3: Test Drive the Template**
1. **Click on `home.md`** in your repository to view the file
2. **Copy the URL** from your browser's address bar
3. **Go to [Docsify-This.net](https://docsify-this.net ':target=_blank')** ↗
4. **Paste the URL and publish** to see your template in action!

> [!TIP]
> **Multi-Page Setup:** If you chose a multiple page template, choose the
> Sidebar for page layout and set the option to load a custom Docsify sidebar in
> the **Advanced Web Page Builder Options** section. Edit the sidebar file
> (`_sidebar.md`) to remove or add new navigation links to additional pages you
> create.

<button type="button" aria-label="Preload Web Page Builder to use a custom Sidebar" style="height: 1.8rem; padding: 0 12px; box-sizing: border-box; border: 1px solid #999; border-radius: 8px; background: #f8f8f8; color: #333;" onclick="window.open('https://docsify-this.net/?advanced=true&url-field=https://github.com/hibbitts-design/docsify-this-multiple-page-open-publishing-site/blob/main/home.md&sidebar=true&loadSidebar=true', '_blank')">Preload Web Page Builder to use custom Sidebar</button>

_Pre-loads the Docsify-This Web Page Builder with Sidebar layout and custom
navigation (using the open publishing site template `home.md` file as the
default Markdown file URL)._

**Step 4: Make It Yours**
1. **Return to GitHub** and edit `home.md` (tap the pencil icon)
2. **Replace the example content** with your own:
   - Change the title
   - Update the introduction
   - Add your own sections
   - Include your images/links
3. **Commit your changes**

**Step 5: Republish and Style**
1. **Refresh your Docsify-This page** to see your changes
2. **Experiment with styling** using the Web Page Builder or URL parameters
3. **Try different layouts** - some templates work great with sidebars!

### Need Help?

**Template not working as expected?**
- Make sure your repository is public
- Check that you're copying the `home.md` URL correctly
- Try refreshing the Docsify-This page after making edits

**Want to see a template in action first?**
- Visit the template's live demo (links in each repository's README)
- Study the example content structure before customizing

### Template Customization Ideas

**Content Edits:**
```
☐ Replace placeholder text with your content
☐ Update headings to match your topic
☐ Add your own images (upload to /images folder)
☐ Customize visual styles using the Web Page Builder or URL parameters
```

**Structure Modifications:**
```
☐ Add new .md pages by copying existing ones
☐ Reorder page content to fit your purposes
☐ Remove .md pages you don't need
☐ Update the list of site pages in the Sidebar
```

### Challenge Review
- [ ] Successfully created a repository from a template
- [ ] Customized content with your own text and structure
- [ ] Published the template and applied custom styling
- [ ] Understand how to modify and expand the template

**Congratulations!** You've just accelerated your publishing workflow using
pre-designed templates. No more starting from scratch!

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

**To use:** Click "Use this template" › Create repo › Edit › Copy `home.md` URL
› Paste URL › Publish!

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

**Session:** From Markdown to Open Web: Hacking the Publishing Barrier with Docsify-This
**Presenter:** [Paul Hibbitts](https://www.hibbittsdesign.org/)
**License:** <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

---

**Remember:** Your content, your control, zero hassle. 🚀
