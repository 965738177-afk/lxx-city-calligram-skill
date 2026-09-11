Skill is valid!
---
name: lxx-city-calligram-skill
description: Transform city photographs into editorial calligram posters or cohesive city cultural-product concepts, including colorful DIY, souvenir, stationery, and food-product visuals. Use for city calligrams, typographic travel posters, or city merch concept requests.
---

# LXX City Calligram Skill

Create one standalone poster per source photograph. Use image generation or image editing tools that accept reference images; do not substitute a text-only prompt when the user expects finished images.

## Resolve the city first

Use the city explicitly named by the user. If none is given, accept a city only when a legible sign or unmistakable landmark identifies it reliably. Otherwise pause and ask: **“这是哪个城市？”** Never silently guess from architecture, vegetation, filenames, metadata, or general atmosphere.

Convert the confirmed city to its standard English name. Preserve the user's preferred romanization when supplied. Use that city name as the dominant repeated word in the calligram.

## Derive the supporting word set

Inspect each photo independently and identify:

- the main recognizable subject or structure;
- the setting and activity;
- visible natural elements, season, light, color, and mood;
- a small number of location-relevant concepts.

Translate these into 6–12 short, natural English words. Prefer concrete subject words over generic slogans. For example, a lakeside kayak scene may yield `KAYAK`, `WATER`, `RIPPLE`, `SUMMER`, `COLOR`, `WEEKEND`, and `SHORE`; a convention center may yield `ARCHITECTURE`, `CROWN`, `EXPO`, `CITY`, `LIGHT`, and `LANDMARK`.

Do not invent facts, event names, venue names, brands, or sentimental claims not supported by the image or user. Avoid meaningless pseudo-English. Keep all large and medium display words correctly spelled. Dense microtype may repeat the confirmed city and the approved supporting words.

## Build the poster

- Use a 3:4 vertical canvas split into two equal-height 1:1 panels.
- Upper panel: preserve the original photograph's subject, viewpoint, proportions, natural texture, lighting logic, and recognizable details. Allow only restrained editorial color refinement. Do not redraw or replace people, faces, vehicles, architecture, signage, or other important content.
- Lower panel: use a warm off-white paper field with generous negative space. Reconstruct only the photograph's most recognizable subject, outline, perspective, gesture, and material rhythm using typography as the actual drawing medium.
- Use large words for the structural skeleton, medium words for planes and contours, dense small words for shadows and texture, and sparse fading words or particles at edges.
- Make the confirmed city name the visual anchor and roughly 40–60% of readable text. Distribute it through both structural and textural layers without monotonous mechanical repetition.
- Let the derived subject words shape the relevant components. Typography must carry form, not sit on top of a conventional illustration.
- Use two to four colors sampled from the source photo. Keep the paper background warm, clean, and lightly tactile.
- Add only restrained editorial microcopy or a handwritten accent when it improves balance. Do not add Chinese text, logos, app UI, watermarks, borders, or unrelated slogans unless requested.

When processing multiple photos, generate separate outputs and vary the lower composition around each image's subject rather than cloning one layout.

## City cultural-product mode

Use this mode when the user wants a city visual system extended into merchandise, souvenirs, colorful handmade DIY, or a small tourism product collection. Confirm the city with the same rule above before generating any city name, landmark label, or map reference.

Treat the photo's main landmark, creature, plant, waterfront, architecture, or activity as the product's recognizable form. Extract a limited color palette from the photo, then simplify it into 3–5 bold, manufacturable colors. Keep one consistent city identity across a series rather than applying unrelated graphics to arbitrary goods.

Choose only the products that fit the subject and the user's purpose. Useful product families include:

- **Collectible souvenirs:** raised PVC, acrylic, ceramic, metal, or wood refrigerator magnets; enamel pins; keychains; bag charms; miniature landmark figurines; coasters.
- **Paper and sticker goods:** postcards, stamp sheets, vinyl stickers, sticker packs, washi tape, mini maps, notebooks, bookmarks, luggage tags, collectible city cards.
- **Colorful DIY:** paint-your-own blank figurines, layered wooden plaques, color-by-number postcards, miniature diorama kits, simple screen-print or rub-on transfer kits. Show a restrained palette, paint pots, and an achievable before/after result when relevant.
- **Food and seasonal concepts:** molded ice pops, ice-cream wrappers, cookie tins, beverage cups, and picnic packaging. Use these as visual concepts only; do not make food-safety, ingredient, or commercial availability claims.
- **Everyday lifestyle goods:** canvas totes, T-shirts, caps, mugs, bottles, umbrellas, phone grips, desk calendars, and small storage pouches.

Favor high-readability silhouettes and a small number of construction layers. For physical mockups, make material, thickness, attachment, and edges believable: magnets need a visible magnet/backing; pins need metal outlines or a pin back; acrylic needs clean cut edges; molded ice pops need a stick and realistic frozen texture; DIY kits need separable parts and a limited number of colors.

For a product series, first define a compact design system: confirmed city name, one hero landmark or motif, 3–5 colors, one line style, and one type style. Then create one product or one coherent product set at a time. Avoid unreadable microtext, copied brand marks, and packaging that imitates a real brand.

### Cultural-product prompt scaffold

```text
Use case: product-mockup
Asset type: city cultural-product concept / product series
Confirmed city: <CITY>
Hero landmark or motif: <SUBJECT>
Product(s): <SELECTED PRODUCT TYPE(S)>
Image-derived color palette: <3–5 COLORS>

Design a cohesive, manufacturable city cultural-product concept. Turn the hero landmark or motif into the recognizable product silhouette or graphic system. Keep “<CITY>” correctly spelled as the primary location label, and use only short image-derived supporting words. Use the selected palette consistently across every item. Show realistic materials, construction, thickness, edges, fastening, and scale.

For DIY items, include an achievable limited-color process and a finished colorful result. For an ice pop or food-themed concept, show an original molded form and packaging without copying any real brand. Use clean editorial product photography or a premium retail presentation, with no watermarks, no UI, no invented official claims, and no copyrighted logos.
```

## Image-generation prompt scaffold

Adapt this scaffold to the selected image tool and the actual photo:

```text
Use case: style-transfer
Asset type: standalone premium 3:4 vertical city calligram poster
Input image: source photo to preserve and transform
Confirmed city: <CITY>
Primary subject: <SUBJECT>
Supporting English words: <6–12 IMAGE-DERIVED WORDS>

Create exactly two equal-height square panels stacked vertically. In the upper panel, preserve the source photograph faithfully: the same subject, camera angle, geometry, people, objects, natural texture, lighting logic, and original atmosphere, with only restrained editorial color refinement.

In the lower panel, reconstruct the main subject on warm off-white paper entirely from English typography. Use “<CITY>” as the dominant repeated anchor word. Use the supporting words only where their meanings correspond to visible parts, activity, light, setting, or mood. Larger words define the skeleton and main silhouette; medium words define planes and contours; dense microtype creates shadow and texture; sparse words dissolve at the edges. The lower image must clearly match the upper subject's silhouette, perspective, rhythm, and key features. Typography is the illustration, not decoration over a normal drawing.

Use two to four colors sampled from the photo, intentional negative space, asymmetric editorial balance, crisp display words, subtle paper grain, and a sophisticated independent travel-magazine aesthetic.

Constraints: one source photo per poster; no collage of multiple sources; no Chinese text unless requested; no invented venue or brand names; no meaningless pseudo-English; no UI, logo, border, or watermark; do not alter identity-sensitive or landmark-defining details in the upper panel.
```

## Check before delivery

Confirm that the city is correct, the main city word is spelled correctly, the two panels are equal, the upper photo remains recognizably faithful, the lower silhouette matches the actual subject, and every prominent supporting word is grounded in the image. If a prominent word is malformed or the upper panel changes a defining sign, face, landmark, or object, regenerate with that single failure called out explicitly.
