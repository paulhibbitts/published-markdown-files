# Big Design, Small Design

## How Design Decisions Can Impact Friction — A&nbsp;Docsify-This Case Study <!-- {docsify-ignore} -->

**Follow along • Try it out • Apply it later**

---

**Docsify-This** is an open-source web app that instantly turns online 
Markdown files into styled web pages.

No web server. No installation. No build process.

> *"I'm blown away just by the fact you put a URL into Docsify-This and 
> then you get a URL back for a web page… done!"*
>
> – J. Groom, Co-founder, Reclaim Hosting

## 📍 Session Outline

| What We're Covering | What You'll Take Away |
|---------------------|-----------------------|
| 📝 Markdown Overview | Why publishing – not writing — is the real barrier |
| 🔍 Big Design, Small Design | A framework for identifying friction at any design level |
| ▶️ Docsify-This | How structural decisions lower barriers for real users |
| ⚡ See It in Action | Hands-on: publish a page in under a minute |
| 🎯 Resources to Go | What to bookmark and try after the session |

> [!TIP]
> This guide works best alongside a browser tab showing live examples – links with ↗ open automatically in a new tab for this purpose.

## 📝 Markdown Overview

Markdown is a lightweight way to format plain text – readable as-is, renderable anywhere. Here's an [example Markdown source file](https://raw.githubusercontent.com/paulhibbitts/demo-markdown-file/refs/heads/main/README.md ':target=_blank') ↗ to explore.

### Basic Markdown Syntax

| You Type | You Get |
|----------------|---------------|
| `# Heading 1` | Large heading |
| `## Heading 2` | Medium heading |
| `**bold text**` | **bold text** |
| `*italic text*` | *italic text* |
| `[link text](URL)` | Clickable link |
| `- Item` | • Bulleted list |

### The Friction Problem

Writing Markdown is quite learnable, but *publishing* it has traditionally required a web server, a build process, or developer-type skills. That's a barrier many educators and open publishers can't cross on their own.

### Publishing with Docsify-This
- A Markdown file stored online (GitHub, Codeberg, Gist, or any web-accessible URL)
- That's it – Docsify-This reads it dynamically and does the rest

> *"Keeping all my course notes as plain text files and deploying them through GitHub and Docsify-This is easy and makes my course development a breeze. Plus, I keep all my materials locally, and can reuse them without being reliant on Canvas."*
>
> – J. Maxwell, Director & Associate Professor, Publishing Program, Simon Fraser University

## 🔍 Big Design, Small Design

A practical interaction design (IxD) framework to consider where a design problem lives, and what design level addresses it.  

Friction is one lens – but Big and Small Design also encompass opportunities and the conditions that support people in reaching their goals.

[Docsify-This](https://docsify-this.net?hide-banner=true ':target=_blank') ↗ is the example here, but the questions this framework asks apply to almost any tool, platform, or learning environment.

### Big Design

The experience around and beyond the interface.

**Ask:**  

❓ Who may face headwinds, be left out, or drop off – and why?  
❓ What structural decisions – workflows, platforms, portability – create friction before anyone starts?

**Key structural choices in Docsify-This:**
- Your files stay where you store them; Docsify-This reads dynamically
- Removes publishing and maintenance friction, not the initial upload step
- Accessibility built into the structure: semantic HTML, keyboard navigable, low visual noise

<details>
<summary>Further details about Big Design</summary>

Big Design asks us to think about outcomes over outputs – not just "did the tool publish the page?" but "did the intended audience get to publish at all?"

**Docsify-This example:**  
Traditional publishing workflows store content within the platform... Docsify-This changes the structure: your files stay where you originally store them. It doesn't eliminate every barrier before you start. Getting your file onto GitHub or Codeberg is still a step. But it removes the publishing and maintenance friction that traditionally follows.

This is a common open-source challenge – Big Design often gets far less attention than the interface itself, leaving less tech-savvy users behind. Docsify-This was designed with the publishing gap in mind.

Accessibility was baked into that structure from the start: semantic HTML, keyboard navigable, low visual noise. That means an author focused on their content automatically gets an accessible result.

</details>

### Small Design

The experience within the interface.

**Ask:**  

❓ Is the experience clear and purposeful at every interaction?  

❓ Are power features accessible without cluttering the simple path for everyone else?  

**Key interface choices in Docsify-This:**
- Progressive disclosure: essentials first, deeper options when wanted
- "Show More Page Appearance Options »" reveals advanced controls only when needed
- Pre-filled, pre-selected URL field: one less click, one less frustration

<details>
<summary>Further details about Small Design</summary>

**Docsify-This example:**  
Docsify-This uses progressive disclosure – the Web Page Builder shows the essentials first, with more options available for those who want to go further. [Open Docsify-This.net](https://docsify-this.net?hide-banner=true ':target=_blank') ↗ to see this in action. Key options like page layout and an "Edit this Page" link for GitHub or Codeberg files are immediately available – all changing how the page appears without touching the content itself.

In addition, the **"Show More Page Appearance Options »"** link reveals additional options only when needed.

And then there's Micro Design – the details that seem small but do a lot of work.

Docsify-This shows two Micro Design details working together: the URL input field arrives pre-filled with a demo URL and already selected – tap once to see the tool work, or paste your own URL to replace it instantly.

One detail at a time. One less click. One less small frustration, multiplied across every person who has ever used the tool.

</details>

---

## 🎯 Using the Framework

Next time you encounter friction using *any* tool: assess which level it belongs to.

🔎 **Big Design** – people face barriers before they even begin  
🔎 **Small Design** – people struggle to achieve their goals  
🔎 **Micro Design** – people stumble on the small details

---

## ⏸️ Brief Pause

**What we've covered so far:**  
✅ Markdown overview and the publishing friction problem  
✅ Big / Small Design as an IxD framework  

**Coming up:** Core Design Principles of Docsify-This!

---

## ▶️ Docsify-This: Design Decisions in Action

These core design principles guided the development of Docsify-This. As you read through, notice how each one reflects a structural choice.

### Core Design Principles

| Principle | What It Means in Practice |
|-----------|--------------------------|
| **Zero Setup and Maintenance Publishing** | No build process, no web server, no dedicated publishing account required |
| **Separation of Content and Presentation** | Same Markdown file, different styles for different contexts |
| **Platform Independence and Choice** | Not locked into any one hosting service or workflow |
| **Your Content, Your Control** | Files stay in GitHub – Docsify-This reads them dynamically |
| **Support the 5 Rs of OER** | Content stays open, portable, and reusable by others (Retain, Reuse, Revise, Remix, Redistribute) |
| **Authors Helping Other Authors** | URL parameters can be pre-configured and shared with others |

## ⚡ See It in Action

**One URL. One page. Right now.**

### The 3-Step Process

**1. Open the Docsify-This Web Page Builder**

- [Open Docsify-This.net](https://docsify-this.net?hide-banner=true ':target=_blank') ↗

Notice the URL field is already selected and waiting. (A small but deliberate detail.)

**2. Use this Markdown file URL**

- [github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md](https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md ':target=_blank') ↗ <br><button type="button" style="height: 1.8rem; padding: 0 12px; box-sizing: border-box; border: 1px solid #999; border-radius: 8px; background: #f8f8f8; color: #333;" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

**3. Press "Publish as a Web Page"**

A Markdown file becomes a styled web page in seconds. That's the moment of delight – and it's intentional.

> [!NOTE]
> This activity uses a pre-hosted file – when publishing your own content requires a place to store it online, such as GitHub or Codeberg.

### Go Further

**How to adjust a URL parameter:**
- Edit the URL directly in your browser's address bar
- Remove `#/`, if present, from the end of the URL
- Add your parameter with & or modify an existing one

Add one of these to the end of your published page URL and press Enter:

| Add to URL | What happens |
|------------|--------------|
| `&sidebar=true` | [Display Docsify sidebar](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true) |
| `&sidebar=true&maxLevel=3` | [Display Docsify sidebar with headings to level 3](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true&maxLevel=3) |
| `&font-size=28px` | [Text gets larger for presenting](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&font-size=28px) |
| `&dark-mode=on` | [Dark theme always on](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&dark-mode=on) |

## 💡 The Key Takeaway

Every design decision you saw today – big, small, or micro – started with a scenario-based question: who is trying to do what, and what friction stands between them and their goal?

That question doesn't change whether you're building a publishing tool, designing a course, or choosing which platform your students will use. The framework travels.

> *"Experience design is ultimately a way to show people that you care. That applies to tools, to documentation, and to the learning environments you'll design as educators."*

---

## 🎉 Session Wrap-up

**What we've done today:**

- ✅ Markdown overview and the publishing friction problem
- ✅ Big / Small Design as an IxD framework
- ✅ Docsify-This design decisions in action
- ✅ Docsify-This in action: publishing a page and adjusting URL parameters

**Before you leave:**
- [ ] Bookmark this guide
- [ ] Bookmark a Docsify-This example URL to revisit later

**After today's session:**
- [ ] Try the self-directed [Leap into Open Publishing guide](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/published-markdown-files/main&homepage=leap-into-open-publishing-standalone-guide.md&sidebar=true&maxLevel=2&font-family=Open%20Sans,sans-serif&header-weight=600&dark-mode=auto) ↗ – 20 minutes, hands-on, no setup
- [ ] Apply the Big / Small / Micro framework to a tool or experience you're designing or evaluating
- [ ] Next time you feel friction using a tool – identify which design level it belongs to

---

## 📚 Resources to Go

### Essential Docsify-This Links

| Resource | Link |
|----------|------|
| **Web Page Builder** | [docsify-this.net](https://docsify-this.net?hide-banner=true ':target=_blank') ↗ |
| **Project overview** | [hibbittsdesign.org](https://www.hibbittsdesign.org/Docsify-This-3330615470e0804faf45e3765f954c14 ':target=_blank') ↗ |
| **Self-directed guide** (20 min) | [leap.docsify-this.net](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/published-markdown-files/main&homepage=leap-into-open-publishing-standalone-guide.md&sidebar=true&maxLevel=2&font-family=Open%20Sans,sans-serif&header-weight=600&dark-mode=auto ':target=_blank') ↗ |
| **Full documentation** | [readme.docsify-this.net](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this/main&homepage=README.md&edit-link=https://github.com/hibbitts-design/docsify-this/blob/main/README.md&sidebar=true&searchbox=true&browser-tab-title=Docsify-This%20ReadMe&edit-link-text=Suggest%20an%20Edit%20on%20GitHub&maxLevel=4&header-weight=600&zoom-images=true&dark-mode=auto&code-copy=true&page-copy-button=true ':target=_blank') ↗ |
| **Video demos** (30–45 sec each) | [YouTube playlist](https://www.youtube.com/playlist?list=PLk2Bz5X36nXArvm20GbOdjAIornJbWmhe ':target=_blank') ↗ |

### Foundations & Frameworks

**All About Markdown**

- [Markdown Guide](https://www.markdownguide.org ':target=_blank') ↗
- [Improving the Accessibility of Your Markdown](https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown/ ':target=_blank') ↗

**Further Reading**

- [Thinking Big and Small](https://blog.prototypr.io/thinking-big-and-small-5b86530cb1d2 ':target=_blank') ↗
- [Design, in the Big and Small](https://www.jonkolko.com/writing/design-in-the-big-and-small ':target=_blank') ↗

**From the HibbittsDesign.org Blog:**
- [Big Design and Small Design](https://www.hibbittsdesign.org/Big-Design-and-Small-Design-13e0615470e080bfb61dc4a0067c5ba9 ':target=_blank') ↗
- [Docsify-This Core Design Principles](https://www.hibbittsdesign.org/Docsify-This-Core-Design-Principles-13e0615470e080e6bfe3e31832d2a13a ':target=_blank') ↗
- [What Documentation Is Really About: Showing Users You Care](https://www.hibbittsdesign.org/What-Documentation-Is-Really-About-Showing-Users-You-Care-Through-Design-3020615470e080d49600fef0374d0e47 ':target=_blank') ↗

---

**Session:** Interactivity and Web Design – EDCI 337, University of Victoria  
**Presenter:** Paul Hibbitts – [hibbittsdesign.org](https://www.hibbittsdesign.org)  
**Note:** Source material analysis and guide development assisted by [Claude](https://claude.ai) (Anthropic)  
**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width:1em;max-height:1em;margin-left:.2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width:1em;max-height:1em;margin-left:.2em;">

---

**Remember:** The Big and Small Design questions don't stop here – they apply to every tool, course, and experience you'll ever build. 🚀
