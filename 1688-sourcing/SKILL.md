---
name: 1688-sourcing
description: Thorough factory/supplier research on 1688.com from a reference product image or description. Use whenever the user wants to find suppliers, factories, manufacturers or wholesale sources on 1688 (or Alibaba China), compare suppliers, or source a product "like this one". Treats the reference image as a description of a product CATEGORY to survey broadly, not as an exact item to find by image search.
---

# 1688 Sourcing Research

The user wants to find the **best factories for a type of product**, not to track down the
seller of one listing. A reference image shows what *kind* of product they want. Your job is
to understand that category, survey the whole market for it on 1688, and recommend the
strongest manufacturers, with evidence.

Never contact sellers, start chats, add to cart, or place orders. Read pages only.
If 1688 shows a login wall or a slider captcha, stop and ask the user to deal with it,
then continue.

Work through the phases in order. Don't skip ahead to a table after a handful of searches.

---

## Phase 0 — Brief (ask before searching)

If the project instructions or conversation don't already answer these, ask in **one**
message (offer sensible defaults so the user can just say "defaults are fine"):

1. Target market / where it will be sold (affects certifications: EU → LFGB/EU 1935/2004,
   US → FDA/Prop 65, etc.)
2. Order quantity for the first order and later (e.g. 300 sets now, 2,000/month later)
3. Target landed cost or price band per unit
4. Must-haves vs nice-to-haves (material, coating, induction, colours, piece counts)
5. Branding needs: logo on product, custom colour, custom packaging, private-label manual
6. What matters most: price / quality / low MOQ / customisation / speed

Write the answers back as a short "Sourcing brief" and use it as the scoring basis.

## Phase 1 — Understand the product (from the image)

Study the reference image(s) and write a **Product spec** before searching:

- **Category & concept** — what it is in plain words and in the Chinese trade term(s)
  (e.g. detachable-handle stackable cookware = 可拆卸手柄锅具 / 叠叠锅 / 可拆把手锅).
- **Defining features** — the things that make a product "the same kind" (e.g. removable
  handle, nesting/stacking, oven-safe without handle).
- **Variable attributes** — things that can differ while still being similar: material,
  coating, colour, piece count, sizes, lid type, handle mechanism, induction base.
- **Quality signals visible in the image** — wall thickness, weights, die-cast vs pressed,
  lid quality, finish.
- **Reference price** — if the image shows a price, note it as a retail/single-unit anchor.

Then define **"similar enough"**: products with all defining features count, whatever the
variable attributes are. Note which variants the user would most likely want, and look at
the rest too.

Read `references/category-notes.md` if the product is cookware.

## Phase 2 — Search plan (go wide)

Build a keyword matrix and write it out before running it:

- **Core terms** — 3–5 Chinese names for the category.
- **Core term × material** — e.g. 压铸铝, 锻打铝, 不锈钢, 复合底, 陶瓷, 麦饭石/石纹, 钛.
- **Core term × configuration** — piece counts (4/5/7/9/10/13/15/17件套), single pieces.
- **Core term × positioning** — 源头工厂, 工厂直销, 跨境专供, 外贸, OEM 定制, 出口.
- **Image search (以图搜图)** — use it as **one** input among many, never the only one.

Run searches in **both**:
- the normal product search (商品), and
- the factory search (找工厂 / 源头工厂 tab), filtering by region where possible.

Also look at the main industrial clusters for the category (see the reference file) and
search each cluster by name + category.

For each search, sort by relevance first, then by sales (销量). Scroll at least 2–3 pages.
Record every relevant **supplier** (not just listings) in a running longlist.

**Coverage target:** aim for a longlist of **30–50 distinct suppliers**. If you have fewer
than 20, keep searching with new keywords before moving on. Report how many searches you
ran and how many suppliers you saw.

## Phase 3 — Screen the longlist (quick pass)

For each supplier, from the search card / hover card / shop header, capture:
shop name, link, city, years on 1688, badges (超级工厂, 实力商家, 源头工厂, 深度验厂,
验厂报告, 全球供, 跨境), 回头率, review count/score, price range, and whether they
actually sell a matching product.

**Factory vs trading-company signals** (record which apply):
- Factory: 验厂报告 / 深度验厂 with photos of their own die-casting, coating or stamping
  lines; stated plant area & headcount; narrow product range; city = known cluster;
  certifications in the company's own name; OEM for named brands.
- Trader: hundreds of unrelated categories; no production photos; 贸易/商贸 in the name
  with no inspection report; same product photos as many other shops.

Drop: obvious traders, shops with no matching product, and very low scores with many
reviews. Keep a short note on **why** each was dropped. Don't drop a supplier just because
it has no badge — mark it "unbadged" and decide in Phase 4 if it looks strong.

Shortlist **12–15** suppliers for a deep dive, covering a spread: top factories, a few
budget options, and anything with unusual strengths (e.g. fluorine-free coating, brand
OEM history, own handle design).

## Phase 4 — Deep dive on each shortlisted supplier

Open the **company/factory profile** (公司档案 / 工厂档案 / 验厂报告), not only the listing.
For each, collect:

**Company**
- Legal name, city, year founded, years on 1688
- Plant area, employees, production lines, annual output (from the inspection report)
- Which processes are in-house (e.g. die-casting, coating, handle moulding, assembly)
- Brands they OEM for, export markets, trade-show participation if shown

**Product** (1–3 best-matching listings per supplier)
- Listing links, materials, coating type & brand (e.g. Whitford, ILAG, Daikin, generic
  water-based), thickness / weights, induction compatibility, oven temperature, handle
  mechanism (button vs clamp), lid type, colours, piece-count options
- **Price tiers** at each quantity break (阶梯价), and the single-unit price
- MOQ, sample policy, stated lead time / delivery days, packaging included
- OEM/ODM: logo method (laser, print, sticker), custom colour MOQ, custom box MOQ and cost

**Evidence**
- Certifications and test reports — note **whose name** is on them and whether they are
  for this product or just the company (ISO 9001 ≠ food-contact test)
- Read the **negative and mid reviews** (差评/中评) and summarise recurring complaints
  (coating peeling, handle loose, dents, shipping damage, wrong colour)
- Note any contradictions (e.g. image says die-cast aluminium, spec table says iron)

Mark each data point as **verified on page**, **claimed in image/marketing**, or **not
found**. Don't fill gaps with guesses.

## Phase 5 — Score and compare

Score each shortlisted supplier 1–5 on:

| Criterion | Default weight |
|---|---|
| Manufacturer credibility (in-house production, inspection report, years, scale) | 25% |
| Product match & quality signals (spec, coating, weights, reviews) | 25% |
| Price at the user's quantity | 20% |
| Compliance evidence for the target market | 15% |
| OEM / customisation fit and MOQ | 15% |

Adjust weights to match "what matters most" from the brief, and say what you used.

## Phase 6 — Deliverables

1. **Executive summary** — 5–8 lines: market overview (typical price bands, where the
   factories are, what separates good from bad), and your top picks.
2. **Recommendations by need** — Best overall, Best value, Best premium/export-ready,
   Best for small MOQ / testing, Best for custom branding. One supplier can win more than
   one; explain each pick with evidence.
3. **Comparison table** of the shortlist (all fields from Phase 4, plus scores).
4. **Full longlist** as an appendix: every supplier seen, with the reason it was kept or
   dropped.
5. **Spreadsheet** — also produce the shortlist and longlist as an .xlsx or .csv file if
   file creation is available.
6. **Red flags & risks** — contradictions, missing certifications, review complaints.
7. **Next steps** — for the top 3–5, a ready-to-send inquiry message **in Chinese** (with
   an English translation) asking for: price at the user's quantities, sample cost and
   shipping, lead time, coating brand, food-contact test reports for the target market,
   custom logo/colour/packaging MOQs, and factory photos/video. The user sends these
   themselves.
8. **Method & coverage** — keywords used, number of searches, suppliers seen, limits
   (e.g. pages that wouldn't load, data you couldn't confirm).

## Quality bar

Before you finish, check:
- Did you treat the image as a category, and include similar products, not just copies?
- Longlist ≥ 30 suppliers (or explain why the market is smaller)?
- Did you open factory profiles / inspection reports, not just listings?
- Did you get quantity price tiers or clearly note there were none?
- Did you read negative reviews for the shortlist?
- Is every claim either verified, marked as marketing, or marked not found?
- Did you avoid contacting sellers or ordering?
