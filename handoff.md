# HANDOFF.md — A Country That Would Not Kneel

## Mission

Continue production of **A Country That Would Not Kneel**, a fictional 2026 epic political-drama trailer. The target deliverable is a polished trailer of approximately 84 seconds, assembled from 14 separately generated clips. Use Google Flow / Veo-style generation or an equivalent video tool.

This repository is a production brief and prompt pack. It does not contain finished footage, approved character images, licensed music, or a rendered trailer.

## Fiction and editorial boundaries

- Treat the entire story as fictional alternate history.
- All characters, dialogue, military units, organizations, command structures, and depicted events are invented.
- Iranian locations and regional names are geographical settings only. Do not imply the fictional massacre or events actually occurred.
- Do not fabricate news reports, casualty lists, evidence, eyewitness testimony, or documentary claims about real current events.
- Do not use real political or military figures, real unit insignia, or actual organizations as characters or villains.
- The conscript's shot is a dramatic plot beat, not an instructional firearm scene. Keep it brief, non-graphic, and focused on moral consequence.
- Avoid graphic injury detail, celebratory execution, or glorification of civilian harm.
- The resolution should favor an accountable, pluralistic civilian transition rather than a new authoritarian ruler.
- Generated footage must never be presented as genuine news, eyewitness documentation, or proof of real events.

## Source-of-truth files

- `README.md` — overview, fiction notice, package index, and workflow.
- `trailer/script.md` — canonical 14-beat screenplay, dialogue, and timing.
- `prompts/master-visual-prompt.md` — global visual direction and continuity constraints.
- `prompts/clip-prompts.md` — individual prompts corresponding to the 14 trailer beats.
- `production/character-bible.md` — fixed character identities, wardrobe, and continuity.
- `production/editing-and-sound.md` — assembly, typography, music, sound, and quality control.
- This file — mission, constraints, generation workflow, and final deliverables.

Do not silently change the central premise, character names, or final line. If revisions are necessary, update the script and all affected prompts together.

## Production workflow

### Phase A — Preproduction

1. Read every source-of-truth file.
2. Create approved visual reference portraits for Darya Mehran, Nima Soroush, General Kaveh Radan, Dr. Laleh Vaziri, Sahar, and Mehrdad.
3. Ensure every character is fictional, adult, and not designed to resemble a known actor, public figure, or real political/military person.
4. Build a continuity sheet with front, profile, and three-quarter views, wardrobe, age, hairstyle, and distinguishing details.
5. Test one wide city shot, one close-up, and one crowd shot before generating all clips.

### Phase B — Video generation

1. Generate the 14 clips separately, targeting approximately 6 seconds per clip. Generate extra handles where useful for editing.
2. Combine the master visual prompt with the matching numbered prompt in `prompts/clip-prompts.md`.
3. Reuse the same approved character references whenever a character returns.
4. Preserve the same visual language, lens behavior, color progression, geography, costumes, and weather continuity.
5. Use native dialogue/audio only when intelligible and consistent. Otherwise generate clean visuals and record dialogue separately.
6. Do not ask the video model to render title lettering, credits, subtitles, or readable news graphics.
7. Keep violent moments brief and non-graphic. The commander's injury must not become a spectacle.

### Phase C — Edit and finish

1. Assemble the clips in the exact order and approximate timings in `trailer/script.md`.
2. Use original or properly licensed music only. Do not imitate a recognizable copyrighted score, song, or living artist's signature style.
3. Add dialogue, ambience, and sound design according to `production/editing-and-sound.md`.
4. Add the title and subtitles in a conventional editor.
5. Include a clear fiction disclosure in the video description or end matter.
6. Export the highest native resolution supported by the footage. Do not claim 4K if the source is lower resolution.

## Character continuity

- **Darya Mehran:** 32, fictional photojournalist; shoulder-length dark hair, dark practical field jacket, compact camera; observant, restrained, determined.
- **Nima Soroush:** 24, fictional conscript; short dark hair, plain unmarked fictional uniform; conflicted and frightened, never a superhero.
- **General Kaveh Radan:** 55, fictional commander; greying hair, dark unmarked command uniform; controlled and severe, not a caricature.
- **Dr. Laleh Vaziri:** 40, fictional emergency physician; tied-back dark hair, practical medical clothing; exhausted but composed, treats civilians and soldiers equally.
- **Sahar:** fictional adult teacher from Sistan; practical everyday clothing; grounded and community-minded.
- **Mehrdad:** fictional adult port engineer from Hormozgan; practical workwear; pragmatic and concerned with civilian infrastructure.

## Required quality checks

- [ ] All 14 clips match the correct beat and order.
- [ ] Character faces, ages, hair, and wardrobe remain consistent.
- [ ] No real-world military insignia, political logos, or identifiable public figures appear.
- [ ] Generated footage is not described or distributed as genuine documentary/news footage.
- [ ] No broken hands, duplicated faces, impossible vehicle geometry, or obvious AI artifacts remain in final selects.
- [ ] The commander's injury is non-graphic and brief.
- [ ] The story does not resolve through a simplistic military takeover or revenge killing.
- [ ] The final line is audible and accurately captioned: “Nobody takes Iran. The people decide what comes next.”
- [ ] Exact title typography is added in post-production.
- [ ] The published trailer is clearly identified as fiction.

## Final deliverables

1. Fourteen approved video clips.
2. Character reference sheets.
3. Edited trailer master, approximately 84 seconds.
4. English subtitle file (`.srt`); optional Persian subtitle file.
5. Title card, poster/thumbnail, and credits.
6. Production log and music/license notes.
7. A public-facing description that identifies the film as fictional alternate-history drama.

## Final creative principle

This is not a revenge fantasy. The story is about moral rupture, the human cost of state violence, the danger of a power vacuum, and the difficult work of building a representative future. End with earned, fragile hope—not an uncomplicated victory parade.
