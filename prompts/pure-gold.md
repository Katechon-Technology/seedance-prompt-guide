# Malfoid and two friends dance on the feast table

> A three-girl choreographed dance trend on a feast table in an empty candlelit hall, one dancer out of sync, and a creaking door that turns them into angels with books.

| | |
|---|---|
| Format | Dance to a song |
| Length | 30 s, vertical 9:16 |
| Model | Seedance 2.5 reference-to-video, 1080p, song as audio reference; opening frame by Seedream 5 Pro; song by Suno |
| Published | 2026-10-16 |
| Watch the output | [Cast showcase page](https://cast.katechon.technology/v/pure-gold?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=pure-gold) · [YouTube](https://www.youtube.com/watch?v=2Boew4cA-z4) · [TikTok](https://www.tiktok.com/@katechon_studio_arc/video/7697068848687664397) · [Instagram](https://www.instagram.com/reel/DeiViBMFFlV/) |
| Prompt page | [https://cast.katechon.technology/prompts/pure-gold](https://cast.katechon.technology/prompts/pure-gold?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=pure-gold) |

**Note:** This video came out before Thea and Odette had their final looks, so the two friends here are earlier designs, not the ones in the Cast pack.

## Why it worked

- Group dances drift: the model averages faces. Re-describing each friend's hair, skin and expression in the frame prompt kept the three apart.
- A planned mistake (Thea goes left, the others go right) makes the choreography feel filmed rather than generated.
- Two seconds of silence before the music lets a spoken line land; the song only starts at 3 s.

## Opening-frame prompt (image model)

The first frame is painted with an image model and the video model animates it. This prompt carries the look.

```text
Vertical 9:16 photo taken by a phone's front camera propped on a stack of golden goblets at the end of a very long wooden feast table, low angle looking along the table top, all three girls fully in frame from head to boots. three young women in their late teens dancing side by side as a squad, all in matching going-out looks: cropped black knit cardigans with silver buttons, emerald-green satin mini skirts, sheer black tights, chunky black boots, silver jewellery. In the middle, the young woman from the reference images: very long straight platinum-blonde hair worn loose, pale porcelain skin, grey-green heavy-lidded eyes, full pouty lips, silver hoops. On her left, Thea: deep brown skin, a short dark curly bob, round cheeks, a big smug grin, gold-flecked brown eyes. On her right, Odette: East Asian, a sleek high black ponytail, sharp straight fringe, cool deadpan eyes, a tiny silver nose stud. They stand on the table top in a tight line in a cocky opening pose, hands on hips, chins up. Around them, like the last reference image, a vast medieval feast hall at night, empty after curfew: four long tables with benches, tall gothic windows, hundreds of lit candles floating in mid-air, and a ceiling that shows a real starry night sky. Photorealistic cinematic look of a gothic castle boarding-school fantasy film: warm golden candlelight, deep shadows, natural skin texture, light phone-camera grain. Clean image, plain photograph without text or interface.
```

## Video prompt (Seedance)

```text
References:
@Image1: The opening frame: the three dancers (platinum-blonde Malfoid in the middle, Thea with the dark curly bob on her left, Odette with the black ponytail on her right), their matching outfits, the long table and the candlelit hall. Open on exactly this composition; keep all three faces exactly.
@Audio1: The song they dance to. It plays from the start; every move lands on its beat and they lip-sync its lyrics.

Visual style: Follow @Image1's photoreal gothic fantasy-film look: warm floating candlelight, starry ceiling.

Avoid: No subtitles. No streaming-interface overlays, phone filters, or masks. No phone body or hand holding a phone in frame or in reflections. No screens, monitors, headphones, cables, electric lights or any other modern technology anywhere. No change to her face.

Three bratty, flirty, aristocratic girlfriends film a choreographed TikTok dance trend standing on a feast table in the empty great hall at night. One uninterrupted take through the front camera of the phone propped on goblets at the end of the table, all three full body, the only viewpoint, no cuts, no camera movement. Tight, perfectly synchronised, sassy and sexy choreography exactly on the beat of @Audio1: hand rolls, shoulder pops, hip-hip, pointing at the lens, body rolls, a hair flip passed down the line. Boots thud on the wood, goblets rattle.

Shot 1 (0-30s): [Phone front camera on the goblets, one continuous take]
0-2.5s: Silence before the music. Malfoid, without moving her pose, says out of the side of her mouth in a crisp posh drawl: "Count of three. Don't embarrass me." Odette, deadpan: "Never have."
3-10s: The song starts and all three hit the routine in perfect sync on the beat: hand roll, shoulder pop, hip-hip, point at the lens, then a hair flip that ripples down the line one girl after another, lip-syncing "gold, gold, gold".
10-17s: On one count Thea goes left while the other two go right. Malfoid freezes mid-move and turns her head slowly to give Thea a death stare; Thea grins sheepishly and slides back into sync.
17-24s: Back on the chant, the hair flip ripples down the line again and all three blow a kiss to the lens together on "blow the peasants a kiss".
24-27s: Finale: all three sink slowly low with body rolls and rise again together, and the floating candles above them flare bright on the final beat as they hit a sharp final pose.
27-30s: A heavy door creaks loudly somewhere off to the side. Instantly all three drop to sit primly on the table edge with their knees together, each holding an open book, looking angelic. Malfoid whispers to the lens: "We were studying."
```

## Song: "Pure Gold" (Suno)

Style prompt: Y2K hyperpop girl-group chant, bratty posh English female vocals, 128 bpm bouncy club beat, handclaps, glittery synths, shouted gang vocals, playful cocky and sexy, vocals start immediately, steady four-count

Lyrics:

```text
[Chant]
Gold, gold, gold, we were born like this
Gold, gold, gold, don't you dare resist

[Verse]
Old money, cold honey, sit down, you're in my seat
Silver on my fingers and the snakes are at my feet

[Chant]
Gold, gold, gold, we were born like this
Gold, gold, gold, blow the peasants a kiss (mwah!)

[Drop]
Low, low, low... and rise
Gold, gold, gold
```

## Make one like it in Cast

Cast expands a single line into a full prompt like the one above. This link opens Cast with the line and settings filled in; nothing is generated until you tap:

> dances on the feast table with her two friends, one of them misses a step, then a door creaks and they pretend to study

[Open in Cast](https://cast.katechon.technology/make?c=malfoid&p=dances%20on%20the%20feast%20table%20with%20her%20two%20friends,%20one%20of%20them%20misses%20a%20step,%20then%20a%20door%20creaks%20and%20they%20pretend%20to%20study&style=dark-fantasy&camera=held&vibe=comedy&utm_source=github)

---

Source: Katechon, [https://cast.katechon.technology/prompts/pure-gold](https://cast.katechon.technology/prompts/pure-gold). License: [CC BY 4.0](../LICENSE).
