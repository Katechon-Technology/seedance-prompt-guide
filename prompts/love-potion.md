# Malfoid's love potion tutorial

> A beauty-guru-style tutorial: rose petals, three stirs clockwise, a sniff of the steam, and a smell that gives away exactly who she likes.

| | |
|---|---|
| Format | Tutorial / how-to |
| Length | 30 s, vertical 9:16 |
| Model | Seedance 2.5 image-to-video, 1080p, native dialogue and sound; opening frame by Seedream 5 Pro; upscaled to 4K for the platforms |
| Published | 2026-10-14 |
| Watch the output | [Cast showcase page](https://cast.katechon.technology/v/love-potion?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=love-potion) · [YouTube](https://www.youtube.com/watch?v=9u8Y46tEPbo) · [TikTok](https://www.tiktok.com/@katechon_studio_arc/video/7696523608100818190) · [Instagram](https://www.instagram.com/reel/DeejlfXjTxg/) |
| Prompt page | [https://cast.katechon.technology/prompts/love-potion](https://cast.katechon.technology/prompts/love-potion?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=love-potion) |

**Note:** The livestream chat overlay was added after generation.

## Why it worked

- Borrowing a real format (the beauty tutorial: ingredient, step, close-up, reveal) gives the model and the viewer a structure they already know.
- Visual payoffs are things the model draws well: colour-shifting liquid, steam spirals, a glowing heart.
- We render one take per video. When a take is wrong, fix the prompt and re-run it; batching extra takes doubles the bill.

## Opening-frame prompt (image model)

The first frame is painted with an image model and the video model animates it. This prompt carries the look.

```text
Vertical 9:16 photo taken by a phone's front camera standing in a stand on a heavy wooden workbench, eye level, slightly wide selfie lens. the young woman from the reference images: very long platinum-blonde hair pulled into a high sleek ponytail, pale porcelain skin, grey-green heavy-lidded eyes with soft smoky liner, full glossy pouty lips, small silver hoop earrings, a black wool school robe with an emerald-green lined hood, white shirt sleeves rolled up, an emerald-and-silver striped tie tucked into her shirt stands behind a small black iron cauldron bubbling over a low flame, a faint pink shimmering mist curling from it, one hand holding a long silver stirring rod, giving the lens a sly, conspiratorial half-smile. On the bench: glass jars of rose petals and strange ingredients, a stone mortar, tiny crystal vials. Behind her, like the last reference image, a gloomy stone dungeon classroom with rows of workbenches, shelves of jars and green-tinged lantern light, lit only by flame. Photorealistic cinematic look of a gothic castle boarding-school fantasy film, natural skin texture. Clean image with only the room in it, plain photograph without text or interface.
```

## Video prompt (Seedance)

```text
References:
@image1: The streamer, the cauldron and the dungeon classroom. Identity, platinum ponytail, black robe, rolled sleeves, the cauldron with pink mist, the ingredients, the room.

Visual style: Follow @image1's photoreal gothic boarding-school film look: green-tinged lantern light, warm flame glow from under the cauldron, pink magical mist.

Avoid: No subtitles. No background music. No streaming-interface overlays, phone filters, or masks. No phone body or hand holding a phone in frame or in reflections. No screens, monitors, headphones, cables, electric lights or any other modern technology anywhere. No change to her face.

A spoiled, aristocratic, bossy, saucy rich girl films a beauty-guru style tutorial for her viewers: how to brew a love potion. One uninterrupted take in continuous time through the front camera of the phone standing still on the workbench, eye level, the only viewpoint, no cuts, no camera movement. Posh English drawl, condescending and flirty, with matching mouth movement. Sound: bubbling cauldron, glass clinks, crackling flame, dripping.

Shot 1 (0-30s): [Front camera of her phone on the workbench, one continuous take]
0-4s: She leans toward the lens over the cauldron, sly: "Love potion tutorial. For when he's too stupid to notice you."
4-9s: She crushes a handful of red rose petals in her fist and lets them fall into the cauldron, which flares pink: "Rose petals. Crushed by hand. By a girl of breeding."
9-14s: She adds one drop from a tiny crystal vial; the potion swirls into shimmering mother-of-pearl and steam rises in slow spirals. She stirs with the silver rod, bossy, pointing at the lens: "Three stirs clockwise. Never anticlockwise, unless you want him to hate you."
14-19s: She closes her eyes and wafts the steam toward her face with her hand, savouring it: "It smells like whatever you love most. Mine is... expensive leather... fresh parchment..."
19-24s: She sniffs again and frowns: "...broom polish?" Another sniff, slower: "...and treacle tart." Her eyes snap open in horror.
24-30s: The pink steam above the cauldron curls into a big glowing heart. She slams the heavy lid onto the cauldron with a clang, cheeks flushed bright pink, and points a furious finger at the lens: "That did not happen. Chat, delete that. Delete it NOW."
```

## Make one like it in Cast

Cast expands a single line into a full prompt like the one above. This link opens Cast with the line and settings filled in; nothing is generated until you tap:

> films a love potion tutorial and the steam turns into a heart

[Open in Cast](https://cast.katechon.technology/make?c=malfoid&p=films%20a%20love%20potion%20tutorial%20and%20the%20steam%20turns%20into%20a%20heart&style=dark-fantasy&camera=selfie&vibe=comedy&utm_source=github)

---

Source: Katechon, [https://cast.katechon.technology/prompts/love-potion](https://cast.katechon.technology/prompts/love-potion). License: [CC BY 4.0](../LICENSE).
