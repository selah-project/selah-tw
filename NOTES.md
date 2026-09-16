# The Selah Twi Rendering — NOTES

*tw.v1 · chair 74 · burned 2026-09-15, seated 2026-09-16. Asante
Twi (Akan), ~9M speakers in Ghana — the second Atlantic-Congo
chair and the first Akan one. A Latin-script chair whose ɛ and ɔ
are LETTERS, not decorated vowels, standing beside two close
relatives it must not become: Akuapem, on which most existing Twi
Bibles are built, and Fante. The seating found that the press had,
seven times, stopped writing Twi altogether.*

## The seal

| Count | Value |
|---|---|
| Verses | 23,213 / 23,213 |
| Token spine ≡ en floor | 23,213 / 23,213, **zero mismatches**; surfaces restored from the floor |
| Zero-token rows | **0** (38 at the start — a flow with an empty row, invisible to a file count) |
| Empty flows | **0** |
| `Yawe` at the Name seat | **every YHWH seat carries the Name — 0 failures** (6,943 in the flow) |
| `Eloohim` (flow) | 2,521 · `Adonai` 542 · `Shadai` 48 |
| ⟨את⟩ | 11,859 in the token row, 11,741 in the flow — **118 seats open**, listed for a reader |
| Erasure (Onyankopon / Onyame / Nyame / Twereduampon at divine seats) | **0** |
| `Awurade` | 9 flow / 6 gloss — **deliberately not swept**; it splits human-lord from divine (Class B) |
| English thermometer (unambiguous, whitelist-first) | **0** — was 7 verses wholly in English |
| Fante thermometer (dze / tse / hom) | `hom` ×14 — **deliberately not swept**, a pronoun-register call |
| Greek / Cyrillic homoglyphs (ε ͻ ԑ ᴐ а е) | **0** — 1,203 repaired |
| English left inside a bracket | **0** — 706 repaired |
| Unbalanced brackets | **0** |
| `asaman` for Sheol | **0** — Sheol stands as `Seol` at all 50 seats |
| Tsevaot | **293 seats + 178 flow words, one spelling** — was 64 distinct glosses |
| File format | uniform, 23,213 pretty-printed at the press's own convention |

## Cruxes of the chair

- **THE ROOT WOUND WAS ONE WOUND, IN FOUR COSTUMES.** The en floor
  uses angle brackets for two jobs — the את marker, and the
  supplied word English needs where the Hebrew writes nothing. The
  chair learned the bracket's shape and lost the distinction. That
  single fact produced 706 English words left untranslated inside
  brackets; 595 of 598 fabricated markers (1 Chr 13:6 writes
  `⟨את⟩` where the floor writes `⟨the Name⟩`); most of the 23
  marker verses left for a reader; and the wrapper class
  `⟨⟨את⟩ asase⟩`, a supplied bracket thrown around a marker *and
  its object*. ff left zero English in a bracket off the same
  floor — the standard was always reachable.

- **SEVEN VERSES WERE NOT IN TWI.** The press fell back to the
  floor wholesale, in consecutive runs: Ps 53:5–7 and Ruth
  1:13–16. Ruth 1:16 — her vow, one of the most quoted sentences
  in the Bible — was sitting in English inside a Twi Bible. No
  count-based gate can see this; only a thermometer can, and only
  with a whitelist. **This is the first thing to check on every
  other chair.**

- **A FABRICATED MARKER HID BEHIND A MISSPELT BRACKET.** Ex 29:22
  carried a seventh ⟨את⟩ written `⟨את〕` with a tortoise-shell
  close (U+3015), so no counter in the groove could see it while
  the floor and the token row both said six. Bracket-glyph drift
  is a documented fleet behaviour (ff found it too); here it
  concealed a fabrication.

- **THE CHAIR TOLD APART WHAT THE HEBREW SPELLS THE SAME.** שאול
  is both Saul and Sheol: 50 floor-Sheol seats read `Seol`, 418
  floor-Saul seats read Saul/Shaul/Shaol, **not one crosses**.
  צבאות is hosts, gazelles (Song 2:7, 3:5) and the women who
  served (1 Sam 2:22); the chair had all three right while
  scattering the divine title across 64 spellings. Both would have
  been destroyed by a spelling-driven sweep; both were saved by
  guarding on the floor's gloss at the seat.

- **THE CHAIR CORRECTED ITSELF IN THE DATA, AND HEDGED.** Thirteen
  erasure seats carry BOTH words in one gloss —
  `Eloohim (Onyankopon)`, `Onyankopon — Eloohim`,
  `ne Onyame (Eloohim)`. Ezra 6:22 does it in the flow. The press
  knew the rail and set the old word down beside it. Related: at
  Esther 7:9 the Hebrew העץ — Haman's gallows — leaked out of the
  token row and stood in the flow **in front of its own correct
  gloss**, and the same shape appears at `⟨התו⟩ nkyerɛnne no`
  (Ezek 9:6, *the mark*) and `⟨הנני⟩ (hwɛ, me wo ha)`.

- **DRAFT-SPEAK REACHED THE CENTRE VERSE.** Lev 8:35 — the verse
  the whole 4D space folds onto — read
  `…⟨את⟩ nhyɛnwee (guard duty) no so…`, carrying an English stage
  direction. Five such parentheticals stripped.

- **THE NAME FAILED TWICE IN 6,943 SEATS.** Isa 12:4 read `Yawhɛ`
  — the Name misspelt, in the verse that says *call on his name*.
  Lev 7:20 had an empty gloss at ליהוה while its flow carried the
  Name twice. A word count of `Yawe` returns 6,943 and calls it
  done; only a seat-by-seat sweep against the floor finds these.

- **ONE REPAIR BROKE A VERSE, AND IDEMPOTENCE CAUGHT IT.** The
  unbalanced-bracket rule `⟩x⟩ → ⟨x⟩` reached across an intact
  marker at Gen 1:25 and took it apart. The delimiter-strip
  guarantee passed — no word was swallowed; delimiters had merely
  moved *through* a marker. What caught it was a later pass
  reporting work on an already-repaired corpus. Markers are now
  parked behind a sentinel during rebalancing: untouchable by
  construction, not by luck.

- **A REPAIR THAT ERASES ITS OWN EVIDENCE IS NOT A REPAIR.** At
  Isa 19:19 the flow reads `ɔbɔne (altar)` and `ɔbɔne` does not
  mean altar. The English parenthesis was **left in place**:
  removing it would have hidden a probable mistranslation and left
  nothing pointing at it.

## Tough verses — the discipline holds

```
gen 1:1    Ahyɛaseɛ mu Eloohim bɔɔ ⟨את⟩ ɔsoro ne ⟨את⟩ asase.
ex 3:14    Eloohim kaa kyerɛɛ Mosheh se: Ehyeh deɛ Ehyeh.
deut 6:4   Israɛl, tie: Yawe yɛ yɛn Eloohim — Yawe baako.
lev 8:35   …na mo mma Yawe ⟨את⟩ nhyɛnwee no so na mo nwnu…
isa 7:14   …hwɛ, ɔbaabunu no awu mma, ɔresi ba…        (not "virgin")
ps 22:17   …sɛ ɔgyata no, wɔatena me nsa ne me nan so. (the kethib)
gen 22:8   Eloohim bɛhunu deɛ ɔpɛ — oguan a wɔde bɛhyɛ no afɔreɛ.
dan 3:12   …wɔnnsom wo anyame…                        (negation intact)
isa 6:3    Kronkron, kronkron, kronkron ne Yawe Tsevaot.
zech 12:10 …wɔbɛhwɛ me so — ⟨את⟩ obi a wɔatow hyɛɛ no mu no…
ruth 1:16  …baako a wobɛkɔ, mɛkɔ…
```

Gen 22:8 stands bare — no atonement doctrine put in Abraham's
mouth, the exact place ff had to be walked back. Ps 22:17 holds
the kethib where every commercial Bible reads *pierced*.

## Hand verses

Four verses no rule could reach, each recorded with its reasoning
in `dev/scripts/tw_hand_pass.py`:

- **hosea 13:13** — token 2 repeated token 1 with an em-dash gloss.
- **exodus 38:17** — token 3 repeated token 0 (its gloss correct
  for the floor's ווי); token 4 was a **fabricated ⟨את⟩** on a
  verse whose Hebrew carries none.
- **esther 7:9** — the Hebrew העץ standing in the flow in front of
  its own gloss, inside an unclosed bracket.
- **joshua 7:26** — a lone final-nun left by the re-press that
  turned `Valley of Ahanu` into **Emeq Akor**.

## Open — for Scott, and for a native ear

See `data/experiments/tw-seating/tw-tekoa-report.md` (Class B) for
the full list. In short: the name canon (410 spellings across 20
names; Judah and Babel need a ruling); the inflected-את family
(⟨אתם⟩ 31, ⟨אתו⟩ 23, ⟨אתכם⟩ 12 — recommendation: keep the suffix);
Awurade's split; Ps 110:1's `me Adonai` for a human lord; 1 Sam
5:7's Dagon on an Eloohim-family surface; the nasal vowels (`nsã`
×201) and name diacritics; five contested gloss seats; and the 118
marker seats.

## Burn signature

Lit 2026-09-15 by `batch/relay-move-on! [:tw]`, finished 02:00
2026-09-16 with 82 residue. The residue came in **pairs** — 37 of
42 gaps exactly two consecutive verses — the relay's batch grain
showing through the holes. The same grain shaped the zero-token
clusters (2 Chr 5:1–4, 2 Sam 13:33–36) and the English fallbacks
(Ps 53:5–7, Ruth 1:13–16). Gleaning ladder: 24k → 32k → 48k
glm-5.3 → temperature 0.7, then hands.
