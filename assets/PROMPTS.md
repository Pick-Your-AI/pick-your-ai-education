# Generated asset provenance

## assets/icon.png
- Date: 2026-10-30
- Tool and model: Codex CLI 0.164.0 / built-in image_gen (session 01a18b6c-86db-7d81-9b9a-c4273f67affd)
- Seed: not supported
- Reference images: none
- Prompt:

```text
Use your image generation capability to create ONE image. Do not modify any other files.

Create one square 1024 x 1024 px (1:1) image of a single repository icon glyph.
Use a simple geometric silhouette with a crisp solid outline and one accent spark.
Background: a perfectly flat, untextured, uniform solid #F0FDFA fill (a single flat colour, no tint variation), with no floor, grid, gradient, vignette or glow touching the edges. Keep the glyph inside the central 688 x 688 px square, with at least 10% empty margin on all sides.

GLYPH: Open book with rising learning path. A simple geometric open book seen from the front, two flat pages meeting at a centre spine. From the spine a short staircase of three ascending square steps rises up and to the right above the pages, like a learning path. Thin even outline strokes only, no fill except the spark. The glyph is about 600 to 660 px on each side.
SPARK PLACEMENT: a single small four-point spark sitting on the top corner of the highest step.
PALETTE (use only these colors): outline #0F766E, one spark in #FBBF24, background #F0FDFA. The spark is the only filled shape and the only element in #FBBF24.
Style: flat clean vector look with solid flat colour fills only, even stroke weight, calm and uncluttered. No glow, no blur, no gradients, no shading, no texture, no noise.

NEGATIVES: no text, letters, numbers, words, labels, symbols, signatures, watermarks, logos or brand marks; the book pages stay blank with no lines of writing. No people, faces or hands. No photorealism, no 3D scene, no platform, no shadow on a floor, no extra objects, no clutter, no third-party IP.
```

- Candidates: 2 attempts (attempt 1, session 01a18b6b-aeaa-73b1-b3d4-d9978723826c, rejected: glow made the normalized PNG 558 KB, over the 300 KB budget); selected: attempt 2 (reason: flat teal outline, one amber spark, blank pages, no text, passes icon QA)
- Post-processing: showcase.py 1.0.0 content icon normalize --ground transparent (auto mode kept the pale ground as an opaque tile and broke the byte budget); output sha256 bd5965ef7860310f7787ba440c7046337daf0c1ca78072e13d6d506d4525d2a9; 121.7 KB
