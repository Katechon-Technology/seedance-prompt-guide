# Malfoid, Thea and Odette walk in like they own it

> A walk-up-and-break-it-down trend: three girls strut toward a low camera in formation, break into solo moves on the beat switch, and snap back together.

| | |
|---|---|
| Format | Trend format |
| Length | 30 s, vertical 9:16 |
| Model | Seedance 2.0 Fast (the model behind Cast's Standard videos): two chained 15-second halves, the second started from the first half's last frame; opening frame by Seedream 5 Pro; song by Suno |
| Published | 2026-10-16 |
| Watch the output | [Cast showcase page](https://cast.katechon.technology/v/own-it?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=own-it) · [YouTube](https://www.youtube.com/watch?v=JTuB_idi1Wo) · [TikTok](https://www.tiktok.com/@katechon_studio_arc/video/7697389302426193165) · [Instagram](https://www.instagram.com/reel/Dekj5nQj0RP/) |
| Prompt page | [https://cast.katechon.technology/prompts/own-it](https://cast.katechon.technology/prompts/own-it?utm_source=github&utm_medium=referral&utm_campaign=seedance-prompt-guide&utm_content=own-it) |

## Why it worked

- Seedance 2.0 Fast caps a clip at 15 seconds. Half B is image-to-video pinned on half A's last frame; feeding half A back as a video reference restarted the scene and caused a visible jump.
- Each girl gets a signature move (ponytail whip, body roll, deadpan pop-and-lock), which is what keeps three similar characters readable.
- "The camera itself is never visible" is in the avoid list because Seedance kept painting a phone case into the foreground.
- On our account this whole 30-second take cost about $2.50 on 2.0 Fast, against roughly $9 for 30 seconds on 2.5 at 720p.

## Opening-frame prompt (image model)

The first frame is painted with an image model and the video model animates it. This prompt carries the look.

```text
Vertical 9:16 photo from a camera set low on a wooden bench inside a canvas team changing tent, looking straight down the length of the tent toward its wide-open entrance flap. Far back in the open entrance, small in frame but full body, three young women stand side by side in a confident V formation, backlit by blazing golden late-afternoon light from the sports pitch outside, about to walk toward the camera. Identical faces, skin tones and hair to the references: in the middle and slightly ahead Malfoid (first reference image), very long platinum-blonde hair in a high sleek ponytail; on her left Thea (second reference image), very long straight glossy jet-black hair, flirty sly smirk; on her right Odette (third reference image), shoulder-length dark curls, freckles, cool sultry deadpan look. All three strikingly beautiful. Matching fitted sports kits: snug tailored emerald-green and silver long-sleeved jerseys with white side stripes and no logos, crests or numbers, tucked in; skin-tight white equestrian riding breeches; tall glossy brown leather riding boots to the knee. Between them and the camera: the empty tent floor with wooden benches on both sides, broomsticks racked on the walls, green and silver pennants, silver confetti on the ground, the castle visible on the horizon behind them. Photorealistic cinematic look of a gothic castle boarding-school fantasy film, golden rim light, natural skin texture, light phone-camera grain. Clean image, plain photograph without text or interface.
```

## Video prompt (Seedance)

This one was rendered as 2 chained 15-second halves; half B started from half A's last frame.

### Half A

```text
References:
@Image1: The opening frame: the three girls standing far back in the bright tent entrance in a V formation (platinum-blonde Malfoid in the middle, Thea with long straight jet-black hair on her left, Odette with dark curls on her right), their fitted kits and the tent. Open on exactly this composition.
@Image2: Thea's face. @Image3: Odette's face. Keep all three identities exactly.
@Audio1: The song. It plays from the start; every step lands on its beat.

Visual style: photoreal gothic fantasy-film look: blazing golden backlight from the pitch, warm canvas glow, silver confetti. All three girls strikingly beautiful and cute, faces exactly as their references, fitted emerald jerseys, skin-tight white riding breeches, tall brown riding boots.

Avoid: No subtitles. No streaming-interface overlays, phone filters, or masks. No phone body or hand holding a phone in frame or in reflections. No screens, monitors, headphones, cables, electric lights or any other modern technology anywhere. No change to her face. The camera itself is never visible: no phone, phone case, tripod or screen in the foreground. No on-screen interface, icons, labels, text or recording indicators drawn into the image. No logos, crests or numbers on the kits.

Three cocky, flirty, aristocratic girlfriends do a TikTok "walk-up and break it down" dance trend in their team tent right after winning the big match. One uninterrupted take from the camera fixed low on the bench, the only viewpoint, no cuts, no camera movement. Everything lands exactly on the beat of a hard dark phonk-trap track with cowbell and heavy 808s, and they lip-sync its lyrics. Muffled crowd cheering outside.

Shot 1 (0-15s): [Low fixed camera on the bench, one continuous take]
0-13s: The slow-motion-feeling catwalk strut: all three walk straight toward the camera in perfect formation, one step on every beat, hips swaying, shoulders back, chins up, Malfoid slightly in front swinging her ponytail, Thea running a hand through her black hair, Odette deadpan and perfectly in step. Backlit by the golden light, they grow from small figures in the entrance to full body filling the frame, lip-syncing "walk in like we own it".
13-15s: They stop right in front of the camera, full body to the boots, all three cock their heads at the lens at the same instant, and Malfoid raises one finger: wait for it.
```

### Half B

```text
The start image is the exact first frame: the three girls (platinum-blonde Malfoid in the middle, Thea with long straight jet-black hair on her left, Odette with dark curls on her right) standing close in front of the camera at the end of their strut. Continue from exactly this frame, same girls, same faces, same outfits, same tent, same camera position, same light.

Visual style: photoreal gothic fantasy-film look: blazing golden backlight from the pitch, warm canvas glow, silver confetti. All three girls strikingly beautiful and cute, faces exactly as their references, fitted emerald jerseys, skin-tight white riding breeches, tall brown riding boots.

Avoid: No subtitles. No streaming-interface overlays, phone filters, or masks. No phone body or hand holding a phone in frame or in reflections. No screens, monitors, headphones, cables, electric lights or any other modern technology anywhere. No change to her face. The camera itself is never visible: no phone, phone case, tripod or screen in the foreground. No on-screen interface, icons, labels, text or recording indicators drawn into the image. No logos, crests or numbers on the kits.

Three cocky, flirty, aristocratic girlfriends do a TikTok "walk-up and break it down" dance trend in their team tent right after winning the big match. One uninterrupted take from the camera fixed low on the bench, the only viewpoint, no cuts, no camera movement. Everything lands exactly on the beat of a hard dark phonk-trap track with cowbell and heavy 808s, and they lip-sync its lyrics. Muffled crowd cheering outside.

Shot 1 (15-30s, continuing the start image without a cut): [Low fixed camera on the bench, one continuous take]
0-1s: On the beat switch all three explode apart, breaking formation.
1-9s: The break-away: each one freestyles her own signature move on the fast beat, all three full body in frame. Malfoid in the middle whips her ponytail in circles with a sharp hip-hop groove and a smug smile; Thea on the left does a slow sexy body roll and a hair flip, smirking at the lens; Odette on the right does a flawless robotic pop-and-lock with a completely deadpan face. Silver confetti kicks up around their boots.
9-13s: On "look at us now" they snap back together into formation and hit one sharp synchronised pose, leaning toward the lens.
13-15s: Malfoid leans right into the lens and says in a crisp smug posh drawl: "Obviously." Odette, deadpan, right behind her: "Obviously." Thea blows a kiss.
```

## Song: "Own It" (Suno)

Style prompt: dark sexy phonk trap strut anthem, cowbell melody, heavy distorted 808, crisp hi-hats, half-time 140 bpm catwalk groove, confident breathy posh English female vocals with whispered girl-gang chants, huge beat switch drop at 15 seconds into a faster bouncy club beat, vocals start immediately

Lyrics:

```text
[Strut]
Walk in like we own it (we do, we do)
Silver on the skin and the whole pitch knows it
Walk in like we own it (we do, we do)
Mud on the boots, still the cutest, show it

[Beat switch]
Break it, break it, break it down
Snakes on top, the lions on the ground
Break it, break it, break it down
Look at us now
```

## Make one like it in Cast

Cast expands a single line into a full prompt like the one above. This link opens Cast with the line and settings filled in; nothing is generated until you tap:

> walks toward the camera with Thea and Odette in formation, then they each break into their own dance move

[Open in Cast](https://cast.katechon.technology/make?c=malfoid,thea,odette&p=walks%20toward%20the%20camera%20with%20Thea%20and%20Odette%20in%20formation,%20then%20they%20each%20break%20into%20their%20own%20dance%20move&style=cinematic&camera=held&vibe=hype&utm_source=github)

---

Source: Katechon, [https://cast.katechon.technology/prompts/own-it](https://cast.katechon.technology/prompts/own-it). License: [CC BY 4.0](../LICENSE).
