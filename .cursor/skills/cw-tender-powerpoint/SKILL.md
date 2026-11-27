---
name: cw-tender-powerpoint
description: Use when making or editing 創威電子系統有限公司 (Chong Wai / CW) tender or sales security-system PowerPoint decks, including reusable Sales templates, product-page swaps from uploaded catalogs, new product pages, and layout fixes.
---

# CW tender / sales PowerPoint

## Platform and start file

- If the user named PowerPoint, Google Slides, or another slides app, use that. If they attached a `.pptx`, use PowerPoint. If they did not name a platform and did not attach a deck, ask before building.
- Prefer the file they attached or named. A reusable Sales template is typically named `CW_Security_Solution_Sales_Template.pptx` (an `OfficeCompat` variant is often easier to open in Microsoft PowerPoint or WPS). Site-specific decks are edits of that template, not a new visual family.
- Follow the Cursor-managed `slides` skill for the deck workflow (`edit` for an existing deck; `new-template` when starting from the Sales template). Do not build or edit slides in the parent turn; the `knowledgeWork` child does the slide work.
- Deliver an editable `.pptx` (or Google Slides if they asked). Use an ASCII filename when sharing; Chinese filenames can fail on WhatsApp, email, or older Windows.

## Language, naming, and look

- All slide text, captions, tables, and speaker notes: formal written Traditional Chinese (繁體書面語). Never colloquial Cantonese (for example 我哋、唔使、睇、咪高峰).
- Always write the company name in full as 創威電子系統有限公司, including on awards.
- BA = Burglar Alarm（防盜）, not Building Automation. AC = Access Control（門禁）, not Air Conditioning.
- Use CW brand colours `#ED1B24` and `#2E3192`.
- Follow the 大眾安全 visual style and layouts, not CW’s older look. Use plenty of real photographs on key slides, not AI-drawn images. Company pages (公司簡介, 牌照, 獎項, 案例) must use CW’s own real photos. Long text is fine only when every line is a key point, with key phrases in red bold. The deck must not look AI-made.
- Keep the company-background section short (about 4 pages). A corporate-structure page may use CW’s org-chart PDF directly. Company introduction may be copied from the company profile. Keep cover, divider, and closing slides simple; keep references, situation/proposal, scope, timeline, and maintenance pages detailed.
- Keep the theme font names already in the deck (typically Microsoft JhengHei, Arial, Times New Roman), even if a Linux preview falls back to other fonts. They display correctly in Windows PowerPoint.

## Slide rules

- No overlapping text or shapes. Double-check tables against footers and banners.
- Do not mark product 型號, model numbers, or order codes on slides, captions, or tables. Use family or feature names only. Models and order codes may go in speaker notes only.
- For lists such as 系統類別, use center-line symmetry so the `|` column aligns vertically (tag on the left, Chinese name on the right), not a left-ragged list.
- Product facts and photos must come only from the catalogs or sources provided for that job. Do not invent specifications or carry over leftover specs from an older product on the same slide (wrong brand, range, WDR, storage, and similar).
- Every photo must visibly show the item the nearby text describes. Camera photos should show the camera body, not a full datasheet page. Barrier or gate photos should show the actual equipment described (for a straight-arm barrier, the cabinet/machine together with the arm; with LPR, the camera as well).
- Job references（過往項目）must match that tender’s ELV systems and site type. Tag references by system and pick the closest matches. Put references managed by the same property-management company as the tender site first. Favour well-known Hong Kong brand clients (for example MTR) when they fit.
- Timeline slides need a short caption under each milestone saying what it is, not only a date or name.
- In `[Content_Types].xml`, the jpg default must be `image/jpeg`, not `image/jpg`.

## Product swaps and new product pages

When the user wants to change or add a product from an uploaded datasheet:

- Extract official packshots from that catalog (product on a clean background). Do not use a full-page crop that includes surrounding datasheet text.
- Update related overview and checklist wording when the product line changes.
- If inserting a new page, place it in the right system order, shift later slides, and fix footer page numbers. Add the item to the system overview list and the combination checklist in page order.
- Typical quotation system order: CCTV first, then BA（外圍／防盜偵測）.
- Crowding details (for example an optional lens size) may stay in speaker notes rather than on the slide.
- Do not rewrite unrelated slides. Leave cover project/customer/sales fields unless the user asked to change them.

## What not to publish

- Never commit API keys, secrets, or credentials.
- Do not put vendor catalog PDFs, or a filled customer deck with contact details or client-logo walls, into a public repository.
