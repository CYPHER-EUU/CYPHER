# Direct Consumer Competitors to Glowy: AI/Photo-Based Skin Diagnosis + Personalized Skincare Apps

**Scope note on data quality:** Web search results for this category are heavily polluted by AI-generated "review" content farms (sites like fapam.edu.br, blog.jingtea.com, old.media-azi.md publishing "MDacne Reviews 2026" articles with suspiciously precise, unverifiable stats such as "V4 Neural Scan," "99.2% accuracy," "15,000+ aggregated 2026 inputs"). These are almost certainly fabricated/SEO-spam, not primary reporting, and are explicitly **excluded** from the Cited Findings below. All figures used are drawn from app-analytics aggregators (AppFollow, SplitMetrics, SimilarWeb, AppPricingLab), company/press pages, CB Insights, and direct news coverage. Direct WebFetch access to apps.apple.com, getskinbliss.com, and eu-startups.com was blocked by the research environment's egress proxy, so app-store and company-site figures below are sourced via search-engine snippets of third-party aggregators rather than primary-page fetches — treat exact figures as directionally reliable but re-verify before publishing if precision matters.

---

## MDacne (MDalgorithms Inc.)

### Takeaway
MDacne is the most mature and highest-traction player in this set: a 2017-founded, YC-backed US company with ~4M+ app users, proprietary in-house AI, a branded compounded-treatment business model (not third-party product affiliate), and a dermatologist-message-board layer — making it the closest full analog to a "diagnosis + commerce + light telehealth" model.

### Cited Findings
- Positioning: a dermatology-grade app where users "take and upload photos of their skin and create a personalized 30-day treatment plan based on clinical data" via selfie + questionnaire. — [Digital Commerce 360 (via search synthesis)](https://www.digitalcommerce360.com/?p=292092)
- Founded 2017 by CEO Oded Harth and dermatologist Dr. Yoram Harth; went through Y Combinator. — [Y Combinator company page](https://www.ycombinator.com/companies/mdalgorithms-inc); [Times of Israel](https://www.timesofisrael.com/phone-app-seeks-to-bust-acne-using-selfies-and-algorithms/)
- Funding: seed round in 2017 with Y Combinator/SV Angel/Khosla Ventures participation; a 2022 seed extension (~$6.0M across backers per StartupHub/Seedtable) led by Moxxie Ventures with REDO Ventures, Burst Capital, Idealab, and Niche Capital; Craft.co separately totals lifetime funding at $2.4M (sources disagree on cumulative total — flagged as a conflict). — [Moxxie Ventures investment announcement](https://moxxie.substack.com/p/announcing-our-investment-in-mdalgorithms); [Seedtable](https://seedtable.com/companies/mdalgorithms-inc); [Craft.co](https://craft.co/mdalgorithms)
- Scale: app used by "more than 4 million people"; sister product lines MDhair (hair loss) and Nuvane. — [Craft.co / company materials via search synthesis](https://craft.co/mdacne)
- Diagnostic method: selfie photo + intake questionnaire; AI (described by the company as proprietary, built entirely in-house, trained on "the largest global dataset of acne and scalp images") analyzes blemishes/lesions in real time, on-device processing noted in older coverage. — [Times of Israel](https://www.timesofisrael.com/phone-app-seeks-to-bust-acne-using-selfies-and-algorithms/); [PromptLoop company summary (via search synthesis)](https://promptloop.com/directory/what-does-mdalgorithms-inc-do)
- Skin metrics: primarily acne severity/type (comedones, papules, pustules, cysts) and scalp/hair condition (via MDhair); not positioned around wrinkles/pores/redness/hydration broadly — it is an acne-first (and more recently hair-loss-first) specialist, not a general skin-health scanner.
- Monetization: free app download; subscription tiers reported at $1.99/week, $6.99/month, $50/year for premium content, plus the core business model is selling a custom-compounded topical treatment kit shipped to the user (product revenue, not pure SaaS). — [AppPricingLab-style aggregator data via search synthesis](https://apppricinglab.com/app/apple/1044050208)
- Telehealth element: users can post acne questions to a message board and get a response from an MDacne-affiliated dermatologist, reported turnaround ~72 hours — a lightweight async consultation layer, not live video telehealth. — [Trustpilot review aggregation via search synthesis](https://nz.trustpilot.com/review/www.mdacne.com?page=6)
- Traction signal (use with caution — not independently fetched): search-aggregated data points to an Apple App Store rating around 4.6★ on roughly 18.7K ratings, and a Trustpilot TrustScore of 4.5/5. — [AppFollow aggregator](https://apps.appfollow.io/ios/acne/6464321534?country=hk); [Trustpilot](https://nz.trustpilot.com/review/www.mdacne.com?page=8)
- Geography/demographic: pricing in USD, press coverage via Times of Israel and SF Chronicle frames it as a US-market consumer product from an Israeli-founded team; acne skews toward a teen/young-adult demographic given the product focus. — [San Francisco Chronicle (via search synthesis)](https://preview-prod.w.sfchronicle.com/business/article/Got-acne-This-startup-says-its-selfie-app-can-12512723.php)

### Inferences
- MDacne is fundamentally a treat-and-ship compounded-product business wrapped in an AI-diagnosis UX, not a pure recommendation/affiliate engine — its revenue model (product fulfillment) is structurally different from an app like Glowy that would point users to third-party SKUs.
- The brand is now acne/hair-loss-specific rather than general "skin health," which narrows its direct overlap with a broad-spectrum skin-diagnosis app like Glowy to the acne-prone-skin segment specifically.

### Gaps
- No single authoritative, current (2025-2026) total funding figure — sources (Craft.co $2.4M vs. StartupHub $6M) conflict and neither could be verified against Crunchbase/PitchBook directly (WebFetch to apps.apple.com and most primary sites was blocked).
- Team size is not confirmed by any source found.
- Exact current App Store description copy (verbatim marketing wording) could not be retrieved since apps.apple.com fetches were blocked; the positioning line above is paraphrased from secondary coverage, not quoted verbatim from Apple's listing.
- No confirmation of which specific CV model/architecture MDacne uses beyond its own claim of being "proprietary" and "in-house" — unverified by an independent technical source.

---

## Skinive

### Takeaway
Skinive is best understood as a **medical skin-condition/cancer-risk screening and triage tool** (CE-marked software, used by/with dermatologists) rather than a cosmetic skincare-recommendation app — it overlaps with Glowy only partially, on the computer-vision photo-analysis piece, and is a weaker direct comparable on the "personalized skincare routine" dimension.

### Cited Findings
- Mission statement: Skinive is "on a mission to help 2 billion people take care of their skin's health and beauty in an easier and faster way." — [PeerPush](https://peerpush.com/p/skinive-ai-skin-scanner); [Callin.io AI tools directory](https://callin.io/ai-tools/skinive/)
- Diagnostic method: user takes a close-up photo of a spot/rash/blemish; proprietary computer-vision/deep-learning algorithms compare it against a clinical-case image database; the algorithm is described as adapting across ages, skin types and skin tones. — [Callin.io](https://callin.io/ai-tools/skinive/); [ioplus.nl](https://ioplus.nl/archive/en/skinives-ai-detects-skin-diseases-through-your-smartphone/)
- Skin metrics/conditions detected: 50+ skin conditions including acne, eczema, psoriasis, rashes, moles/spots, and skin-cancer risk categories (melanoma, basal cell carcinoma, squamous cell carcinoma) — this is disease/pathology detection, not cosmetic metrics like wrinkles/pores/hydration. — [Irish Tech News](https://irishtechnews.ie/skin-pathologies-identified-up-to-95-accuracy/amp/)
- Reported accuracy claim: "up to 95% accuracy" in identifying skin pathologies (company claim, Dutch-startup framing). — [Irish Tech News](https://irishtechnews.ie/skin-pathologies-identified-up-to-95-accuracy/amp/)
- Regulatory/credibility: positioned as CE-marked medical software; claims GDPR & ISO compliance; states it is "trusted by dermatologists" and explicitly frames itself as a pre-diagnostic e-health tool, not a replacement for a doctor. — [Callin.io](https://callin.io/ai-tools/skinive/)
- Scale claim (company-reported): "over 3,000,000 risk assessments performed" and "more than 200,000 cases of skin diseases" detected. — [Callin.io](https://callin.io/ai-tools/skinive/)
- Founded 2020, headquartered Amsterdam, Netherlands; CEO Artyom Trofimuk; one data point puts headcount at 13 employees. — [CB Insights company profile (via search synthesis)](https://www.cbinsights.com/company/skinive/financials); [GetLatka](https://getlatka.com/companies/skinive.com)
- Funding: reported as $21M raised across 6 rounds, including a $20M "Grant" round dated Jan 10, 2023; investors include Rockstart, BergTop VC, Angels Band, TechMinsk, European Network of AI Excellence Centres, and Malta Enterprise (grant). The very large size of the "Grant" relative to typical seed rounds is unusual and should be re-verified against a primary source before being treated as equity funding. — [CB Insights (via search synthesis)](https://www.cbinsights.com/company/skinive/financials)
- There is a companion product, "SkiniveMD," explicitly built "for medical doctors," indicating a B2B2C / clinician-facing distribution channel alongside the consumer app. — [AppFollow listing](https://apps.appfollow.io/ios/skinivemd-for-medical-doctors/1509531637?country=is)
- App store traction is thin/inconsistent in the data found: one minor aggregator shows a 5.0★ rating from only 3 reviews; GetApp shows no user reviews at all — suggesting low consumer app-store review volume relative to its usage claims. — [AppFollow](https://apps.appfollow.io/ios/skin-scanner-mole-uv-checker/1633219654?country=is); [GetApp](https://www.getapp.com/all-software/a/skinive/)

### Inferences
- Skinive's core value proposition (disease/cancer-risk screening) is adjacent to, but distinct from, Glowy's cosmetic-diagnosis + routine-recommendation model; it does not appear to generate personalized skincare *product* routines at all — it triages and refers users toward medical care rather than toward a shopping/routine outcome.
- The gap between its large claimed "risk assessments performed" figure (3M+) and its minimal app-store review footprint suggests usage may be concentrated through B2B/clinical channels (SkiniveMD, partner distribution) rather than organic consumer App Store/Google Play acquisition.

### Gaps
- No clear monetization model found (no confirmed subscription price, one-time fee, or affiliate structure for the consumer app) — this is a meaningful gap for the monetization-model requirement.
- Google Play rating/review count for the main consumer "Skin Scanner" app could not be pinned down (SimilarWeb link found but not fetched with concrete numbers).
- No evidence found on whether Skinive recommends any skincare products at all (cosmetic or medical) as a follow-on to its scans.
- Primary geographic market/target demographic is not explicitly stated anywhere found; Amsterdam HQ and CE-marking suggest an EU/regulatory-first orientation, but this is inference, not a cited claim.

---

## Skin Bliss (Skin Bliss SIA / getskinbliss.com)

### Takeaway
Skin Bliss is a single company (not an ambiguous naming collision) that began as an ingredient-matching/questionnaire skincare-routine app and has since added an AI face-scanning + daily-photo progress-tracking layer — its current App Store identity, "Skin Bliss: Skincare Routines," markets itself as "the world's smartest skincare app," making it a close functional analog to Glowy, albeit much smaller in scale.

### Cited Findings
- Company founded 2021 in Barcelona, Spain, by Dr. Maria Otworowska (after her own struggle with adult acne) together with a co-founder named Marvin; described as having a remote HQ with an office in Copenhagen, Denmark. — [CB Insights company profile (via search synthesis)](https://www.cbinsights.com/company/skin-bliss); [Skin Bliss Notion careers page](https://skinbliss.notion.site/Head-of-Marketing-consumer-mobile-app-c42a726085d94ac19bbb4a8b44f7d918)
- Funding: $100K convertible note, last raised 1/1/2022, from investors Accelerace and Overkill Ventures — a very small/early check relative to MDacne or Skinive. — [CB Insights (via search synthesis)](https://www.cbinsights.com/company/skin-bliss)
- Original/core positioning (ingredient-matching product): users fill in a skin profile (skin tone, redness, acne concerns), lifestyle filters (cruelty-free, halal, vegan) and blacklisted/favorite ingredients, and the app matches them to suitable third-party products using "scientific foundations and chemical insights" rather than user-generated/crowd reviews. — [CB Insights company description (via search synthesis)](https://www.cbinsights.com/company/skin-bliss)
- Current App Store product, "Skin Bliss: Skincare Routines," is marketed as "the world's smartest skincare app," combining: (1) an AI face scanner that detects visible concerns and builds a skin profile; (2) a routine builder (from scratch or expert-designed templates) with "ingredient-smart" product scheduling; (3) progress tracking via daily photo uploads that the AI compares against the user's original scan; (4) a skin diary for logging symptoms/triggers. — [App Store search synthesis](https://apps.apple.com/app/1385561364)
- Monetization: free to download; Apple listing shows no in-app purchases per one aggregator while the Google Play listing does show in-app purchases — a discrepancy worth flagging (possibly reflects platform-specific rollout, or stale data on one side). — [AppPricingLab iOS](https://apppricinglab.com/app/apple/1385561364); [AppPricingLab Google Play](https://www.apppricinglab.com/app/google_play/com.getskinbliss.skinbliss)
- Traction: Apple App Store rating ~4.7★ (figures of 759 and 855 reviews both appear across aggregators — minor inconsistency); Google Play rating 4.4★ from ~9.3K reviews, with Google Play showing roughly 1.0M installs. — [SplitMetrics](https://splitmetrics.com/apps/skin-bliss-beauty-skincare/id1385561364); [AppFollow](https://appfollow.io/ios/skin-bliss-skincare-routines/1385561364?country=us)
- Marketing claim: the app "has helped millions discover their unique skin profiles" and is described by the company as "rooted in AI, scientific research, and supported by world-class skincare experts." — [search synthesis of App Store/company copy](https://similarweb.com/app/apple/1385561364)
- CB Insights lists TroveSkin as a direct comparable/competitor to Skin Bliss in its database. — [CB Insights compare page](https://www.cbinsights.com/compare/skin-bliss-vs-troveskin)

### Inferences
- Skin Bliss recommends existing third-party market products (it does not appear to manufacture or sell its own branded skincare line) — its business model is closer to a recommendation/affiliate layer than MDacne's compounded-product model.
- Given the company's small team/funding ($100K convertible note) relative to its Google Play install base (~1M), it likely relies on organic/App Store Optimization growth rather than large paid-acquisition budgets, and the AI face-scan feature may have been added later as a differentiator against newer entrants (like Glowy) rather than being the original product core.

### Gaps
- No confirmed subscription price point was found for Skin Bliss premium features.
- No information found on whether the AI face-scanning technology is built in-house or licensed from a third party (e.g., Haut.AI, Perfect Corp) — flagged as unverified either way.
- No dermatologist/telehealth consultation feature was found referenced anywhere for Skin Bliss; absence of evidence is not confirmation of absence, so this is noted as a gap rather than a negative finding.
- Could not verify current team size.
- Primary geographic market not explicitly stated; Barcelona/Copenhagen base suggests a European go-to-market, but the app appears to be in English and distributed globally via both app stores — treat any geography claim as inference only.

---

## OnSkin

### Takeaway
OnSkin's dominant, well-documented identity is as an **ingredient/product scanner** (barcode or packaging photo of a *product*, not a selfie) with a questionnaire-driven routine builder — evidence for a genuine photo-based *facial skin* AI diagnosis feature is thin, low-confidence, and directly contradicted by other descriptions of the same app, so this should be flagged as a likely partial mismatch with Glowy's core category.

### Cited Findings
- Core positioning: "a science-backed ingredient checker and product scanner for skincare, makeup, hair care, and household products — trusted by over 8 million users," backed by a database of 2 million products. — [search synthesis of OnSkin marketing copy](https://mwm.ai/apps/id/1630768985)
- Diagnostic/analysis method (primary, well-attested): users scan a product barcode, take a photo of product packaging, or search by name to get an ingredient-safety breakdown (flags for allergens, endocrine disruptors, carcinogens, overexposure risk). This is **product-photo scanning, not a user selfie/face scan**. — [SplitMetrics](https://splitmetrics.com/apps/onskin-ai-product-scanner/id1630768985)
- Personalization layer: users complete a "Skin Profile" questionnaire (skin type, needs, concerns), and the app's "Skin Match" feature flags products (e.g., comedogenic ingredients for oily/acne-prone skin) and builds a personalized AM/PM routine; a companion "Hair Lab" does the same for hair products; "Shelf Scan" batch-scans a user's whole product shelf. — [search synthesis of app description](https://apps.appfollow.io/ios/onskin-beauty-product-scanner/1630768985?country=id)
- Ratings-based quality claims: described as using "an in-house team of biologists and physicians" assessing ingredients against toxicology/dermatology research, positioned as an unbiased alternative to crowd-sourced ratings. — [search synthesis](https://cafebazaar.ir/app/skin.care.product.scanner.skincare.cosmetic.ingredient.checker?l=en)
- App Store traction: reported 4.7★ rating from 32.4K reviews; user feedback flags "aggressive paywall" as a recurring complaint alongside praise for recommendation usefulness. — [search synthesis of aggregator data](https://appfollow.io/ios/onskin-ai-product-scanner/1630768985?country=bt)
- **Conflicting claim:** a low-confidence freelancer-portfolio source states OnSkin "can scan a user's face, analyze skin conditions in real-time, and deliver personalized skincare routines" using computer vision/TensorFlow, crediting "Muhammad Usama, CTO of M TECHUB LLC" as a developer, and notes the app is copyrighted to "AIBY Inc" (as of 2023). This directly contradicts the dominant description above (which centers on *product* scanning, not *face* scanning) and comes from a single self-published portfolio page, not the company itself — **treat as unverified / likely inaccurate or describing a feature that does not actually exist in the shipped app**. — [Contra.com freelancer portfolio](https://contra.com/p/FebWsOWv-ai-skincare-scanner-app-computer-vision-tensor-flow)
- Listed among "top AI skin analysis apps" roundups by Perfect Corp's own blog content (Perfect Corp is itself a competing AI skin-analysis technology vendor), which is a marketing-content context and should be read as a mention, not an endorsement of technical parity. — [Perfect Corp blog](https://www.perfectcorp.com/business/blog/ai-skincare/top-ai-skin-analysis-app)

### Inferences
- OnSkin's real core competitive wedge is "Yuka-for-skincare" ingredient transparency plus a routine builder layered on top of a questionnaire — not a computer-vision facial diagnosis engine. If Glowy's differentiation rests on photo/CV-based skin diagnosis specifically, OnSkin is a weaker direct comparable on that dimension than MDacne or Skin Bliss, despite strong overall app-store traction.
- OnSkin recommends third-party products exclusively (it is fundamentally a database/checker for products already on the market); it has no own-brand product line evidence anywhere in the research.

### Gaps
- Could not confirm or disconfirm, from a reliable source, whether OnSkin has ever shipped a true selfie/face-scan skin-diagnosis feature (as opposed to product-package scanning) — this is the single most important open question for comparability with Glowy and could not be resolved within the research budget (apps.apple.com fetch was blocked).
- No funding, founding year, or team-size data found for OnSkin / its operating company (AIBY Inc or M TECHUB LLC) from any credible source.
- No confirmed subscription price point found (only that a paywall exists and is described by users as aggressive).
- Primary geographic market/demographic not found; the app is distributed in many country storefronts (checked listings spanning Netherlands, Poland, Azerbaijan, Lebanon, Armenia, Bhutan, etc.), consistent with a broad global/English-first distribution strategy typical of utility-app publishers, but no explicit target-market statement was found.

---

## Other Apps Found With Similar Positioning (Photo/Questionnaire Diagnosis → Personalized Skincare)

### Takeaway
Beyond the four named apps, three other products recur in competitive-set discussions: TroveSkin (closest match — daily-photo progress tracking + recommendations), and two hardware-dependent outliers, Atolla and Revea, which are useful as contrast cases because they diagnose via physical test kits/light-based devices rather than a phone camera alone.

### Cited Findings
- TroveSkin is described as an app "known for its ability to track skin progress over time, allowing users to take daily photos and analyze changes in their skin's condition while offering personalized skincare tips and product recommendations based on the analysis," and is free to try. CB Insights independently lists it as a direct comparable to Skin Bliss. — [search synthesis, low-confidence single source](https://www.cbinsights.com/compare/skin-bliss-vs-troveskin)
- Atolla (Brooklyn-based, co-founded 2017 by Meghan Maupin, data scientist Sid Salvi, and dermatologist Ranella Hirsch) diagnoses via a **physical at-home test kit** measuring hydration, oil, pH, and absorption — not a photo/selfie — then ships a custom-compounded serum on a monthly subscription, reformulated each cycle. — [Dezeen](https://www.dezeen.com/2019/09/03/atolla-personalised-skin-care-products/); [Best Practice AI case study](https://bestpractice.ai/ai-use-cases/case-studies/consumer-retail/atolla-identifies-skin-health-issues-and-recommends-skin-care-products-using-machine-learning)
- Revea's app diagnoses skin type/concerns using a proprietary light-based hardware device that measures how different light wavelengths penetrate and reflect within skin layers (company analogizes it to "an MRI or X-ray for the skin"), then recommends ingredients/products based on results — again a hardware-dependent method, not photo-only. — [Hypebae](https://hypebae.com/2022/9/revea-skincare-ai-technology-mobile-app)

### Inferences
- Among the apps surveyed across both research passes, TroveSkin is the closest pure functional match to Glowy's described model (phone-camera-only, repeat-photo progress tracking, product recommendations, no hardware requirement) and should be considered a priority for deeper individual research if not already covered by another researcher on this project.
- Atolla and Revea represent an adjacent competitive category — "diagnose with hardware, deliver custom/compounded product" — which is a meaningfully different (more capital- and logistics-intensive) business model than Glowy's presumed phone-only approach, and likely compete more with MDacne/Atolla-style compounding businesses than with pure-software recommendation apps.

### Gaps
- TroveSkin could not be independently verified beyond one synthesized search result; no funding, founding year, ratings, or monetization data were found for it in this pass — it needs a dedicated research pass (direct site/App Store fetch) if it's to be included as a full profile.
- No current (2024-2026) status check was done on whether Atolla or Revea are still operating/shipping (both citations are from 2019 and 2022 respectively) — flag as potentially stale.

---

## Cross-Cutting Key Questions

### Takeaway
Across the four core apps, only MDacne clearly sells its own branded product (compounded treatment); Skin Bliss and OnSkin both operate as third-party product recommendation/affiliate-style layers; Skinive is the outlier that does not appear to recommend cosmetic products at all. None of the four offer live human dermatologist telehealth — MDacne's async message board is the closest thing. AI/CV technology appears to be built in-house for MDacne and Skinive (per company claims); it is unverified for Skin Bliss and contradictorily sourced for OnSkin. On app-store traction, OnSkin (4.7★/32.4K reviews) and MDacne (4.6★/~18.7K reviews) show the strongest, most consistent consumer engagement signals; Skin Bliss shows moderate but smaller/mixed traction (4.7★ but only ~760-855 iOS reviews vs. 4.4★/9.3K Android reviews); Skinive shows the weakest app-store review footprint of the four despite large claimed usage numbers, consistent with it running more through B2B/clinical channels. Only Skin Bliss and TroveSkin (among apps found) explicitly market repeat-photo progress tracking against an original scan as a named feature.

### Cited Findings
- Own-brand vs. third-party: MDacne ships a custom-compounded treatment kit it manufactures/fulfills itself (own product). — [Times of Israel](https://www.timesofisrael.com/phone-app-seeks-to-bust-acne-using-selfies-and-algorithms/)
- Own-brand vs. third-party: Skin Bliss's original ingredient-matching model explicitly recommends existing market products filtered by user preferences (vegan, cruelty-free, halal, etc.), i.e., third-party recommendations. — [CB Insights](https://www.cbinsights.com/company/skin-bliss)
- Own-brand vs. third-party: OnSkin is fundamentally a scanner/database for products already on the market (2M-product database), i.e., third-party recommendations. — [SplitMetrics](https://splitmetrics.com/apps/onskin-ai-product-scanner/id1630768985)
- Telehealth: MDacne offers an async dermatologist Q&A message board (~72-hour response), the only confirmed human-clinician touchpoint among the four. — [Trustpilot aggregation](https://nz.trustpilot.com/review/www.mdacne.com?page=6)
- Telehealth: Skinive is "trusted by dermatologists" and has a companion clinician-facing app (SkiniveMD), suggesting clinical-channel distribution, but no evidence of direct consumer-to-dermatologist live consultation inside the consumer app. — [AppFollow](https://apps.appfollow.io/ios/skinivemd-for-medical-doctors/1509531637?country=is)
- AI/CV source: MDacne states its AI is proprietary and built entirely in-house on its own acne/scalp image dataset. — [PromptLoop (via search synthesis)](https://promptloop.com/directory/what-does-mdalgorithms-inc-do)
- AI/CV source: Skinive describes its own computer-vision/deep-learning algorithms compared against its own clinical-case database (no third-party vendor named). — [ioplus.nl](https://ioplus.nl/archive/en/skinives-ai-detects-skin-diseases-through-your-smartphone/)
- Ratings comparison snapshot (all figures via aggregators, not primary-fetched): OnSkin 4.7★/32.4K reviews; MDacne 4.6★/~18.7K reviews (Apple) plus 4.5 Trustpilot TrustScore; Skin Bliss 4.7★/~760-855 reviews (Apple) and 4.4★/9.3K reviews + ~1.0M installs (Google Play); Skinive ~5.0★ on only 3 reviews on one minor aggregator, no reviews visible on GetApp. — see per-app sections above for individual sources
- Progress tracking: Skin Bliss explicitly markets daily-photo uploads that the AI compares to the user's original scan. — [App Store description via search synthesis](https://apps.apple.com/app/1385561364)
- Progress tracking: TroveSkin is described as tracking skin progress via daily photos compared over time (lower-confidence, single source). — [search synthesis](https://www.cbinsights.com/compare/skin-bliss-vs-troveskin)

### Inferences
- No app in this set licenses a well-known third-party white-label skin-analysis engine (e.g., Haut.AI, Perfect Corp) by confirmed, reliable evidence — MDacne and Skinive affirmatively claim in-house CV; Skin Bliss and OnSkin's underlying tech stack is unconfirmed either way. If Glowy's own pitch is built on a specific licensed CV vendor, that may itself be a point of differentiation (or a point of parity) worth confirming against these four directly, since none could be confirmed as using the same vendor.
- Traction ranking (rough, review-count proxy only): OnSkin > MDacne > Skin Bliss > Skinive. This should be treated as a directional signal only, since review counts reflect different review-prompt strategies, store/region mixes, and app age, not necessarily current MAU.

### Gaps
- No app in the set could be confirmed to use Haut.AI or Perfect Corp specifically (or any other named third-party CV vendor) — this remains an open question for all four.
- Could not obtain unified, same-date, same-store (e.g., all-US-iOS) rating/review snapshots for all four apps; the figures compared above come from different aggregators, different store regions, and possibly different capture dates, which limits precision of the traction comparison.
- No current downloads/MAU estimates (e.g., from Sensor Tower or data.ai) could be retrieved for any of the four apps within the research budget — all scale claims are either company-reported usage stats (Skinive's "3M risk assessments," MDacne's "4M users") or install proxies from a single storefront (Skin Bliss's ~1M Google Play installs), not independently verified download totals.
