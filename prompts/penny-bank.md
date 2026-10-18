# Penny explains how to build a bank from scratch

> An 82-second money explainer: Penny, a low-poly banker, goes from gold under the mattress to deposits, paper money and interest.

| | |
|---|---|
| Format | Explainer |
| Length | 82 s, vertical 9:16 |
| Model | 31 Seedance 2.0 Fast image-to-video clips at 720p, each started from a Seedream 5 Pro frame; narration by ElevenLabs v3; music by Suno; edited together |
| Published | 2026-10-17 |
| Watch the output | [Cast showcase page](https://cast.katechon.technology/v/penny-bank?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=penny-bank) · [YouTube](https://www.youtube.com/watch?v=AmkM3QPNQH4) · [TikTok](https://www.tiktok.com/@katechon_studio_arc/video/7697636504843078926) |
| Prompt page | [https://cast.katechon.technology/prompts/penny-bank](https://cast.katechon.technology/prompts/penny-bank?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=penny-bank) |

**Note:** Penny is a studio character, not part of a Cast pack. Below is the prompt for one of the 31 shots (the gold bar shot); every shot used the same two-part recipe.

## Why it worked

- The art style lives in the image prompt, not the video prompt. The video prompt only says what moves, so 31 clips stay one look.
- Every shot starts from a still that the same reference image anchors, which is how one character survives 31 separate generations.
- "Nobody speaks; mouths closed or smiling" stops the model from inventing lip movement under a voice-over it never heard.

## Opening-frame prompt (image model)

The first frame is painted with an image model and the video model animates it. This prompt carries the look.

```text
Low-poly 3D video game screenshot, PS1 / early-2000s console render, flat-shaded chunky polygon geometry, pixel-art textures, big expressive 2D anime eyes on the 3D faces, bright soft daylight unless stated, cozy toy-like world, vertical 9:16 frame. Penny is the woman in the first reference image: same face, auburn-brown bob with bangs, translucent green banker's eyeshade visor with a gold $ badge, fitted navy blazer, white blouse, navy pencil skirt, black heels, gold pen in the pocket, curvy figure.  Scene: Busy low-poly market square with fruit and bread stalls. Penny in heels drags an enormous gold bar behind her on a rope, leaning forward, pixel-art sweat drops flying off her head, annoyed face. No captions, no UI, no watermark.
```

## Video prompt (Seedance)

```text
She strains and drags the huge gold bar a few steps across the cobblestones, sweat drops popping off her head. Camera follows. Low-poly 3D game animation, stylized, smooth motion. Nobody speaks; mouths closed or smiling. No captions, no text overlays, no new characters appearing.
```

Voice-over line for this shot (ElevenLabs, added in the edit): "But gold is heavy, and dragging it to the market every time you want bread is ridiculous."

This is one of 31 shots; every shot used the same frame + motion recipe.

## Make one like it in Cast

Cast expands a single line into a full prompt like the one above. This link opens Cast with the line and settings filled in; nothing is generated until you tap:

> drags an enormous gold bar across a market square, sweating, then pays for bread with a paper receipt

[Open in Cast](https://cast.katechon.technology/make?name=Penny&d=a%20cheerful%20low-poly%203D%20banker%20with%20an%20auburn-brown%20bob%20and%20bangs,%20a%20green%20eyeshade%20visor,%20navy%20blazer%20and%20pencil%20skirt&p=drags%20an%20enormous%20gold%20bar%20across%20a%20market%20square,%20sweating,%20then%20pays%20for%20bread%20with%20a%20paper%20receipt&style=toon3d&camera=auto&vibe=comedy&utm_source=github)

---

Source: Katechon, [https://cast.katechon.technology/prompts/penny-bank](https://cast.katechon.technology/prompts/penny-bank). License: [CC BY 4.0](../LICENSE).
