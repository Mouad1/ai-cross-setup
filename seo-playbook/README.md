## WHAT YOU'LL BUILD
By the end of this guide, your website will have everything AI models need to
recommend your business:
1. llms.(txt/md) : This is the main file. It's a plain text document or an md file that sits at yourwebsite.com/llms.(txt/md)and tells AI exactly what your business is.It's one-page pitch written for a machine.
2. Structured data (schema) — machine-readable business info AI and Google
both love
3. A strong FAQ section — direct Q&A pairs that AI quotes back to users
4. Location + industry pages — one page per city and per service so AI has
something specific to cite
5. AI crawler access — robots.txt set up so GPTBot, ClaudeBot, and PerplexityBot
can actually read your site

## WHY THIS WORKS
AI models don't "search" the way Google does. They pull from pages that are clear,
structured, and easy to summarize. Most business websites are bloated with
marketing fluff and pop-ups.If you give AI a clean, direct source of truth, it will
quote you over the noise.

## PREREQUISITES
- Claude Code installed
- Basic info about your business
- 15–30 minutes for the llms.(txt.md) + schema. A few hours if you want to do the full
location/service pages

## STEPS
1. Create the llms.(txt.md) and paste it to your claude code
2. Upload It to Your Website: The file has to live at yourwebsite.com/llms.txt — not in a subfolder, not in a blog post, not behind a login. Root of the site. Test it in your browser after uploading by typing the URL directly.
paste this to claude code : 
```text
I have a website hosted on [YOUR HOST —
GitHub/Netlify/Squarespace/WordPress/Webflow/etc.].
Walk me through exactly how to upload the llms.txt file we just
created to the root of my site. Give me step-by-step instructions for
my specific host. After I upload it, tell me how to confirm it's live
by visiting the URL directly.
```
3. Add Schema Markup (Structured Data)
Schema is code AI and Google can read to understand exactly what your business
is. It lives inside your website HTML, invisible to visitors, but very visible to
machines.
Paste [[schema-markup.md]] to claude code
- After you paste it in, test the schema at validator.schema.org and
search.google.com/test/rich-results. Both free. They'll tell you if anything is
broken.

4. Open the Door for AI Crawlers
- AI bots like GPTBot (ChatGPT), ClaudeBot (Claude), and PerplexityBot have to be
allowed to crawl your site. A lot of templates block them by default. You want them
in.
- Paste [[robot-gen.md]] to claude code
>COUNTERINTUITIVE BUT TRUE
Every "SEO best practice" article from 2023 told you to block AI bots to "protect
your content." Don't. You want AI to read your site. The whole point is to get quoted
in AI answers. Let them in.

5. Add a Real FAQ Section to Your Homepage
- AI pulls quotes directly from FAQ blocks. They're structured, they're direct, and they match how people ask questions. If your homepage has a good FAQ, AI will quote
you word-for-word in its answers.
- Paste [[faq-gen.md]] to claude code

6. Build Location + Service Pages (Optional but Powerful)
- This is the step that took me from being mentioned to being the top
recommendation. Create one page per city you serve and one page per core
service. Each page is a clean, specific, AI-readable target.
paste [[location-services.md]] to claude code

>THE MULTIPLIER EFFECT
One llms.txt gets you in the door. Twenty location and service pages get you
quoted. Every page is another chance for an AI to pull from your site instead of a
competitor's. This is what took my traffic from ~7/day to ~150/day in two weeks.

7. Test
Wait 3-7 days after everything is live (AI models need time to recrawl). Then test:
    1. Open ChatGPT. Ask "who does the best [your service] in [your city]?"
    2. Ask Perplexity the same question.
    3. Ask Claude the same question.
    4. Ask Google's AI Overview (appears at the top of normal Google searches) the same question.If you show up in 1-2 of them early, you're on the path. If you show up in all 4,you've built a moat. Keep adding pages, keep updating your llms.txt as you add services, and check back every couple weeks.

- paste the [[audit.md]] in claude code

## TIPS
1. Specificity beats polish. Real prices, real cities, real numbers. AI will quote
specifics. It will ignore vague marketing copy.
2. Update llms.txt every time your business changes. New service? New price?
New location? Update the file. It's literally a text doc.
3. Don't block AI bots, even "to save on bandwidth." You want the exposure more
than you want the server cycles.
4. One clean page beats five bloated ones. A 500-word location page with real
info outperforms a 3,000-word SEO monster stuffed with keywords.
5. AI cares about FAQs more than paragraphs. Questions and answers get quoted.
Paragraphs get ignored. Add FAQs everywhere.
6. Check your Google Search Console. You'll start seeing impressions for queries
you never targeted. That's AI-adjacent traffic showing up.
7. Ask AI about yourself regularly. "Best [service] in [city]" — do this weekly. It's
free feedback on what's working.






