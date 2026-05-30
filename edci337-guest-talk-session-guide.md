# Interactivity & Web Design

<h2> An Interaction Design Framework Through a Real-World Example </h2>

**Follow along • Try it out • Take it with you**

---

**Docsify-This** is an open-source web app that instantly turns online Markdown text files into styled web pages – no installation, no build process, just paste a URL and go!

In this session, you'll see how interaction design decisions can lower the friction of a real-world open publishing project, and how the same framework applies to almost any tool or learning experience you design.

**By the end of this session, you'll be able to:**
- Identify where friction lives in a digital tool using the Big / Small Design framework
- Recognize how specific interaction design decisions lower barriers for users
- Experience firsthand how interaction design decisions shaped a publishing tool

> [!NOTE]
> Links with ↗ will automatically open in a new browser tab so this guide stays available as you follow along.

## 📍 Session Outline

| What We're Covering | Focus |
|---------------------|-------|
| 📝 Markdown Basics | The promise – and the friction |
| 🔍 Big Design, Small Design | An Interaction Design (IxD) framework |
| ▶️ Docsify-This | Design decisions in action |
| ⚡ Try It Yourself | One URL, one page, right now |
| 🎯 Resources to Go | What to carry forward |

---

## 📝 Markdown Basics

Markdown is a lightweight way to format plain text – readable as-is, renderable anywhere. Here's an [example Markdown source file](https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main/home.md ':target=_blank') ↗ to follow along with.

| You Would Type | You Would Get |
|----------------|---------------|
| `# Heading 1` | Large heading |
| `## Heading 2` | Medium heading |
| `**bold text**` | **bold text** |
| `*italic text*` | *italic text* |
| `[link text](URL)` | Clickable link |
| `- Item` | • Bulleted list |

**The friction problem:** Writing Markdown is quite learnable, but *publishing* it has traditionally required a web server, a build process, or developer-type skills. That's a barrier most educators can't cross on their own.

To publish with Docsify-This, you'll need your Markdown file stored somewhere online – a GitHub or Codeberg repository is the most common choice, though a GitHub Gist or any web-accessible location works too. **Once it's there, Docsify-This does the rest.**

> *"Platforms come and go. Markdown files don't."*

---

## 🔍 Big Design, Small Design

A practical interaction design (IxD) framework for locating *where* an interaction design problem lives, and whose job it is to fix it.

[Docsify-This](https://docsify-this.net?hide-banner=true ':target=_blank') ↗ is the example here, but the questions this framework asks apply to any tool, platform, or learning environment.

### Big Design – The Strategic Problem

The barriers that live above and beyond the user interface.

**Ask:** Who may face headwinds or is left out, and why? What structural decisions – workflows, platforms, portability – create friction before anyone even starts using the tool?

**Docsify-This example:**  
Traditional publishing workflows store content within the platform: configure → write → format → publish → maintain. That structure confines content and creates "walled gardens." Docsify-This changes the structure: your files stay where you originally store them (e.g. GitHub), Docsify-This provides the lens.

This is a common open-source challenge — Big Design often gets far less attention than the interface itself, leaving less tech-savvy users behind. Docsify-This was designed with that gap in mind.

Accessibility was baked into that structure from the start: semantic HTML, keyboard navigable, low visual noise. That means an author focused on their content automatically gets an accessible result.

### Small Design – The UX Layer

The experience of actually using the tool: first-use flow, key tasks, progressive disclosure, and microcopy.

**Ask:** Does the default experience make sense immediately? Are power features accessible without cluttering the simple path for everyone else?

**Docsify-This example:**  
Docsify-This uses progressive disclosure — the Web Page Builder shows the essentials first, with URL parameters available for those who want to go further. Customize via the builder, or directly via URL parameters like `&toc=true` and `&font-size=36px` — styling the page without ever touching the content itself. URL parameters work wherever the URL is used, even when embedding pages in other platforms.

> *"Every configuration option is a decision the system has transferred to the user."*

And then there's Micro Design – the details so small they barely register, until they're missing. The URL input field is automatically selected the moment you land on the page. One detail. One less click. One less small frustration, multiplied across every person who has ever used the tool.

---

> [!TIP]
> Next time you feel friction using *any* tool: ask which level it belongs to.
> - **Big Design** – people face barriers before they even begin
> - **Small Design** – people struggle to achieve their goals
> - **Micro Design** – people get caught on small details

---

## ⏸️ Brief Pause

**Questions or observations before we continue?**

**What we've covered so far:**
- ✅ Markdown basics and the publishing friction problem
- ✅ Big / Small Design as an IxD framework

**Coming up:** Design Decisions in Action!

---

## ▶️ Docsify-This: Design Decisions in Action

Each of these principles maps directly to the framework – as you read through, consider which level each one belongs to.

### Core Design Principles

| Principle | What It Means in Practice |
|-----------|--------------------------|
| **Zero Setup and Maintenance Publishing** | No build process, no web server, no dedicated publishing account required |
| **Separation of Content and Presentation** | Same Markdown file, different styles for different contexts |
| **Platform Independence and Choice** | Not locked into any one hosting service or workflow |
| **Your Content, Your Control** | Files stay in GitHub – Docsify-This reads them dynamically |
| **Support the 5 Rs of OER** | Content stays open, portable, and reusable by others (Retain, Reuse, Revise, Remix, Redistribute) |
| **Authors Helping Other Authors** | URL parameters can be pre-configured and shared with others |

> [!NOTE]
> Notice that all six principles are Big Design decisions – Docsify-This was shaped primarily by structural choices that make publishing more accessible to more people.

### The Core Feedback Loop

Change a URL parameter → see the result immediately. That's the core IxD feedback loop, shortened to a single URL edit.

**Try it:** Open both links and compare — they point to the same page, one URL parameter apart:

- [Default font size](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&hide-banner=true ':target=_blank') ↗
- [With `&font-size=28px` added](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&hide-banner=true&font-size=28px ':target=_blank') ↗

One URL edit. One immediate response. That's the feedback loop.

---

## ⚡ Try It Yourself

**One URL. One page. Right now.**

> [!NOTE]
> No account needed. Nothing to install. Works in any browser.

### The 3-Step Process

**1. Open the Docsify-This Web Page Builder**

- [Open Docsify-This.net](https://docsify-this.net?hide-banner=true ':target=_blank') ↗

Notice the URL field is already selected and waiting. (A small but deliberate detail.)

**2. Paste this Markdown file URL**

- [github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md](https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md ':target=_blank') ↗ <br><button type="button" style="height: 1.8rem; padding: 0 12px; box-sizing: border-box; border: 1px solid #999; border-radius: 8px; background: #f8f8f8; color: #333;" aria-label="Copy Markdown file URL" onclick="event.stopPropagation(); event.preventDefault(); navigator.clipboard.writeText('https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md').then(()=>{const b=this;const orig=b.textContent;b.textContent='Copied!';setTimeout(()=>b.textContent=orig,1500)})">Copy URL</button>

**3. Press "Publish as a Web Page"**

Watch a Markdown file become a styled web page in seconds. That's the moment of delight – and it's intentional.

> [!NOTE]
> This activity uses a pre-hosted file — publishing your own content requires a place to store it online, such as GitHub or Codeberg.

> [!TIP]
> After publishing, look at the URL in your browser's address bar. Notice how your Web Page Builder choices appear as URL parameters on the generated page. That's Small Design – your choices, made visible and shareable.

---

## 💡 The Key Takeaway

Every design decision you saw today – big, small, or micro – started with a scenario-based question: who is trying to do what, and what friction stands between them and their goal?

That question doesn't change whether you're building a publishing tool, designing a course, or choosing which platform your students will use. The framework travels.

> *"Experience design is ultimately a way to show people that you care. That applies to tools, to documentation, and to the learning environments you'll design as educators."*
> – Paul Hibbitts, HibbittsDesign.org

---

## 🎉 Session Wrap-up

**What we've done today:**

- ✅ Markdown basics and the publishing friction problem
- ✅ Big / Small Design as an IxD framework
- ✅ Docsify-This design decisions and feedback loop
- ✅ Publishing your first page and adjusting URL parameters

**Before you leave:**
- [ ] Bookmark this guide
- [ ] Save the Docsify-This URL you created

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
| **Self-directed guide** (20 min) | [leap.docsify-this.net](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/published-markdown-files/main&homepage=leap-into-open-publishing-standalone-guide.md&sidebar=true&maxLevel=2&font-family=Open%20Sans,sans-serif&header-weight=600&dark-mode=auto ':target=_blank') ↗ |
| **Full documentation** | [readme.docsify-this.net](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this/main&homepage=README.md&sidebar=true&searchbox=true&dark-mode=auto ':target=_blank') ↗ |
| **Video demos** (30–45 sec each) | [YouTube playlist](https://www.youtube.com/playlist?list=PLk2Bz5X36nXArvm20GbOdjAIornJbWmhe ':target=_blank') ↗ |

### All About Markdown

- [Markdown Guide](https://www.markdownguide.org ':target=_blank') ↗
- [Improving the Accessibility of Your Markdown](https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown/ ':target=_blank') ↗

### Further Reading

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
