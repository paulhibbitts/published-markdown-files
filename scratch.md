# Docsify-This Session Guide
## "Leap into Open Publishing with Docsify-This!"

**Follow along during the session • Take notes • Try the challenges**

---

## 📍 Session Roadmap (30 Minutes)

| Time | What We're Doing | Your Action |
|------|------------------|-------------|
| **0-3 min** | Intro & Hook | Watch the magic! |
| **3-8 min** | Web Page Builder Demo | Take notes on workflow |
| **8-15 min** | **🎨 Style Challenge** | **CREATE your page!** |
| **15-18 min** | Power Tip: URL Parameters | Learn the shortcut |
| **18-23 min** | **🔍 Scavenger Hunt** | **MATCH the design!** |
| **23-26 min** | Templates & Resources | Grab links to save |
| **26-30 min** | Q&A & Next Steps | Ask questions! |

---

## 🚀 Quick Start (Before Challenge 1)

### The 3-Step Process

**1. Get Your Markdown URL**
- GitHub: View file → Click "Raw" → Copy URL
- Or use the example provided in Discord

**2. Visit the Web Page Builder**
```
https://docsify-this.net
```

**3. Paste → Style → Publish!**
- Paste Markdown URL
- Choose page layout (Content Only / ToC / Sidebar)
- Click "Publish as a Web Page"
- Copy your new URL to share!

---

## 🎨 Challenge 1: Style Challenge (8-15 min)

### Your Mission
Transform this Markdown file YOUR way:
```
https://raw.githubusercontent.com/hibbitts-design/
docsify-this-one-page-article/main/home.md
```

### Try These Styles

**Presentation Mode**
```
☐ Large font (32-36px)
☐ Dark mode: On
☐ Max width: 80%
☐ Sidebar: Closed
```

**LMS Embedding**
```
☐ Font: Match your LMS
☐ Size: 16-18px
☐ Hide credits: Yes
☐ Max width: 100%
```

**Professional Document**
```
☐ Serif font (Merriweather)
☐ Table of Contents: Yes
☐ Edit link: Yes
☐ Clean, readable
```

**Your Brand**
```
☐ Your fonts: _____________
☐ Your colors: _____________
☐ Your layout: _____________
```

### Share Your Result!
Post your Docsify-This URL in Discord and describe your design choice!

**My Challenge 1 URL:**
```



```

---

## ⚡ Power Tip: URL Parameters (15-18 min)

### The Secret Shortcut
Instead of using the Web Page Builder every time, **edit URL parameters directly**!

### Example URL Breakdown
```
https://docsify-this.net?basePath=...
&homepage=home.md
&font-size=18px          ← Change this!
&dark-mode=auto          ← Or this!
&link-color=0374B5       ← Or this!
```

### Common Parameters to Remember

| Parameter | Options | Example |
|-----------|---------|---------|
| `font-size` | 10-72px | `&font-size=24px` |
| `font-family` | Font name | `&font-family=Open%20Sans` |
| `dark-mode` | false/auto/on | `&dark-mode=auto` |
| `link-color` | Hex (no #) | `&link-color=CC0000` |
| `max-width` | px or % | `&max-width=800px` |
| `sidebar` | true/false | `&sidebar=true` |
| `toc` | true/false | `&toc=true` |

### Why This Matters
✅ **Batch-style** multiple pages  
✅ **Share recipes** as plain text  
✅ **Troubleshoot** remotely  
✅ **Create presets** for reuse  

**My notes on parameters:**
```



```

---

## 🔍 Challenge 2: Parameter Scavenger Hunt (18-23 min)

### Your Mission
**Match the target design!** Look at the screenshot posted in Discord.

### Starting Point (Unstyled)
```
https://docsify-this.net?basePath=
https://raw.githubusercontent.com/hibbitts-design/
docsify-this-one-page-article/main&homepage=home.md
```

### Target Specs (Check Discord for screenshot!)
```
☐ Layout: Sidebar navigation
☐ Font: Clean sans-serif
☐ Size: Reading-friendly (~18px)
☐ Headers: Semi-bold (600)
☐ Theme: Auto dark/light
☐ Links: Subtle blue
☐ Width: Focused (not full-width)
```

### Parameters to Find (6-7 total)
```
☐ sidebar=?
☐ font-family=?
☐ font-size=?
☐ header-weight=?
☐ dark-mode=?
☐ link-color=?
☐ max-width=?
```

### Hints Along the Way
Watch Discord for progressive hints if you get stuck!

**My Challenge 2 URL:**
```



```

---

## 📚 Templates & Resources (23-26 min)

### Ready-to-Use Templates
**Don't start from scratch!** Use these GitHub templates:

```
☐ docsify-this-one-page-article
   → Single article/document

☐ docsify-this-one-page-course
   → Course module page

☐ docsify-this-multiple-page-site
   → Multi-page website

☐ docsify-this-lms-content-pages
   → LMS-ready content pages

☐ docsify-this-visual-portfolio
   → Portfolio/showcase site
```

**To use:** Click "Use this template" → Create repo → Edit → Publish!

### Load-and-Go Presets
Pre-configured styling for common needs:

```
☐ Presentations: present.docsify-this.net
☐ Canvas LMS: canvas.docsify-this.net
☐ Moodle LMS: moodle.docsify-this.net
☐ Brightspace: brightspace.docsify-this.net
☐ Sakai LMS: sakai.docsify-this.net
```

Just paste your Markdown URL and go!

---

## 🔗 Essential Links (BOOKMARK THESE!)

| Resource | URL |
|----------|-----|
| **Web Page Builder** | docsify-this.net |
| **Full Documentation** | docsify-this.net (scroll down) |
| **Templates** | github.com/hibbitts-design/ |
| **Discord Community** | discord.gg/docsify |
| **GitHub Repository** | github.com/hibbitts-design/docsify-this |

**Resources to check in Discord after session:**
```
☐ Challenge results gallery
☐ Scavenger hunt solution
☐ Template starter links
☐ Advanced customization guides
```

---

## 💡 Quick Reference

### Page Layout Options
- **Content Only** — Simple, clean page
- **Table of Contents** — Side navigation
- **Docsify Sidebar** — Collapsible nav (best for multi-page)

### Essential Styling Tips
```
For Presentations:
✓ Font: 36px, sans-serif
✓ Dark mode: On
✓ Width: 80% or 55ch

For LMS Embedding:
✓ Match platform font
✓ Hide credits
✓ Full width (100%)
✓ Adjust link colors

For Documentation:
✓ Serif font
✓ Table of Contents
✓ "Edit this Page" link
✓ Comfortable line height
```

### Embedding Code
```html
<iframe src="YOUR-DOCSIFY-THIS-URL" 
  width="100%" 
  height="800px" 
  style="border:none;">
</iframe>
```

---

## 🎯 Your Next Steps

### Before You Leave
```
☐ Save both your challenge URLs
☐ Bookmark docsify-this.net
☐ Join Discord #Docsify-This channel
☐ Try embedding in your platform
```

### This Week
```
☐ Publish your own Markdown file
☐ Try a ready-made template
☐ Share with a colleague
☐ Embed in your LMS or website
```

### This Month
```
☐ Create a multi-page site
☐ Develop your preset configs
☐ Help someone else get started
☐ Explore advanced customization
```

---

## ❓ Quick Q&A Reference

**Q: Do I need to install anything?**  
A: No! 100% web-based. Just paste and go.

**Q: Where is my content stored?**  
A: On YOUR GitHub/server. You keep full control.

**Q: Can I use private repos?**  
A: Yes! Enable GitHub Pages, then use that URL.

**Q: Will Google index my pages?**  
A: No (client-side rendering). Perfect for LMS content!

**Q: Is there a cost?**  
A: Free and open source forever!

**Q: Can I customize more?**  
A: Yes! Host your own instance or use advanced URL parameters.

---

## 📝 My Session Notes

**Key insights:**
```




```

**Ideas to try:**
```




```

**Questions to explore:**
```




```

**URLs to remember:**
```




```

---

## 🌟 Post-Session

### Get Help & Stay Connected
```
Discord: discord.gg/docsify → #Docsify-This
GitHub: github.com/hibbitts-design/docsify-this
Tag your work: #DocsifyThisWorks
```

### Share Your Success!
Post your Docsify-This projects in Discord — we celebrate wins! 🎉

---

**Session:** "Leap into Open Publishing with Docsify-This!"  
**Presenter:** Paul Hibbitts  
**Resources:** docsify-this.net | discord.gg/docsify

---

**Remember:** Your content, your control, zero hassle. 🚀
