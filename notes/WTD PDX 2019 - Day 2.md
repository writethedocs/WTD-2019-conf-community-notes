---
title: WTD PDX 2019 - Day 2
created: '2019-05-20T13:24:38.426Z'
modified: '2019-05-21T21:36:28.650Z'
tags: [WTD]
---

# WTD PDX 2019 - Day 2
## Tuesday 5/21

### Talks

#### [Alicja Raszkowska - Draw the Docs](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-alicja-raszkowska)
- HTML <ruby> tag for pronunciation
- Julia Evans; Kubernetes do technical comic/drawing designs
- Make documentation engaging; systems thinking for debugging, problem-solving (whiteboarding corollary)
- Biz case made by approaching each dept and speaking to how they each use diagrams and charts today (engineers whiteboard and sketch during pairing; tech writers use diagrams and Sketch w/ designers to explain concepts; Sales uses simple visuals to engage prospects)
- Explored various tools for drawing that would be reusable, scalable, version control, slots into existing team workflow/pipelines (tools shown draw.io, p5.js, mxGraph, etc.)
- Uses Mermaid -- open source p5.js (JS, markdown syntax, CSS styling, web-generating, web interface, CLT/workflow automation)
- Demo shows that CSS declarations set for the graphics used, can then use Mermaid GUI in browser to text edit the diagrams + icons (lightweight compared to Visio...)
- Showed that based on the CSS call, can go from her "whimsy" hand-drawn and cartoony graphics to a different CSS setup with more professional graphics and typeface
- Gotchas: htmlsvg, doesn't play well with Sketch/other SVG editors; CSS styling would need to be maintained alongside other company assets/branding changes. 
- https://mermaidjs.github.io

#### [Sarah Moir - Just Add Data: Make it easier to prioritize your documentation](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-sarah-moir)
- Describing telemetry data and web analytics (time on page, bounce rate, user IP, etc.)
- Looking and not finding
  - Search results, cases, forum questions
- More help needed?
  - Look at support, course enrollment
- Look for new use cases coming from customers (something they're doing or executing that isn't clearly documented; proactive)
- Large amount of data isn't correlated to better understanding; rather, representative data
- Focus on outliers; standard deviation
- Segment data features for more targeted analysis
- Combine pageviews, sales leads and customer numbers to get a wider picture; but be sure to differentiate between potential and current clients
- Interpret using expertise, find alternate explanations and aggregate; knowing customers rate content 3 stars in aggregate isn't as helpful to know that's an average of 1-5 stars vs. majority rate a consistent 3 stars.
- Filtering the results thru expertise on docs -- example of how someone is searching for API endpoints, but do they really mean X/Y/Z. Only we know in detail to interpret the data we gathered. API endpoints discussed on forums, so know that this topic should be prioritized.
- Data on what customers aren't using/doing can also help share what you AREN'T doing, with reasoning.
- _The Product is Docs_ (Splunk book)

#### [Matt Reiner - Show Me the Money: How to Get Your Docs the Love and Support They Deserve](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-matt-reiner)
- K15t speaker (our Confluence server macro/integration provider)
- The "I can do so much more if we just `BLANK` the docs"
- Great, says manager, write a biz case! *eye roll*
- Building biz cases as TWs
- Leadership cares about impact, duplication of effort, impact on you
- Leaders care if you rewrite/redo/duplicate; if training is a cost center; reducing silos
- Prevention-focused (TW) vs. Promotion-focused (everyone else, those who are lauded); leaders care because when we aren't recognized.
- **Format shown is Exec Summary (primary focus here for skimmers) >> SWOT >> Biz Description (where we've been and how request tells us where we're going) >> Marketing strategy (how it will deployed and marketed so there's interest and excitement) >> Operations Overview >> Product Plan >> Financial Plan**
- To align w/ biz leaders, be very connected to biz plan and company goals (from the board level down to our quarterly goals)
- Know your elevator pitch to hammer in on the why
- Also know your USP
- Marketing: knowing the moments before an event and capitalizing on when to deploy
- Connect documentation to the brand identity
- Speak to Marketing in their lingo; campaigns, and how our docs would fit in and a request would satisfy
- Speak to Sales in terms of leads and opps; know that they use our content and ensure there is accuracy from what was promised/described thru the docs. Key in to the benefits, as Sales focuses on these.
- Mentions support (less relevant for us and KCS considering our model is changing drastically) -- take that feedback, throw 50% away and give support a "kb to document stuff in, and take some of it for docs" -- basically what we are do and will do w/ KCS.
- Use data! IE support deflections bc of docs means won't need more headcount; last 10 sales were lost due to docs, etc.

#### [Chris Bush - SDK Reference Manuals: A flow-based approach](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-chris-bush)
- N/A to Smarsh at this point, but check talk if needed later.
- SDK/dev docs is written for implementers, not users.
- Function over form (naturally)

#### [Kay Miles - Product Documentation Strategy: What Is It and Why Do We Need It?](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-kay-miles)
- Information architect presenting
- Examples given of her company having multiple types of authors for software/hardware/systems and different tools/processes/etc. and nothing is consistent across the entire team. Have created silos across many years.
- More time on the TECHNICAL less writer
- Siloing and lack of focus means always just pushing out MVP
- Strategy is a solution to the above
- Roles include: IA (blueprints for information spaces; where nav goes, what content appears, etc.) > Content Strategy (w/w/w/w/w - content types and buckets) > Content Engineering (this makes the blueprint and theory of the IA and strategic designs into a reality; what CMS, how do we publish, etc.) = a tangible, real place for content
- Let TW focus on writing, leave the above to strategists
- Without a team devoted to this, we only fix what we can see (small issues like a client asking where a PDF output is); but what we don't know is a writer in another dept solved that problem differently and now creating an inconsistent experience with multiple variations of this content/info
- **Not fixing the Root Cause** just fixing Band-Aids. Building a house of cards.
- Doc Strategy can look at the evolution of customer experiences and solve the root cause.
- **Users expect consistency** (the Apple example of unity across products)
- **Users expect Google** (first results of relevant content, mindreading autocompletion)
- How to solve? Make content SMART.
  - Invest in *intelligent content*
  - Make sure content is **findable, usable, useful**.
  - If not sticking to a blueprint and consistency then keep contributing to the problem
- Investment in design = ??
  - Templates, guidelines, process docs = giving writers tools to think of how to write great, granular content separated from the design and look.
  - Using metadata across microcontent (yup!)
- Lessons learned
  - Infrastructure refactoring is slow
  - Ownership; more rules means less creativity; standards do not dampen TWs, make that clear to them. Strategic thought allows writers to thrive because that thinking is offloaded from them.
- Example of over 1m pages for their company and 80% (?) had 0 views. Again reiterating to me that it doesn't matter unless content is findable and relevant.
- Do we invest in UX? Metadata? More content people hours?
- Decided to just stop creating content -- freaked the org out; gain was 2600 hours no longer spent pumping out unused content; the benefit is back to the sales/marketing team and use those free hours to reinvest in the existing content to pair down, fix, improve, etc.
- Resources:
  - [_Designing Connected Content...]((https://www.amazon.com/Designing-Connected-Content-Products-Tomorrow/dp/0134763386)_ by Mike Atherton, Carrie Hanes -- the **go to** for content modeling
  - [_Information Architecture for the Web_](https://www.amazon.com/Information-Architecture-Beyond-Louis-Rosenfeld/dp/1491911689/ref=sr_1_1?crid=1KZQ8SCXA38SW&keywords=information+architecture+for+the+web+and+beyond&qid=1558474366&s=books&sprefix=information+architec%2Cstripbooks%2C208&sr=1-1) by Rosenfeld, Morville, Arango
  - [_Intelligent Content_](https://www.amazon.com/Intelligent-Content-Primer-Ann-Rockley/dp/193743446X/ref=sr_1_1?keywords=intelligent+content&qid=1558474539&s=books&sr=1-1-spell) by Rockley, Cooper, Abel
  - [_Intertwingled_](https://www.amazon.com/Intertwingled-Information-Everything-Peter-Morville/dp/0692225587/ref=sr_1_1?keywords=intertwingled&qid=1558474568&s=books&sr=1-1) by Morville

#### [Jessica Parsons - Lessons Learned in a Year of Docs-Driven Development](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-jessica-parsons)
-

#### [Jodie Putrino - Defying the Status Quo: How a grassroots effort can transform an organization](https://www.writethedocs.org/conf/portland/2019/speakers/#speaker-portland-2019-jodie-putrino)
- 

### Lightning Talks
- Mapbox using Copyeditor, an automated checker for prose (rules like non-descriptive link text)
  - Copyeditor is a CLI tool, checking repos, can't push/merge if rules are violated
  - Based on alexjs.com
  - retext -- also used
  - Mapbox forked Alex, customized; also created a styleguide plugin
  - Not open source but look at Alex
- camelCase, subtle issues
  - Git issues in differentiating between similar files in camelCase or not
  - SEO doesn't play well with camelCase
  - Ethnocentricity -- certain languages are unicase (hebrew, hindi, arabic) -- camelCase isn't feasible
- SEO = good content strategy
  - Search data is customer data, and it's plentiful
  - intent-driven pages win searches
  - Strategic, smaller doc sets win more than large, unstructured doc sets
  - Search is primary way customers FIND docs (not our case at Smarsh but good to know)
  - 

### Unconferences
- N/A


