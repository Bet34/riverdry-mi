# RiverDry Michigan — Instant Basement & Crawl Space Estimate

Single-file landing page for Downriver / Metro Detroit basement waterproofing and crawl space encapsulation leads.

## Opportunity score

| Factor | Score | Why |
| --- | --- | --- |
| Speed to cash | 9/10 | Live today. Form + phone. Sell first lead this week. |
| Traffic potential | 8/10 | Local intent + calculator dwell time. Crawl-space terms are easier than HVAC. |
| Competition | 8/10 | SERP is franchise templates. Almost no interactive local estimator. |
| Lead value | 9/10 | Jobs $3k–$15k. Crawl-space clicks ~$51 nationally. Shops pay $50–$150+ per exclusive lead. |
| Fit | 9/10 | Downriver housing stock + Michigan clay + freeze-thaw. |

This is a **lead + rank-and-rent** asset, not a SaaS. Do not pretend it is a contractor brand until a licensed partner is on the phone number.

## Money path

1. Deploy free on GitHub Pages.
2. Put your real phone and Formspree on the page.
3. Call 5 Downriver waterproofing shops. Offer exclusive inspection leads at $75–$125 each, or $900/mo flat for the page once it gets calls.
4. Post in local Facebook groups and Nextdoor with the calculator, not a hard sell.
5. After 10 real reviews from the partner’s jobs, add them to the page.

Realistic first 30 days if you grind outreach: 0–8 leads. One closed waterproofing job pays the partner more than a month of rent. Your cut is the lead fee or the rent.

## Files

- `index.html` — the whole site
- `robots.txt`
- `sitemap.xml`

## Edit before traffic

Open `index.html` and change the `CONFIG` object near the bottom:

```js
const CONFIG = {
  phoneDisplay: "(734) 555-0148",
  phoneHref: "tel:+17345550148",
  formEndpoint: "https://formspree.io/f/YOUR_ID",
  ga4: "G-XXXXXXXX"
};
```

Also replace every `(734) 555-0148` and `tel:+17345550148` in the header, hero, footer, and JSON-LD. Replace the GitHub Pages URL in canonical / schema after you know the live URL.
