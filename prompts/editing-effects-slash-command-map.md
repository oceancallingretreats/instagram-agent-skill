# Ocean Calling — real slash-command definitions

This file maps **50 command names** to editing instructions. The commands are *native Claude Code project commands* only after installing the `.claude/commands/*.md` files from the downloadable command package. In ordinary ChatGPT, the names are shorthand interpreted through a Custom GPT or chat instructions, **not native registered slash commands**. The local `effects.py` dispatcher renders seven simple effects on still images; all other commands return a rendering instruction for an image editor. This file does not itself install or execute any effect.

## Command names

- `/outline` — Add a loose hand-drawn white outline around [subject] without obscuring details.
- `/arrows` — Draw three sketched arrows pointing to [feature] with clear anatomy.
- `/scribble` — Add energetic scribbles behind [subject], not in front of it.
- `/stars` — Surround [subject] with small drawn stars and sparkles in [brand accent].
- `/hearts` — Add tasteful hand-drawn hearts near [subject] while keeping faces clear.
- `/circles` — Mark [specific fact] with an uneven marker circle and emphasis ticks.
- `/dotted-path` — Draw a dotted motion trail following [animal or object] through the image.
- `/sticker-notes` — Add two empty torn-paper sticker labels for verified educational text later.
- `/mini-diagrams` — Create small annotation arrows and blank label tabs without inventing anatomy.
- `/mixed-doodle-collage` — Combine restrained hand-drawn arrows, white outline, tiny sparkles and one sticker.
- `/cinematic` — Apply subtle cinematic color grading with realistic contrast and natural marine colors.
- `/vintage-film` — Give the image a subtle vintage-film aesthetic with fine grain and faded shadows.
- `/editorial` — Frame [subject] as a high-end lifestyle editorial with ample negative space.
- `/golden-hour` — Give the scene believable warm golden-hour ambient lighting.
- `/dreamy` — Add soft diffused dreamy highlights without removing relevant detail.
- `/flash-photo` — Create a realistic direct-flash-camera aesthetic with sharp texture.
- `/polaroid` — Place the photo inside a slightly tilted blank Polaroid-style white frame.
- `/scrapbook` — Build a restrained scrapbook treatment with textured paper and decorative tape.
- `/moody-outdoors` — Create moody natural outdoor lighting, retaining realistic greens and blues.
- `/summer-travel` — Use an airy sunlit summer travel-diary style with natural skin and ocean colors.
- `/mood-board` — Build a four-image moodboard from [uploaded photos] with consistent gutters.
- `/photo-grid` — Arrange four photos into a simple 2x2 grid with subtle borders.
- `/scrapbook-carousel` — Create a layered scrapbook collage with photographic prints and taped corners.
- `/film-strip` — Arrange three photos as a consistent vertical vintage filmstrip.
- `/before-after` — Make a balanced before-and-after layout with matching subject scale.
- `/travel-journal` — Create an editorial travel-journal page using [destination photos].
- `/polaroid-stack` — Stack three tilted Polaroid-style prints with natural overlapping shadows.
- `/editorial-spread` — Make an asymmetric magazine spread with one dominant hero image.
- `/torn-paper-montage` — Combine photos as a realistic torn-paper montage with all subjects visible.
- `/carousel-cover` — Design a polished vertical 4:5 first-slide cover with a text-safe hero image.
- `/remove-background` — Precisely remove the background from [subject], preserving realistic edges.
- `/neutral-studio` — Replace the background with a warm neutral photography studio.
- `/beach-lifestyle` — Place [product] in realistic coastal lifestyle surroundings with correct shadows.
- `/underwater-environment` — Use an ecologically plausible underwater environment for [species] and realistic scale.
- `/minimal-gradient` — Replace only the background with a two-tone brand-color gradient.
- `/texture-backdrop` — Use a tactile linen, stone or sand texture behind the unchanged product.
- `/sunlit-window` — Introduce soft plausible window light in a minimal indoor backdrop.
- `/nature-setting` — Place [subject] into an appropriate natural outdoor habitat with matching perspective.
- `/color-swap` — Change only the background to [HEX code] without recoloring the subject.
- `/depth-of-field` — Keep [subject] sharp and subtly soften the existing background focus.
- `/add` — Add [object] at [position] using realistic scale, perspective and shadows.
- `/remove` — Remove [object] and reconstruct the original background behind it.
- `/replace` — Replace [object A] with [object B] without changing anything else.
- `/expand` — Outpaint the original image to [9:16 or 4:5] with plausible continuation.
- `/reposition` — Reposition [subject] to [left/right] to create a clean caption-safe area.
- `/product-levitation` — Make [product] appear to float just above the surface with plausible shadow.
- `/duplicate` — Duplicate [product] into a neat repeated arrangement, matching perspective.
- `/flat-lay` — Rearrange [items] into an overhead magazine-style flat-lay on [surface].
- `/composite` — Composite [subject from photo A] into [setting B] with consistent scale and lighting.
- `/hero-close-up` — Recompose to focus attention on [detail] while preserving accurate texture.

## Usage

Claude Code: install the package `.claude/commands/` into a project and enter `/outline` with an image in context. ChatGPT: configure a custom GPT with the mapping and use `/outline` as chat shorthand. WSL: `python3 effects.py /outline input.jpg -o output.png`. The original reel editing script will need integration for automatic video application.

## Accuracy

The source screenshots are too small to transcribe the original editor command labels reliably; these are newly defined command names tied to the previously saved 50 descriptions.
