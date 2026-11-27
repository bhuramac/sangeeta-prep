# Sangeeta Pravesha Prathama Prep App: Requirements & Plan

**Status:** Approved. **v1 ships today (11/23)** so practice can start now; improvements follow in short iterations (§7).
**Learner:** Parent's daughter (vocal student)
**Exam:** Karnataka Sangeeta Pravesha Prathama (Junior Level 1), Sangeeta Bharati. **Sunday 12/28/2026**, virtual, 45 minutes, 50 marks
**Prep window:** 11/23/2026 → 12/28/2026 (35 days). The app stays in use after the exam.
**Devices:** iPhone, iPad, laptop. Must work on the move.

---

## 1. Source material

| Source | What it gives us | Notes |
|---|---|---|
| Textbook: *Sangeeta Pravesha Prathama* (v2026.02, no-flute version, 64 pp) | Every composition with notation, raga, arohana/avarohana, tala, vaggeyakara, bhasha | The canonical item list. Licensed CC BY-ND, so the app links to page numbers. It does not copy the notation. |
| Evaluation sheet (standalone, 4 pp) | Marks per section, SC/EC selection rules, oral questions, examiner instructions | **Treated as the authority.** Its marks differ from the older sheet printed in the textbook (pp. 46–48). See §3.3. |
| Syllabus page (sangeetabharati.org) | Minimum counts per section | Matches the textbook (p. 45). |
| YouTube playlist "Karnataka Sangeeta Pravesha (Vocal)", Sangeeta Bharati America, 32 videos | Practice recordings for the textbook lessons | I couldn't read the video titles from here. They get mapped at build time (§4, R1). |

---

## 2. Syllabus catalog (the app's master item list)

All Swaravali items are in **Mayamalavagaula** (15th melakarta), arohana `S R1 G3 M1 P D1 N3 S'`, avarohana the reverse, Adi tala unless noted. They are tested in **3 speeds**. Every other item is tested at **any one speed**, with swara + sahitya (Bhajan: sahitya only).

| # | Section | In textbook | Minimum required | Tested in exam (SC + EC) | Marks |
|---|---|---|---|---|---|
| 1 | Sarale Varase | 10 | 7 | 3 (1 SC + 2 EC) | 3 × 1 = 3 |
| 2 | Janti Varase (vilamba Adi, 2 kale) | 12 | 5 | 2 (1 SC + 1 EC) | 2 × 3 = 6 |
| 3 | Tarasthayi Varase | 7 | 3 | 2 (1 SC + 1 EC) | 2 × 1 = 2 |
| 4 | Mandrasthayi Varase | 5 | 3 | 2 (1 SC + 1 EC) | 2 × 1 = 2 |
| 5 | Datu Varase | 5 | 3 | 2 (1 SC + 1 EC) | 2 × 1 = 2 |
| 6 | Alankara (Suladi Sapta Tala) | 7 | 5 | 2 (1 SC + 1 EC) | 2 × 3 = 6 |
| 7 | Pillari Geetam | 4 | **all 4** | 2 (1 SC + 1 EC) | 2 × 4 = 8 |
| 8 | Sanchari / Samanya Geetam | 8 | 5 | 2 (1 SC + 1 EC) | 2 × 4 = 8 |
| 9 | Nottuswara | 2 | **all 2** | 1 (EC) | 1 × 3 = 3 |
| 10 | Bhajan | 1 | 1 | 1 (SC) | 1 × 3 = 3 |
| | **Practical subtotal** | **61** | **38** | | **43** |
| 11 | Maukhika (Oral) | — | — | 6 questions, all EC | 5 |
| 12 | Ideals of an Indian Fine Arts Student | — | — | conduct | 2 |
| | **Total** | | | | **50** |

### 2.1 Alankara talas (7)
1 Chaturashra jati Dhruva · 2 Chaturashra jati Matya · 3 Chaturashra jati Rupaka · 4 Mishra jati Jhampe · 5 Tishra jati Triputa · 6 Khanda jati Ata · 7 Chaturashra jati Eka

### 2.2 Compositions with metadata (this feeds the oral question bank)

| Item | Raga (parent mela) | Arohana / Avarohana | Tala | Vaggeyakara | Bhasha | Book p. |
|---|---|---|---|---|---|---|
| **Pillari 1:** Lambodara Lakumikara (Shri Gananatha, Ganesha stuti) | Malahari (15, Mayamalavagaula janya) | S R1 M1 P D1 S' / S' D1 P M1 G3 R1 S | Chaturashra jati Rupaka | Purandaradasa (1480–1565) | Sanskrit | 22 |
| **Pillari 2:** Kunda Gaura Gauri Vara (Shiva stuti) | Malahari | same | Chaturashra jati Rupaka | Purandaradasa | Sanskrit | 23 |
| **Pillari 3:** Kereya Neeranu Kerege Chelli (tatva geetam) | Malahari | same | Tishra jati Triputa | Purandaradasa | **Kannada** | 24 |
| **Pillari 4:** Padumanabha Paramapurusha (Vishnu geetam) | Malahari | same | Tishra jati Triputa | Purandaradasa | Sanskrit | 25 |
| **Samanya 1:** Varaveena Mrudupani (Lakshmi geetam) | Mohana (28, Harikambhoji janya) | S R2 G3 P D2 S' / S' D2 P G3 R2 S | Chaturashra jati Rupaka | Unknown | Sanskrit | 27 |
| **Samanya 2:** Kamalajadala Vimala Sunayana (Vishnu geetam) | Kalyani (65th mela) | S R2 G3 M2 P D2 N3 S' / reverse | Tishra jati Triputa | Unknown | Sanskrit | 28 |
| **Samanya 3:** Analekara Unnatonnata | Shuddha Saveri (29, Shankarabharanam janya) | S R2 M1 P D2 S' / S' D2 P M1 R2 S | Tishra jati Triputa | Purandaradasa | **Bhandira** | 29 |
| **Samanya 4:** Mandaradhare Mokshamurare (Krishna geetam) | Kambhoji (28, Harikambhoji janya, bhashanga) | S R2 G3 M1 P D2 S' / S' N2 D2 P M1 G3 R2 S N3 P D2 S | Adi (Chaturashra jati Triputa) | Paidala Gurumurthy Shastry (18th c.) | Sanskrit | 30 |
| **Samanya 5:** Kamala Sulochana (Lakshmi stuti) | Anandabhairavi (20, Natabhairavi janya, bhashanga vakra) | S G2 R2 G2 M1 P D2 P S' / S' N2 D2 P M1 G2 R2 S | Adi | Paidala Gurumurthy Shastry | Sanskrit | 31 |
| **Samanya 6:** Govindachyuta | Shankarabharanam (29th mela) | S R2 G3 M1 P D2 N3 S' / reverse | Chaturashra jati Matya | Unknown | Sanskrit | 32 |
| **Samanya 7:** Janakasuta Kucha Kunkuma | Saveri (15, Mayamalavagaula janya) | S R1 M1 P D1 S' / S' N3 D1 P M1 G3 R1 S | Rupaka | Unknown | Sanskrit | 33 |
| **Samanya 8:** Re Re Shri Ramachandra | Arabhi (29, Shankarabharanam janya) | S R2 M1 P D2 S' / S' N3 D2 P M1 G3 R2 S | Tishra jati Triputa | Paidala Gurumurthy Shastry | Sanskrit | 34 |
| **Nottuswara 1:** Shakti Sahita Ganapatim (Ganesha stotra) | Shankarabharanam | — | Tishra nade | Muthuswami Dikshitar | Sanskrit | 38 |
| **Nottuswara 2:** Varashiva Balam Valli Lolam (Subrahmanya stotra) | Shankarabharanam | — | Chaturashra nade | Muthuswami Dikshitar | Sanskrit | 39 |
| **Bhajan:** Jaya Ganesha Jaya Ganesha | Hamsadhvani (29, Dheera Shankarabharanam janya) | S R2 G3 P N3 S' / reverse | Chaturashra jati Eka (tishra gati) | Unknown | Sanskrit | 42 |

Nottuswara raga (Shankarabharanam) and composer (Muthuswami Dikshitar) are confirmed by the parent; they are given on the textbook's "Nottuswaras" title page.

---

## 3. Exam rules extracted from the evaluation sheet

### 3.1 Test-taking reminders (shown before every session, R6)
1. No scripts, books, notes or electronic aids during the exam. *(In app mock mode the notation stays hidden.)*
2. Bring your own shruti instrument, set to **G**, and tune it before you start.
3. Keep tala with **hand gestures** throughout. The examiner may give tala if needed.
4. Swaravali: **3 speeds**. Every other item: **any one speed**.
5. Sing **both swara and sahitya** for every composition except the Bhajan.
6. Sing every item **from start to finish** with fluency, bhava and clear pronunciation. The examiner may also ask for a selected portion.
7. For every item, know the **title, raga (name, arohana, avarohana), tala, vaggeyakara and bhasha**.
8. Be ready to state your **Guru's full name respectfully, with an honorific**: **Smt. Deepa Bhatt**.
9. **Ideals (2 marks):** neat self-presentation, care of your instrument, a respectful greeting (namaskara) at the start and end, polite conduct, following instructions.
10. The full minimum syllabus must be prepared. **Every unprepared item costs the marks of one EC question.**
11. The exam is encouraging. Small slips are fine, but keep **tala and laya steady** and **finish** every item.

### 3.2 Oral (Maukhika) questions, all examiner's choice (5 marks)
| Q | Question | Marks |
|---|---|---|
| 1 | Name a composition | 0.5 |
| 2 | Name **and demonstrate** the tala of a composition | 1 |
| 3 | Name the raga, give arohana, give avarohana | 0.5 + 0.5 + 0.5 |
| 4 | Name the vaggeyakara | 0.5 |
| 5 | Give the bhasha | 0.5 |
| 6 | State the Guru's full name with an honorific | 0.5 + 0.5 |

### 3.3 Discrepancy to note
The textbook's printed sheet has older marks (Sarale 4 of 7 for 4 marks, Alankara 2 × 4, Nottuswara and Bhajan 4 marks each, no oral section). **The app uses the standalone evaluation sheet** (§2 table). The marks table sits in one config file, so it's a one-line change if Sangeeta Bharati revises it.

---

## 4. Functional requirements

### R1 Recordings mapped to every syllabus item
- Every one of the 61 practical items, plus the Bhajan, has a recordings slot. Swaravali sections are mapped at section level and per exercise where a video covers individual exercises.
- **Default source:** the 32-video Sangeeta Bharati playlist, mapped as below. Unmatched items are flagged "No recording yet" so the parent knows where to add links.

| Syllabus items | Playlist video(s) |
|---|---|
| Sarale 1–10 | 1.1 Sarale Varase (one video covers all) |
| Janti 1–5 | 1.2.1 – 1.2.5 Janti Varase 1–5 |
| Janti 6–12 | **missing** |
| Tarasthayi 1–7 | **missing** (the playlist has no 1.3) |
| Mandrasthayi 1–5 | 1.4 Mandrasthayi Varase |
| Datu 1–5 | 1.5 Datu Varase |
| Alankara 1–7 | 1.6.1 – 1.6.7 (one per tala) |
| Pillari 1–4 | 2.1.1 – 2.1.4 |
| Samanya: Varaveena, Kamalajadala, Mandaradhare, Kamala Sulochana | 2.2.2.1, 2.2.3, 2.2.4, 2.2.5 |
| Samanya: Analekara, Govindachyuta, Janakasuta, Re Re Shri Ramachandra | **missing** |
| Nottuswara: Varashiva Balam | 3.2 |
| Nottuswara: Shakti Sahita Ganapatim | **missing** |
| Bhajan: Jaya Ganesha | 5.1 |

Videos in the playlist that aren't in this level's syllabus (the Title Tune, the Disclaimer, the Jatiswaras, and Nottuswaras 3.3–3.5) are left out.
- **Parent override:** a parent screen to add, edit or remove extra links per item (any URL, optional start time and label). These links are saved in the Drive file.
- Playback opens in an embedded player where the platform allows, or in the YouTube app/tab otherwise. On a phone the YouTube app is often better.
- Each item also shows its **textbook page number**, so she can follow along in the printed book during prep.

### R2 Three mock test types
| Mock type | Content | Target duration | Max marks |
|---|---|---|---|
| Oral only | 6 oral questions (§3.2) drawn from her prepared compositions + Ideals checklist | ~10 min | 7 |
| Practical only | One full exam draw: each section's SC + EC picks per §2 | ~35 min | 43 |
| Oral + Practical | Full exam simulation in exam order, with a 45-min clock | 45 min | 50 |
- **SC:** she picks her own item for that section. **EC:** the app picks at random, weighted toward items that are weak or haven't been tested recently, so every item gets tested over time (R7).
- An **"unprepared" button** on any item. It scores 0 and is logged, mirroring the exam's deduction rule.
- Ends with a mark sheet in the evaluation-sheet format, plus specific remarks per item (the sheet bans vague remarks, and so does the app).

### R3 Prep completion %
Coverage is reported three ways:
1. **Per mock type:** % of the material eligible for that mock that she has been tested on at least once (oral facts for oral mocks, practical items for practical mocks).
2. **Overall coverage:** % of all 61 items + all oral facts touched in prep or mock.
3. **Mastered:** % of items whose latest mock result is "exam-ready" (see R7).
Shown as a dashboard with a breakdown by section and a "not yet touched" list.

### R4 Prep mode vs Mock mode
| | **Prep (working) mode** | **Mock (testing) mode** |
|---|---|---|
| Purpose | Learn and practice | Simulate the exam |
| Notation and metadata | Visible (page refs + metadata card) | **Hidden** (no aids, rule #1) |
| Recordings | Available | Unavailable |
| Tanpura drone | Optional | Optional (she brings her own shruti in the real exam) |
| Recording | Optional, with instant pitch feedback + live shruti tuner | **Required** for each practical item |
| Timer | None | 45-min exam clock + per-item time |
| Scoring | Self-check ("got it / shaky / not yet") | Marks per evaluation sheet |
| Item choice | She browses freely | SC/EC draw |
- Prep mode also includes **oral flashcards**: raga ↔ arohana/avarohana, composition ↔ tala, vaggeyakara, bhasha.

### R5 Audio recording + shruti analysis (G tanpura)
- **Reference:** Sa = **G4 (392 Hz)**. Mandra sthayi Sa = G3 (196 Hz), tara sthayi Sa = G5 (784 Hz). Editable in Settings.
- **Tanpura:** a built-in synthesized G drone (Pa–Sa–Sa–Sa' cycle) with volume control. **Headphones are recommended** when recording, so the drone doesn't bleed into the analysis.
- **Analysis, done on the device in the browser (pitch tracking per audio frame):**
  1. **Shruti alignment:** how closely her Sa and Pa sit to the G reference, in cents.
  2. **Swarasthana accuracy:** % of sung time on notes allowed in that item's raga (for example, Mayamalavagaula uses R1 G3 M1 D1 N3), and the average deviation in cents per swara.
  3. **Pitch stability:** wobble on sustained (deergha) notes.
  4. **Range check:** whether tara-sthayi and mandra-sthayi notes were actually reached (for those sections).
  5. **Speed check** (Swaravali): whether the 2nd and 3rd kalas are roughly 2× and 4× the 1st. *Deferred to v2; in v1 the parent rates laya.*
  6. **Octave auto-detect:** the middle Sa is detected from the recording, so the sthayi checks work whether she sings at G4 or G3.
- **Output:** an easy-to-read "Shruti score" (0–100) with colour bands, a pitch-over-time graph against the swara lines, and 1–3 specific tips ("Ga is a bit sharp in the tara sthayi").
- **Honesty and tone:** gamakas (Kambhoji, Anandabhairavi, Saveri) mean the pitch math is approximate, and the evaluation sheet says perfect shruti isn't expected at Prathama. So the shruti score is advisory and encouraging. It never alone decides the mark for an item. The item mark combines the shruti score with a quick rating of **completeness, tala/laya, sahitya and fluency**. **The parent gives that rating**: after a mock, the parent opens a "Rate this mock" screen on any device, listens to each item's recording, and enters marks plus specific remarks. A mock shows as "Awaiting parent rating" until then; the pitch analysis is available immediately.
- **The latest 2 recordings per item** are kept so she can replay and compare them. Older audio is deleted automatically, but all scores, ratings and remarks are kept forever.

### R6 Pre-session reminder
- Every session, prep or mock, opens with the §3.1 checklist. In mock mode she ticks each box before the clock starts. In prep mode a short version appears that she can dismiss.
- Mock mode adds a "set up like the real exam" step: quiet room, shruti box on G, camera framing (virtual exam), namaskara.

### R7 Full syllabus, two readiness scores
The goal is **mastery of the whole syllabus**, not just the minimum.
- **Syllabus Competency** (full level material, all 61 items + all oral facts): each item has a mastery level (Not started → Learning → Shaky → Ready). It is computed from the latest prep self-checks, mock marks and shruti scores, with recent results weighted more.
- **Exam Readiness** (vs the evaluation sheet): an expected score out of 50. For every section it assumes EC could be **any** item in her prepared set. A weak item drags the score down even if her SC pick is strong, because the examiner may choose it. Also shows the trend across mocks.
- **EC draws favour weak or untested items**, so mock practice keeps spreading across the whole syllabus.
- **Daily focus list:** "Today: Janti 7–8, Kamala Sulochana sahitya, Datu 3 at 3rd speed." Built from what's weakest and least recent, paced to cover everything by about 12/21 and leave the last week for full mocks.

### R8 Persistence in Google Drive
- **The source of truth is one JSON file in the parent's Google Drive**, e.g. `Sangeeta Prep/progress.json`. It holds the item catalog state, every session, every mock result, parent links and settings.
- **Durability safeguards (persistence is critical):**
  - The app writes to Drive after each item, not just at session end.
  - It keeps an on-device cache plus an **offline queue**, so sessions in a car or on a flight sync when the device is back online, with no data loss.
  - **Daily snapshot copies** (`progress-YYYY-MM-DD.json`), plus Drive's own version history, so a bad write can't wipe progress.
  - Conflict handling when two devices are used: records are append-only with timestamps and are merged, never overwritten.
  - An "Export / Restore" button for a manual backup.
- **Audio files** go to Drive in `Sangeeta Prep/recordings/`: the latest 2 per item (about 60–200 MB total). Older audio is removed; scores are never removed.
- Kept after 12/28 for ongoing practice and for the next level (Dwiteeya). The catalog is versioned to allow that.

### R9 Phone, iPad, laptop
- A responsive web app with a single codebase and no install. Can be added to the home screen on iOS. Large tap targets and fonts work for a 9-year-old, portrait and landscape.
- Mic recording and the tanpura must work in Safari on iOS/iPadOS and in Chrome on the laptop.
- Recordings and notation display must work fully offline. Only YouTube playback and Drive sync need a connection.

### R10–R13 Additional requirements (confirmed by parent)
- **R10 Tala practice aid:** a visual and audio tala metronome for all 7 suladi talas, Rupaka, Triputa and Eka, at the 3 speeds. Oral Q2 requires *demonstrating* tala.
- **R11 Kid-friendly motivation:** streaks, a progress garden, praise lines. Matches the evaluation sheet's "encouraging" spirit.
- **R12 Parent view:** a weekly summary of time spent, coverage and readiness trend.
- **R13 Bhajan swap:** the parent can add a different Bhajan (from *Rana Sangeetam*) with its metadata.

---

## 5. Non-functional requirements
- **Privacy:** her recordings and progress stay in the parent's Drive. No third-party analytics.
- **Accessibility:** readable diacritics (IAST), plus an optional plain-ASCII spelling of names.
- **Copyright:** the textbook is CC BY-ND, so the app **references page numbers and does not reproduce the notation**. Metadata facts (raga, tala, composer) are fine to include.
- **Performance:** pitch analysis runs on the device in under 2 s for a 3-minute recording on an iPhone.

---

## 6. Architecture (decided)

**Option C: a self-hosted web app (GitHub Pages) with Google Drive sign-in.** The parent chose this on 11/23 so the app can record from the microphone. Option A (hosted on Claude) can't: Claude-hosted pages are not allowed to use the microphone.

- **Front end:** static `index.html`, plus `sw.js` (offline cache), `manifest.json` and an icon, served over HTTPS by GitHub Pages. It can be added to the home screen on iPhone and iPad.
- **Audio:** recording uses the browser's MediaRecorder (Safari and Chrome). Pitch analysis (YIN, downsampled to 11 kHz) runs on the device. The tanpura and tala click are synthesized in the browser with Web Audio.
- **Persistence:** Google Drive API v3 with the **`drive.file` scope**, so the app can see only the files it created. Sign-in uses Google Identity Services, with a one-time OAuth Client ID that the parent sets up (~15 min, steps in SETUP.md).
  - `My Drive/Sangeeta Prep/progress.json` is the master record. On each sync the app downloads it, merges by record ID (newest wins, nothing is ever dropped) and uploads it again.
  - `progress-YYYY-MM-DD.json` is a daily snapshot. Drive keeps its own version history as well.
  - `recordings/` keeps the latest 2 audio clips per item.
- **Offline-first:** every change is saved on the device first (IndexedDB) and synced when online and signed in. Recordings made offline are queued and uploaded later.
- **Fallback:** Export/Import a JSON backup from Settings.
- **Privacy:** GitHub Pages code is public, so it contains no personal data. The Guru's name is entered in Settings and lives only in Drive and on the devices.
- **Sign-in:** Google web tokens last 1 hour, after which one tap on the sync chip refreshes it. Data is always written on the device first, so nothing is lost while signed out.

### 6.1 Data model (sketch)
```
progress.json
├─ meta        { schemaVersion, level:"prathama", examDate:"2026-12-28", shrutiSa:"G4", guruName:"Smt. Deepa Bhatt" }
├─ catalog     [ { id:"sarale-03", section, title, raga, aro, avaro, tala, composer, bhasha, page,
│                  speeds:3, required:true, links:[{url,start,label,source:"playlist|parent"}] } ]
├─ sessions    [ { id, mode:"prep|mock", mockType:"oral|practical|full", start, end, device } ]
├─ attempts    [ { sessionId, itemId, speed, selfRating, parentMarks, parentRemarks, ratedAt, maxMarks, unprepared,
│                  shruti:{score, saCents, paCents, swaraDevs, inRagaPct, stability}, audioFileId, remarks } ]
├─ oralAnswers [ { sessionId, itemId, question, correct, marks } ]
└─ settings    { tanpuraVolume, octave, ecWeighting, … }
```
Mastery, coverage and readiness are **computed** from attempts and never stored as the only copy, so they can't drift out of sync.

---

## 7. Delivery plan

| Release | Scope | When |
|---|---|---|
| **v1** | Everything in R1–R13 at a usable level: catalog + recordings + parent links, prep mode (flashcards, tanpura, live tuner, tala aid, self-check), 3 mock types with reminders, recording + shruti analysis, parent rating, coverage/competency/readiness dashboards, daily focus, streaks, weekly parent summary, Drive sync + offline queue, export/import | **Today, 11/23** |
| v1.x | Fixes and tuning from the first days of real use (scoring weights, wording, UI on each device) | 11/24 – 11/30 |
| v2 | Swaravali speed check, richer per-item feedback, mock history comparisons, any new asks | early Dec |
| — | She practices; the last week (12/21–12/27) is full 45-min mocks | until 12/28 |

**Acceptance check before handover:** a full mock completed on each of the 3 devices; data visible in Drive and unchanged after reload on another device; offline session syncs correctly; every syllabus item shows a recording or a "missing" flag.

---

## 8. Decisions (11/23/2026)
| # | Question | Decision |
|---|---|---|
| Q1 | Hosting | **Option A**: Claude-hosted app + Google Drive connector |
| Q2 | Scope of "complete syllabus" | **Confirmed:** Competency covers all 61 textbook items; Exam Readiness covers the evaluation sheet. Both are reported. |
| Q3 | Who rates mock practicals | **Parent** (pitch analysis stays automatic) |
| Q4 | Audio retention | **Latest 2 recordings per item**, all scores kept |
| Q5 | Shruti / octave | **G4** (Sa = 392 Hz) |
| Q6 | Guru | **Smt. Deepa Bhatt** |
| Q7 | Bhajan | **Confirmed:** Jaya Ganesha (textbook). The parent can swap it in Settings. |
| Q8 | Nottuswara metadata | **Confirmed:** Shankarabharanam, Muthuswami Dikshitar |
