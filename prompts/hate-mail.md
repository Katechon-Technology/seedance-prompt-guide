# Malfoid reads her hate mail live

> A storytime livestream at breakfast: she reads insults, burns one, gets screamed at by an enchanted red letter, and melts at the last, kind note.

| | |
|---|---|
| Format | Phone-POV livestream |
| Length | 30 s, vertical 9:16 |
| Model | Seedance 2.5 image-to-video, 1080p, native dialogue and sound; opening frame by Seedream 5 Pro; upscaled to 4K for the platforms |
| Published | 2026-10-14 |
| Watch the output | [Cast showcase page](https://cast.katechon.technology/v/hate-mail?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=hate-mail) · [YouTube](https://www.youtube.com/watch?v=Crm5HbDCqRw) · [TikTok](https://www.tiktok.com/@katechon_studio_arc/video/7696585604859038990) · [Instagram](https://www.instagram.com/reel/Dee_ILylGbE/) |
| Prompt page | [https://cast.katechon.technology/prompts/hate-mail](https://cast.katechon.technology/prompts/hate-mail?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=hate-mail) |

**Note:** The livestream chat overlay you see was added after generation; the model rendered only the scene.

## Why it worked

- "Phone propped still on the table, eye level, the only viewpoint, no cuts" is the whole livestream look. Say it in the frame prompt and again in the video prompt.
- Five beats in 30 seconds, each with its own sound effect (owl, paper, flame, shriek, confetti), keeps a static camera from feeling static.
- Dialogue is written as exact quotes. Seedance 2.5 lip-syncs quoted lines in the voice you describe ("posh English drawl").
- The last beat flips her character (the snob softens). The turn is what people comment on.

## Opening-frame prompt (image model)

The first frame is painted with an image model and the video model animates it. This prompt carries the look.

```text
Vertical 9:16 photo taken by a phone's front camera propped against a goblet on a long wooden dining table, eye level, slightly wide selfie lens. the young woman from the reference images: very long straight platinum-blonde hair worn loose with a centre part, pale porcelain skin, grey-green heavy-lidded eyes, full glossy pouty lips, small silver hoop earrings, a black wool school robe with an emerald-green lined hood, a charcoal knit vest over a white shirt and an emerald-and-silver striped tie sits at the table facing the lens with a bored, superior smirk, holding up an opened parchment letter between two fingers. In front of her: a messy pile of sealed parchment envelopes, a silver toast rack, a goblet of pumpkin juice. Behind her, like the last reference image, an enormous candlelit stone dining hall with long house tables, students in black robes chatting at a distance, hundreds of floating candles and tall arched windows with morning light. Photorealistic cinematic look of a gothic castle boarding-school fantasy film, natural skin texture. Clean image with only the hall in it, plain photograph without text or interface.
```

## Video prompt (Seedance)

```text
References:
@image1: The streamer at breakfast with her pile of letters, and the great hall. Identity, platinum hair, black robe, striped tie, the table and the hall.

Visual style: Follow @image1's photoreal gothic boarding-school film look: floating candles, soft morning light from tall windows, warm wood.

Avoid: No subtitles. No background music. No streaming-interface overlays, phone filters, or masks. No phone body or hand holding a phone in frame or in reflections. No screens, monitors, headphones, cables, electric lights or any other modern technology anywhere. No change to her face.

A spoiled, aristocratic, bossy, saucy rich girl reads her hate mail live at breakfast. One uninterrupted take in continuous time through the front camera of the phone propped still on the table, eye level, the only viewpoint, no cuts, no camera movement. Posh English drawl, dry and cutting, with matching mouth movement. Sound: busy hall chatter far behind, cutlery clinks, owls hooting and wingbeats, paper tearing.

Shot 1 (0-30s): [Front camera of her phone on the breakfast table, one continuous take]
0-4s: She waves the letter at the lens: "Reading my hate mail. Live. Because I'm that hated." A brown owl swoops in from above and drops another envelope on her head; she swats it away without looking.
4-9s: She reads the letter in a mocking voice: "'You are a spoiled brat.'" She shrugs: "Correct. Next." She flicks it over her shoulder.
9-14s: She opens another, sniffs it, wrinkles her nose: "Cheap ink. Smudged. Clearly from a commoner." She taps it with her wand and it bursts into green flame mid-air and crumbles to ash.
14-20s: A bright red envelope drops onto the table in front of her, smoking at the corners and trembling. Her face falls: "Oh, no." It springs up, its flap opening like a mouth, and shrieks in a furious old woman's voice: "HOW DARE YOU HEX MY GRANDSON'S EYEBROWS OFF!" She covers her ears, deadpan.
20-25s: The red letter rips itself into confetti that rains over her. She brushes it out of her hair, smirks at the lens, and sips her juice: "Worth it."
25-30s: She opens the last envelope, small, cream, sealed with red wax. She reads; her face melts into a shy, helpless smile and her cheeks flush pink: "'Nice hair today.'" She glances off to the side across the hall, gasps softly, clutches the note to her chest, then glares into the lens: "Not. A. Word."
```

## Make one like it in Cast

Cast expands a single line into a full prompt like the one above. This link opens Cast with the line and settings filled in; nothing is generated until you tap:

> reads her hate mail live at breakfast and one letter starts screaming at her

[Open in Cast](https://cast.katechon.technology/make?c=malfoid&p=reads%20her%20hate%20mail%20live%20at%20breakfast%20and%20one%20letter%20starts%20screaming%20at%20her&style=dark-fantasy&camera=selfie&vibe=comedy&utm_source=github)

---

Source: Katechon, [https://cast.katechon.technology/prompts/hate-mail](https://cast.katechon.technology/prompts/hate-mail). License: [CC BY 4.0](../LICENSE).
