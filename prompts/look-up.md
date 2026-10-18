# Malfoid dances on the tower at blue hour

> A solo 30-second dance livestream: Malfoid dances to an original song on a castle tower at dusk, then a gust of wind wrecks her hair and she insists it was intentional.

| | |
|---|---|
| Format | Dance to a song |
| Length | 30 s, vertical 9:16 |
| Model | Seedance 2.5 reference-to-video, 1080p, with the song as an audio reference; opening frame painted with Seedream 5 Pro; song made with Suno |
| Published | 2026-10-16 |
| Watch the output | [Cast showcase page](https://cast.katechon.technology/v/look-up?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=look-up) · [YouTube](https://www.youtube.com/watch?v=ABy5LJdO2DY) · [TikTok](https://www.tiktok.com/@katechon_studio_arc/video/7697327597180439821) · [Instagram](https://www.instagram.com/reel/DekI4qJEd_5/) |
| Prompt page | [https://cast.katechon.technology/prompts/look-up](https://cast.katechon.technology/prompts/look-up?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=look-up) |

## Why it worked

- The camera is a real object in the scene (a phone on a telescope tripod), so the model holds one locked frame for 30 seconds instead of inventing cuts.
- Every beat has a timestamp. Seedance follows 0-3s / 3-13s / 13-23s blocks far better than a paragraph of vibes.
- The song goes in as @Audio1, so moves land on the beat and her lips follow the lyrics. We removed our usual "no background music" line for this one; it fights the audio reference.
- The ending is a physical gag (wind, hair, one line of dialogue). A clear last beat gives the clip a reason to be rewatched.

## Opening-frame prompt (image model)

The first frame is painted with an image model and the video model animates it. This prompt carries the look.

```text
Vertical 9:16 photo taken by a phone's front camera mounted on a brass telescope tripod, chest height, slightly wide selfie lens, her whole body in frame from head to boots. the young woman from the reference images: very long straight platinum-blonde hair worn loose and lifting in the wind, pale porcelain skin, grey-green heavy-lidded eyes with smoky liner, full glossy pouty lips, small silver hoop earrings; a black silk slip top, high-waisted emerald satin wide-leg trousers, a long black wool robe with an emerald-lined hood slung low off her shoulders, a slim dark wooden wand in one hand stands a few steps back from the lens on the open stone top of a tall castle astronomy tower, one hip cocked, chin up, giving the lens a cool, challenging look. Around her: crenellated battlements, brass telescopes and star charts weighed down with stones; beyond, far below, a vast lit gothic castle with many towers, a black lake and dark mountains under a deep blue twilight sky with the first stars. Photorealistic cinematic look of a gothic castle boarding-school fantasy film: cold blue dusk, warm torchlight on the stone, wind in her hair, natural skin texture, real silk and wool, light phone-camera grain. Clean image, plain photograph without text or interface.
```

## Video prompt (Seedance)

```text
References:
@Image1: The opening frame: the dancer, her outfit, the tower top and the twilight view. Open on exactly this composition.
@Audio1: The song she dances to. It plays from the start; every move lands on its beat and her lips sync to its lyrics.

Visual style: Follow @Image1's photoreal gothic fantasy-film look: cold blue dusk, warm torchlight, wind.

Avoid: No subtitles. No streaming-interface overlays, phone filters, or masks. No phone body or hand holding a phone in frame or in reflections. No screens, monitors, headphones, cables, electric lights or any other modern technology anywhere. No change to her face.

A spoiled, aristocratic, flirty rich girl films a TikTok dance on the top of the castle's astronomy tower. One uninterrupted take through the front camera of the phone fixed on the telescope tripod, full body, the only viewpoint, no cuts, no camera movement. Confident, sassy, sultry, playful dancing, perfectly on the beat of @Audio1: hair flips, slow body rolls, hip sways, shoulder shimmies, a wink, lip-syncing the lyrics. Wind pulls at her hair and robe the whole time.

Shot 1 (0-30s): [Phone front camera on the tripod, one continuous take]
0-3s: Over the song's intro she steps back into place, bored, and drawls at the lens: "Once. Since you begged."
3-13s: The vocals start and she snaps into the dance with a slow hair flip on the first beat, lip-syncing "look up, look up". Slow, sultry, controlled choreography on the beat continues: a body roll, hip sways, she points up at the stars, then slowly at herself, then dismissively at the lens; a sly wink; her robe slides lower off her shoulders as she rolls them.
13-23s: On the beat drop she flicks her wand at the sky and the whole twilight sky behind her bursts into glittering emerald sparkles; she hits sharp, powerful moves on every beat and finishes a slow spin with her robe fanning out.
23-27s: The vocals return; she lip-syncs "look up, look up, darling" with slow hip sways and a sly wink at the lens.
27-30s: A huge gust of wind blows her long platinum hair straight across her face. She stops dead, spits a strand out of her mouth with total dignity, glares at the lens and says in a crisp posh drawl: "That was intentional." She stalks toward the phone, reaching for it.
```

## Song: "Look Up" (Suno)

Style prompt: dark pop, sultry breathy female vocal, posh English accent, slow 92 bpm trap beat, deep 808, music-box bells, cold reverb, sparse, sexy, confident, vocals start immediately, big beat drop at 18 seconds

Lyrics:

```text
[Hook]
Look up, look up, darling, that's where I am
Stars in my hair and the world in my hand
You can stare from the ground, I don't mind, I insist
Look up, look up, you were never on my list

[Drop]
(Mm.) Higher.

[Hook]
Look up, look up, darling, that's where I am
Stars in my hair and the world in my hand
Look up, look up, you were never on my list
```

## Make one like it in Cast

Cast expands a single line into a full prompt like the one above. This link opens Cast with the line and settings filled in; nothing is generated until you tap:

> dances on the castle tower at blue hour, then the wind blows her hair across her face

[Open in Cast](https://cast.katechon.technology/make?c=malfoid&p=dances%20on%20the%20castle%20tower%20at%20blue%20hour,%20then%20the%20wind%20blows%20her%20hair%20across%20her%20face&style=dark-fantasy&camera=held&vibe=hype&utm_source=github)

---

Source: Katechon, [https://cast.katechon.technology/prompts/look-up](https://cast.katechon.technology/prompts/look-up). License: [CC BY 4.0](../LICENSE).
