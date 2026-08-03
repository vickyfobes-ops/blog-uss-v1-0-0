# Research and SEO Rules

## Topic-Only Input

When the user supplies only a topic:

1. Use the topic phrase as the initial primary-keyword candidate.
2. Infer the product category, target buyer, likely market, and commercial intent.
3. Research current results and refine the keyword only when another phrase clearly matches intent better.
4. Continue with reasonable assumptions; record them in metadata rather than blocking on optional questions.

## Search Research

Capture:

- primary keyword;
- four to eight secondary keywords;
- search intent and funnel stage;
- five or more user questions;
- recurring competitor structures;
- factual claims that need primary sources;
- content gaps the article can answer more clearly;
- useful internal-link opportunities.

For news, legal, medical, financial, safety, standards, prices, software, and other changing claims, use current authoritative sources. Do not rely on memory for unstable facts.

## Source Priority

Prefer sources in this order:

1. regulators, standards bodies, and official government guidance;
2. original manufacturer planning or technical documentation;
3. verified first-party brand or product information;
4. recognized industry publications;
5. competitor guides only for content-pattern analysis.

Use competitor pages to identify unanswered questions, not to borrow their wording or unverified numbers.

## On-Page SEO

- SEO title: 45-60 characters.
- Meta description: 140-160 characters.
- URL handle: concise, lowercase, hyphenated, no version suffix.
- H1: one only; include the primary keyword naturally.
- Opening: answer intent and use the main keyword naturally.
- Opening variation: select an opening mode from the quality standard, reject reusable short-answer formulas, and compare the normalized first 12 words against recent drafts.
- H2s: map to meaningful subtopics and secondary keywords; avoid near-duplicate headings.
- Sources: put a short `Sources and Technical References` H2 immediately before FAQ and explain what each external source supports.
- FAQ: five concise, genuine high-intent questions. Do not turn a source list or editorial note into an FAQ.
- Images: generate at least five topic-specific original AI design visualizations with descriptive alt text, distinct local filenames, and no repetitive keyword stuffing.
- Internal links: use crawlable Markdown links with descriptive anchors. When destinations are verified, include at least one product or collection link and one related-blog link in the article. Record at least one existing page that should link back to the new article after publication. Keep unverified handles out of publish-ready body copy and mark them in metadata.
- CTA: appear before the sources and FAQ sections, select one intent trigger using the quality-standard CTA matrix, and ask for the information needed for that exact next step. Do not add quantified brand proof unless the trigger explicitly permits it.

Do not target a keyword-density percentage. Readability and intent coverage take priority.

## Indexing Readiness

Writing can improve index eligibility, but it cannot guarantee or force Google indexing. Build each article so publication can satisfy these discovery and indexability checks:

- serve one distinct search intent instead of creating near-duplicate pages for small keyword variations;
- give the useful answer or diagnostic orientation within the first 120 words;
- add original analysis, calculations, decision tools, verified first-hand observations, or supplied real-world evidence instead of merely summarizing competitors;
- keep early paragraphs editorial and move quantified brand proof or collection promotion later unless supplier trust is the query;
- use one stable canonical handle and do not publish local `-vN` variants as separate URLs;
- ensure at least one already discoverable site page can link to the new canonical URL;
- after publication, verify a public HTTP 200 response, no `noindex`, crawl permission, self-referencing canonical, and sitemap inclusion;
- use Search Console URL Inspection once after the live checks pass; repeated requests are not an acceleration strategy.

Record the technical items as publication checks when the live site is outside the task scope. Do not claim a predicted indexing time or describe on-page scores as evidence that Google will index the page.

Official references for this checklist:

- [Google: ask Google to recrawl URLs](https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl)
- [Google: crawlable links and internal linking](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)
- [Google: helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Shopify: finding and submitting the automatically generated sitemap](https://help.shopify.com/en/manual/promoting-marketing/seo/find-site-map)

## Scoring

Use internal scores only as editorial diagnostics:

- `aiToneScore`: lower is better.
- `originalityRiskScore`: lower is better.
- `seoScore`: on-page readiness, not a ranking forecast.
- `conversionScore`: usefulness of decision support and CTA.
- `factualRisk`: lower is better.

Never describe a score as proof that the article will rank.
