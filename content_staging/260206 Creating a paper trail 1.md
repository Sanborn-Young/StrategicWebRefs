


Today we are going to talk about implementing a system for taking notes with a pencil/pen and paper.  Now, there is a level of sophistication and planning that you will do, but it is a system that will work with minor effort if you organize and put in the effort up front.  And it has the advantage of being robust in terms of the capture.  There nothing like paper and pencil, which have no batteries and can't be destroyed, even if you run over your notebook with a car.

Here is an over of the process flow:

1. You take all notes on a bound notebook.  You may have used this in college or high school, potentially labeled as an "Composition" or "Engineering" notebook.  However, you need to keep a couple of hook in your notes, as we want to be able to digitize them later.
2. Once you have filled the notebook, you cut the pages out of the notebook.
3. You scan the papers with a high speed double sided scanner.
4. Save the file as PDF.
5. Then wait for 12-36 months because any commercial LLM will be able to process your notes into a nice extract, or you can do some vibe coding and use PP-OCRv5, a great model from Baidu.  However, you have to be somewhat technical, so I think most people should just wait.

Let's break down each step.

**Capture in a bounded composition or engineering notebook**

So, how do you keep notes, maybe growing up you had them in a loose leaf notebook or perhaps you had it in a spiral bound notebook? But by far the best way to capture these things is actually to have some sort of a composition or engineering notebook. These, in essence, look a lot like small books that you can write in and they either have lined or grabbed paper. The most important thing about these books is a fairly robust cover and thinness and lightness and being almost impossible to somehow lose a page or have the binding damaged and crunched because you happen to jam it someplace or step on it or sit on it in some ways. These books are highly robust and almost indestructible and really the number one way of capturing your notes.

And bought in book at Amazon they are dirt cheap. Really these are some of the modern miracles for capturing your notes.

Now, we are eventually going to digitize these notes.  So we want to have some hooks inside of our notes to make sure that after we digitize them we've left footprints of where we've been.





The whole notebook scene actually is a niche market where there are many upper end notebooks and you can go to YouTube and see a lot of real connoisseurs talk about different sizes and elastic bands and things like moleskin or moleskin derived notebooks. But at the end of the day, the simplest, most robust, and most commercially available is the simple bounded notebook.

2 Cut the pages out of the book using a commercial cutter

The single biggest problem with paper is that you can't search it, and so the goal of what we're going to do is make a system where that no longer will be a problem. So somehow you need to get that data out of that notebook and into a form that is electronic that you can search.

The first step is simply removing the pages. These notebooks classically are somewhere between 100 to 200 pages and so you could do things like try to take multiple cuts with an X-Acto knife or perhaps try to buy some sort of paper were cutter at the local store, but almost in all cases they choke on more than 20 to 30 pages.

I would suggest buying what is called a commercial paper guillotine. The one that I have is called SG 298 12-inch heavy-duty industrial guillotine paper cutter.  I've had it for a number of years and it will slice through two or three hundred pages of paper leaving a very clean edge. Truly an amazing device. Unfortunately it's not cheap but having a great cut on the pages will be important for the next step.

3 Scan the pages

If you have to scan any pages at all, having a scanner with an automatic document feed, especially any of the newer ones, is completely revolutionary. You can drop in 50 to 100 pages, and it scans through them amazingly quickly, and it does it both single side and double-sided. I have a Epson FastFoto FF-680W, which allows high speed scanning of both paper and my parents old photo collection.  

This will create a PDF of you notes.

Now most people will be done.

4 Carefully store the notebooks in a central site

I have suggested this before, but putting the date information into a file name ensures that you don't need to rely on metadata for understanding when the notes were created.  I suggest that you use a six letter to identify you files:

250101_250715_Notes.pdf would be from January 1st, 2025 to July 15, 2025.  







And there does seem to be what I would call non-cognitive benefits of paper and pen. For all the technology we have, generally it's just slower to engage with your phone tablet or PC versus grabbing a notebook and flipping it over and start writing with the pen. It's almost instantaneous.  I know we have all experiences where a critical thought comes into our brain of turning off a faucet, paying a bill, making a phone call, buying an item, getting batteries for a flashlight before the next big storm and because there was a leg in putting something down, you didn't capture it.  At one point in my business career, I would only wear shirts that had a shirt pocket where I had a special micro notebook with a pen attached that if If something hit me, I could instantaneously write it down. turns out it truly was critical.  Generally, pen and paper will always have advantage.
{As a side note to this, if you don't use a pen and paper, you do need to be able to capture something with no more than a one to two second lead time. In a future post, we'll talk about strategies to capture these fleeting thoughts before they're gone.}

#### Discussing Pen or Pencil Input

We're going to start off with a special case. If you are a classically trained engineer, I won't need to explain this. However, I think it's useful to understand how a job class, which is completely rewarded on their ability to handle ideas have traditionally tracked and handled those ideas.

The engineering notebook is probably the best known and most codified piece of engineering technology and yet it is nothing but a bound notebook that engineers take their notes on and normally date the front side of the cover.  Now it does need to actually be bound. It can't be spiral bound and it can't be a loose-leaf notebook. The reason why is these are classically used as legal documents in IP fights. There have been hundreds of millions if not billions of dollars saved because some engineer was able to drag out of this stack of of notebooks which he accumulated sometimes for decades in his cubicle a drawing or an invention or a disclosure or some sort of thought that was useful for an IP fight.  But I believe for most people this is a niche product as it's expensive if not bought in bulk and specifically designed for IP.

However, after spending many years in the engineering culture, both as an engineer and a manager, there are a few things as nice to hold as a thin engineering notebook. It's classically smaller and lighter and pages never fall out of it, and it serves as just a wonderful tool to capture your ideas. But I think you need to be a certain class of person that enjoys the ascetics of it. But unfortunately, if you're not buying these things in bulk, engineering notebooks are expensive for what you get.

I believe for most people that are thinking about capturing something on pen and paper, you need to keep it inside of a spiral notebook. These are relatively thin and I believe you want to be able to capture your data in a sequential format. This keeps everything together and you can simply take a look at what you put on one day versus the other.  Less acceptable but still a valid format would be to have it in a loose leaf notebook that you can clip open and close.

The one great advantage of either having a loosely or spiral bound notebook is the ability to digitize the information. Over the years, I have had a series of high-speed dual-sided scanners. And they are quick and fast, albeit a bit expensive. But virtually any one of them will allow you to take your notes, insert it into an automatic document feed or ADF, and quickly turn those handwritten notes into something which is electronic that you can refer to at any computing device that you have.

The biggest change that's coming to this market is the abilities of LLMs to transfer that handwritten information into actual searchable text. This is an interesting problem because it is immensely solvable by LLMs and yet the product set is not quickly available. today, you can pay what I would say is a reasonable fee to have your PDFs of handwritten notes scanned and returned to you in some sort of format such as Markdown. However, I've I've written my own model calling the Google flashback end and I can transfer a page for virtually no cost and the recognition is really very good. I have not written a public utility for this, but this is one of these things where it will either be offered by somebody at a reasonable cost because it's such an obvious thing to have or in the next couple of years you will be able to vibe code your own or somebody else will vibe code it for you. So taking these notes today and scanning them is an investment that will pay off shortly as as you will be able to scan them and turn them into text.

My wife is a dedicated hand note taker and so we've bought her a Kindle scribe where she takes the vast majority of her notes. This allows you to have something which is thinner than any notebook and the interaction with the writing on the scribe is very good. While not exactly pen and paper, it becomes very, very close. In addition, Amazon has the ability to send these handwritten notes off to their own service, where they will not only turn them into PDFs, but also do an OCR on your note using one other models. Now, writing legible does help, but generally their models are pretty good. So this is a way that you can instantaneously take pen notes and start to accumulate them. My one fault with this entire system is it does center around PDFs, and I have standardized on Markdown. To turn a PDF into Markdown, you then need to go through an additional stock step such which is IBM's docling, which is open source and excellent.

Finally, you can get applications to be able to do pen writing on either Android or Apple tablets. I currently use an Android tablet for this task. And in retrospect, it's probably something that I should do more to hand annotate graphics that I create, because there is a certain warmth that you can only do with a tablet and a digital pin. However, I find the actual writing of notes much less satisfying than on my wife's kindle scribe. While some people are able to do it, I think the vast majority find tablets in whatever arrangement they try to do it as generally unsatisfactory. So I'm not saying not to do it. I would only encourage you to try it out first. For myself, I find the Nebo app on Android actually quite excellent. It just simply is another their stopover point for me, which I don't believe is necessary.

But, even for myself, where I feel like I have the tools and skills to do a lot of automation, this turns into enough work where I would just simply try to take all my notes directly on a computer.


#### Effectively free (core use is free)

| Package      | Approx. users (order of magnitude) | Notes / comments |
|-------------|-------------------------------------|------------------|
| [Obsidian](https://obsidian.md) | ~5–10M users, 1M+ confirmed | Free for personal use; local `.md` files; paid sync/publish are optional add‑ons, core PKM and plugins fully usable free. |
| [Simplenote](https://simplenote.com) | Millions | Completely free; cloud notes with Markdown support; no significant paid tier. |
| [Joplin](https://joplinapp.org) | Hundreds of thousands–low millions | Open source; full Markdown notes/tasks free; optional Joplin Cloud for sync as paid add‑on. |
| [Logseq](https://logseq.com) | Hundreds of thousands–low millions | Free and open source; local Markdown/Org outliner; paid offering focused on sync/hosting, not core use. |
| [GitBook](https://www.gitbook.com) | 1M+ users (teams + OSS) | Has free tier for small projects and OSS docs; paid tiers for teams/advanced features. |
| [Docusaurus](https://docusaurus.io) | 100k+ projects | Open‑source static site generator; entirely free, self‑hosted docs in Markdown. |
| [HackMD](https://hackmd.io) | Hundreds of thousands | Generous free tier for individuals/small groups; paid for larger org features/seats. |
| [BookStack](https://www.bookstackapp.com) | 50k–200k installs/sites | Open source and self‑hosted; no license cost, optional paid hosting from third parties. |
| [Wiki.js](https://wiki.js.org) | 50k–200k installs/sites | Open source wiki; Markdown content; free to run, pay only for infra. |
| [Outline](https://www.getoutline.com) | 10k–100k teams/users | Source‑available/self‑hosted option; free for self‑hosting, paid for managed/hosted plans. |
| [Zettlr](https://www.zettlr.com) | 50k–200k | Free, open source Markdown editor; donations optional. |
| [Notable](https://notable.app) | 50k–200k | Tag‑centric notes stored as Markdown files; good for devs who want Git + tags. |
| [1Writer](https://1writerapp.com) | 10k–100k | One‑time low‑cost iOS app; effectively “paid once, then free,” but no ongoing subscription. |
| [SilverBullet](https://silverbullet.md) | 10k–50k | Open source, self‑hosted PKM on Markdown; free aside from your hosting. |

#### Primarily paid / paid‑first

| Package      | Approx. users (order of magnitude) | Notes / comments |
|-------------|-------------------------------------|------------------|
| [Evernote](https://evernote.com) | ~200M accounts lifetime, far fewer active now | Free tier heavily limited; serious use generally requires a paid plan. |
| [Notion](https://www.notion.so) | ~30–40M+ users | Solid free tier, but many teams and heavy users pay; data is DB‑backed with Markdown‑like editing. |
| [Bear](https://bear.app) | 1M+ downloads; hundreds of thousands active | Core requires Bear Pro subscription for sync and advanced features; uses Markdown‑flavored syntax. |
| [Typora](https://typora.io) | 100k–500k paid users (est.) | Commercial Markdown editor; one‑time license; no meaningful free tier beyond trial. |
| [Acreom](https://acreom.com) | 10k–100k | Has free plan, but many advanced features (calendar integrations, AI, etc.) live on paid tiers. |
| [NotePlan](https://noteplan.co) | 10k–100k | Subscription‑based on Apple platforms; focuses on daily notes and tasks in Markdown. |
| [UpNote](https://upnote.com) | 10k–100k (est.) | Freemium with lifetime and subscription options; Markdown editor with sync and organization features. |
| [Inkdrop](https://www.inkdrop.app) | 10k–50k (est.) | Subscription‑based developer‑oriented Markdown notes; sync and plugins are core to usage. |
| [Supernotes](https://supernotes.app) | 10k–50k (est.) | Card‑based note platform; free tier limited, serious PKM use tends to be on paid plans. |
