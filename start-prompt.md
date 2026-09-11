Using my skill and my project file, create content idea, 
hook, caption, and carousel outline for my niche this week.
Use the prompt enhancer skill to turn this into a full prompt, then send it to me to render: a rough video idea


Pull this with included transcript, only newer than 3 month post, work out their median view, so we can score outlier properly then run the full 
teardown on it and give me the pattern. 

My niche is AI, careers and technology content for Indian
students and freshers.
0–2s   hook
2–6s   avatar / visual context
6–12s  main point
12–18s supporting visual
18–25s payoff
25–30s CTA
Here is my niche, my audience, and my offer.

Plan content: 
hook,
the angle for each,
the caption,
and the exact prompt I should paste into
my voice tool and my image tool for each one.

Make the hook specific, not generic, 
and tell me which trend each one is riding.
Turn this into one reel script
a carousel 
a text post 
a YouTube Short title  
Keep my voice.
Look at my post topic and tell me 
the theme that is working. 

Then give me new hook in that theme.

Find the exact lines where a viewer would click away,
and rewrite those moments to keep them watching.
TOPIC
SCRIPT
TARGET AUDIENCE
VIDEO LENGTH
BRAND TONE
You are my short-form content director. 
 
Turn this into a script 8-60 second Instagram Reel. 
 
Give me: 
1. hook 
2. narration 
3. shot-by-shot storyboard 
4. visual for every line 
5. image prompt 
6. video prompt 
7. on-screen text 
8. caption 
9. CTA 
10. suggested sound effects 
 
Keep every visual achievable with AI generation.
HOOK:
0–2 sec

BODY:
2–24 sec

PAYOFF:
24–27 sec

CTA:
27–30 sec
You are my AI short-form content director for a technology 
and career-focused Instagram page. 
 
I will give you a topic and youll gimme a script in return. 
 
Your job is to convert it into a production-ready vertical 
Instagram Reel between 8 and 60 seconds. 
 
Do NOT jump directly into video generation. 
 
First create: 
 
1. HOOK 
2. FINAL POLISHED SCRIPT 
3. SHOT LIST 
4. AVATAR / CHARACTER LOCK 
5. VISUAL STYLE LOCK 
6. INDIVIDUAL IMAGE PROMPT FOR EACH SHOT 
7. IMAGE-TO-VIDEO PROMPT FOR EACH SHOT 
8. VOICEOVER SCRIPT WITH EMOTION TAGS 
9. ON-SCREEN TEXT 
10. CAPTION STYLE 
11. SOUND EFFECT CUES 
12. TRANSITION / CUT NOTES 
13. FINAL CTA 
 
Production rules: 
 
- vertical 9:16 
- one clear visual idea per shot 
- one main camera movement per AI shot 
- maintain identical character appearance 
- keep lighting and colour palette consistent 
- no generated text inside AI visuals unless specifically required 
- reserve the lower third for captions 
- change visuals when the narrative idea changes 
- prioritize the first 2 seconds as the hook 
- create still frames first, then animate approved frames 
- generate 2–3 takes for important shots and select the best 
- keep prompts specific rather than using vague words like 
  "cinematic", "beautiful", or "cool" 
- describe subject, action, environment, camera, lighting, 
  style and constraints concretely 
 
The final output should be something I can execute directly 
inside my AI image/video/voice/editing workflow.
Deep Web research
---
name: prompt-enhancer
description: >
  Cinematic prompt enhancer for AI image and video generation. Use whenever
  turning an idea, script beat, or shot description into a generation prompt,
  or when upgrading a weak prompt into a director-grade one. Works with any
  modern video or image model (Seedance, Kling, Veo, Sora, Higgsfield, Arcads,
  Midjourney and similar). Output is always a single standalone prompt.
---

# Prompt enhancer: vibe directing system

Turn a plain idea into a prompt that directs the model like a film crew. The difference between AI slop and cinema is not the model, it is the prompt. A good prompt covers six things: subject, action, scene, camera, style, and locks. This skill teaches you to write all six like a director.

**Output: always one single standalone prompt, in a code block, ready to paste into the generator.**

---

## Core principle: write the visible

The model reacts to what can be seen and measured, not to mood words. Translate every abstraction into something observable.

- Bad: "tense scene" → Good: "man freezes, slowly clenches his fist, light only from the side, half his face in shadow"
- Bad: "cool cinematic shot of a car, epic, fast" → Good: "low tracking shot alongside the car through a wet curve, headlights glowing, spray off the tyres, hard buffeting camera shake"
- Bad: "she looks sad" → Good: "her eyes drop to the table, jaw tightens, she swallows once before answering"

Write in plain, clear, instruction-style language. Fewer precise words beat many vague ones. Before generating, mentally watch the prompt as a viewer: is the first frame non-empty, is it clear where the subject is, where they look, and where the light comes from?

---

## The six parts of every prompt

**1. Subject.** Who or what is in frame. Age, build, current state, unique visible features, wardrobe as material and condition ("cracked leather jacket, rain-dark at the shoulders"), not as a color list. If using a reference image, keep the text description minimal: long appearance text fights the reference and degrades it. Anchor only the critical details the model tends to drop (small text, logos, exact colors).

**2. Action.** What happens, stated physically and in order. Camera motion and subject motion described separately. Emotion through muscle movement, never labels: knuckles whiten, breath shortens, eyes never leave hers. State environment interaction physically: snow melts on skin, wind moves fabric, rain runs down hair.

**3. Scene.** The space in three layers: foreground, midground, background. Where the camera stands, where the light comes from, movement paths. One time of day and one weather per scene.

**4. Camera.** Be concrete and motivated. Shot size (ECU, CU, MCU, MS, WS, EWS), field of view in degrees, operator behavior (height, distance, movement, focus), and why the camera moves. Examples:
- "Low-angle 18 degree dolly-in, slow push from waist to chest as she realizes"
- "Static 47 degree two-shot, eye-level, locked off, lets the silence sit"
- "Handheld 63 degrees, follow from behind, camera lags half a beat"

FOV anchor table (use these discrete steps, not arbitrary numbers):

| FOV | Feels like | Use for |
|-----|-----------|---------|
| 107 | ultra-wide | huge interiors, epic establishing |
| 84 | wide | establishing, group blocking |
| 63 | observational | reportage, immersive follow |
| 47 | neutral human eye | universal medium shots |
| 29 | portrait compression | dialogue, emotion |
| 18 | close portrait | identity-preserving close-ups |
| 12 | tele detail | hands, objects, watching from afar |
| 8 | extreme compression | broadcast, surveillance feel |

**5. Style.** Distributed, not a label. Never open a prompt with a style prefix. Each style aspect lives next to what it governs: lighting in the scene, color tied to material and light ("crimson silk scarf catching the cold tungsten spill from the corridor", never "she wears red"), skin and acting detail with the performance, and only the technical format notes (photoreal, resolution, grain, real-time vs slow motion) as a short suffix at the end. White balance in Kelvin fixed per scene (3200K warm night, 5600K daylight). Describe the look, never gear: no camera models, no director names, no film references.

**6. Locks.** Short hard fixers against the failures you predict, placed at the end and restating each critical fact once: "headlights stay glowing in every shot", "same jacket, same hair, same face in every cut", "cuts only at the specified points, the camera does not cut on its own". Character consistency lives here: identity, wardrobe, prop state, screen direction, and light held identical across every cut.

---

## Prompting rules that separate pros from slop

- **Positive phrasing by default.** Describe the target, not the prohibition: "stays upright, feet planted" beats "does not fall backward". If your model supports a separate negative-prompt field, put avoids there (warped hands, extra fingers, garbled text, melting props, flicker); never mix avoids into the main description.
- **Numbers over adjectives.** Speeds in km/h ("camera pans at 5 km/h"), atmosphere in percent and meters ("fog density 40 percent, haze visible at 15 meters"), scale by human comparison ("stands as tall as four humans stacked head to toe").
- **Left and right are from the camera's view.** Always.
- **Every generation is a blank slate.** The model remembers nothing from your previous shot. Never write "as before" or "continues from the last scene". Each prompt is a sealed, complete document, and continuity is enforced by restating the locks.
- **One reference, minimal text.** A reference image sets identity; text sets what happens. Never describe at length what the reference already shows.
- **Restraint out-acts drama.** A whisper beats a shout. Micro-pauses, precise eye-lines, small muscle movements.

---

## The asset pipeline (for series and recurring characters)

Never prompt a video cold. For any recurring character or world, build still-image assets first, then reference them in every scene:

1. **Character sheet.** Generate a 4-panel reference sheet in one image: close front portrait, full-length front, true 90-degree side profile, full-length back, all on a seamless light-grey background with identical lighting. Build it from reference photos under a strict hierarchy where each reference gets ONE job stated in caps (image_1 = costume and hair ONLY; image_2 = face 100%; image_3 = side profile) plus an explicit conflict rule ("face structure always from image_2; costume always from image_1"). Stylised traits (unusual eye color, pale skin) are color-only overrides: "nothing else changes", never structure.
2. **Location plate.** Generate the empty set with no people in it. Pin the camera height in meters, tilt in degrees, and aspect ratio; describe the space in distance bands (0-30 m, 30-150 m, 150-400 m, beyond); name ONE color grade and repeat it word for word in every scene of the series. The repeated grade is what makes a series look like a series.
3. **Scene prompts reference the banked assets, never re-describe them.** Attach the sheet and plate as references, tag them, and anchor each with one minimal line plus "100% matches the reference". Long prose descriptions of a referenced character fight the reference and cause identity drift.

Doctrine that ships with the pipeline:
- Camera locked static, plus exactly ONE motivated move per shot (an impact shoves the camera into a dutch tilt; a launch pulls it back).
- Endings are designed, never faded: end on a hard button (object flies into the lens, cut to true black, a threshold crossed).
- **Failure log:** every failed generation earns ONE new lock line in the series' prompt template, naming the exact failure you saw ("web reads as fine silk threads, never grey fog"). Locks are scar tissue: accumulate them and never re-fight a solved failure.

---

## Cuts and timing (video)

Pick the precision the shot needs:

- **Single continuous shot:** write "one continuous shot, the camera does not cut on its own".
- **Sequential cuts:** "CUT 1 ... CUT 2 ... CUT 3" in order, when the cut order matters but timing does not.
- **Timed multishot:** explicit hard cuts at stated seconds, when beats must land on a clock:

```
0.0s to 1.0s: [description]
1.0s HARD CUT
1.0s to 3.0s: [description]
```

Whenever you specify cuts, add the lock: "cuts only at the specified points, the camera does not cut on its own". Across cuts, hold the same character set, geometry, screen direction, gaze, light, wardrobe, and prop state.

---

## Sequences across generations (multi-scene videos)

One generation holds one scene well (5 to 10 seconds). A video that changes scenes is a stack of separate generations assembled in an editor, never one prompt:

1. Write the full shot list before generating anything: each shot is one scene, 4-10 seconds, with its own complete prompt.
2. Attach the same character sheet and location plate to every shot, and repeat the grade line word for word. That is what holds identity and world across cuts.
3. Design every shot to start and end on a cuttable beat: enter on action, exit on a button (object into lens, exit frame). Cuts hide inside motion; never plan a cut on a static hold.
4. A prop that crosses shots gets its own identical lock line in every prompt; keep screen direction consistent between shots.
5. For seamless joins, use the previous shot's final frame (or a generated keyframe still) as the next shot's start frame.
6. Speed changes are separate shots: slow motion gets its own generation, one speed per shot.
7. Generate several takes per shot, submit the best, and let the edit plus one continuous sound mix make separate generations read as a single take.

---

## Self-QA before submitting any output

Check every frame for:

1. **Identity drift:** same face, same person, same energy in every image and every video frame. This is the number one kill criterion.
2. **Artifacts:** hands, teeth, eyes, text, logos, warped props, impossible physics, flicker between frames.
3. **First-frame readability:** would the opening frame stop a scroll at thumbnail size?
4. **Clean start and end:** no half-formed motion at either end; loops close cleanly.
5. **The brief:** did the output honor the prompt, or did the model freestyle? If it drifted, fix the prompt (usually a missing lock), then regenerate. Generation is cheap, polishing is expensive: a shot that fails twice gets reconceived, not polished.

---

## Final rules

- English prompts only.
- One standalone prompt per generation, in a code block.
- State every important thing exactly once, clearly.
- Dense where control matters, sparse where it does not.
---
name: video-prompt-enhancer
description: Turn a rough one-line video idea into a full cinematic prompt (subject, action, scene, camera, style, and what to avoid), ready to generate. Use whenever the user wants an AI video and gives a vague or short description, asks to "make a video", "enhance this prompt", or wants to generate through Arcads.
---

# Video Prompt Enhancer

When the user gives you a rough video idea, expand it into ONE detailed, photoreal cinematic prompt built from these six elements. Never hand back the user's thin one-liner: always return the enhanced version.

1. **Subject** — who or what is on screen (age, look, wardrobe, defining details).
2. **Action** — what they are doing, moment to moment.
3. **Scene** — the setting, time of day, background, atmosphere.
4. **Camera** — shot type and movement (slow dolly-in, handheld close-up, macro, orbit).
5. **Style** — the look (cinematic, film grain, colour palette, lighting, mood, lens).
6. **What to avoid** — negatives (no on-screen text, no warped hands, no extra limbs, no logos, no plastic skin).

## How to respond
- Ask ONE quick clarifying question only if the idea is too vague to place a subject or a scene. Otherwise make tasteful, concrete choices and proceed.
- Output the enhanced prompt as one clean paragraph (or labelled lines), specific and photoreal, with all six elements woven in.
- Keep it realistic: concrete nouns, real lighting, believable motion. Avoid empty adjectives like "beautiful" or "amazing".

## Generating the video
If the Arcads connector is enabled and the user asks you to generate, send the enhanced prompt to Arcads to render. Note that Arcads runs the top models in one place (Veo 3.1, Sora, Kling), and that turning on Fable 5 improves realism. If Arcads is not connected, tell the user to add it under Customize, then Connectors, then generate with the enhanced prompt.
