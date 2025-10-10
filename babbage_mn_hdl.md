# **BabbageMN HDL — Master Template**

*A universal language of signs for the delineation and proof of purely mechanical Engines; framed after the Forms, Periods, and Trains of Mr Babbage’s Mechanical Notation.*

---

## Title Page

- **Appellation of the Engine:** ☐ *(to be supplied by the Mechanician)*  
- **Draughtsman (Author):** ☐  
- **Place & Date:** ☐  
- **Patron or Establishment (if any):** ☐

**Revision Ledger**

| Rev. | Date | Clerk | Scope of Alteration | Remarks |
|---:|:---|:---|:---|:---|
| 0.0 | ☐ | ☐ | First issue of the Template | Neutral scaffolding only |

> **Editorial Injunction.** This master document is a *generic* scaffold. No particular Engine, geometry, or arithmetic is to be presumed herein. All examples are placeholders to be specialised thereafter.

---

## Preface & Charter

**Purpose.** The present language, **BabbageMN**, is instituted as a *language of signs* for three great heads of doctrine: **Form** (apparatus and pieces), **Periods** (time, admission, and dwell), and **Trains** (causation and government); to the end that the mechanician may attain a *paper-proof* of correctness prior to the expense and hazard of construction. The document thereby enables a clerk to reason on the Engine as surely as the Analyst reasons upon symbols.

**Charter of the Work.**
1. To declare, without ambiguity, the members of an Engine (frames, axes, and pieces), the several **working points** by which they converse, and any **permanent unions** amongst them.  
2. To appoint a ledger of **Periods** in which motions are *admitted* or *detained*, with engagements and releases set down in their proper intervals.  
3. To exhibit **Trains** of cause—entrances, admitted clutches, conveyed motions, guards and interlocks—and to show by these why and under what conditions a motion is permitted.  
4. To furnish a **Proof** consisting of self-necessary verifications for identity, admission safety, sufficiency of time, and the termination of any backing.

**Scope.** The work treats solely of the **purely mechanical** conveyance of motion: wheels, levers, cams, clutches, detents, pawls, springs, and the like; and the government thereof by guards and interlocks. The **Mill** and the **Store** are spoken of only as *mechanical offices*—the Mill as the seat of combined and tested operations; the Store as the repository of appointed Variables—without reference to any electrical or magnetic agency.

**Exclusions.** No electrical currents, magnets, or other arts exterior to mechanism are admitted. No fixed arithmetic, geometry, scale, or tooth-count is presumed by this template; such particulars belong to the draughtsman’s separate tables and plates. No promise is made respecting material strengths or workmanship; the present language concerns logic and order, not metallurgy.

**Editorial Style.** Throughout, the idiom shall be Babbagean: *Frames, Pieces, Working Points, Periods, Trains, Guards, Interlocks, Combined Operations, Tested Operations,* and *Table of the Work*. Modern computational slang is to be avoided. Examples, where unavoidable to illustrate form, shall be *placeholders only* and shall not instantiate any concrete part.

---

## Conventions & Vocabulary

### Alphabets of Form
- **Frames** (fixed members) employ **upright capitals**: *A, B, C…*  
- **Pieces** (movable members—axes, wheels, levers, cams, clutches, detents, springs) employ **inclined capitals**: *I, J, K, L…*  
- **Working Points** (contacts of action) employ **small letters**: *a, b, c…* The same small letter **must** appear upon both pieces that are in converse at that point.

### Working Points & Pairing
1. Each working point is declared upon **two and only two** pieces (save holes or seats in frames as allowed by the editor).  
2. The point inherits the **identity index** of its parent piece, so that the ledger shall identify its assembly without doubt.  
3. Contact mode (rolling pair, sliding pair, clutch, detent) is to be specified **without geometry**, as a quality of the engagement.

### Indices (Enumeration & Seat)
- **Identity Index**: denotes assembly membership or sameness across a group.  
- **Linear Index**: denotes order in a row or depth (succession of fellows).  
- **Circular Index**: denotes angular seat around a circle or turn.  
Indices are employed only where the disposition is material to the work; else they may be omitted.

### Unions, Engagements, & Symbols
- **Permanent Union** (constant mesh or fixed fastening): marked in plates by a *barred* contact; in code by `permanent <point>`.  
- **Admitted Engagement** (clutch or latch): effected only under **admission** within a Period, and may be **forbade** by a named guard.  
- **Clutch**, **Detent**, **Stop**, **Escapement**: named as pieces or guards according to office; their geometry and dimensions remain for the draughtsman’s separate care.

### Vocabulary & Tokens of BabbageMN (Design‑Agnostic)
- **`frame`**, **`axis`**, **`piece … form`**, **`point`**, **`permanent`** — for **Form**.  
- **`periods`**, **`moves`**, **`dwell`**, **`engaged`**, **`latch`**, **`release`** — for **Time**.  
- **`train`**, **`when`**, **`admit`**, **`thence`**, **`unless guard`** — for **Causation**.  
- **`guards`**, **`interlock`** — for restraints upon admission.  
- **`combined`**, **`tested`**, **`proof`**, **`table_of_the_work`** — for higher organisation and verification.  
*(These tokens are to be used only as neutral signs; they are not to instantiate any concrete contrivance.)*

### Miniature “Rule of the Clerk” (Editorial Checklist)
- [ ] **Alphabet Law** obeyed: frames upright; pieces inclined; working points in small letters upon both pieces.  
- [ ] **Pairing Law** obeyed: every point appears upon exactly two pieces (save special frame seats explicitly allowed).  
- [ ] **Indices** present where identity, linear order, or circular seat is material; superfluous indices avoided.  
- [ ] **Unions** marked: permanent unions declared with `permanent`; admitted engagements deferred to **Periods**.  
- [ ] **Vocabulary** kept in Babbagean idiom; modern electrical or computational slang excluded.  
- [ ] **Neutrality** preserved: no concrete parts, toothings, measures, or geometries introduced in this section.  
- [ ] **Guards & Interlocks** referred to by office only; particulars postponed to their library.

---

## Document Map of Sections

1. **Mechanical Alphabet (Symbols & Legend).** Canon of ninety signs with usage rules; legend sheet for the plates.  
2. **Apparatus (Form).** Declaration of frames, axes, pieces, working points, and any permanent unions; observance of the letter-laws and indices.  
3. **Periods (Time).** Ledger of admissions and dwells over the Engine’s cycle; engagements and releases of working points; latching intervals.  
4. **Trains (Causation).** Chains of cause—conditions of entrance, admitted clutches, conveyance by named points, issues, and exceptions under guards.  
5. **Guards & Interlocks.** Library of guards, stops, detents, mutual exclusions, and other restraints; mechanical patterns of admission (conjunct, alternative, inverted).  
6. **Combined Operations & Tested Operations.** Reusable works with appointed Variables (as abstract Stores), conditions of entrance, entered trains, and declared issue; tests and backing under proper termination.  
7. **Proof & Table of the Work.** Self-necessary verifications for identity consistency, admission safety, timing sufficiency, termination; blank Table of the Work for each operation.  
8. **Appendices.** Glossary of terms; editorial checklist; plates, ledgers, charts, and the **Mechanical Alphabet** full list.

---

## Mechanical Alphabet — Canon of Ninety Signs (Design‑Agnostic)

> *A perennial legend to be read with the plates and code. It declares **what kind of piece** something is (Form), **how it may move** (Motion), **how it converses** (Coupling), **how it is governed** (Guards/Interlocks), and **when** (Period). The full catalogue stands in **Appendix A**.*

### Usage within BabbageMN
- **Form signs** are attached to pieces by `form`: e.g., `piece K form wheel;`, `piece L form lever;`.  
- **Motion/Coupling signs** are attached to working points by `mode`: e.g., `point m mode spur_mesh_external;`, `point n mode rolling_pair;`.  
- **Governance signs** are named guards in the library and cited from **Trains** and **Periods**.  
- **Period signs** are the verbs of the timing ledger (`moves`, `dwell`, `engage`, `release`, `latch`, `admit`).

**Canonical Tokens.** For code, employ **lower-case with underscores** derived from the names in Appendix A (e.g., `bevel_mesh`, `ratchet_pawl`, `clutch_block`, `escapement_beat`). Coarser terms like `rolling` or `clutch` are permitted shorthands and are resolved by the clerk to a canonical token at proof time.

**Family Sum.** 28 (Form) + 18 (Motion) + 20 (Coupling) + 12 (Governance) + 12 (Period) = **90** signs.

**Miniature Example (pure placeholder)**
```babbagemn
apparatus {
  axis I; piece K on I form wheel; piece L on I form clutch;
  axis J; piece M on J form pinion;
  point m on K matches m on M mode spur_mesh_external; // coupling sign
  point n on L matches n on M mode dog_clutch;          // coupling sign (clutch-jaw)
}
```

---

## Apparatus (Form) — Template & Laws

> *This section is wholly design‑agnostic. It declares how one **ought** to speak of Frames, Axes, Pieces, and their Working Points; it binds no man to any geometry or tooth.*

### 1) Prose Guide to Frames, Pieces, Axes, and Assemblies

**Frames.** Fixed members of the Engine—bedplates, cheeks, and standards—are denoted by **upright capitals** (*A, B, C…*). Frames afford seats, guides, holes, and bearings; they do not themselves partake of the motion.

**Axes.** Principal shafts and spindles are **pieces** and therefore take **inclined capitals** (*I, J, K…*). An axis is the carrier of other pieces and may rotate or reciprocate according to the later **Periods**.

**Pieces.** All movable members—wheels, pinions, drums, levers, arms, cams, clutches, detents, pawls, springs—are styled **pieces** and bear inclined capitals. They converse by **working points** and may be fast upon an axis, keyed, feathered, or otherwise admitted by clutch.

**Assemblies (by Identity).** Where several members are to be considered one set, they bear a common **identity index**. This index ties drawings and code to the same assemblage without presuming dimensions. Linear and circular indices further distinguish fellows in succession or seat around a turn.

**Law of the Letters.**  
1) Frames upright; moving pieces inclined.  
2) Working points in **small letters**, and the **same letter** must appear upon both pieces in converse.  
3) Indices appear wherever identity, order, or angular seat is material to the work.  
4) **Permanent unions** are declared explicitly; **admitted engagements** are governed only under **Periods** and **Guards**.

---

### 2) Tabular Checklist for Each Declaration (to be duplicated per item)

| Kind (Frame/Piece/Axis/Point/Union) | Name (ID) | Nature (wheel/lever/cam/clutch/detent/axis/frame) | Parent (axis or frame) | Identity Index | Linear Index | Circular Index | **Alphabet Form Sign** | Intended Working Points | **Default Mode Sign** (optional) | Permanent Union? (☑/☐) | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ (from Canon) | ☐ | ☐ (from Canon) | ☐ | ☐ |

> **Clerk’s Direction.** Choose **Alphabet signs** only from the Canon (Appendix A). For **Points**, set *Kind = Point*, list the paired pieces under *Notes*, and set *Mode Sign* to the coupling or contact (e.g., `spur_mesh_external`, `rolling_pair`, `detent_engagement`).

---

### 3) Generic Code Template for Apparatus (with Assemblies & Indices)

```babbagemn
apparatus {

  // === Assembly α (identity index: α) ===
  // Frames — upright capitals
  frame A[id=α];

  // Axes & carriers — inclined capitals
  axis I[id=α];

  // Pieces — nature declared; indices as required (identity/linear/circular)
  // piece K[id=α, lin=1, cir=0] on I form wheel;          // TODO: name and nature only
  // piece L[id=α, lin=2] on I form clutch;                // TODO: declare clutch without geometry

  // Working points — same small letter on both pieces
  // point m[id=α] on K matches m[id=α] on L;              // TODO: pair the point across two pieces

  // Permanent unions (constant mesh or fastening)
  // permanent m;                                          // TODO: mark only if perpetual

  // === Sub‑Assembly β (identity index: β) ===
  // frame B[id=β]; axis J[id=β];
  // piece M[id=β, lin=1] on J form lever;
  // point n[id=β] on M matches n[id=α] on K;              // cross‑assembly engagement allowed

  // Additional assemblies may be declared in like manner.
}
```

> **Notation.** The bracketed attributes `id`, `lin`, and `cir` are editorial conveniences for indices. They bear no geometry and may be omitted where not material. Identity symbols (α, β, 1, 2, &c.) are at the draughtsman’s discretion so long as consistency is maintained.

---

### 4) Validation Notes (to be enforced at Proof)

- **Pairing of Points.** Every working point must be declared upon **two and only two** pieces (save seats or holes expressly allotted to frames).  
- **Alphabet Law.** Frames in upright capitals; all movable pieces in inclined capitals; working points in small letters.  
- **Indices Present Where Due.** If order or seat is material, **linear** or **circular** indices must appear; otherwise they may be spared.  
- **Permanent vs. Admitted.** Constant meshes and fixings declared as **permanent**; all other engagements are to be **admitted** in the **Periods** and governed by **Guards**.

---

### 5) Note on Draughtsman’s Plates (Auto‑Derived Later)

From the foregoing declarations the clerk shall derive, without additional exertion:

1) **Lettered Plates of Form**: frames upright; pieces inclined; points in small letters upon both sides of each contact; permanent unions barred.  
2) **Index Markings**: identity, linear, and circular indices carried onto the plates to preserve assembly and order.  
3) **Reference Tables**: a concordance from names in code to labels upon the plates, ensuring that Form, Periods, and Trains cross‑reference without ambiguity.

---

### Working Points, Contacts, and Unions (Dedicated Subsection)

> *To be inserted within **Apparatus (Form)**; applies to any Engine and binds no geometry.*

#### 1) Rule‑Set for Naming & Pairing
- **Small letters** (*a, b, c…*) name **working points**. The **same letter** must be inscribed upon the **two pieces** in converse at that point.  
- A working point **inherits the identity index** of its **parent piece**; when the counterpart lies in another assembly, each side bears its own identity index and the **letter equality** records the pairing.  
- Working points shall not be multiplied beyond two parties (save special frame seats expressly noted by the editor).  
- Contact **mode** (rolling, sliding, clutch, detent) is declared as a *quality* of the point, without geometry.

#### 2) Catalogue of Contact Modes (Design‑Agnostic Patterns)
Provide one of the following **neutral patterns** for each paired point. Fill only the fields; do not assign measures.

- **Rolling Pair** — continuous rolling contact.
  - *Fields:* `clearance: ☐`, `backlash: ☐`, `direction: bidirectional|advance_only|return_only`.
- **Sliding Pair** — guided sliding contact.
  - *Fields:* `clearance: ☐`, `backlash: ☐`, `direction: bidirectional|advance_only|return_only`.
- **Intermittent Clutch** — admitted engagement under a later **Period/Guard**.
  - *Fields:* `clearance: ☐`, `backlash: ☐`, `direction: bidirectional|advance_only|return_only`.
- **Detent Engagement** — arrest or release by pawl/stop/escapement under a guard.
  - *Fields:* `clearance: ☐`, `backlash: ☐`, `direction: hold|release_on_guard`.

*(The above are **qualities of engagement** only; no tooth count, cam rise, or angle is to be stated here.)*

#### 3) Declarations for Permanent vs. Admitted Engagements
- **Permanent Union (barred contact):** declare `permanent <point>;` after pairing to mark constant mesh or fastening.
- **Admitted Engagement (clutched):** omit `permanent`; declare the **mode** as `clutch` or `detent`; the **admission** and **release** shall be governed later by **Periods** and **Guards**.

#### 4) Correctness Ledger (for Automatic Proof Later)
- **Pairing Law:** each working point must appear upon **two and only two** pieces (save permitted frame seats).  
- **Mode Compatibility:** both sides of a paired point must declare **the same mode** (rolling with rolling, &c.); incompatible modes are a *fault*.  
- **Permanent Precedence:** a `permanent` point may not be admitted or forbade by any Train; such contradiction is a *derangement*.  
- **Direction Consistency:** the admissible `direction` must not contradict declared **Periods** of motion for either piece.  
- **Index Sufficiency:** identity indices present; linear/circular indices supplied where order or seat is material.

#### 5) Minimal, Design‑Agnostic Code Scaffold

```babbagemn
apparatus {
  // … frames and axes declared above …

  // Placeholder pieces (no geometry chosen)
  // piece K[id=α] on I form wheel;
  // piece M[id=β] on J form lever;

  // Working point pairing with declared mode (no measures)
  // point m[id=α] on K matches m[id=β] on M mode rolling { clearance: ☐; backlash: ☐; direction: bidirectional; };

  // Intermittent clutch to be governed by Periods/Guards later
  // piece L[id=α] on I form clutch;
  // point n[id=α] on L matches n[id=β] on M mode clutch { clearance: ☐; backlash: ☐; direction: advance_only; };

  // Permanent union example (constant mesh or fastening)
  // permanent m;  // if and only if the rolling pair is perpetual
}
```

---

## Periods (Time) — Ledger & Admission Grammar

> *A general ledger of motion, altogether free of design particulars; it prescribes when motions are **admitted** or **detained**, when points **engage** or **release**, and how latching is recorded; it binds no geometry nor work of the Mill or Store.*

### 1) Choice of Time Base (Placeholders to be Bound Later)
- **Principal Turn**: divide the revolution of a main axis into convenient parts (e.g., sixteenths, degrees, or any fractional seat).  
- **Escapement Ticks**: count discrete beats of an escapement or equivalent pulse.  

*Template Declaration (design‑agnostic):*

```babbagemn
periods turn (timebase: turn, granularity: ☐ // e.g., 1/360 ) { /* entries follow */ }
periods ticks (timebase: tick, count: ☐     // e.g., 120       ) { /* entries follow */ }
```

### 2) Grammar for Admissions, Dwells, Engagements, and Latching
Use the following neutral forms; supply only names and intervals, not measures.

- **Motion Admission** — a piece is permitted to move:  
  `moves <Piece> [t0 .. t1];`
- **Detention (Dwell)** — a piece is held:  
  `dwell <Piece> [t0 .. t1];`
- **Working‑Point Engagement** — contact is made and kept:  
  `engage <Point> [t0 .. t1];`  
  `release <Point> at t;`
- **Clutch or Detent Latching** — a latch is held under a guard:  
  `latch <ClutchOrDetent> [t0 .. t1];`
- **Admission of a Train** — admits a named train to act within the interval (its internal guards still govern):  
  `admit <TrainName> [t0 .. t1];`

*Notes.* (i) Intervals may be expressed in the chosen base (fractions of a turn or numbered ticks). (ii) Overlapping entries are allowed only where guards or interlocks are declared.

### 3) Concurrency Discipline
- If **two trains** would court the **same coupling** (clutch/point) within an **overlapping interval**, the specification must name an **interlock** that forbids the conflict.  
- Absent such interlock, the **Proof** shall raise *interference of motions* and the ledger is rejected.  
- Mutual exclusion may be stated in the Guards library; the Periods merely **expose** the overlap for the clerk to judge.

### 4) Reusable Code Template for Multiple Cycles
Supply neutral cycles as suits the Engine; keep all entries as placeholders.

```babbagemn
// Cycle of forward work
periods turn (timebase: turn, granularity: ☐) {
  // Approach
  // moves Piece?      [☐ .. ☐];
  // engage Point?     [☐ .. ☐];
  // Execute
  // admit Train?      [☐ .. ☐];
  // Latch as needed
  // latch Clutch?     [☐ .. ☐];
  // Release & Restore
  // release Point?    at ☐;
  // dwell Piece?      [☐ .. ☐];
}

// Return stroke or reverse
periods return (timebase: turn, granularity: ☐) {
  // housekeeping without naming any operation
  // moves Piece?      [☐ .. ☐];
  // dwell Piece?      [☐ .. ☐];
}

// Reset & Proofing cycle
periods reset (timebase: tick, count: ☐) {
  // restore springs, clear latches, home positions
  // latch/engage/release entries as required by guards; keep generic
}
```

*Housekeeping.* The cycle templates above presume non‑specific acts such as approach, engagement, execution, release, and restore, yet bind the draughtsman to no arithmetic, carry, or other Mill behaviour.

### 5) Editorial Checklist for Timing Sufficiency
- [ ] **Approach**: interval allotted for pieces to come into position before engagement.  
- [ ] **Engagement**: interval sufficient for contact to settle with stated clearance/backlash.  
- [ ] **Execution**: interval wherein the work is accomplished under admitted trains.  
- [ ] **Release**: explicit release instant; overlapping releases are guarded.  
- [ ] **Restore**: interval for returning latches, springs, and pieces to their seats.  
- [ ] **Quiet**: reserve of slack time against accumulations and tolerances.  
- [ ] **No Illicit Overlap**: any overlap upon the same coupling is accompanied by a named interlock; else it is a *derangement*.

---

## Trains (Causation) — Canon

> *A universal method for expressing chains of cause, binding no man to any particular work. All that follows is neutral in matter and Victorian in manner.*

### 1) Sentence‑Form for Trains
The **canonical sentence** reads thus:

> **when** *Entrance* **then admit** *ClutchOrDetent*; **thence motion at point** *p* **conveys** *Piece₁ → Piece₂*; **unless guard** *g* **detains**; **issue** *Outcome*.

This sentence may be repeated in stanzas to express a succession of admissions and conveyances, each grounded upon **named working points** declared in **Apparatus**.

### 2) Roles & Neutral Abstractions
- **Entrance.** Any external or internal governor of admission (cards, pegs, or a control lever). In a general specification we name entrances abstractly: *Entranceα, Entranceβ, Controlγ*.
- **Admitted Member.** A **clutch** or **detent** that, once admitted, permits or forbids a conveyance.
- **Conveyance.** A **named working point** *p* by which motion passes from a **source piece** to a **recipient piece**.
- **Guard.** A restraint (escapement, stop, opposed detent) which, if set, detains the act.
- **Issue.** The declared result or state when the stanza completes (e.g., *Issueα*), without committing to any arithmetic or geometry.

### 3) Matrix Template (Entrances → Admissions → Conveyances → Issues)
Fill with placeholders only; duplicate rows as needed.

| Entrance (cards/pegs/control) | Admitted Clutch/Detent | Working Point (p) | Conveyance (Piece₁ → Piece₂) | Guard(s) Referenced | Issue (Outcome) |
|---|---|---|---|---|---|
| ☐ Entranceα | ☐ Clutch? | ☐ p | ☐ Piece? → Piece? | ☐ Guard? | ☐ Issueα |
| ☐ Entranceβ | ☐ Detent? | ☐ q | ☐ Piece? → Piece? | ☐ Guard? | ☐ Issueβ |

> **Clerk’s Note.** The names under *Working Point* and *Pieces* must correspond exactly to declarations made in **Apparatus**; else the Proof shall fault the line.

### 4) Code Scaffold for Multiple Trains (Design‑Agnostic)

```babbagemn
// General work of the Engine — neutral and empty of design
train GeneralWork {
  // when Entranceα then admit Clutch?;
  // thence motion at point p conveys Piece? -> Piece?;
  // unless guard G? detains;
  // issue Issueα;

  // Additional stanzas may follow in like manner
}

// Resetting motions — restore seats, release latches; content is placeholder only
train Resetting {
  // when Entranceβ then admit Detent?;
  // thence motion at point q conveys Piece? -> Piece?;
  // unless guard H? detains;
  // issue Issueβ;
}

// Proofing motions — neutral stanzas for verifications
train Proofing {
  // when Controlγ then admit Clutch?;
  // thence motion at point r conveys Piece? -> Piece?;
  // unless guard J? detains;
  // issue Issueγ;
}
```

*Editorial Usage.* Prefer short, legible stanzas; avoid compounding more than one conveyance per line unless the logic requires it. Reference **guards** by their library names only; their construction is deferred to *Guards & Interlocks*.

### 5) Verification Note (to be enforced at Proof)
- **Declared Names Only.** Every *Entrance*, *Clutch/Detent*, *Working Point*, and *Piece* cited in a Train must have been declared in **Apparatus** (or its libraries). A missing reference is a **fault**.  
- **Point Pairing.** The *Working Point* must be a valid pairing between two pieces; if not, the stanza is rejected.  
- **Guard Presence.** Where two stanzas would seek the same coupling in overlapping **Periods**, an explicit **interlock** or guard reference must be present; else the clerk shall raise *interference of motions*.  
- **Issue Declaration.** Each stanza concludes with a neutral **Issue** name; repeated names are allowed only when the equivalence is intended and noted.

---

## Guards & Interlocks — The Mechanical Alphabet of Logic

> *A general library of restraints and permissions whereby admissions are governed; wholly design‑agnostic and expressed in workshop idiom.*

### 1) Guard Archetypes (Reusable Named Forms)
Each archetype is a **form of governance**; it contains no geometry. Supply only the fields.

- **Escapement** — permits motion by *beats*; detains between beats.  
  *Fields:* `entrance_condition: ☐` (e.g., Entranceα present), `release_condition: ☐` (e.g., beat), `holds: between_beats`, `reset_required: yes|no`.

- **Stop** — absolute arrest at a limit or until a release is given.  
  *Fields:* `entrance_condition: ☐`, `release_condition: ☐`, `blocks: advance|return|both`.

- **Detent** — a catch that holds or frees on condition.  
  *Fields:* `entrance_condition: ☐`, `release_condition: ☐`, `holds: engaged|disengaged`.

- **Opposed Detent** — two detents in contrary, ensuring that one being set forbids the other.  
  *Fields:* `entrance_condition_A: ☐`, `entrance_condition_B: ☐`, `mutual_exclusion: true`.

- **Pawl‑and‑Ratchet Restraint** — permits advance, forbids return, subject to lifting.  
  *Fields:* `entrance_condition: ☐`, `release_condition: lift_on_command|never`, `blocks: return_only`.

- **Clutch Block** — prevents a named clutch from entering while set.  
  *Fields:* `entrance_condition: ☐`, `release_condition: ☐`, `blocks: <ClutchName>`.

> **Clerk’s Note.** Guards are *pieces in government*; their construction (springs, pallets, clicks) is reserved to the plates and is not here described.

### 2) Mechanical Logic in Terms of Admission
Express logical intentions by **admission patterns** rather than symbols.

- **Conjunct Admission** — *both levers raised → admit.*  
  *Pattern:* `admit X when LeverA and LeverB are raised within the same tick; else detain.`

- **Alternative Admission** — *either lever raised → admit.*  
  *Pattern:* `admit X when (LeverA or LeverB) is raised; if both, prefer X once only.`

- **Inverted Admission** — *lever set → forbid.*  
  *Pattern:* `forbid X while LeverC is set; release upon LeverC falling.`

- **Mutual Exclusion** — *admit A forbids B within the same Period.*  
  *Pattern:* `if A admitted within [t0..t1], then B is forbidden in [t0..t1]; reciprocity optional.`

These patterns are realised by the archetypes above (often by **detents** and **clutch blocks**) but are here stated as neutral governance.

### 3) Neutral Hazards & Remedies
- **Race of Trains.** Two trains seek one coupling with near‑simultaneous claims.  
  *Remedy:* impose **precedence** by an opposed detent or escapement beat; in Periods, ensure a non‑overlapping window.

- **Double Admission.** A second admission is granted before the first has released.  
  *Remedy:* **latching** detent that holds after the first admission and a **clutch block** against renewed entry until release.

- **Starvation of Reset.** Resetting trains never obtain admission due to continual work.  
  *Remedy:* Period **reset window** and an **interlock** that forbids new work until reset issues a release.

> **Editorial Maxim.** Where a hazard is discovered, either provide a **guard** (piece in government) or a **timing remedy** (Period separation); do not rely upon good fortune.

### 4) Code Templates (Declarations & References)

**Guard Declarations (Library; design‑agnostic)**
```babbagemn
guards {
  // Escapement pattern — detains between beats
  guard Escapement_α {
    entrance: ☐;          // e.g., Entranceα
    release:  ☐;          // e.g., beat
    holds: between_beats; // template only
  }

  // Opposed detents enforcing mutual exclusion
  guard Opposed_β {
    entrance_A: ☐;  // e.g., LeverA raised
    entrance_B: ☐;  // e.g., LeverB raised
    mutual_exclusion: true;
  }

  // Clutch block — prevents named clutch while set
  guard Block_γ {
    blocks: Clutch?;      // placeholder clutch name
    entrance: ☐; release: ☐;
  }
}
```

**Referencing Guards from Trains (neutral stanzas)**
```babbagemn
train GeneralWork {
  // when Entranceα then admit Clutch?;
  // thence motion at point p conveys Piece? -> Piece?;
  // unless guard Opposed_β detains;  // mutual exclusion enforced
  // issue Issueα;
}
```

**Referencing Guards from Periods (timed latching)**
```babbagemn
periods turn (timebase: turn, granularity: ☐) {
  // latch Escapement_α [☐ .. ☐];  // hold between beats
  // release Escapement_α at ☐;     // generic release instant
}
```

> **Verification Reminder.** Every guard mentioned must be **declared** in the library and referenced by name only; its internal contrivance belongs to the plates.

---

## Combined & Tested Operations — Generic Library

> *This library gathers larger works under conditions of entrance and declares their issue—wholly neutral, without arithmetic or geometry. The Mill and Store are spoken of only as mechanical offices.*

### 1) Template for a **CombinedOperation** (Design‑Agnostic)
A **CombinedOperation** names a piece of work, appoints abstract **Variables** (as Stores), states its **conditions of entrance** (cards/pegs/controls), enters one or more **Trains**, and declares its **Issue**.

**Fields (prose):** *Name*, *Appointed Variables*, *Entrance*, *Trains Entered*, *Issue*, (optional) *Table of the Work* emission.

**Code Template:**
```babbagemn
combined OperationName(Inputs -> Outputs) {
  variables: { Vα: Store?, Vβ: Store? };  // appointed Variables (abstract Stores); fill or remove as needed
  entrance: Entranceα;                    // cards/pegs/controls — placeholder only

  // Entry to one or more trains (neutral stanzas)
  enter GeneralWork;                      // TODO: replace with actual train names from Trains section
  // enter Resetting;                    // optional

  issue Issueα;                           // declared outcome name (neutral)

  emit table_of_the_work;                 // produce blank ledger for proofing (see template below)
}
```

### 2) Template for **Tested Operations** (Purely Mechanical Trials)
A **Tested Operation** performs a trial (by zero/non‑zero, sign, or position), then admits or detains trains accordingly. Trials are expressed as *mechanical* tests; no arithmetic is presumed.

**Neutral Trials (prose):**
- **Trial by Zero** — a condition that, when satisfied, admits one course and otherwise detains or admits another.  
- **Trial by Sign** — a condition observing contrary states (e.g., forward/return, positive/negative as a mechanical sense).  
- **Trial by Position** — a condition by seat, index, or limit‑stop.

**Code Template:**
```babbagemn
tested TrialName(Input -> Outcome) {
  trial zero(Input?) {
    when true  then admit Train_T; issue Issue_T;   // TODO: replace names
    when false then admit Train_F; issue Issue_F;
  }

  // Alternative: sign or position
  // trial sign(Input?)       { when positive then … ; when negative then … }
  // trial position(Seat?)    { when at Seatα then … ; otherwise … }
}
```

### 3) Rules for **Backing** (Repetition) & **Termination Obligation**
- **Backing under Guard.** Where repetition is intended, it shall be declared as **backing** under an explicit **guard** named from the Guards library.  
- **Diminishing Condition.** Every backing must name a **termination**: *counter* (decrementing tally), *limit‑stop* (physical seat), or *exhaustion of cards/pegs*.  
- **Fault on Omission.** Absence of an explicit termination marks the work a **derangement** and shall be refused at Proof.

**Code Template:**
```babbagemn
backing {
  guard: Guard?;                     // e.g., Opposed_β or Block_γ
  termination: counter(name: C?, limit: ☐)
             | limit_stop(name: Seat?)
             | cards_exhausted;
}
```

### 4) Code Scaffold — Placeholder Operations (Neutral)
```babbagemn
combined OperationAlpha(Inputs -> Outputs) {
  variables: { X?: Store?, Y?: Store? }; // TODO: appoint variables only as names
  entrance: Entranceα;                   // TODO: bind to an abstract entrance
  enter GeneralWork;                     // TODO: reference declared trains
  issue IssueAlpha;                      // neutral outcome
  emit table_of_the_work;
}

combined OperationBeta(Inputs -> Outputs) {
  variables: { R?: Store? };
  entrance: Entranceβ;
  enter Resetting;                       // neutral restoring train
  issue IssueBeta;
  emit table_of_the_work;
}

// Example of a tested operation steering between trains
tested TrialGamma(Input -> Outcome) {
  trial position(Seat?) {
    when at Seatα then admit GeneralWork; issue Issue_On;   // TODO: replace
    otherwise           admit Proofing;   issue Issue_Off;
  }
}
```

### 5) **Table of the Work** — Blank Form (per Operation)
> *To be emitted whenever `emit table_of_the_work` is encountered; the clerk fills the ledger during proof.*

| Step | Entrance (cards/pegs/controls) | Trains Entered | Guards Active | Working Points Engaged | Periods Consumed | Issue (Declared) | Remarks |
|---:|---|---|---|---|---|---|---|
| 1 | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |
| 2 | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |
| 3 | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |

> **Clerk’s Reminder.** The names under *Trains* and *Working Points* must match earlier declarations in **Trains** and **Apparatus**. The ledger is part of **Proof** and must balance against the Periods.

---

## Proof — Self‑Necessary Verifications & Table of the Work

> *This section is universal and binds no Engine to any special contrivance. It establishes the clerk’s proofs whereby the specification is accepted or returned for amendment.*

### 1) Identity Consistency
- **Pairing of Points.** Every **working point** appears upon **two and only two** pieces (save permitted frame seats).  
- **Letter Law.** Frames in **upright capitals**; all movable pieces in **inclined capitals**; working points in **small letters** shared by both pieces.  
- **Indices Coherent.** Identity, linear, and circular indices present where material and consistent across Apparatus, Periods, and Trains.  
- **Alphabet Conformity.** Every `form` and `mode` token is a **canonical sign** from the Mechanical Alphabet; shorthands resolve to canon; unknown tokens are a **fault**.  
- **Concordance.** Names of pieces and points agree between text, code, and plates; no phantom members.

### 2) Admission Safety
- **No Double Admission.** No coupling (clutch or point) is **admitted** by two trains within the **same Period** unless a declared **interlock** provides mutual exclusion.  
- **Guards Referenced.** Every stanza that forbids by a guard must cite a **declared** guard in the library; undefined guards are a fault.  
- **Latching Discipline.** Latches hold and release only within their appointed intervals; contradictory orders are refused.

### 3) Timing Sufficiency
- **Approach → Engagement → Execution → Release → Restore** are each afforded an interval within the **Periods** ledger.  
- **Slack.** A margin is reserved for carriage/return and tolerances.  
- **Overlap Scrutiny.** Any overlap upon the same coupling is defended by a named **interlock**; else the clerk declares *interference of motions*.

### 4) Termination of Backing
- **Diminishing Condition.** Every **backing** (repetition) names a termination: *counter*, *limit‑stop*, or *exhaustion of cards/pegs*.  
- **Continuous Works.** If a loop is intended perpetual, it shall be labelled **continuous work** and isolated from ordinary trains by guard.  
- **Fault on Omission.** Absent termination or continuous‑work label, the stanza is a **derangement** and shall be rejected.

### 5) Table of the Work — Blank Emission
> *To be emitted per Combined or Tested Operation; the clerk fills the ledger during proof.*

| Step | Entrance | Trains Entered | Guards Active | Periods Consumed | Issue |
|---:|:---|:---|:---|:---|:---|
| 1 | ☐ | ☐ | ☐ | ☐ | ☐ |
| 2 | ☐ | ☐ | ☐ | ☐ | ☐ |
| 3 | ☐ | ☐ | ☐ | ☐ | ☐ |

*Editorial Direction.* Where an operation spans several cycles (turn/return/reset), add rows accordingly; cross‑reference to the Periods ledger by page and line.

### 6) Formal Declaration of Faults
Failure of any verification above constitutes either **interference of motions** (a conflict in time or cause) or **derangement** (a fault of description or governance). Such faults must be remedied **before construction**.

### Proof Block — Neutral Code Template
```babbagemn
proof {
  check identity_consistency;    // points paired; letters & indices coherent
  check admission_safety;        // no double admissions without interlock
  check timing_sufficiency;      // approach, engagement, execution, release, restore
  check termination_of_backing;  // every loop has a diminishing condition or is marked continuous

  // Emit tables for each declared operation (names are placeholders)
  emit table_of_the_work for OperationAlpha;
  emit table_of_the_work for OperationBeta;
}
```

---

## BabbageMN **Spec Skeleton**

> The following scaffold is **design-agnostic**. All identifiers and comments are placeholders to be specialised by the mechanician.

```babbagemn
spec EngineName {

  // I. APPARATUS (FORM)
  // Declare frame(s), axes, pieces, and working points. Use identity, linear, and circular indices.
  apparatus {

    // frame and fixed forms
    frame A;

    // axes & principal moving pieces
    axis I; axis J;

    // declare pieces (wheels, levers, clutches, cams, detents) without committing to any design
    // piece K on I form wheel;
    // point m on K matches m on …;

    // permanent unions (barred contacts)
    // permanent m;
  }

  // II. PERIODS (TIME)
  periods turn {
    // Define the time base and admission/dwell intervals as placeholders.
  }

  // III. TRAINS (CAUSATION)
  train GeneralWork {
    // when … then admit …; thence motion at point … conveys …; unless guard … detains …
  }

  // IV. GUARDS & INTERLOCKS
  guards {
    // Define guard patterns (escapements, clutches, stops) as reusable named forms.
  }

  // V. COMBINED & TESTED OPERATIONS
  combined OperationName(Inputs -> Outputs) {
    // conditions of entrance; appointed Variables; entry to trains; issue
  }

  // VI. PROOF
  proof {
    // identity consistency; admission safety; timing sufficiency; termination of backing; table of the work
  }
}
```



## Derived Artefacts, Editorial Polishing, & Delivery

> *All artefacts herein are **placeholders** auto‑derived from declarations already made. They exhibit the **Form**, **Periods**, **Trains**, and **Guards** without committing to geometry, measure, or specific work. They are intended for circulation with the master template only.*

### 0) Mechanical Alphabet Legend — Sheet A (Template)
A one‑page legend listing all ninety canonical tokens by family; to be printed at the head of the plates. Include mapping between **token** (code) and **caption** (plate text), with two specimen arrows showing `mode` markings.

| Family | Token (code) | Caption (plate) | Remark |
|:--|:--|:--|:--|
| Form | `wheel` | Wheel (spur) | No geometry implied |
| Coupling | `spur_mesh_external` | Spur Mesh—External | Parallel axes |
| Motion | `oscillatory` | Circular—Oscillatory | Limited swing |
| Governance | `clutch_block` | Clutch Block | Forbids entrance |
| Period | `latch_interval` | Latch Interval | Timing verb |

---

### 1) Draughtsman’s Plates — Lettered Diagrams (Template Captions)
For each assembly identity (α, β, …), emit a plate respecting the laws of the letters.

**Plate Template (caption text):**
- **Plate I — Form of Assembly ☐ (id=☐).** Frames upright (*A, B…*); pieces inclined (*I, J, K…*); working points in small letters (*a, b…*) upon both pieces; permanent unions barred. Indices set forth: identity ☐, linear ☐, circular ☐. *(Template caption; replace tokens only.)*
- **Plate II — Sub‑Assemblies & Cross‑Engagements.** Cross‑assembly working points marked; no geometry shown; arrows denote reference only. *(Template caption.)*
- **Plate III — Seats & Guides.** Frame seats and bearings enumerated; points to refer to Periods and Trains ledgers. *(Template caption.)*

> **Emission Note.** The plates are produced from the Apparatus declarations; the captions above remain boiler‑plate until the mechanician replaces tokens.

---

### 2) Period Tables — Timing Ledgers (Placeholders)
For each named cycle (`turn`, `return`, `reset`, …) emit a ledger. Intervals are expressed in the declared base (fractions of a turn or ticks) yet left blank.

| Row | Cycle | Entry (move/dwell/engage/release/latch/admit) | Subject (Piece/Point/Train) | Start | End/Instant | Guards Named | Remarks |
|---:|:---|:---|:---|:---|:---|:---|:---|
| 1 | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |
| 2 | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |
| 3 | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |

> **Clerk’s Rule.** Overlaps upon the same coupling must correspond to an interlock named in Guards; else the Proof shall charge *interference of motions*.

---

### 3) Train Charts — Causal Maps (Structural Only)
Represent each stanza as a directed row from entrance to issue; geometry is forbidden.

| Stanza | Entrance | Admit (Clutch/Detent) | Working Point (p) | Conveyance (Piece₁ → Piece₂) | Guard(s) | Issue |
|---:|:---|:---|:---|:---|:---|:---|
| 1 | ☐ | ☐ | ☐ | ☐ → ☐ | ☐ | ☐ |
| 2 | ☐ | ☐ | ☐ | ☐ → ☐ | ☐ | ☐ |

> **Reference Law.** Names under *Point* and *Pieces* must be drawn from Apparatus. Guards must be declared in the library.

---

### 4) Guard & Interlock Catalogue — Neutral Patterns
Summarise the library without revealing construction.

| Name | Archetype (escapement/stop/detent/opposed detent/pawl‑ratchet/clutch block) | Entrance | Release | Holds/Blocks | Notes |
|---|:---:|:---|:---|:---|:---|
| ☐ | ☐ | ☐ | ☐ | ☐ | ☐ |

> **Maxim.** Where hazards are known (race of trains, double admission, starvation of reset), record the remedy (precedence, latch, block, reset window) in this catalogue for the clerk’s ready reference.

---

### 5) Final Editorial Pass — Glossary & Style
- [ ] **Babbagean Vernacular.** Terms confined to *Frames, Pieces, Working Points, Periods, Trains, Guards, Interlocks, Combined/ Tested Operations, Table of the Work*.  
- [ ] **Alphabet Law.** Frames upright; pieces inclined; points in small letters; indices where material.  
- [ ] **No Modern Slang.** Expunge electrical or computational jargon; no voltages, processors, or code‑machines.  
- [ ] **Neutrality.** No geometry, toothings, measures, or arithmetic results included.  
- [ ] **Cross‑Reference.** Names in plates, ledgers, charts, and code agree; no phantoms.

---

### 6) Delivery Bundle — Publication Packet (Template)
Prepare the following items for circulation. All are **placeholders** and ready for specialisation by any mechanician.

1. **BabbageMN Source** — the master template document (this volume) with placeholders intact.  
2. **Artefact Sheets** — the Plates of Form, the Period Tables, the Train Charts, and the Guard & Interlock Catalogue as completed **templates**.  
3. **README (Template)** — guidance for replacing placeholders without disturbing the rules.

**README — Template Text**

> **Title.** *BabbageMN Specification — How to Specialise this Template.*  
> **Aim.** To instruct the mechanician in substituting his own **Forms**, **Periods**, **Trains**, **Guards**, and **Operations** for the placeholders herein, without altering the language of signs.
>
> **Steps.**  
> 1) **Apparatus.** Replace placeholder names with your frames, axes, and pieces; declare working points; add indices where order or seat is material; mark permanent unions.  
> 2) **Working Points & Modes.** For each paired point, choose a mode (rolling/sliding/clutch/detent); fill only *clearance*, *backlash*, and *direction* fields—omit geometry.  
> 3) **Periods.** Bind a time base (turn or tick); assign admissions, dwells, engagements, releases, and latches; remove overlaps or provide interlocks.  
> 4) **Trains.** For each entrance, admit the necessary clutches; name the working point; state the conveyance and the issue; cite any guard.  
> 5) **Guards & Interlocks.** Select archetypes and name instances; specify entrances and releases; record in the Catalogue.  
> 6) **Operations.** Gather works under **combined** or **tested** operations; appoint variables as abstract Stores; if repetition is needed, declare **backing** with a termination (counter/limit‑stop/cards).  
> 7) **Proof.** Run the self‑necessary verifications; emit and complete the **Table of the Work**; remedy any *interference of motions* or *derangement* prior to construction.
>
> **Style.** Retain the Babbagean idiom; avoid modern slang; keep all measures and drawings to the separate plates if required.

> **Closing Injunction.** The packet is a universal template. To specialise, replace placeholders with your own members and intervals; do not alter the underlying rules of letters, indices, admissions, guards, or proof.

---



## Appendix A — Mechanical Alphabet (90 Signs)

> *A reasoned canon of symbols to be employed in Forms, Periods, and Trains. Tokens shown in **code** are the canonical names for BabbageMN; captions are their plate titles. No geometry is implied.*

### A. Signs of **Form** (Pieces & Supports) — 28
1. **`frame`** — Frame — A fixed member that affords seats and guides.  
2. **`bedplate`** — Bedplate — Principal foundation‑plate.  
3. **`standard`** — Standard (Cheek) — Upright fixed piece supporting bearings.  
4. **`bearing`** — Bearing (Journal‑Seat) — Fixed seat in which a journal runs.  
5. **`axis`** — Axis (Shaft) — Principal revolving carrier of pieces.  
6. **`arbor`** — Arbor — Light axis for small works.  
7. **`spindle`** — Spindle — Delicate axis for quick or exact guidance.  
8. **`wheel`** — Wheel (Spur) — Toothed circular piece for parallel axes.  
9. **`pinion`** — Pinion — Lesser spur wheel mating with a wheel.  
10. **`bevel_wheel`** — Bevel Wheel — Toothed conical wheel for oblique axes.  
11. **`crown_wheel`** — Crown Wheel — Right‑angled face gear.  
12. **`worm`** — Worm — Screw‑like driver.  
13. **`worm_wheel`** — Worm‑Wheel — Driven wheel of worm train.  
14. **`rack`** — Rack — Straight toothed bar.  
15. **`sector`** — Sector — Portion of toothed circle for limited swing.  
16. **`pulley`** — Pulley — Smooth wheel for belt or cord.  
17. **`drum`** — Drum (Barrel) — Broad cylinder for cords or cards.  
18. **`sprocket`** — Sprocket — Toothed pulley for chain.  
19. **`cam_disc`** — Cam (Disc) — Profiled plate driving a follower.  
20. **`cam_barrel`** — Cam (Barrel) — Helical/axial cam governing along length.  
21. **`follower_roller`** — Follower (Roller) — Rolling follower constrained by cam.  
22. **`follower_flat`** — Follower (Knife/Flat) — Sliding follower constrained by cam.  
23. **`lever`** — Lever — Bar on a fulcrum converting motion/force.  
24. **`bell_crank`** — Bell‑Crank — Right‑angled lever changing line of action.  
25. **`link`** — Link (Connecting Rod) — Bar conveying motion between points.  
26. **`slideway`** — Slideway (Prismatic Guide) — Fixed guide for rectilinear travel.  
27. **`spring`** — Spring — Elastic piece to store/restore motion.  
28. **`weight`** — Weight — Mass employed for effort or regulation.

### B. Signs of **Motion** (Kinds & Qualities) — 18
29. **`circular_uniform`** — Circular—Uniform — Constant angular velocity.  
30. **`circular_accelerated`** — Circular—Accelerated — Angular velocity changes.  
31. **`oscillatory`** — Circular—Oscillatory — Limited swing to and fro.  
32. **`linear_uniform`** — Linear—Uniform — Steady rectilinear travel.  
33. **`linear_reciprocating`** — Linear—Reciprocating — To and fro translation.  
34. **`intermittent_circular`** — Intermittent—Circular — Alternate motion/dwell.  
35. **`intermittent_linear`** — Intermittent—Linear — Alternate motion/dwell.  
36. **`reversive`** — Reversive — Alternating advance and return.  
37. **`dwell`** — Dwell — Express detention from motion.  
38. **`advance_only`** — Advance‑Only Admissible — Forward sense only.  
39. **`return_only`** — Return‑Only Admissible — Backward sense only.  
40. **`slip`** — Slip (Frictional Yield) — Drive may yield by friction.  
41. **`backlash`** — Lost Motion (Backlash) — Free play between members.  
42. **`compliance`** — Compliance (Elastic Yield) — Springing under load.  
43. **`revolute_pair`** — Revolute Pair — Constrained turning about a pin/journal.  
44. **`prismatic_pair`** — Prismatic Pair — Constrained sliding in a guide.  
45. **`cylindrical_pair`** — Cylindrical Pair — Combined turning and sliding.  
46. **`spherical_pair`** — Spherical/Universal Pair — Ball‑like freedom within limits.

### C. Signs of **Coupling** (Contacts & Engagements) — 20
47. **`permanent_union`** — Permanent Union (Rigid) — Constant fastening.  
48. **`keyed_fast`** — Keyed Fast — Fixed upon an axis by key/spline.  
49. **`feathered`** — Feathered (Sliding Key) — Fast in rotation, free to slide.  
50. **`pinned`** — Pinned/Bolted — Fixed by pin, rivet, or bolt.  
51. **`spur_mesh_external`** — Spur Mesh—External — Parallel axes, exterior.  
52. **`spur_mesh_internal`** — Spur Mesh—Internal — Pinion within a ring.  
53. **`bevel_mesh`** — Bevel Mesh — Intersecting axes engagement.  
54. **`worm_drive`** — Worm Drive — Screw to wheel with high reduction.  
55. **`friction_pair`** — Friction Pair — Smooth wheels by pressure.  
56. **`belt_open`** — Belt—Open — Flexible band, concordant rotation.  
57. **`belt_crossed`** — Belt—Crossed — Flexible band, reversing rotation.  
58. **`cord_pulley`** — Cord & Pulley — Round cord upon pulley/drum.  
59. **`chain_drive`** — Chain Drive — Articulated chain upon sprocket.  
60. **`dog_clutch`** — Clutch—Dog/Jaw — Positive entrance by dogs.  
61. **`friction_clutch`** — Clutch—Friction — Entrance by surfaces.  
62. **`conical_clutch`** — Clutch—Conical — Friction clutch with cones.  
63. **`ratchet_pawl`** — Ratchet & Pawl — Advance admitted, return forbade.  
64. **`escapement_impulse`** — Escapement Impulse — Controlled let‑off.  
65. **`brake`** — Band/Brake — Arrest by band or shoe.  
66. **`cord_winder`** — Cord Winder (Take‑Up) — Drum to store/render cord.

### D. Signs of **Governance** (Guards & Interlocks) — 12
67. **`detent`** — Detent (Catch) — Latch that holds or frees.  
68. **`opposed_detents`** — Opposed Detents — Contrary latches; one forbids the other.  
69. **`stop`** — Stop (Limit‑Stop) — Block forbidding travel beyond seat.  
70. **`escapement_beat`** — Escapement Beat — Regulating beat between impulses.  
71. **`clutch_block`** — Clutch Block — Guard forbidding entrance of a clutch.  
72. **`selector`** — Selector (Card/Peg Entrance) — Admission by card/peg/control.  
73. **`mutual_exclusion`** — Mutual Exclusion — A admitted forbids B within Period.  
74. **`precedence`** — Precedence — Fixed order when two trains court one coupling.  
75. **`latch_hold`** — Latch (Hold‑On) — Holds an admitted state until release.  
76. **`release_trip`** — Release (Trip) — Commanded discharge of a latch/detent.  
77. **`governor_fly`** — Governor (Fly) — Regulator steadies speed.  
78. **`safety_fuse`** — Safety Fuse/Shear Link — Sacrificial protection of train.

### E. Signs of **Period & Admission** (Time & Proof) — 12
79. **`admission`** — Admission — Formal permission to act.  
80. **`detention`** — Detention — Formal restraint.  
81. **`engagement`** — Engagement (Make) — Interval/instant of making contact.  
82. **`release`** — Release (Break) — Instant of breaking contact.  
83. **`latch_interval`** — Latch Interval — Interval held by detent/clutch.  
84. **`approach`** — Approach — Time to come into position.  
85. **`execution`** — Execution — Time wherein the work is done.  
86. **`restore`** — Restore — Time to return latches and members.  
87. **`tick`** — Tick — Discrete beat of escapement or pulse.  
88. **`turn_fraction`** — Turn Fraction — Fractional part of a revolution.  
89. **`overlap_window`** — Overlap Window — Declared concurrency needing interlock.  
90. **`interference_mark`** — Interference Mark (Fault) — Token that rule is broken and proof fails.

> **Clerk’s Usage.** Employ these tokens exactly in code and captions. Where a coarse shorthand is used (e.g., `clutch`), the clerk must resolve it to a canon token (e.g., `dog_clutch` or `friction_clutch`) before Proof may pass.

