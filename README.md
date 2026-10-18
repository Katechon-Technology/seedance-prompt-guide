# Seedance prompt guide

A first-hand field guide to prompting ByteDance **Seedance 2.0 Fast** and **Seedance 2.5** for short vertical AI videos, plus a library of the **exact prompts behind published videos**: the opening-frame prompt, the timed video prompt, the song prompt where there is one, and why each one worked.

Written by [Katechon](https://katechon.technology) from rendering dozens of published videos in October 2026. Every number is either measured on our own account or quoted from the provider, with the date. Licensed [CC BY 4.0](LICENSE).

- Web version: <https://cast.katechon.technology/guides/seedance-prompts?utm_source=github>
- Prompt library on the web: <https://cast.katechon.technology/prompts?utm_source=github>
- Last updated: 2026-10-18

## Guides

| Guide | What's in it |
|---|---|
| [Seedance prompting field guide](guides/seedance-prompting-field-guide.md) | Prompt skeleton, measured prices per second, model limits, chaining past 15 s, dancing to a song, what the copyright filter blocks and what fixed it, common artifacts |
| [AI influencer livestream videos](guides/ai-livestream-video.md) | The phone-POV one-take format step by step, and what a fake live-chat overlay did to YouTube Shorts reach |
| [Character consistency across videos](guides/ai-character-consistency.md) | Master reference + description, frame-first generation, multi-character drift, celebrity-lookalike blocks |

## Prompt library

Every entry produced a video we published on YouTube, TikTok and Instagram. No made-up examples.

| Video | Format | Length | Model | Output |
|---|---|---|---|---|
| [Malfoid dances on the tower at blue hour](prompts/look-up.md) | Dance to a song | 30 s | Seedance 2.5 reference-to-video | [watch](https://cast.katechon.technology/v/look-up?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=look-up) |
| [Malfoid and two friends dance on the feast table](prompts/pure-gold.md) | Dance to a song | 30 s | Seedance 2.5 reference-to-video | [watch](https://cast.katechon.technology/v/pure-gold?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=pure-gold) |
| [Malfoid, Thea and Odette walk in like they own it](prompts/own-it.md) | Trend format | 30 s | Seedance 2.0 Fast (the model behind Cast's Standard videos): two chained 15-second halves | [watch](https://cast.katechon.technology/v/own-it?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=own-it) |
| [Malfoid reads her hate mail live](prompts/hate-mail.md) | Phone-POV livestream | 30 s | Seedance 2.5 image-to-video | [watch](https://cast.katechon.technology/v/hate-mail?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=hate-mail) |
| [Malfoid's love potion tutorial](prompts/love-potion.md) | Tutorial / how-to | 30 s | Seedance 2.5 image-to-video | [watch](https://cast.katechon.technology/v/love-potion?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=love-potion) |
| [Penny explains how to build a bank from scratch](prompts/penny-bank.md) | Explainer | 82 s | 31 Seedance 2.0 Fast image-to-video clips at 720p | [watch](https://cast.katechon.technology/v/penny-bank?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=penny-bank) |

## The short version

1. **Paint the opening frame with an image model, then animate it.** The image prompt carries the look; the video prompt carries motion, dialogue and sound.
2. **Write the video prompt as a timeline** (`0-4s`, `4-9s`…) with exact quoted dialogue. Seedance follows timestamps far better than prose.
3. **Make the camera a physical thing in the scene** ("the phone propped on the table, eye level, the only viewpoint, no cuts") to get one believable take.
4. **2.0 Fast vs 2.5:** on our account 2.0 Fast was about 10x cheaper per second (about $0.058/s at 720p vs $0.59/s for 2.5 at 1080p, reference-to-video, 2026-10-16), caps clips at 15 s and renders 720p natively; 2.5 runs 4-30 s and 1080p.
5. **The copyright filter runs on the output.** The top cause of blocks for us was a character whose face resembled a famous actor; redesigning the face was the only fix.
6. **Render one take.** If it's wrong, fix the prompt and re-render; spare takes double the bill.

## Try a prompt without writing it

[Cast](https://cast.katechon.technology/?utm_source=github) is Katechon's AI character video app. It expands one line into a full Seedance prompt like the ones here and renders a 5, 10 or 15-second vertical video; the first 5-second video is free with no sign-up. Deep links open it with everything filled in (nothing is generated until you tap):

```
https://cast.katechon.technology/make?c=malfoid&p=<what happens>[&style=&camera=&vibe=&s=5|10|15]
https://cast.katechon.technology/make?name=<new character>&d=<what they look like>&p=<what happens>
```

Example: [Malfoid reads her hate mail live](https://cast.katechon.technology/make?c=malfoid&p=reads%20her%20hate%20mail%20live%20at%20breakfast&camera=selfie&vibe=comedy&utm_source=github). Agents can use the no-auth MCP server at `https://cast.katechon.technology/mcp` (docs: <https://cast.katechon.technology/agents>).

Related data: [AI video price index](https://github.com/Katechon-Technology/ai-video-price-index), dated USD-per-second list prices for 20 text-to-video models.

## Disclosure

Katechon makes Cast and [Arc](https://arc.katechon.technology). The guides recommend techniques, not products; where Cast fits, it says so.

## License and citation

Text and prompts: [CC BY 4.0](LICENSE). Credit "Katechon, Seedance prompt guide" with a link to this repository or <https://cast.katechon.technology/guides/seedance-prompts>. See [CITATION.cff](CITATION.cff).

The characters in the example videos (Malfoid, Thea, Odette, Penny) are Katechon's own characters; the license covers the text of this repository, not the videos or character designs.
