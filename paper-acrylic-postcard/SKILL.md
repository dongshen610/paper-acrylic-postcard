---
name: paper-acrylic-postcard
description: Turn an uploaded lifestyle photo into a horizontal 3:2 collectible postcard that combines the unchanged original photograph with a smaller irregular paper-textured acrylic illustration, Chinese numbering, one restrained caption, a divider, and exactly three color swatches. Use when users ask for a paper-acrylic postcard, photo-plus-illustration keepsake, minimalist painted photo card, or continuation/editing of this numbered postcard series.
---

# Paper Acrylic Postcard

Create one finished raster postcard from each supplied photograph. Use the built-in image generation/editing tool; do not replace the requested bitmap artwork with HTML, SVG, or a text-only prompt.

## Required reference

Read [references/full-prompt.md](references/full-prompt.md) completely before generating or editing a postcard. Treat it as the visual specification and acceptance checklist.

## Workflow

1. Inspect the supplied photo and determine whether it is portrait or landscape.
2. Identify the most memorable subject, action, relationship, silhouettes, object, and emotion. Remove unrelated background detail from the illustration only.
3. Choose the next three-digit number. Continue an existing series when prior numbered works are present; otherwise begin at `001`.
4. Write one natural Chinese caption of 12–20 Chinese characters based on the actual photo. Keep it warm, restrained, specific, and on one line.
5. Generate a horizontal 3:2 postcard:
   - Keep the original photo photographic, clear, and recognizable.
   - Use a left-photo/right-illustration layout for portrait photos.
   - Use a top-photo/bottom-illustration layout for landscape photos.
   - Make the illustration a smaller emotional echo, not a competing image. Target 60–70% of the photo's visible area and leave substantial paper around it.
   - Form the illustration with irregular dry-brush acrylic edges and no rectangular painted background.
   - Use no more than four main illustration colors.
   - Place a thin divider below the illustration. Under it, align the number, caption, and exactly three swatches on one baseline and to the same total width.
6. Inspect the result before delivery. If the illustration is oversized, the photo is repainted, the information row is misplaced, Chinese text is wrong, or extra text appears, perform one targeted edit and recheck.
7. Save non-destructively. Report the final path and caption.

## Invariants

- Preserve identities, faces, expressions, poses, clothes, and key objects in the original photo.
- Never upload or reveal credentials, tokens, private metadata, or unrelated user files.
- Do not add English, dates, locations, names, logos, watermarks, titles, or extra symbols.
- Do not add people or objects absent from the source.
- Keep the photograph visually dominant and the acrylic illustration refined, smaller, and surrounded by negative space.
- Keep only the number, one Chinese caption, and three swatches as textual/information elements.

## Editing an existing postcard

When the user asks for a scale or layout adjustment, edit the supplied finished postcard rather than regenerating from the raw photo. Lock the photo and all approved content. Change only the named layout property. For the approved refined proportion, reduce an oversized illustration by about 10–12%, keep it substantial, and shorten/reflow the divider and information row to match.
