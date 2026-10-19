# Royal Henna by Neha — handoff at ~60%

**Live:** https://10elizabethbell.github.io/royalHennaByNeha/ · **Repo:** https://github.com/10elizabethbell/royalHennaByNeha · **Built:** 2026-10-18 from Muse brief (run 2026-10-19, FB group posts 2026-10-18)

## What's built
- **World:** henna on skin. The page ground is warm skin (#d6a476); wine (#4a1131) and rani pink (#a3205a) bands come from her flyer; marigold is the hover accent.
- **Signature (hero):** a henna cone pipes a mandala in wet, glossy paste by itself. When it's finished, the paste dries and crumbles off in a sweep (little falling crumbs), and the stain deepens from fresh orange to maroon, holds, then fades for the next design (3 variants rotate). Visitors pipe their own paste with a finger or mouse: up, down, sideways. Their lines dry and stain the same way. The cone pauses while they draw and carries on 2.5s after.
- **Carried everywhere:** every section boundary is a scalloped skin "cuff" with a henna lace border that the same cone draws when it scrolls into view, then stains and keeps.
- **Sections:** header (wordmark + 313 number top-right) · hero (headline, promise, Book on WhatsApp + Plan your henna) · All occasions accepted (8 tappable rows, each opens WhatsApp pre-filled for that occasion) · How booking works + Where I go · See my work (big Instagram link) · Plan your henna form · close · footer.
- **Contact:** WhatsApp `wa.me/17324987248` with pre-filled messages. The form writes occasion, date, town, headcount, name and notes into a WhatsApp message, with a quiet "send as a regular text" fallback to 313-979-6757. Tap-to-call 313 in the header, the close and the footer. No email anywhere (none exists).
- Tunables are named at the top of the henna script (`T`: speeds, dry/stain/hold/fade times, line widths).

## Assumptions I made
- **WhatsApp as the primary action:** the flyer prints it explicitly; 313 is printed "for booking", so it's the header call number and the SMS fallback. *Whether 313 takes texts isn't confirmed.*
- **"I come to you" / "I bring everything and draw at your home or venue":** inferred from Muse's "mobile event beauty service" and the NJ/NYC/Philly/PA area. No address is shown anywhere.
- **"Send me pictures of designs you love, or let me suggest some":** inferred (normal for henna artists), not stated by her.
- **Single artist, first person, named Neha:** from the brand name; not confirmed she's the owner.
- **Colors:** the IG profile picture (her flyer) is cream, henna-brown and black serif; Muse reported pink/red/purple. I used rani pink and wine for the bands and skin as the ground, and kept the serif lettering.
- **Headline "Henna worth showing off." and close "Hands are in every photo from the day…":** my copy.
- **Fonts:** system stack (house rule); headings use the system serif (Iowan/Palatino/Georgia) to echo the "ROYAL" serif on her flyer.

## Placeholders and gaps
- **No work photos.** Facebook posts are a video and Instagram needs a login. The "See my work" band is just the Instagram link for now; it's built to take a photo row above the link.
- **No logo:** the favicon and home-screen icon are an "R" in the site's serif (wine/marigold).
- **No Facebook page found** (posts come from a "Royal HennaArtist" profile in groups), so there's no Facebook link. The "see more of my work" link goes to Instagram (verified live 2026-10-18: 631 posts).
- No hours, prices, reviews, years in business, or email: nothing about them on the page.

## Questions for the owner
- Can 313-979-6757 take texts, or should everything go to WhatsApp?
- Is "I come to you" right? Does she travel to venues/homes? Any travel fee or minimum?
- 6–10 of her favourite photos (bridal full hands, simple guest designs, tattoos) for the work band.
- Does she use natural henna (no PPD/"black henna")? That's a strong trust line if true.
- Aftercare tips, typical stain timeline, and bridal vs guest pricing ("starting at") if she wants them published.
- Her Facebook page URL, if she has one.

## Ideas not built (yours to pick)
- **Runner-up world:** mehndi night: marigold garlands and string lights on rani pink, with petals you can scatter.
- A hand outline for the hero (pipe onto a palm instead of open skin); paisley + vine designs in rotation alongside the mandalas.
- Work photos framed as stained "hand" cards, with the lace edge around each.
- Small reward: a henna dot blooms on the chip you pick in the form.
- A real display face (self-hosted) for the headings, if you want more personality than the system serif.
- Instagram embed of her latest posts (needs her account / a token).

## Open from the finish review
- **Phone first screen shows only the top half of the mandala** at Facebook in-app height (390x664): the centre sits just above the fold. I kept the headline, promise and 56px buttons at full size rather than shrink them. Options: cap the mandala radius on short screens (below ~720px tall), or accept it as an invitation to scroll.
- Impeccable finish review: 2 rounds; 7 of 8 material fixes resolved, the one above is partial, and the one regression found (SMS fallback link centred) is fixed. Full mode sweep (critique, audit, polish, bolder, quieter, distill, harden, animate, colorize, typeset, layout, delight, overdrive, clarify, adapt, optimize) applied. Declined only where a house rule wins (webfont, touch-action pan-y on the stage, hero call button, invented trust content).
- Detector: clean; one `cramped-padding` false positive suppressed for index.html in `.impeccable/config.json` (sections pad via `.wrap`).

## Not verified
- Real-device touch drawing (iOS Safari, Android Chrome, Facebook in-app browser); `getCoalescedEvents` smoothness.
- WhatsApp/SMS handoff on real phones (iOS `sms:?&body=` form used).
- Frame rate on older phones (hero is ~2.5–5k segments redrawn per frame plus up to 5 edge canvases while they draw).
