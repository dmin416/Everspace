# Space Mercenary: Formatting and Rules

Use this file when writing, editing, or processing story chapters.

---

## References

### Main Character: D

**D** is the protagonist. In narration, refer to him by name. Use **he**, **him**, and **his** naturally when D is clearly the subject. Do not use **D's** when **his** reads more naturally (e.g. "before his very eyes", not "before D's very eyes").

#### Narration (third person)

When describing what D does, thinks, or feels, use third-person narration with **D**. Never use **you** or **I**.

| Do | Don't |
|---|---|
| D opened the airlock. | You opened the airlock. |
| D felt the deck shudder. | I felt the deck shudder. |
| D checked his rifle. | You checked your rifle. |

#### Dialogue (first person allowed)

When D is speaking, he may use **I**, **me**, **my**, and **mine** normally in his dialogue.

Other characters may also use first and second person in their own speech.

#### Summary

- **Narrator → D:** third person with **D**, **he**, **him**, and **his**. Never **you** or **I**
- **D speaking:** **I** / **me** / **my** are fine in dialogue
- **Never** address the reader as D with **you**
- **D's thoughts:** first-person internal voice in italics only. Never put the narrator's voice in italics

#### Temperament

- D is **calm**. He does not panic easily and he does not fall apart in strange situations
- He is **not prescient.** He does not instantly know where he is, what things are, or what is going to happen
- He is **not tactical or hyper-competent.** No checklists, military jargon, or SWAT-style readouts in his head
- He is **not clueless either.** He is a regular guy keeping his head, not bumbling or helpless
- Show calm through plain reactions and simple observations. Let him figure things out at a normal pace
- **Never allude to his experience.** Do not state or imply prior training, familiarity with the situation type, muscle memory, years of practice, or similar (e.g. no "as he'd done before," "old habit," "years of," "this wasn't his first")

#### Infinite transmigrator (writer reference only)

- D is an infinite transmigrator. Waking up somewhere new like this is familiar to him and he **knows what is going on**
- He may not know **where** he is or what his **goal** should be yet. Show that through calm reflection, not panic or denial
- Show acceptance through matter-of-fact behavior. He is not confused, surprised, or in denial about the situation itself
- **Never name or allude to transmigration in the prose.** No "again," "like last time," "another world," "this happens all the time," or similar
- **Do not recap or reference events from previous chapters.** The reader already read them. Move the story forward

---

### Speech, Thoughts, and Sound Effects

Each of these gets its **own line**. Do not run them inline with narration on the same line.

#### Speech

- Wrap spoken words in **quotations and italics**
- Markdown: `*"like this"*`
- Put each line of dialogue on a new line

Example:

```markdown
D stopped at the hatch.

*"I don't like this."*

D kept moving anyway.
```

With an attribution tag, keep the spoken words quoted and italicized:

```markdown
*"I don't like this,"* D said.
```

#### Thoughts

Thoughts are **D's internal voice only**. They are what D is thinking to himself in the moment.

- Use **italics only** (no quotation marks)
- Markdown: `*like this*`
- Put each thought on a new line
- Write thoughts in **first person** (*I*, *me*, *my*) because they are D's mind speaking
- **Never** use italics for narrator commentary, exposition, or third-person observations. If it is not D's direct internal voice, write it as normal narration instead

| Do (D's thought) | Don't (narrator in italics) |
|---|---|
| *This doesn't feel like my bed at all.* | *This didn't feel like his bed at all.* |
| *There's no place on Earth where I can see this.* | *There's no place on Earth where anyone can see this.* |

Example:

```markdown
D scanned the corridor.

*Something's wrong here.*

D raised his rifle.
```

#### Sound Effects

- Use **bold**
- Markdown: `**like this**`
- Put each sound effect on a new line

Example:

```markdown
D hit the deck.

**BOOM**

D's ears rang.
```

---

### Chapter Files

- Chapters live in `Story/` as numbered files: `1.md` through `20.md`
- Each file is one chapter

#### Chapter structure

```markdown
# Chapter [number]

[Story content goes here]

---

# Navigation

[Previous: Chapter X](X.md) | [Next: Chapter Y](Y.md)
```

#### Navigation rules

- **Chapter 1:** next link only
- **Chapters 2 through 19:** previous and next links
- **Chapter 20:** previous link only
- Put `# Navigation` on its own line; put the links on the line below it
- Use relative links to adjacent chapter files (e.g. `[Next: Chapter 2](2.md)`)

---

### Canonical names

See [`d-assets.md`](d-assets.md) for D's gear, [`Glossary.md`](Glossary.md) for currency and other canonical terms, [`crafting.md`](crafting.md) for the gear crafting premise, and [`travel.md`](travel.md) for how ships move and arrive. When writing or processing story text, always use these names:

| Use this | Not this |
|----------|----------|
| **Credits** | Enel |
| **rare materials** | rare metals, rare metal |
| **Saanahti** (D calls it **the Orca**) | Krishna |
| **Everspace** | Stella Online |
| **Raven** | (power armor, when referenced) |
| **Denali** | (mothership, appears much later) |

- **Credits** are the galaxy currency in Story/. Always capital **C**. See [`Glossary.md`](Glossary.md). Never use Enel in story chapters
- **Rare materials** not rare metals. See [`Glossary.md`](Glossary.md). Never use rare metal or rare metals in story chapters
- **Travel** arrivals use **dropping out of warp**, not scans. See [`travel.md`](travel.md) and [`Glossary.md`](Glossary.md)

- **Saanahti** is D's fighting ship. **The Orca** is what he calls it. The game it comes from is **[Everspace]**, not Stella Online. It is a completely different ship from anything that came with the game
- If source material or older drafts use Krishna or Stella Online, substitute the canonical names
- Do not introduce Denali until much later in the story

---

### General Writing Rules

- The prose in `Story/` is rewritten from the **novel** source
- The **manga outline** (`References/Manga Outline.md`) is the target structure and pacing guide. The manga version has better flow
- Rewrite everything to fit D's voice, style and personality. Do not treat either source as copy-paste material
- Preserve the user's voice, plot, and intent when editing or expanding
- Do not change established facts, names, or events without being asked
- Keep prose clear and direct; match the tone of existing chapters
- Follow the speech, thought, and sound-effect formatting above in all chapters
- **No em dashes.** Do not use em dashes (—) in story prose or chapter text. Rephrase with commas, periods, colons, or separate sentences instead

#### Punctuation and sentence length (when you can)

- **Avoid Oxford commas.** Do not put a comma before the final item in a list (e.g. write "bright and dim stars, a colorful nebula and an asteroid field" not "bright and dim stars, a colorful nebula, and an asteroid field")
- **Avoid commas before *but* or *and* when joining clauses.** Prefer splitting into two sentences or rephrasing instead (e.g. "It was cold. He looked around." instead of "It was cold, and he looked around.")
- **Avoid sentences shorter than four words.** Combine or expand very short sentences when it reads naturally (e.g. merge *The heck!* into surrounding prose or expand the beat rather than leaving a one-word narration line). Short speech and thoughts are fine when they are clearly D's voice
- **No ellipses.** Do not use `...` or `…` in story prose, speech, or thoughts. Rephrase with a period, comma, question mark, or a full sentence instead

#### Rewrites and edits

- When the user references a line and gives text, the **line is a starting point** only. It shows where to work, not necessarily what to delete
- Use the **first word** of what they provide as the anchor. Build from there
- Reworking is fine **going forward**. Use their wording as the starting point and integrate it into the line naturally. Do not re-edit a line they have already approved
- **Do not erase or remove lines the user has not asked to change.** When editing a section, add to or rewrite only what they point at. Keep everything else intact
- Do not ignore their text or move it to a different line unless they ask
- `...` in user notes means "continue from here," not text to include in the story
