# seniorwalkinbathtubs.com · MASTER GAMEPLAN
Last updated 2026-11-08 (overnight aging-network push). Network plan: Desktop\02 AGING SAFELY BATHS\07 Aging Safely Website Network\MASTER GAMEPLAN.md. Rules: C:\Users\zachw\aging-sweep\notes\RULES.md.

## Lane
Buyer's guides for seniors themselves: cost, installation, small/bariatric/hydrotherapy tubs, Medicare and tax.

Every page here supports agingsafelybaths.com (quotes, installs) and never targets its head terms (walk in tubs, walk in tub cost, handicap showers, roll in showers, Medicaid/grants head terms). Max 2 followed network links per page; other network links nofollow; one nofollow Eye To Ad credit.

## Business facts
Aging Safely Baths & More, LLC. 1-888-779-2284, sales@agingsafelybaths.com. BBB A+ since 2012. Published prices only (RULES.md): walk-in tub about $15,500 installed after the $2,000 promo, $15,250 veterans, roll-in showers $13,500 to $17,000, wide/transfer/bariatric from about $19,000.

## Targets (one page owns one term)
- senior walk in bathtubs
- walk in tub installation
- small walk in tubs
- walk in tub tax deduction

## Competitors (live check 2026-11-08; search results, not verified rank)
- theseniorlist.com / thisoldhouse.com: ranked comparisons and cost tables
- rebath.com: benefit lists, no evidence
- aquaticausa.com: type explainer, no fit measurements

**How we beat them:** Dated sourced numbers, a 'who should not buy' view, fit measurements, winter safety.

## Done tonight (2026-11-08)
- Quote forms now post to the company lead server (clients.eyetoad.com/lead/send.php, saves to disk first, then emails sales) through /lead-send.js, with the old sender (FormSubmit or EmailJS) as automatic fallback. Pilot verified in a live browser on walkintubsflorida.com.
- GA4 tag (property per site, events generate_lead, phone_click, estimator_use) confirmed on every indexable page; Search Console verification file googleadb17462a109b3ca.html present.
- Lighthouse (home page, live, 2026-11-08 early morning) recorded before and after in _overnight-reports/aging-sites-report.md.
- New /walk-in-tub-winter-cold-safety/ (fill and drain wait, room temperature, heated seat and inline heater, 120°F; NIA and CPSC sources).
- GSC 28-day: 3,990 impressions, 13 clicks, avg position 37.7; installation and compact-tub queries lead.

## Next
1. Walk-in tub vs walk-in shower after stroke or Parkinson's (ASA checklist PDFs)
1. Medicare Advantage bathroom benefit: what to ask (plan benefit sheet wording); update the existing Medicare page, no new page
1. Refresh the 15 em-dash pages flagged by qa.mjs

## Morning to-dos (network)
- Add the six EmailJS satellites (seniorwalkintub, utahwalkintubs, walkintubdenver, walkintubscalifornia, walkintubschicago, walkintubstexas) to lead-config.php on clients.eyetoad.com so they stop falling back to EmailJS.
- Confirm where aging-site leads from the lead server are emailed (sales@agingsafelybaths.com?) and that the mail lands; fix eyetoad.com SPF/DMARC.
- Request indexing in Search Console for every new or changed URL listed in the report.
- AdSense: not added to these lead-gen pages on purpose (ads next to a quote form cost leads). Decide if any info-only page should carry it.

## Measurement
GA4 property per site (account 45765285), key events generate_lead and phone_click. Search Console: bare domain property, sitemap.xml submitted. Check queries and positions in GA4's Search Console report at the start of every project.
