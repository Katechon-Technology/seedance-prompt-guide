# Keeping an AI character consistent across videos

How we keep Malfoid, her two friends and a low-poly banker looking like themselves across dozens of separate AI video generations, and what broke when we did not.

Web version: <https://cast.katechon.technology/guides/ai-character-consistency>. Last updated 2026-10-17.

## 1. One master picture and one master description

Each character has a single reference image and a written description that never changes: hair, face, outfit, then personality. Both go into every generation. In Cast, a character you make gets four Midjourney looks (15 credits as of 2026-10-18); the one you tap becomes the reference for every later video.

## 2. Generate the first frame, then animate it

A video model that starts from your still keeps the face far better than one that only gets a text description. For our explainer [Penny](../prompts/penny-bank.md), 31 separate clips each started from a frame painted off the same master image; the style sentence lived in the image prompt, and the video prompt described only motion. The result reads as one character across 82 seconds.

## 3. Describe every extra character explicitly

When a frame is derived from an earlier one, secondary characters drift: in one batch the two friends lost their skin tones and hair. The fix was to restate each friend's hair, skin and expression in every frame prompt, and to pass each one's own reference image. Cast does this by sending every cast member's picture and description as numbered references (`@image1`, `@image2`…) in the same order every time.

## 4. Lock the face when the look changes

For a photo set where we wanted a new style, Midjourney set the look and an image-edit model then face-locked each pick to the master face. Generating straight from the reference images gave the most on-model faces, which mattered most in group shots.

## 5. Change outfits on purpose, not by accident

Write the outfit into the prompt for every video, even when it is the default. Our dance videos use "off-duty" looks written out in full; when the outfit is left to the model, it drifts.

## 6. Do not design a celebrity

A character whose face resembles a famous actor gets blocked by the video model's copyright filter, after the render, over and over. Redesigning the face is the only fix that worked for us, and then every earlier video with that character has to be re-rendered to stay consistent. Design original faces from the start.

## 7. Give each character a signature

Consistency is also behaviour. Malfoid always says "Obviously", Thea is always half a step off, Odette never changes expression. Viewers recognise those faster than a face.

Examples: [Own It](../prompts/own-it.md), [Penny](../prompts/penny-bank.md), [Pure Gold](../prompts/pure-gold.md).

---

License: [CC BY 4.0](../LICENSE). Attribution: Katechon, <https://cast.katechon.technology/guides/ai-character-consistency>.
