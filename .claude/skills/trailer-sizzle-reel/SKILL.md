---
name: trailer-sizzle-reel
description: Plan, script, and edit-map a trailer, teaser, or sizzle/pitch reel for a documentary, docuseries, reality/unscripted show, podcast, brand, or person. Use when the user asks for a trailer, sizzle, sizzle reel, pitch reel, teaser, promo, or "hype video", or wants to cut footage/interviews/transcripts into a short promotional piece. Produces a timed beat sheet, shot list, soundbite pull, music and SFX cue map, and an edit plan. Built from a shot-by-shot study of the Cocaine Cowboys trailer (testimonial-driven, act breaks marked by music drops, SFX-punctuated).
---

# Trailer & Sizzle Reel Builder

You're acting as a trailer editor or story producer. The output is a **cut-ready plan**: an editor (or an AI video
pipeline) should be able to build the piece from it without asking questions.

The reference model is the *Cocaine Cowboys* trailer. Read `references/cocaine-cowboys-breakdown.md` before the
first draft in a session. It's the worked example behind every rule below.

## 1. Intake (ask only what you can't infer)

Collect these, defaulting sensibly and stating the defaults:

| Field | Default |
|---|---|
| **Format**: trailer (finished project, sells viewing) · sizzle/pitch (unfinished, sells the *idea* to buyers/funders) · teaser (mood only) · social cut | sizzle if the project isn't made yet |
| **Length** | trailer 90–150s · sizzle 60–120s (≤3 min) · teaser 30–45s · social 15/30/60s, vertical |
| **Assets**: interviews/transcripts, archival, B-roll, recreations, stills, none (AI-generated) | ask |
| **Tone**: crime/thriller · uplifting · comedic · prestige · investigative | infer from the subject |
| **Audience & platform**: buyers, festival, Netflix-style streamer, YouTube, TikTok/IG | infer from the format |
| **Ending action**: date/platform card, URL, "Now in development", contact | per format |

If transcripts or footage logs exist, **read them fully**. The best trailers are found in the material, not
written on top of it.

## 2. Core engine: 12 beats

Scale the timings to the target length. Percentages come from the reference trailer (83s).

| # | Beat | % of runtime | Job | Rules |
|---|---|---|---|---|
| 1 | **Cold open** | 0–7% | Build the world before any words | Atmosphere + one recurring **SFX motif**. **Plant a prop/image** you'll pay off later. |
| 2 | **Hook story** | 7–17% | First-person anecdote already in motion | Starts mid-story, with VO over B-roll (J-cut) before the speaker's face. Camera moves closer (ECU→CU→MCU). |
| 3 | **Reveal** | 17–22% | Punchline to the hook | **Ask in audio, answer in picture.** |
| 4 | **Stakes + thesis** | 22–34% | Why this matters | **One concrete number** + **the thesis line**, the sentence that makes the story bigger than its subject. |
| 5 | **Drop 1: the world** | 34–41% | Show the appeal | Music enters on a cut. Palette/texture flips. Pace ×1.5. |
| 6 | **Turn** | 41–51% | Things go wrong | Second anecdote with a darker tone. **Change texture** (archival, B&W, surveillance, phone video) to signal "real". |
| 7 | **Antagonist / obstacle** | 51–58% | The opposing force, at the midpoint | **Name it → show it → sting on the image.** |
| 8 | **Drop 2: escalation** | 58–76% | Everything at once | ~1s shots, **a hard SFX on every cut**, **braid opposites** (pleasure↔punishment, hope↔setback). |
| 9 | **Title chant / title card** | 76–83% | Brand it | The title spoken by 2–4 voices as a refrain, or the title card on a hit. Close the SFX motif loop here. |
| 10 | **Money shot** | 83–87% | The biggest single image | Held back until now. Ideally **pays off the beat-1 plant**. |
| 11 | **Button** | 87–93% | Release with personality | One deadpan, funny, or chilling line on a slow shot. Character, not plot. |
| 12 | **Stings + end card** | 93–100% | Final hits + CTA | 1–2 close-ups on hits → card (title, date/platform/URL or "Now in development" + contact). |

**Cadence curve:** average shot length ~2.5s (beats 1–4) → ~1.5s (5–7) → ~1.0s (8–9) → hold 3–4s (10–11).
For 60s cuts, merge beats 2+3, 5+6 and 9+10. For ≤30s, keep only 1, 4 (thesis), 8, 9, 11, 12.

## 3. The 16 craft rules (check every draft against these)

1. Subjects narrate. Use an announcer VO only if no interviews exist. In that case, write it as a character voice, not "In a world…".
2. Anecdotes beat exposition: 2–3 micro-stories, each with a setup and a punchline.
3. Ask in audio, answer in picture.
4. One specific number or fact is worth ten adjectives.
5. There's exactly one thesis line, and it's quotable.
6. Plant and pay off: a visual prop *and* a sound motif, each introduced early and closed late.
7. Music drops = act breaks (3 musical states minimum). Cuts land on downbeats.
8. SFX are punctuation. Every hard cut in the escalation gets a sound (slam, click, whoosh, impact, riser end).
9. Accelerate, then stop dead for the button.
10. Contrast textures: day/night, warm/cool, color/B&W, polished/raw.
11. Braid opposites in the same montage, never in separate blocks.
12. Use the proximity ladder: move the camera closer as a story gets more intimate.
13. J-cut into speakers. The face is a payoff.
14. The title is said or slammed right before the climax, not at the start.
15. The biggest spectacle comes after the title.
16. End on character. A great button makes people want to *spend time* with these people.

Format adjustments:
- **Sizzle/pitch:** add credibility. Use lower-thirds naming key talent/access, and optionally 1–2 super cards
  stating the hook ("Unprecedented access to…"). Make clear what the *series* is (the engine and repeatability,
  not just one story). End on "Now in development" + logline + contact.
- **Social:** the hook has to work **in the first 1.5s with sound off**. Burn in captions, use 2–4 word supers,
  shoot vertical (9:16), and skip the slow cold open.
- **Trailer for release:** a date/platform card is required. The button can come after the date card ("post-card button").
- **Teaser:** beats 1, 4 (thesis only), 8 (short), 9, 12. No plot.

## 4. Deliverables (always produce all six)

1. **Logline + thesis line**: one sentence each.
2. **Beat sheet**: table with columns `timecode | beat | picture | audio (VO/soundbite) | music | SFX | text on screen`.
3. **Soundbite pull**: ranked candidate lines from the transcripts with source + timecode, tagged by beat
   (HOOK / REVEAL / NUMBER / THESIS / TURN / ANTAGONIST / CHANT / BUTTON). If there are no transcripts, write
   *interview questions designed to elicit* each tagged line.
4. **Shot list / B-roll wishlist**: every picture slot with source (archival, interview, B-roll, recreation, AI-gen),
   shot size and duration. Mark the **plant** and **payoff** shots.
5. **Music + SFX cue map**: the three music states with entry timecodes, BPM/feel references (described, not named
   copyrighted tracks unless the user has licensed them), and every SFX hit.
6. **Edit notes**: J/L-cuts, texture shifts, color palette per act, captions/supers, end card copy, and a
   **checklist pass** against the 16 rules, noting any that are intentionally broken.

Optional extras when asked: an EDL/CSV of the beat sheet, alt cuts (15/30/60s, vertical), and AI-generation prompts.

## 5. AI-generated footage path

If there's no footage and the user wants generated shots, convert each shot-list row into a generation prompt
(subject, action, shot size, lens/camera move, lighting, palette, era texture, duration ≤ model limit). Keep a
consistent **look bible** per act (e.g. Act 1 warm saturated 35mm, Act 2 cool neon night, archival = B&W
low-res). Use the user's video-model skills or tools if present (e.g. Seedance/Higgsfield skills), and generate
the plant and payoff shots first so they match.

Never fabricate real people's testimony or present recreations of real events as genuine archival footage.
Label recreations, and keep invented quotes out of the mouths of real, named people.

## 6. Analyzing a reference trailer

When the user gives a trailer to study (YouTube etc.):
1. Get a scene-by-scene breakdown. Use a video-analysis tool if one is available (e.g. Higgsfield
   `video_analysis_create` with `youtube_url`, then poll `video_analysis_status`). Otherwise use downloaded frames +
   ffmpeg scene detection (`ffmpeg -i in.mp4 -vf "select='gt(scene,0.3)',showinfo" -f null -`).
2. Compute stats: runtime, shot count, average shot length per section, music-drop timecodes, how many times the title is spoken.
3. Map it onto the 12 beats and note where it deviates.
4. Pull the transferable rules into a short "steal this" list for the user's project.
5. Paraphrase the dialogue. Don't transcribe a copyrighted trailer in full.
