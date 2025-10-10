# Hyperbolic Braid Engine (HBE)

> **Canon.** The whole is submitted in the idiom of the Babbagean Mechanical Notation (BabbageMN). We commit to **Form**, **Period**, **Train**, **Governance**, and **Proof** as our chief ledgers; the **language of signs** is observed throughout. No geometry, tooth-count, nor gauge is here fixed; only identities, admissions, and their lawful precedence are appointed.

---

## 0) Preambles & Canonical Dispositions

- **Mechanical Alphabet.** Members are named strictly; *pieces* in Capitals, *working points* in lower-case; **permanent unions** are barred (‖). Opposed detents, stops, clutches, and escapements are drawn from the canonical catalogue.
- **Scales & Signs.** Decimal **Store** employs **balanced digits** (−5…+4) with a decoding issue at print (PT‑1). Governance registers are two-position **plates**. Programme medium is a **braided cord tape** with **residue lanes** (mod 7, 9, 11) for self-location.
- **Time Bases.** A **MainTurn** for slow works; a **Tick** escapement for swift governance. Polyphase stanzaing is admitted (Phase A/B/C).
- **Universality.** Two libraries are furnished: **Two‑Counter Calculus** and **Braid‑Head Microcode**; either suffices for a universal clerk.

---

## 1) Apparatus (FORM)

### 1.1 Frames & Axes
- **FRAME_A** (principal upright), **FRAME_B** (Store cheek), **FRAME_C** (Mill cheek).
- **SHAFT_Ω** (main), **SHAFT_α**, **SHAFT_β** (auxiliaries).
- **GOVERNOR_FLY** with safe capture and discharge.

### 1.2 The Triune Store
- **STORE_DEC** — Decimal Storehouse of Columns `Col[i]`, i ∈ ℤ≥0.
  - **PIECES:** `figure_wheel[i,k]` (places k), `carry_dog[i,k]`, `anticipant[i,k]`.
  - **WORKING POINTS:** `cw[i,k].a`, `cw[i,k].b` (advance / settle), `carry[i,k].c`.
  - **MODES:** Balanced‑digit, Carry‑Save ledgers (Sum, Carry), scheduled **Reconcile**.

- **STORE_REG** — Plate‑Register Conclave.
  - **PIECES:** `plate[j]` (two‑position), `selector_comb[r]`, `reset_bar`.
  - **WORKING POINTS:** `plate[j].p` (set), `plate[j].q` (reset), `comb[r].s`.
  - **MODES:** Temporal majority read (k−1,k,k+1); Hamiltonian single‑change orderings.

- **STORE_BRAID** — Braid Magazine & Head.
  - **PIECES:** `cord`, `sprocket`, `cord_winder`, `residue_lane{5,7,9,11} (PT‑2)`, `feeler_read[m]`, `pawl_write`.
  - **WORKING POINTS:** `head.l` (left step), `head.r` (right step), `head.u` (raise knot), `head.d` (lower), `lane[t].f` (residue feeler).
  - **MODES:** Self‑witnessing symbols (parity + forbidden prefixes); Chinese‑Remainder position recovery.

### 1.3 The Symplectic Mill
- **MILL_DIFF** — Differential Mesh & Integrators.
  - **PIECES:** `diff[p]`, `worm[q]`, `clutch[c]` (dog‑tooth), `reversal_cam`.
- **MILL_CAM** — Function‑Cams for logarithmic conveyance.
  - **PIECES:** `cam_principal` (hyperbolic law; nodes per CT‑1), `cam_whisper` (residual), `follower_shoe[W_shoe]` with **W_shoe := 1⁄3·δ_node** (δ_node = minimum Chebyshev node spacing along the sweep), `ratio_train` (Chebyshev nodes), `diff_whisper` (summing differential), `clutch[c_cam]`, `clutch[c_w]`.
  - **MODES:** Whisper engagement is a declared admission (`WHISPER_ON`), amplitude **1:10**, speed **10:1** relative to principal (PT‑5); follower settle required before release.- **MILL_ROT** — Rotation Engine by Admitted Increments.
  - **PIECES:** `lever_scale[s]` (dyadic 1:2^s; PT‑3), `sign_toggle`, `sum_diff_link`, `norm_pair` (renormalising gears p:q = 135:82; PT‑4).
  - **MODES:** Palindromic micro‑stanzas `(+α/2, +β, +α/2)`; involutory patterns for reversibility.

### 1.4 Programme Apparatus & I/O
- **PEG_BARREL**, **CARD_SERIES** (operation/variable/number).
- **PRINT_ENGINE** — Issue & Table of the Work.
  - **PIECES:** `type_wheel[k]` (0…9), `impression_lever`, `paper_carriage`, `line_ratchet`, `decode_bar` (borrow carry to higher place), `double_strike_detent`, `audit_wheels` {**⑨**, **⑪**}, `proof_gate` (prove‑again), `ink_bar` (may be lifted for dry trial).
  - **WORKING POINTS:** `tw[k].pick` (select figure), `impress.p` (strike), `paper.advance`, `audit.tick9`, `audit.tick11`.
  - **GUARDS:** `Opposed_β(κ₄)` (single seizure); `Block_γ(LateFigure)` (detains impression until `Digits_Balanced` latched); `Block_γ(DoubleStrike)` (detains repeat strike until `paper.advance`).
  - **DECODING STANZA (balanced → ordinary):** For each place low→high, if stored digit `d∈{−5…−1}`, print `10+d` and actuate `decode_bar` to **borrow +1** to the next higher place for this print only; if `d≥0`, print `d` without borrow. Decode is purely **issue‑side**; the Store remains balanced.

---

## 2) Periods (TIME LEDGER)
> Declare admissions, dwells, releases; forbid overlaps upon the same coupling save by interlock.

### 2.1 Time Bases & Phasing
- `MainTurn` period: `T_Ω` (placeholder).
- `Tick` period: `τ` with sub‑ticks for temporal majority (−1, 0, +1).
- **Polyphase Stanzaing:** `{Phase A, Phase B, Phase C}`; each touches disjoint coupling classes.

### 2.2 Latin‑Square Timetable (Collision‑Free)

> **Aim.** In every Tick, each coupling class κ₁…κ₄ is seized by at most one stanza; by Latin arrangement, columns contain each symbol once. We treat **S1…S4 as slot classes**, then map them per‑row to lawful stanzas.

**Coupling classes.** κ₁: Store‑Carriage · κ₂: Braid‑Step · κ₃: Mill‑Traverse · κ₄: Print.

**Slot classes.** S1, S2, S3, S4 (Latin symbols).

**Row‑wise mapping of slot → stanza:**
- κ₁ (Store): S1→`DecimalAdvance` (FETCH/RESTORE/ACCUMULATE), S2→`Reconcile` (carry drizzle), S3→Idle, S4→Idle.
- κ₂ (Braid): S1→`BraidStep/Read/Write` (tape head), S2→Idle, S3→`BraidStep/Read/Write`, S4→Idle.
- κ₃ (Mill): S1→`CamTraverse`, S2→`RotateStep` (and `Normalise` if declared), S3→`CamTraverse`, S4→`RotateStep` (and `Normalise`).
- κ₄ (Print): S1→`PrintIssue/Audit`, S2→Idle, S3→`PrintIssue/Audit`, S4→Idle.

**Latin block (period 4 ticks), repeated.**

```
Tick class  :   t0   |   t1   |   t2   |   t3
Phase       :    A   |    B   |    C   |    A   (phases then continue B,C,A… over repeats)
κ1 (Store)  :   S1   |   S2   |   S3   |   S4
κ2 (Braid)  :   S1   |   S2   |   S3   |   S4
κ3 (Mill)   :   S1   |   S2   |   S3   |   S4
κ4 (Print)  :   S1   |   S2   |   S3   |   S4
```

**Twelve‑tick cycle (three Latin blocks) with phases.**

| Tick t | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Slot S | S1 | S2 | S3 | S4 | S1 | S2 | S3 | S4 | S1 | S2 | S3 | S4 |
| Phase  |  A |  B |  C |  A |  B |  C |  A |  B |  C |  A |  B |  C |

**Availability (per stanza family):**
- `DecimalAdvance/Accumulate` → ticks {0,4,8} (κ₁·S1; phases A,B, C respectively).
- `Reconcile` (carry drizzle) → ticks {1,5,9} (κ₁·S2; phases B, C, A).
- `BraidStep/Read/Write` → ticks {0,2,4,6,8,10} (κ₂·S1,S3; phases A,C,B,A,C,B).
- `CamTraverse` → ticks {0,2,4,6,8,10} (κ₃·S1,S3; phases A,C,B,A,C,B).
- `RotateStep/Normalise` → ticks {1,3,5,7,9,11} (κ₃·S2,S4; phases B,A,C,B,A,C).
- `PrintIssue/Audit` → ticks {0,2,4,6,8,10} (κ₄·S1,S3; phases A,C,B,A,C,B).

### 2.3 Reset Windows & Settling
- After any bank flip in **STORE_REG**, admit `Reset_Window[1·τ]` before next trial (temporal‑majority window over sub‑ticks −1,0,+1).
- After any **κ₁·S1** engagement, reserve a **Settle_Slot[⅓·τ]** immediately following for carry drizzle; **CARRY_RECONCILE** consumes this slot in ticks {1,5,9} (κ₁·S2). Where reconciliation is not needed, the slot remains open for settle only.
- Plate temporal‑majority cadence: sample at sub‑ticks **(t−1, t, t+1)** and decide by 2‑of‑3, then honour `Reset_Window` before any further admission.
 Reset Windows & Settling
- After any bank flip in **STORE_REG**, admit `Reset_Window[1·τ]` before next trial (temporal‑majority window over sub‑ticks −1,0,+1).
- Decimal **Reconcile** reserved to calm carry drizzle once per macro‑stanza.

### 2.4 Palindromic & Involutory Patterns
- For **MILL_ROT** steps, enforce palindrome admission per sub‑tick to cancel even‑order defects.
- For reversible trains, mirror stanza sequences to enable true backing and energy husbandry.

---

## 3) Trains (CAUSATION)
> Each stanza: **Entrance** → **Admissions** (with order) → **Unless Guarded** → **Issues** (named outcomes).

### 3.1 Primitive Stanzas (Executable Idiom)
> **Form of each stanza:** *Entrance* → ordered *Admissions* (with couplings κ and working points in lower‑case) → *Unless* (Guard) → *Issue* → *Phase/Tick‑class* → *Hazard Note*.

**BRAID_STEP(dir)**
- *Entrance:* `E_Braid` *(κ₂)*.
- *Admissions (order):*
  1) `Opposed_β(κ₂)` proves coupling free; admit `head.l` **or** `head.r` (per `dir`).
  2) Engage `sprocket` to `cord` by `clutch[c₂]`; advance one step; dwell `Settle_Slot[⅓·τ]`.
  3) Sample residues by `lane[5].f`, `lane[7].f`, `lane[9].f`, `lane[11].f` across sub‑ticks (t−1,t,t+1); latch residues.
- *Unless:* `Block_γ` if any write admission is pending within κ₂ at this tick.
- *Issue:* `Pos_Update` (absolute by CRT; PT‑2).
- *Phase/Tick‑class:* κ₂·(S1,S3) → ticks {0,2,4,6,8,10}; phases {A,C,B,A,C,B}.
- *Guard pattern:* `Opposed_β(κ₂)` then `Block_γ` during Settle.
- *Hazard Note:* Do not step during write; precedence `Settle ≺ Read ≺ Write` enforced by schedule and guard.

**KNOT_READ → SYM**
- *Entrance:* `E_Read` *(κ₂)*.
- *Admissions (order):*
  1) Honour preceding `Settle_Slot[⅓·τ]` if a step occurred.
  2) Lower `feeler_read[m]` upon symbol word; perform **parity trial** and **forbidden‑pattern** test.
- *Unless:* `Stop_σ` on inconsistent word; `Opposed_β(κ₂)` if κ₂ already seized.
- *Issue:* `SYM{0,1,Blank,Error}`.
- *Phase/Tick‑class:* κ₂·(S1,S3) → ticks {0,2,4,6,8,10}; phases {A,C,B,A,C,B}.
- *Guard pattern:* `Opposed_β(κ₂)`; `Stop_σ` on error.
- *Hazard Note:* Bruised knots return `Error` rather than silent misread.

**KNOT_WRITE(SYM)**
- *Entrance:* `E_Write` *(κ₂)*.
- *Admissions (order):*
  1) `Opposed_β(κ₂)` proves exclusivity on κ₂.
  2) Raise or lower via `pawl_write` to stamp the word; enforce **forbidden prefix/suffix** pattern and parity.
  3) Dwell `Settle_Slot[⅓·τ]` to allow fibre recovery.
- *Unless:* `Stop_σ` if input `SYM=Error`.
- *Issue:* `Word_Stamped` (with parity witness).
- *Phase/Tick‑class:* κ₂·(S1,S3) → ticks {0,2,4,6,8,10}; phases {A,C,B,A,C,B}.
- *Guard pattern:* `Opposed_β(κ₂)`; `Stop_σ`.
- *Hazard Note:* Writing during plate reset is detained by `Block_γ` (cross‑guarded event).

**PLATE_TEST(j) → BRANCH**
- *Entrance:* `E_Test` *(non‑seizing; plate governance only).* 
- *Admissions (order):*
  1) Temporal majority read of `plate[j]` at sub‑ticks (t−1, t, t+1).
  2) Present result to `Opposed_β` branch detents.
- *Unless:* `Block_γ` during `Reset_Window[1·τ]` after any set/reset on the same bank.
- *Issue:* `Branch{True,False}`.
- *Phase/Tick‑class:* May occur in any tick, consumes no κ; honours `Reset_Window[1·τ]` (Table P‑2).
- *Guard pattern:* `Block_γ` during reset; `Opposed_β` for branch.
- *Hazard Note:* Mid‑state plates are undecided; branch detained until majority settles.

**DECIMAL_FETCH(i) / DECIMAL_RESTORE(i)**
- *Entrance:* `E_Fetch` / `E_Store` *(κ₁).* 
- *Admissions (order):*
  1) `Opposed_β(κ₁)` proves coupling free.
  2) Couple `Col[i]` via `clutch[c₁]` to Mill; other columns parked.
  3) For RESTORE: dwell `Settle_Slot[⅓·τ]` before release.
- *Unless:* `Block_γ` if carry drizzle is in progress.
- *Issue:* `Value_to_Mill` / `Value_from_Mill`.
- *Phase/Tick‑class:* κ₁·S1 → ticks {0,4,8}; phases {A,B,C}.
- *Guard pattern:* `Opposed_β(κ₁)`; `Block_γ` vs reconciliation.
- *Hazard Note:* Avoid mass carriage; reconciliation is segregated to κ₁·S2.

**CARRY_SAVE_ACCUMULATE**
- *Entrance:* `E_Acc` *(κ₁).* 
- *Admissions (order):*
  1) Write addends to **Sum** ledger; update **Carry** ledger separately (no propagate).
  2) Latch partial totals.
- *Unless:* `Block_γ` if a Settle slot is active.
- *Issue:* `Partial_Totals`.
- *Phase/Tick‑class:* κ₁·S1 → ticks {0,4,8}; phases {A,B,C}.
- *Guard pattern:* `Opposed_β(κ₁)`; `Block_γ` during settle.
- *Hazard Note:* Mis‑phase with reconciliation barred by Latin schedule.

**CARRY_RECONCILE** (scheduled)
- *Entrance:* `E_Reconcile` *(κ₁).* 
- *Admissions (order):*
  1) For each place, drizzle carry ±1 to neighbour; ensure local bounds {−5…+4} (PT‑1).
  2) Dwell `Settle_Slot[⅓·τ]` and latch.
- *Unless:* `Opposed_β(κ₁)` if κ₁ already seized by S1.
- *Issue:* `Digits_Balanced`.
- *Phase/Tick‑class:* κ₁·S2 → ticks {1,5,9}; phases {B,C,A}.
- *Guard pattern:* `Opposed_β(κ₁)` ensures segregation from S1 works.
- *Hazard Note:* Mass advance is forbidden; only ±1 per place per admission.

**CAM_TRAVERSE(f)**
  - *Entrance:* `E_Cam[f]` *(κ₃).* 
  - *Admissions (order):*
  1) `Opposed_β(κ₃)` proves exclusivity; `Clutch_Interlock_δ` confirms no other κ₃ clutch active.
  2) Engage `clutch[c_cam]` to `cam_principal`; set follower to **node plan CT‑1** (Chebyshev nodes). 
  3) **WHISPER_ON:** engage `clutch[c_w]` to `diff_whisper`, summing `cam_whisper` at amplitude **1:10** and speed **10:1** (PT‑5) to cancel equal‑ripple residual.
  4) Bring `follower_shoe[W_shoe]` to seat; dwell `Settle_Slot[⅓·τ]`; latch `Seat_f`.
  - *Unless:* `Block_γ` if follower unsettled; `Clutch_Interlock_δ` if any κ₃ clutch seized.
  - *Issue:* `Seat_f` to MILL_DIFF; **ε_cam ≤ 3×10⁻³** full‑scale before whisper, **≤ 3×10⁻⁴** after whisper (CT‑3).
  - *Phase/Tick‑class:* κ₃·(S1,S3) → ticks {0,2,4,6,8,10}; phases {A,C,B,A,C,B}.
  - *Guard pattern:* `Opposed_β(κ₃)`; `Clutch_Interlock_δ`; `Block_γ` for settle.

- **ROTATE_STEP(sign, scale_idx)**
  - *Entrance:* `E_Rotate`.
  - *Admissions:* `lever_scale[scale_idx]` ±, palindromic order; update (x,y).
  - *Issue:* `(x',y')`, *Unless:* `Block_γ` on unsettled follower.
  - **Phase/Tick‑class:** κ₃·(S2,S4) → ticks {1,3,5,7,9,11}; phases {B,A,C,B,A,C}.

- **NORMALISE(135:82)**
  - *Entrance:* `E_Norm` at stanza boundary.
  - *Admissions:* couple fixed ratio train 135:82; single clean stroke.
  - *Issue:* `Scaled_OK`.
  - **Phase/Tick‑class:** prefer κ₃·S4 immediately after a rotation run (ticks {3,7,11}); else κ₃·S2 (ticks {1,5,9}).

- **AUDIT_CONGRUENCE(mod 9, 11)**
  - *Entrance:* `E_Audit` (per macro‑stanza end).
  - *Admissions:* tally wheels advance from ledger; compare to expectation.
  - *Issue:* `Audit{Pass,Fail}`.
  - **Phase/Tick‑class:** κ₄·(S1,S3) alongside print cadence; ticks {0,2,4,6,8,10}.

- **PRINT_ISSUE**
  - *Entrance:* `E_Print`.
  - *Admissions:* couple selected columns to type‑wheels; guard against late figures.
  - *Issue:* `Table_of_the_Work` lines.
  - **Phase/Tick‑class:** κ₄·(S1,S3) → ticks {0,2,4,6,8,10}; phases {A,C,B,A,C,B}.

$1 Control Stanzas (Universality)
- **COUNTER_INC/DECZ(k)** — Two‑Counter primitives with zero‑trial branch.
- **TAPE_MACHINE_STEP** — `{BraidStep, KnotRead, KnotWrite, Branch}` trio.
- **POTENTIAL_CHECK(Φ)** — Ranking function strictly diminishes on loop admission.

---

### 3.2 Control Stanzas (Universality)
> Two minimal libraries are furnished as **macros** over the primitive stanzas of §3.1. No new pieces; only admissions, guards, and lawful order. Phase/Tick availability follows Table P‑1.

#### A) Two‑Counter Calculus — Macro Stanzas
Let `COUNTER[k] := Col[c_k…c_k+L−1]` for `k∈{0,1}`; constants `ONE := …001` and `ZERO := …000` reside in Store.

**INC(k)** *(increment COUNTER[k] by 1)*
- *Entrance:* `E_INC(k)`.
- *Macro (κ & order):* κ₁·S1 `DECIMAL_FETCH(c_k…)` → κ₁·S1 `CARRY_SAVE_ACCUMULATE(+ONE)` → κ₁·S2 `CARRY_RECONCILE` → κ₁·S1 `DECIMAL_RESTORE(c_k…)`.
- *Unless:* `Block_γ` vs settle; `Opposed_β(κ₁)` exclusivity.
- *Issue:* `COUNTER[k] ← COUNTER[k]+1`.
- *Phase/Tick‑class:* κ₁·S1/S2 as cited.

**DECZ(k) → BRANCH{Zero,NonZero}** *(decrement if non‑zero; branch on result)*
- *Entrance:* `E_DECZ(k)`.
- *Macro:*
  1) κ₁·S1 `DECIMAL_FETCH(c_k…)` → κ₁·S1 `CARRY_SAVE_ACCUMULATE(−ONE)` → κ₁·S2 `CARRY_RECONCILE`.
  2) Test sign/zero by `PLATE_TEST(Sign(c_k))` (temporal majority; Table P‑2).
  3) Branch: if **Zero/Non‑negative**, *Issue:* `Zero` after restoring by κ₁·S1 `CARRY_SAVE_ACCUMULATE(+ONE)` → κ₁·S2 `CARRY_RECONCILE`; else *Issue:* `NonZero` (value kept decremented).
- *Unless:* `Block_γ` during settle.
- *Phase/Tick‑class:* as above.

**CLEAR(k)** *(set to zero)*
- *Entrance:* `E_CLEAR(k)`.
- *Macro:* κ₁·S1 `DECIMAL_FETCH(c_k…)` → overwrite by κ₁·S1 `DECIMAL_RESTORE(ZERO)`; or loop `DECZ(k)` until `Zero` with `POTENTIAL_CHECK(Φ:=|COUNTER[k]|)` (strictly decreasing).
- *Issue:* `COUNTER[k] ← 0`.

**COPY(a → b)** *(preserve a; copy value to b)*
- *Entrance:* `E_COPY(a→b)`.
- *Aux:* scratch `TMP := Col[t…]` initially 0.
- *Macro (shuttle):*
  1) Loop L₁: `DECZ(a) → BRANCH{Zero,NonZero}`. On `NonZero`: `INC(b)`; `INC(TMP)`; back to L₁. On `Zero`: proceed.
  2) Loop L₂: `DECZ(TMP) → BRANCH{Zero,NonZero}`. On `NonZero`: `INC(a)`; back to L₂. On `Zero`: finish.
- *POTENTIAL_CHECK:* Φ₁:=|a| for L₁; Φ₂:=|TMP| for L₂ — both strictly decrease.
- *Issue:* `b ← a`, `a` restored.

#### B) Braid‑Head Clerk — Macro Stanzas
Let the head operate on `STORE_BRAID` with residue lanes {5,7,9,11} (PT‑2) and symbol words with parity.

**TAPE_STEP(Left/Right)**
- *Entrance:* `E_TAPE_STEP(dir)`.
- *Macro:* κ₂·(S1/S3) `BRAID_STEP(dir)` → absolute position recovered by residues; latch index.
- *Issue:* `Pos_Update`.

**TAPE_READ → SYM**
- *Entrance:* `E_TAPE_READ`.
- *Macro:* κ₂·(S1/S3) `KNOT_READ` → *Issue:* `SYM{0,1,Blank,Error}`.

**TAPE_WRITE(SYM)**
- *Entrance:* `E_TAPE_WRITE`.
- *Macro:* κ₂·(S1/S3) `KNOT_WRITE(SYM)` → *Issue:* `Word_Stamped`.

**TAPE_BRANCH(test) → BRANCH**
- *Entrance:* `E_TAPE_BRANCH(test)` where `test ∈ {Is0, Is1, IsBlank, IsError}`.
- *Macro:* `TAPE_READ` then branch by `PLATE_TEST` on outcome plates to `BRANCH{True,False}`.
- *Guards:* `Opposed_β(κ₂)`; `Stop_σ` on Error.

**Witness:** absolute position recovery is built into `BRAID_STEP` by residues {5,7,9,11}; no extra stanza.

## 4) Combined & Tested Operations (LIBRARIES)

### 4.1 Arithmetic & Functions (Executable Combined & Tested Operations)
> **Idiom.** Each operation appoints Variables (Store bindings), then cites primitive stanzas in lawful order with phase/tick availability implied by §2.2. All arithmetic uses **balanced‑digit carry‑save** with scheduled **CARRY_RECONCILE**. Tables show only headings and audits; figures are clerkly.

---

**ADD(A, B → S)**
- *Variables:* Appoint `A := Col[a…a+L−1]`, `B := Col[b…b+L−1]`, `S := Col[s…s+L−1]` (balanced digits; PT‑1). Ledgers: `Sum_S`, `Carry_S`.
- *Course (κ & stanzas):*
  1) κ₁·S1 — `DECIMAL_FETCH(a…a+L−1)`; `DECIMAL_FETCH(b…b+L−1)`.
  2) κ₁·S1 — `CARRY_SAVE_ACCUMULATE` (A,B → Sum_S, Carry_S).
  3) κ₁·S2 — `CARRY_RECONCILE` (drizzle ±1; PT‑1); dwell `Settle_Slot`.
  4) κ₁·S1 — `DECIMAL_RESTORE(s…s+L−1)` (from Sum_S & Carry_S). 
  5) κ₄·(S1/S3) — `AUDIT_CONGRUENCE(mod 9,11)`.
- *Issue:* `S = A + B` (balanced digits).
- *Hazard:* Mass carriage barred; reconciliation segregated to κ₁·S2.
- *Table of the Work (skeleton):*
  | Line | A | B | → | S | mod9 | mod11 |
  |:--:|:--:|:--:|:--:|:--:|:--:|:--:|

---

**SUB(A, B → D)** *(as addition with sign inversion)*
- *Variables:* `A := Col[a…]`, `B := Col[b…]`, `D := Col[d…]`.
- *Course:*
  1) κ₁·S1 — `DECIMAL_FETCH(a…)`; `DECIMAL_FETCH(b…)`.
  2) κ₃·S2 — **Sign inversion of B** by Mill sign toggle on the transfer train (piece `sign_toggle`), then return to Store bus.
  3) κ₁·S1 — `CARRY_SAVE_ACCUMULATE` (A, −B → Sum_D, Carry_D).
  4) κ₁·S2 — `CARRY_RECONCILE`; dwell settle.
  5) κ₁·S1 — `DECIMAL_RESTORE(d…)`.
  6) κ₄·(S1/S3) — `AUDIT_CONGRUENCE`.
- *Issue:* `D = A − B`.
- *Hazard:* Toggle acts on fetched B only; barred from affecting parked columns by `Opposed_β(κ₃)`.
- *Table skeleton:* as ADD with D in the result column.

---

**MULTIPLY(Log‑Cam)  (X · Y → P)**
- *Variables:* `X := Col[x…]`, `Y := Col[y…]`, `P := Col[p…]`.
- *Course:*
  1) κ₁·S1 — `DECIMAL_FETCH(x…)` → Mill.
  2) κ₃·S1 — `CAM_TRAVERSE(log)` → issue `Seat_logX` to `MILL_DIFF`.
  3) κ₁·S1 — `DECIMAL_FETCH(y…)` → Mill.
  4) κ₃·S3 — `CAM_TRAVERSE(log)` → issue `Seat_logY`; **MILL_DIFF** sums `Seat_logX + Seat_logY` by its natural union (no extra stanza).
  5) κ₃·S2 — `CAM_TRAVERSE(exp)` *(reverse train)* to convert summed seat to magnitude.
  6) κ₁·S1 — `DECIMAL_RESTORE(p…)` (carry‑save then reconcile at next κ₁·S2).
  7) κ₄·(S1/S3) — `AUDIT_CONGRUENCE`.
- *Issue:* `P = X·Y` (balanced digits). ε bounded by PT‑5 (equal‑ripple + whisper).
- *Hazard:* Follower must settle each traverse; `Block_γ` enforces.
- *Table skeleton:* `X | Y | → | P | mod9 | mod11`.

---

**MULTIPLY(Rotation)  (X · Y → P)** *(dyadic accumulation via MILL_ROT)*
- *Variables:* `X := Col[x…]` (multiplicand vectorised as (X,0)), `Y := Col[y…]` (multiplier), `P := Col[p…]`.
- *Course:*
  1) κ₁·S1 — `DECIMAL_FETCH(x…)` → Mill registers (seed `(x,0)`).
  2) **Dyadic Expansion of |Y|**: use plate bank `plate[Dyad_s]` to mark bits of a dyadic schedule (derived from Y’s decimal by clerkly microcode using `PLATE_TEST` and balanced decrements during κ₁·S1 / κ₁·S2 beats; no new pieces).
  3) For each marked scale `s` (in descending order): κ₃·(S2/S4) — `ROTATE_STEP(sign=+ , scale_idx=s)` palindromically add scaled copy into the accumulator path; dwell settle each tick.
  4) If `Y < 0`, perform one κ₃·S2 sign toggle on the accumulator.
  5) κ₁·S1 — `DECIMAL_RESTORE(p…)`; κ₁·S2 — `CARRY_RECONCILE`.
  6) κ₄ — `AUDIT_CONGRUENCE`.
- *Issue:* `P = X·Y`.
- *Hazard:* Dyadic schedule must not collide with Store carriage; Latin timetable ensures κ₁ vs κ₃ separation.
- *Table skeleton:* as above.

---

**DIVIDE  (N ÷ D → Q, R)** *(restoring division with convergents)*
- *Variables:* `N := Col[n…]` (numerator), `D := Col[d…]` (denominator, ≠0), `Q := Col[q…]`, `R := Col[r…]`.
- *Course:*
  1) κ₁·S1 — `DECIMAL_FETCH(n…)`; `DECIMAL_FETCH(d…)`.
  2) Loop (bounded by POTENTIAL Φ = remaining digits of N):
     - κ₁·S1 — Trial subtract: `CARRY_SAVE_ACCUMULATE` (R := N − D·10^k for current k).
     - κ₁·S2 — `CARRY_RECONCILE`; if R≥0 then set quotient digit q_k and keep R; else undo (restore) by adding back one D·10^k and set q_k−=1. (Branch by `PLATE_TEST` on sign/zero.)
  3) κ₁·S1 — `DECIMAL_RESTORE(q…)`, `DECIMAL_RESTORE(r…)`.
  4) κ₄ — `AUDIT_CONGRUENCE`.
- *Issue:* `Q` quotient, `R` remainder with `0 ≤ R < |D|`.
- *Hazard:* Trial/restore guarded to alternate beats; `Opposed_β(κ₁)` forbids overlap.
- *Table skeleton:* `N | D | → | Q | R | mod9 | mod11`.

---

**RECIPROCAL  (A → 1/A)** *(Möbius cascade, few stages)*
- *Variables:* `A := Col[a…]`, `R := Col[r…]`.
- *Course:*
  1) κ₁·S1 — `DECIMAL_FETCH(a…)`.
  2) κ₃·(S1/S3) — two to four **Möbius stages**: each stage implements `(u,v) ← (α·u+β·v , γ·u+δ·v)` by lever ratios; choose small integers (continued‑fraction convergents of 1/A). (No new stanzas; uses `CAM_TRAVERSE` where a seat is required, else direct ratios.)
  3) κ₁·S1 — `DECIMAL_RESTORE(r…)`; κ₁·S2 — `CARRY_RECONCILE`.
  4) κ₄ — `AUDIT_CONGRUENCE`.
- *Issue:* `R ≈ 1/A` to declared digits.
- *Hazard:* Stage boundaries only; barred mid‑tick re‑ratios by `Block_γ`.
- *Table skeleton:* `A | → | 1/A | mod9 | mod11`.

---

**ROOT  (√A → S)** *(restoring digit‑by‑digit square‑root)*
- *Variables:* `A := Col[a…]` (grouped in pairs of digits), `S := Col[s…]` (root), `R := Col[r…]` (remainder).
- *Course:*
  1) κ₁·S1 — `DECIMAL_FETCH(a…)`.
  2) For each digit pair from most to least significant:
     - κ₁·S1 — Trial subtract `(20·S + 1)·10^k` from the working remainder using `CARRY_SAVE_ACCUMULATE` (classic restoring root step in balanced digits).
     - κ₁·S2 — `CARRY_RECONCILE` and test sign via `PLATE_TEST`; if negative, restore and set digit d_k one less; else accept and update `S`.
  3) κ₁·S1 — `DECIMAL_RESTORE(s…)`, `DECIMAL_RESTORE(r…)`.
  4) κ₄ — `AUDIT_CONGRUENCE`.
- *Issue:* `S = ⌊√A⌋`, `R = A − S²`.
- *Hazard:* Trial/restore strictly alternated; guards as in DIVIDE.
- *Table skeleton:* `A | → | √A | R | mod9 | mod11`.

---

**Notes common to all operations.**
- All κ₁ actions occur at ticks {0,4,8} for S1 and {1,5,9} for S2; κ₃ traversals/rotations occur at the complementary ticks (§2.2). 
- Where a branch is required, `PLATE_TEST` uses temporal majority and honours `Reset_Window[1·τ]`.
- No new pieces are introduced; differentials, cams, and rotation levers are those already seated in §1.3.

### 4.1A Trigonometric Annex — Rotation with Palindromes & Single Normalise
> Uses **MILL_ROT** palindromic micro‑stanzas (PT‑3) with a **single** `NORMALISE(135:82)` at stanza boundaries (PT‑4). No new pieces.

#### A) SINE & COSINE by Rotation (SINCOS)
- *Variables:* `Θ := Col[θ…]` (angle), `(X,Y)` are Mill registers seeded to `(1,0)`; results to `C := Col[c…]`, `S := Col[s…]`. Angle constants `ANGLE_TABLE[s]` where `tan(α_s)=2^{−s}` for `s∈{0…9}` (PT‑3).
- *Target precision:* **D ≈ 3 decimal digits** with `s=0…9`. To reach **D ≈ 4**, extend to `s=0…13` (table extensible without altering idiom).
- *Stroke sequence (lever scales admitted):* `s = 0,1,2,3,4,5,6,7,8,9`.
  - At each `s`, decide `sign := sgn(R)` where `R` is the residual angle; admit `ROTATE_STEP(sign, s)` as a palindrome. Update `R ← R − sign·α_s` via Store addition: `DECIMAL_FETCH(ANGLE_TABLE[s])` + `CARRY_SAVE_ACCUMULATE` + `CARRY_RECONCILE` on κ₁ beats.
  - Phase/ticks: `ROTATE_STEP` occurs at κ₃·(S2,S4) alternating per Latin schedule; the residual update uses κ₁·S1/S2 between rotation ticks.
- *Course (end‑to‑end):*
  1) κ₁·S1 — `DECIMAL_FETCH(θ…)`; set Mill `(X,Y) ← (1,0)`; set residual `R ← Θ`.
  2) For `s` in 0…9:
     - κ₃·(S2 or S4) — `ROTATE_STEP(sign := sgn(R), scale_idx := s)` (palindromic).
     - κ₁·S1/S2 — update `R ← R − sign·α_s` using `ANGLE_TABLE[s]` (carry‑save then reconcile).
  3) κ₃·S4 — `NORMALISE(135:82)` once.
  4) κ₁·S1 — `DECIMAL_RESTORE(c…)`, `DECIMAL_RESTORE(s…)` from Mill `(X,Y)`; κ₄ — `AUDIT_CONGRUENCE`.
- *Issue:* `(C,S) = (cos Θ, sin Θ)` to **D ≈ 3** decimal digits (extend s‑range for more).
- *Potential & termination:* `Φ := Σ_{k≥s} α_k` strictly decreases each iteration; `Φ_10 ≤ α_10 < 2^{−10}` hence bounded loop. `POTENTIAL_CHECK(Φ)` before each back‑edge.
- *Error budget:* After step `n=10`:
  - **Angular truncation:** `|R_n| ≤ Σ_{k≥n} α_k < 2^{−n}` (since `α_k ≈ arctan 2^{−k} ≤ 2^{−k}`) ⇒ < **9.8×10⁻⁴ rad**.
  - **Scale:** pre‑normalise gain `K_10`; post‑normalise relative error ≤ `|(135/82)/K_10 − 1|` ≲ **2.5×10⁻⁴** (PT‑4).
  - **Digit & reconcile:** balanced‑digit drizzle confines roundoff to ≤ **1 ulp** at the least place of `(C,S)`.
  - **Total:** within **~3 decimal digits**; extend `s` to improve bound geometrically.
- *Stroke‑order table (TT‑1, 10‑scale pattern):*

| Iter i | Scale s | tan(α_s) | Admission | κ/tick class |
|:--:|:--:|:--:|:--|:--|
| 1 | 0 | 1 | `ROTATE_STEP(sign:=sgn R, s:=0)` | κ₃·S2 |
| 2 | 1 | 1/2 | `ROTATE_STEP(sign:=sgn R, s:=1)` | κ₃·S4 |
| 3 | 2 | 1/4 | `ROTATE_STEP(sign:=sgn R, s:=2)` | κ₃·S2 |
| 4 | 3 | 1/8 | `ROTATE_STEP(sign:=sgn R, s:=3)` | κ₃·S4 |
| 5 | 4 | 1/16 | `ROTATE_STEP(sign:=sgn R, s:=4)` | κ₃·S2 |
| 6 | 5 | 1/32 | `ROTATE_STEP(sign:=sgn R, s:=5)` | κ₃·S4 |
| 7 | 6 | 1/64 | `ROTATE_STEP(sign:=sgn R, s:=6)` | κ₃·S2 |
| 8 | 7 | 1/128 | `ROTATE_STEP(sign:=sgn R, s:=7)` | κ₃·S4 |
| 9 | 8 | 1/256 | `ROTATE_STEP(sign:=sgn R, s:=8)` | κ₃·S2 |
| 10 | 9 | 1/512 | `ROTATE_STEP(sign:=sgn R, s:=9)` | κ₃·S4 |

- *Specimen loop (sign‑choosing stanza):*
  - `PLATE_TEST(Sign_R) → BRANCH{Plus,Minus}` where `Sign_R` is the sign plate of residual `R` (temporal majority with `Reset_Window`).
  - Branch to the `ROTATE_STEP(+,s)` or `ROTATE_STEP(−,s)` entrance accordingly; then schedule the residual update on κ₁.

#### B) ATAN by Vectoring (optional)
- *Aim:* Given `(X,Y)` in Mill, return `Angle := atan2(Y,X)` and `R := √(X²+Y²)` (post‑normalise magnitude).
- *Variables:* `(X,Y)` in Mill, `Angle := Col[ang…]` (starts at 0).
- *Course:*
  1) For `s` in 0…9:
     - Choose `sign := sgn(Y)` (drive Y toward 0).
     - κ₃·(S2/S4) — `ROTATE_STEP(sign:=−sgn(Y), s)` (vectoring mode); 
     - κ₁·S1/S2 — update `Angle ← Angle + sign·α_s` via `ANGLE_TABLE[s]` (carry‑save & reconcile).
  2) κ₃·S4 — `NORMALISE(135:82)` to scale `(X,Y)` once.
  3) κ₁·S1 — `DECIMAL_RESTORE(ang…)`; optional store of magnitude to `Col[r…]`.
- *Potential:* `Φ := |Y| + Σ_{k≥s} α_k` strictly decreases (lexicographic by tick), guaranteeing finish.

#### C) Angle Table & Cross‑References
- `ANGLE_TABLE[s]` is a small Store list of the **α_s** expressed as signed‑digit decimals, referenced in residual updates; these are constants derived from PT‑3 (no geometry fixed here).
- `ROTATE_STEP` and `NORMALISE(135:82)` are those defined in §3.1; tick‑class availability is per Table P‑1.

---

## Annex B — Trigonometric Tables (TT‑series)

**TT‑1. Stroke Order (10‑scale SINCOS)** — see table above. Extensible to more scales by continuing the dyadic sequence.

**TT‑2. Error Budget Summary (10‑scale)**

| Component | Bound |
|:--|:--|
| Angular truncation | `< 2^{−10}` rad ≈ 9.8×10⁻⁴ |
| Post‑normalise scale error | `< 2.5×10⁻⁴` relative (PT‑4) |
| Digit reconcile | `≤ 1 ulp` at least place |
| Total practical | ≈ 3 decimal digits; extend scales for more |

### 4.2 Control & Flow — Universality Libraries
> Calling conventions, witness routines, and termination discipline for the Two‑Counter Calculus (A) and the Braid‑Head Clerk (B). These are **libraries** atop §3.2 macros and §3.1 primitives.

#### Library A — Two‑Counter Calculus
**Calling Conventions.**
- **Entrances:** `E_INC(k)`, `E_DECZ(k)`, `E_CLEAR(k)`, `E_COPY(a→b)`.
- **Appointments:** `COUNTER[0] := Col[c₀…]`, `COUNTER[1] := Col[c₁…]`, scratch `TMP := Col[t…]` (cleared on entry).
- **Issues:** Branch tokens `{Zero,NonZero}` per `DECZ`; counters updated in place.
- **Phasing:** All actions on κ₁ per Table P‑1; reconciliation uses κ₁·S2 with settle.

**Witness Routine A1 — Doubling (2n).**  *Input:* `COUNTER[0]=n`, `COUNTER[1]=0`. *Output:* `COUNTER[1]=2n`.
- Loop L: `DECZ(0) → BRANCH{Zero,NonZero}`.
  - On `NonZero`: `INC(1)`; `INC(1)`; back to L.
  - On `Zero`: Halt.
- **POTENTIAL_CHECK:** `Φ := |COUNTER[0]|` decreases by 1 each pass; loop finite.
- **Timetable:** `DECZ` and `INC` alternate κ₁·S1 with κ₁·S2 reconciliation; no κ₃/κ₂ seizures.

**Witness Routine A2 — Copy (preserving).** Implements `COPY(a→b)` using `TMP` as in §3.2; potentials `Φ₁:=|a|`, `Φ₂:=|TMP|` prove finish.

#### Library B — Braid‑Head Clerk
**Calling Conventions.**
- **Entrances:** `E_TAPE_STEP(Left/Right)`, `E_TAPE_READ`, `E_TAPE_WRITE(SYM)`, `E_TAPE_BRANCH(test)`.
- **Appointments:** Head at current seat; residues lanes {5,7,9,11} live; symbol alphabet {0,1,Blank} with parity.
- **Issues:** `SYM{0,1,Blank,Error}`; branches `{True,False}`; `Pos_Update` after steps.
- **Phasing:** All head actions use κ₂·(S1/S3); no κ₁/κ₃ collision by Latin schedule.

**Witness Routine B1 — Recognise Alternation (0101… of length m).**  *Input:* `m` in `COUNTER[0]`; tape head at leftmost examined seat. *Output:* Branch `True` iff the next `m` seats alternate 0/1.
- Initialise `expect := 0` (plate mark).
- Loop L (for i from 0):
  1) `DECZ(0) → BRANCH{Zero,NonZero}`. On `Zero`: **Halt True**. On `NonZero`: continue.
  2) `TAPE_READ → SYM`.
  3) `TAPE_BRANCH(test := (SYM == expect)) → BRANCH{True,False}`. On `False`: **Halt False**.
  4) `TAPE_STEP(Right)`.
  5) Flip `expect` plate (0↔1); back to L.
- **POTENTIAL_CHECK:** `Φ := |COUNTER[0]|` decreases by 1 per lap; loop finite.
- **Timetable:** κ₂ actions occupy {0,2,4,6,8,10}; κ₁ counter decrements occupy {0,4,8} with reconciliation at {1,5,9}; collision‑free.

**Witness Routine B2 — Left‑to‑Right Copy of a Unary Block.**  *Input:* A block of `1`s of length `m` beginning at the head, a blank gap to the right; *Output:* a second block of `1`s of length `m` written after a single Blank separator.
- Outline: While `DECZ(0)` reports `NonZero`: `TAPE_READ`; if `Is1` then `TAPE_STEP(Right)` to target zone, `TAPE_WRITE(1)`, then step back left by residue‑guided returns; finally step right one to continue. When `Zero`: stop. (Employs only the four head macros; movement safety via residues.)
- **Potential:** `Φ := |COUNTER[0]|` strictly decreasing.

—

**Sufficiency Claim.** Either Library A (two counters with tested branch) or Library B (tape head with read/write/branch/step and unbounded winder) suffices to **make the Engine go** for any finite method; both obey the Period schedule and Guards by construction. Proof obligations are tabulated in §6.

### 4.3 Instruments of Communication — Printing, Decoding & Audits

#### 4.3.1 Decoding Stanza & Guards
- **Decoding (balanced → ordinary).** For each place from least to most significant: if `d∈{−5…−1}`, the `decode_bar` selects type `10+d` and raises a **borrow flag** to the next higher place for this **issue only**; if `d≥0`, print `d` and lift the flag. The Store remains in balanced digits throughout; only the printed figure is adjusted. 
- **Guards.** `β(κ₄)` ensures single seizure; `γ(LateFigure)` detains impression until `Digits_Balanced` is latched from reconciliation; `γ(DoubleStrike)` holds the `impression_lever` until `paper.advance` confirms line movement; the `ink_bar` may be lifted for a **dry trial**.

#### 4.3.2 “Table of the Work” — Forme
- **Layout.**
  - **Col 1:** *Index* (line number).  
  - **Col 2:** *Operation/Case* (e.g., ADD, SUB, …).  
  - **Cols 3–4:** *Inputs* (A, B …).  
  - **Col 5:** *Result* (S, Q,R, etc.).  
  - **Col 6:** **⑨** tally (residue of the whole line).  
  - **Col 7:** **⑪** tally.  
  - **Col 8:** *Parity* (•) if braid parity signalled any recovery during programme steps.
- **Imposition.** Tallies **⑨/⑪** are advanced from ledgers at κ₄ and printed in small; parity mark printed only when a parity correction occurred.

#### 4.3.3 Specimen Line (ADD)
- **Case.** `A=1234`, `B=0567` (leading zero printed), `S=1801`.
- **Flow.** κ₁·S1 fetch A,B → `CARRY_SAVE_ACCUMULATE` → κ₁·S2 reconcile → κ₁·S1 restore S → κ₄ print & audit.
- **Audits.**
  - **mod‑9:** `A≡(1+2+3+4)≡1`, `B≡(0+5+6+7)≡0` ⇒ expected `S≡1`; printed `1+8+0+1≡1` ✓.
  - **mod‑11 (alternating sum):** `A≡(4−3+2−1)=2`, `B≡(7−6+5)=6` ⇒ expected `8`; printed `1−0+8−1=8` ✓.
- **Contrived error.** If the last figure be bruised to `S'=1802`, then **⑪** prints `2−0+8−1=9` ≠ expected `8`; **Audit Pause** (§5.4) arises, clerk employs `proof_gate` to **prove‑again** (re‑issue audit and, if ink lifted, the line) from the last good ledger; persistent mismatch invites `Stop_σ` and a return to previous stanza.

#### 4.3.4 Operator’s Rite (Brief)
1) **Trial Impression.** Lift `ink_bar`; admit `PRINT_ISSUE` to dry trial; observe type selections and witness dials (⑨/⑪) without marking paper.
2) **Witness Dials.** Confirm **⑨/⑪** residues against clerkly calculation before lowering `ink_bar`.
3) **Prove‑Again.** If an **Audit Pause** or parity fault appears, draw `proof_gate` to re‑admit `AUDIT_CONGRUENCE` and, if commanded, re‑strike the last line once only (double‑strike detented). 
4) **Proceed.** Lower `ink_bar`; admit `PRINT_ISSUE`; upon line advance the detent releases for the next impression.

—

*With these instruments, a clerk may follow a specimen line from Store digits, through decoding, to type‑wheels and audits; intentional corruption is exposed by the tallies, and a calm rite exists to prove again without fresh mischief.*

## 5)## 5) Governance (GUARDS & INTERLOCKS)

> **Object.** Ensure that overlaps upon any coupling are impossible by timetable or else barred by a named Guard; publish precedence as a partial order; bind interlocks to stated conditions; admit only sanctioned lapses.

### 5.1 Formal Guard Patterns (with Parameters)

**Escapement_α(τ; sub=\{-1,0,+1\}; settle=⅓·τ).**
- *Law:* Emits exactly one **Tick τ** per MainTurn slice; within each Tick provides **sub‑ticks** (−1,0,+1) for temporal majority and a **settle slot** of duration `settle` usable by any stanza that declares it. 
- *Guarantees:* (i) No double‑tick; (ii) sub‑tick order strict; (iii) `Settle_Slot[settle]` excludes further admissions on the same coupling until expired.

**Opposed_β(κ; priority=PO).**
- *Law:* For coupling class **κ ∈ {κ₁,κ₂,κ₃,κ₄}**, at most one claimant may seize κ in any Tick. If several present, apply **priority order PO** derived from the Latin schedule for that Tick (earlier slot wins; others detained). When used as a branch detent, the two seats are mutually exclusive by construction.
- *Guarantees:* Mutual exclusion; deterministic choice consistent with timetable; starvation impossible under periodic Latin block.

**Block_γ(P).**
- *Law:* For predicate **P**, detain the attempted admission until **P=false**. Typical predicates: `FollowerUnsettled`, `Reset_WindowActive`, `LateFigure`, `WriteDuringStep`.
- *Guarantees:* Safety against mid‑state plates, unsettled followers, or late impressions; no deadlock because predicates expire by schedule (settle window) or by operator action.

**Clutch_Interlock_δ (κ₃‑only).**
- *Law:* Within κ₃, at most one clutch in `{c_cam, c_w, norm_pair, lever_scale[*]}` may be engaged during a Tick. Attempts to seize a second are **blocked** until release of the first.
- *Guarantees:* Cam traverse, whisper drive, rotation, and normalise are **pairwise exclusive**.

### 5.2 Partial Order & Chain Decomposition

Let **Σ** be the set of critical stanzas:
`{ BRAID_STEP, KNOT_READ, KNOT_WRITE, DECIMAL_FETCH, CARRY_SAVE_ACCUMULATE, CARRY_RECONCILE, DECIMAL_RESTORE, CAM_TRAVERSE, ROTATE_STEP, NORMALISE, AUDIT_CONGRUENCE, PRINT_ISSUE }`.

**Precedence (partial order ≺):**
- **General head rule:** `Settle ≺ Read ≺ Write ≺ Reconcile ≺ Print` (already posted).
- **κ₁ (Store):** `DECIMAL_FETCH ≺ CARRY_SAVE_ACCUMULATE ≺ CARRY_RECONCILE ≺ DECIMAL_RESTORE ≺ PRINT_ISSUE`.
- **κ₂ (Braid):** `BRAID_STEP ≺ KNOT_READ ≺ KNOT_WRITE`.
- **κ₃ (Mill):** `CAM_TRAVERSE` and `ROTATE_STEP` are **incomparable** but **exclusive** by `Clutch_Interlock_δ`; any `NORMALISE` must follow a run of `ROTATE_STEP` and precede `DECIMAL_RESTORE` → thus `ROTATE_STEP* ≺ NORMALISE ≺ DECIMAL_RESTORE`.
- **κ₄ (Print):** `AUDIT_CONGRUENCE ≺ PRINT_ISSUE`.

**Chain decomposition (mapped to phases):**
- **Chain C₁ (κ₁ Store, phases A→B→C repeating):** `S1: {DECIMAL_FETCH / CARRY_SAVE_ACCUMULATE} → S2: {CARRY_RECONCILE} → S1: {DECIMAL_RESTORE}` … (ticks {0,1,4,5,8,9}).
- **Chain C₂ (κ₂ Braid, phases A↔C↔B alternating):** `S1/S3: BRAID_STEP → (Settle) → KNOT_READ → (optional) KNOT_WRITE` (ticks {0,2,4,6,8,10}).
- **Chain C₃ (κ₃ Mill — Cam branch, phases A↔C):** `S1/S3: CAM_TRAVERSE` separated by settle slots; no adjacency with rotation by `Clutch_Interlock_δ` (ticks {0,2,4,6,8,10}).
- **Chain C₄ (κ₃ Mill — Rotation branch, phases B↔A with S2/S4):** `S2/S4: ROTATE_STEP … ROTATE_STEP → NORMALISE` (ticks {1,3,5,7,9,11}).
- **Chain C₅ (κ₄ Print, phases A↔C↔B):** `S1/S3: AUDIT_CONGRUENCE → PRINT_ISSUE` (ticks {0,2,4,6,8,10}).

Acyclicity follows since every edge respects increasing Tick class within the 12‑tick block; cross‑coupling edges (e.g., `NORMALISE ≺ DECIMAL_RESTORE`) stride forward in class.

### 5.3 Interlock Index (by Coupling)

| Coupling κ | Active Guards | Conditions |
|:--|:--|:--|
| **κ₁ Store‑Carriage** | `Opposed_β(κ₁)`, `Block_γ(Reset_WindowActive ∨ Settle)`, head‑rule precedence | During S1/S2; `Block_γ` detains fetch/store if reconciliation or settle in effect. |
| **κ₂ Braid‑Step** | `Opposed_β(κ₂)`, `Block_γ(WriteDuringStep ∨ Settle)`, `Stop_σ` | Step and write/read never coincide; mis‑read raises `Stop_σ`. |
| **κ₃ Mill‑Traverse** | `Opposed_β(κ₃)`, `Clutch_Interlock_δ`, `Block_γ(FollowerUnsettled)` | Cam, whisper, rotation, normalise are mutually exclusive; follower must settle before release. |
| **κ₄ Print** | `Opposed_β(κ₄)`, `Block_γ(LateFigure)`, precedence with κ₁ | No impression if any Store digit unsettled; print only after reconcile/decoding. |

### 5.4 Lapse Catalogue (Sanctioned Stalls & Remedies)

1) **Settle Wait (⅓·τ).** *Cause:* follower or carriage settling. *Remedy:* expire by Escapement_α; no operator action.
2) **Reset Window (1·τ).** *Cause:* plate temporal‑majority decision and reset. *Remedy:* expires automatically; further plate admissions detained by `Block_γ`.
3) **Timetable Idle.** *Cause:* waiting for the next admissible Latin slot. *Remedy:* none; structural.
4) **Audit Pause.** *Cause:* `AUDIT_CONGRUENCE` indicates `Fail`. *Remedy:* operator lever to re‑read stanza; if persistent, `Stop_σ` and return to last good Table line.
5) **Error Word (Tape).** *Cause:* parity failure/forbidden pattern. *Remedy:* `Stop_σ`; clerk may `TAPE_STEP` off the bruised seat and rewrite.

> **Conclusion.** With these Guards and chains, overlaps upon any coupling are either structurally impossible by the Latin timetable or else barred by an explicit named Guard. The partial order is acyclic within the 12‑tick block and cited above.

## 6) Proof Obligations & Error Budget (PROOF)

> **Rule.** Every claim is tied to a named Guard (α, β, γ, δ), a schedule property (Tables P‑1…P‑3), or a small inequality from the Parameter/Annex tables (PT‑*, CT‑*, TT‑*). No geometry is presumed.

### 6.1 Global Identity & Uniqueness
- **Letters & Points.** Each member and working point bears a unique letter (cf. MA‑1). The **Store** columns `Col[i]`, the **Braid** lanes {⑤⑦⑨⑪}, and the **Mill** clutches `{c_cam, c_w, norm_pair, lever_scale[s]}` are disjoint by name and coupling. *Hence* identity consistency holds.
- **Couplings.** Exactly four couplings κ₁…κ₄ are recognised. Every stanza cites at most one **⟂κ** symbol (MA‑2, MA‑3). *Therefore* by construction no stanza is ambiguous in its seizure.

### 6.2 Admission Safety (No Double Seizure)
- **Latin schedule (P‑1).** In each Tick t the Latin rectangle presents each slot S₁…S₄ exactly once per row (κ). The **Opposed_β(κ)** guard detains all but the rightful claimant for that κ at t. *Thus* two stanzas cannot seize the same κ in the same Tick. 
- **Mill exclusivity (δ).** Within κ₃, **Clutch_Interlock_δ** forbids simultaneous engagement of `{c_cam, c_w, norm_pair, L_s}`; any second attempt meets `γ(P:=ClutchEngaged)` until release. *Therefore* cam traverse, whisper, rotation, and normalise are pairwise exclusive.
- **Plate discipline (γ).** Temporal‑majority reads (Table P‑2) are followed by `Reset_Window[1·τ]`; **Block_γ(Reset_WindowActive)** detains further plate admissions. *Hence* no mid‑state branch admits.

### 6.3 Time Sufficiency (Approach→Engage→Execute→Release→Restore)
- **Tick budget.** **Escapement_α(τ)** supplies sub‑ticks (−1,0,+1) for plate majority and a **Settle_Slot[⅓·τ]** for any stanza that declares it. The Latin timetable allocates at most one seizing stanza per κ per Tick. *Therefore* each admitted stanza has uninterrupted budget for `approach→engage→execute→release`, and—where declared—`restore` occurs either within the settle slot or the next admissible Tick on that κ.
- **Examples.** (i) `BRAID_STEP` executes seize→advance→[Settle]→residue sample within one κ₂ Tick; (ii) `CARRY_RECONCILE` executes drizzle→[Settle] within κ₁·S2; (iii) `CAM_TRAVERSE` and `ROTATE_STEP` each include a settle guard `γ(FollowerUnsettled)` ensuring follower restore before release.

### 6.4 Termination of Declared Loops
- **Two‑Counter loops.** Potentials **Φ:=|COUNTER[k]|** decrease by 1 per `DECZ(k)` lap (Sections 3.2 & 4.2 A); lexicographic pairs `(Φ₁,Φ₂)` handle the `COPY` shuttle. **⟦Φ⟧** is checked before back‑edges; *therefore* loops finish.
- **Trig loops (SINCOS, ATAN).** Potential **Φ:=Σ_{j≥s} α_j** strictly decreases with each admitted `ROTATE_STEP` (PT‑3), bounded below by 0. After n steps, `Φ_n<2^{−n}`; n=10 suffices for our declared precision. *Therefore* vectoring and rotation loops finish.
- **Division & Root.** Each digit pass reduces the remaining place index k; **Φ:=k** strictly decreases; trial/restore is alternated by schedule and guarded by β.

### 6.5 Numerical Bounds
- **Cam truth (ε_cam).** With Chebyshev nodes N=9 (CT‑1) the equal‑ripple principal error satisfies `ε_cam,pre ≤ 3×10⁻³` full‑scale by design of nodes; engagement of `WHISPER_ON` adds the first residual mode at **1:10** amplitude and **10:1** speed (CT‑2), cancelling the dominant ripple and yielding `ε_cam,post ≤ 3×10⁻⁴`. **γ(FollowerUnsettled)** ensures measurements are taken only after shoe settle. *Hence* `ε_cam = ε_cam,post` is the operative bound in all seat work.
- **Rotation scale (ε_rot).** Let K be the gain after the admitted 10‑scale rotation train. One boundary `bring‑to‑standard` via **N(135:82)** yields a relative error 
  `ε_rot := |(135/82)/K − 1| ≤ 2.5×10⁻⁴` (PT‑4). Because normalisation is applied **once per stanza boundary** (never per Tick) and detained by δ against other κ₃ clutches, error does not accumulate within a stanza. *Hence* `ε_rot` is bounded as declared.
- **Balanced digits (reconciliation correctness).** Maintain the invariant for any column vector of digits **d** with carry vector **c**:
  `Value = Σ_i (d_i + 10·c_i)·10^i`.
  `CARRY_SAVE_ACCUMULATE` preserves the invariant with **local** updates to (Sum, Carry). `CARRY_RECONCILE` performs only local moves `d_i←d_i−10·s`, `d_{i+1}←d_{i+1}+s` with `s∈{−1,0,+1}`, chosen to enforce `d_i∈{−5…+4}`. The ℓ₁‑norm `||c||₁` strictly decreases on any non‑trivial step; therefore reconciliation terminates in finitely many drizzles and yields a unique balanced representative. The final decode at print (PT‑1) is a bijection to ordinary 0…9 digits with a single borrow per negative place. 
- **Braid self‑location (validity over declared span).** Moduli {5,7,9,11} are pairwise coprime (PT‑2). The product **M = 3465** gives a unique position class modulo M by the Chinese Remainder Theorem. The home word recurs every M steps; the Engine reconstructs absolute position via staged residues (Garner form) and compares against the expected class; any creep or slip < M manifests as residue inconsistency and is caught by `Stop_σ`. *Hence* self‑location is valid over the declared span M.

### 6.6 Printing Safety & Audits
- **No late figure.** `PRINT_ISSUE` declares `γ(LateFigure)`; it admits only after `Digits_Balanced` and decoding (PT‑1). *Therefore* no impression occurs with unsettled Store digits.
- **Audits.** Auxiliary congruence wheels **⑨, ⑪** advance from the ledger and compare to expectation (MA‑2). A mismatch raises the **Audit Pause** (§5.4) and invites operator recourse; correctness follows from the congruence invariants of addition and product.

### 6.7 Conclusion (Proof Ledger)
All families—**Store**, **Braid**, **Mill**, **Print**—satisfy identity, admission safety, and time sufficiency by guards {α,β,γ,δ} and by the Latin schedule. Declared loops terminate under named potentials; numerical bounds **ε_cam** and **ε_rot** are held by CT‑ and PT‑tables; reconciliation is correct and terminating; braid self‑location is valid on its span. No geometry has been presumed.

## 6′) Mechanical Alphabet Annex — Signs & Tokens (MA‑series)

> **Object.** To furnish a canonical **alphabet of signs** by which the Draughtsman may letter the Plates and the Clerk may read the Trains without resort to modern coinage. Signs are textual surrogates for Babbage’s language of signs and admit neatly into our ledger.

### MA‑0. Legend of Signs (canonical)

**Members & Points**
- **Capitals** = members (*pieces*), e.g., `FRAME_A`, `SHAFT_Ω`, `CAM_PRINCIPAL`.
- **lower‑case** = working points, e.g., `head.l`, `cw[i,k].a`.
- **‖** = permanent union (bar), e.g., `CAM_PRINCIPAL ‖ follower_shoe`.
- **⊳** = admission/engagement of a clutch or seize of a path; **⊣** = release.
- **⟂κₙ** = seize coupling **κₙ** (n∈{1,2,3,4}); detain others by `Opposed_β(κₙ)`.
- **Δ** = differential mesh (MILL_DIFF); **N** = `norm_pair`; **L_s** = `lever_scale[s]`.

**Motions & States**
- **↺ / ↻** = rotation (CW/CCW as context bids); **→ / ←** = linear advance/retreat; **↑ / ↓** = raise/lower.
- **⌶** = seat reached (cam seat or latched position); **[Settle]** = settle slot (⅓·τ) declared.
- **{…}** = set of alternatives; **/** = exclusive alternative; **→** (thin) inside a sign stream = consequential step.

**Governance & Proof**
- **α** = `Escapement_α(τ)` (tick & sub‑ticks); **β** = `Opposed_β(κ)`; **γ** = `Block_γ(P)`; **δ** = `Clutch_Interlock_δ`.
- **⟦Φ⟧** = `POTENTIAL_CHECK(Φ)`; **≺** = precedence (partial order). 
- **⑨ / ⑪** = audit congruence wheels (mod‑9, mod‑11).
- **⑤ ⑦ ⑨ ⑪** = residue lanes (mod 5/7/9/11) at the braid edge.

*Reading rule.* A **sign‑sequence** is read left→right within a Tick; line breaks mark subsequent Ticks. When a coupling sign **⟂κₙ** appears, mutual exclusion follows by **β**; where **[Settle]** appears, further admissions upon that κ are detained by **γ** until expiry.

### MA‑1. Offices to Signs (extract)

| Office | Sign | Note |
|:--|:--|:--|
| cam_principal | `Cᵖ` | principal cam member |
| cam_whisper | `Cʷ` | residual cam |
| diff_whisper | `Δʷ` | differential summing whisper |
| follower_shoe | `f_shoe` | width `W_shoe` per PT‑5 |
| lever_scale[s] | `L_s` | dyadic scales PT‑3 |
| norm_pair | `N` | gear train 135:82 PT‑4 |
| clutch[c_*] | `c_*` | specific clutch as subscript |
| plate[j] | `P_j` | two‑position governance plate |
| tally_9 / tally_11 | `⑨ / ⑪` | audit wheels |
| lane[5/7/9/11].f | `⑤/⑦/⑨/⑪` | residue feelers |

### MA‑2. Primitive Stanzas — Sign‑Sequences

**BRAID_STEP(dir)**  
`α:τ :: β(κ₂) ⟂κ₂ ⊳c₂ · head.{l/r} → sprocket→cord → ⌶ [Settle] → (⑤,⑦,⑨,⑪) sample → Pos_Update`

**KNOT_READ → SYM**  
`β(κ₂) ⟂κ₂ · feeler_read↓ → parity? → forbidden? → {SYM0/SYM1/Blank/Error}`

**KNOT_WRITE(SYM)**  
`β(κ₂) ⟂κ₂ ⊳c₂ · pawl_write{↑/↓}(SYM) → parity seat ⌶ [Settle] → Word_Stamped ⊣c₂`

**PLATE_TEST(j) → BRANCH**  
`α:sub(−1,0,+1) · P_j{0/1} (temporal‑majority) → β(branch) → {True/False}`  
(with `γ(Reset_Window)` detaining further plate admissions until lapse)

**DECIMAL_FETCH(i)**  
`β(κ₁) ⟂κ₁ ⊳c₁ · S[i]→Mill → Value_to_Mill`

**DECIMAL_RESTORE(i)**  
`β(κ₁) ⟂κ₁ ⊳c₁ · Mill→S[i] → ⌶ [Settle] → Value_from_Mill ⊣c₁`

**CARRY_SAVE_ACCUMULATE**  
`β(κ₁) ⟂κ₁ · Sum←(addends) ‖ Carry←(partials) → Partial_Totals`

**CARRY_RECONCILE**  
`β(κ₁) ⟂κ₁ · drizzle(±1) place‑wise → bounds{−5…+4} → ⌶ [Settle] → Digits_Balanced`

**CAM_TRAVERSE(f)**  
`β(κ₃) ⟂κ₃ δ · ⊳c_cam Cᵖ@CT‑1 + ⊳c_w Δʷ(Cʷ,1:10@10:1) → follower f_shoe→⌶ [Settle] → Seat_f ⊣c_cam ⊣c_w`

**ROTATE_STEP(sign,s)**  
`β(κ₃) ⟂κ₃ δ · L_s (palindrome: +α_s/2 ; [Settle] ; +α_s/2) → (x,y)→(x',y')`

**NORMALISE(135:82)**  
`β(κ₃) ⟂κ₃ δ · N(135:82) → ⌶ [Settle] → Scaled_OK`

**AUDIT_CONGRUENCE(mod 9,11)**  
`⑨,⑪ advance ← ledger → compare → {Pass/Fail}`

**PRINT_ISSUE**  
`β(κ₄) ⟂κ₄ · S[sel]→typewheels → decode(−5…+4 → 0…9 with borrow) → impress → paper→advance → latch ⑨,⑪`

### MA‑3. Combined & Tested Operations — Sign‑Sequences

**ADD(A,B→S)**  
```
κ₁:S1  β ⟂κ₁ ⊳c₁  S[a]→Mill ; S[b]→Mill
κ₁:S1  Sum‖Carry ← (A,B)
κ₁:S2  drizzle ±1 → [Settle]
κ₁:S1  Mill→S[s]
κ₄:S1  ⑨,⑪ audit
```

**SUB(A,B→D)**  
```
κ₁:S1  β ⟂κ₁  S[a], S[b]→Mill
κ₃:S2  sign_toggle(B)
κ₁:S1  Sum‖Carry ← (A,−B)
κ₁:S2  drizzle ±1 → [Settle]
κ₁:S1  Mill→S[d]
κ₄:S1  ⑨,⑪
```

**MULTIPLY(Log‑Cam)**  
```
κ₁:S1  S[x]→Mill
κ₃:S1  δ ⟂κ₃  ⊳c_cam Cᵖ + ⊳c_w Δʷ → Seat_logX
κ₁:S1  S[y]→Mill
κ₃:S3  δ ⟂κ₃  ⊳c_cam Cᵖ + ⊳c_w Δʷ → Seat_logY
—        Δ : Seat_logX + Seat_logY
κ₃:S2  reverse‑train(exp) → magnitude
κ₁:S1  Mill→S[p] ; κ₁:S2 drizzle ; κ₄ audit
```

**MULTIPLY(Rotation)**  
```
κ₁:S1  S[x]→Mill ; seed (X,0)
repeat s∈{0…9}:
  κ₃:S2/S4  δ ⟂κ₃  L_s (palindrome) → (X,Y)
  κ₁:S1/S2  update residual angle (ANGLE_TABLE[s]) with drizzle
κ₃:S4  N(135:82)
κ₁:S1  Mill→S[p] ; κ₁:S2 drizzle ; κ₄ audit
```

**DIVIDE(N÷D→Q,R)**  
```
κ₁:S1  S[n],S[d]→Mill
loop over k (high→low):
  κ₁:S1  trial Subtract D·10^k via Sum‖Carry
  κ₁:S2  drizzle ; PLATE_TEST(sign R) → {accept/restore}
κ₁:S1  Mill→S[q],S[r] ; κ₄ audit
```

**RECIPROCAL(A→1/A)**  
```
κ₁:S1  S[a]→Mill
κ₃:S1/S3  Möbius stages (small integer ratios; optional cam seats)
κ₁:S1  Mill→S[r] ; κ₁:S2 drizzle ; κ₄ audit
```

**ROOT(√A→S)**  
```
κ₁:S1  S[a]→Mill
for each digit‑pair high→low:
  κ₁:S1  trial Subtract (20·S+1)·10^k → Sum‖Carry
  κ₁:S2  drizzle ; PLATE_TEST(sign R) → {accept/restore}
κ₁:S1  Mill→S[s],S[r] ; κ₄ audit
```

**SINCOS(Θ→C,S)**  
```
κ₁:S1  S[θ]→Mill ; R←Θ ; (X,Y)←(1,0)
for s=0…9:
  κ₃:S2/S4  δ ⟂κ₃  L_s (palindrome)
  κ₁:S1/S2  R←R−sgn(R)·α_s (ANGLE_TABLE[s]) with drizzle
κ₃:S4  N(135:82)
κ₁:S1  Mill→S[c],S[s] ; κ₄ audit
```

**ATAN((X,Y)→Angle)**  
```
for s=0…9:
  κ₃:S2/S4  δ ⟂κ₃  L_s (vectoring: sign=−sgn Y)
  κ₁:S1/S2  Angle ← Angle + sign·α_s with drizzle
κ₃:S4  N(135:82) ; κ₁:S1  Mill→S[ang]
```

### MA‑4. Gloss of Replacements (no modern coinage)

| Modern parlance (avoided) | Our sign / phrase |
|:--|:--|
| bit, binary | **plate** state; **two‑fold** ratios; `L_s` dyadic scale |
| register (electronic) | **Store column** `S[i]`; **Mill** working seat |
| algorithm | **Method**; **Combined & Tested Operation** |
| interrupt / lock | **Guard** `β`, `γ`, `δ` as named |
| normalise | **bring‑to‑standard** `N(135:82)` |
| error correction | **witness & audit** (⑨, ⑪), **parity** on knots |
| CRT | **residues with reconstruction** (lanes ⑤⑦⑨⑪) |
| micro‑step | **stroke** (palindromic if named) |

> With this annex every stanza and operation bears a **sign‑sequence** fit to be lettered upon the Plates. The Draughtsman may now ornament Plates A–F with these concise sign streams, and the Clerk may drive the Engine by them without recourse to modern coinage.

## 7) Draughtsman’s Plates — Captions & Lettering Instructions
> No geometry is fixed; letter members, points, and sign‑sequences only.

Plate A — Offices & Couplings (General Plan)
- Letter: FRAME, STORE, BRAID, MILL, PRINT; couplings κ₁…κ₄ named.
- Place working points: entrances `E_Fetch`, `E_Braid`, `E_Cam[f]`, `E_Rotate`, `E_Norm`, `E_Print`.
- Show signs: `⟂κ₁…⟂κ₄` beside entrances; guards α, β, γ, δ in a small canon.
- Caption stream (example): `β(κ₁) ⟂κ₁ → STORE ⇄ MILL ; β(κ₃) ⟂κ₃ → MILL (Cam/Rotate/N)`.

Plate B — Store & Carry Pipeline
- Letter: a Store column `S[i]`, ledgers **Sum** and **Carry**, `decode_bar`, `Reset_Window`.
- Working points: `E_Fetch`, `E_Acc`, `E_Reconcile`, `E_Store`.
- Show signs (bands): `β ⟂κ₁ ⊳c₁  S[i]→Mill` ; `Sum‖Carry ← (addends)` ; `drizzle ±1 → bounds{−5…+4} → [Settle]` ; `Mill→S[i]`.
- Margin: “Balanced digits {−5…+4}; decode only at PRINT.”

Plate C — Braid Head & Residues
- Letter: `head.{l,r}`, residues ⑤ ⑦ ⑨ ⑪, parity ticket, forbidden‑pattern slip, home word.
- Working points: `E_Braid`, `E_Read`, `E_Write`.
- Show signs: `β ⟂κ₂ ⊳c₂ head.{l/r} → ⌶ [Settle] → (⑤,⑦,⑨,⑪)` ; `feeler_read↓ → parity? → {SYM0/SYM1/Blank/Error}` ; `pawl_write{↑/↓} → parity seat`.
- Margin: “Absolute position by residues; unique mod M=3465.”

Plate D — Mill: Rotation Levers
- Letter: `lever_scale[s] (s=0…9)`, `norm_pair N(135:82)`, registers `(X,Y)`, `ANGLE_TABLE[s]`.
- Working points: `E_Rotate`, `E_Norm`.
- Show signs: `L_s palindrome (+α_s/2 ; [Settle] ; +α_s/2) → (x,y)→(x',y')` ; `N(135:82) → [Settle]`.
- Margin: “Single normalise per stanza boundary; δ bars other κ₃ clutches.”

Plate E — Mill: Function Cams & Whisper
- Letter: `Cᵖ` principal cam, `Cʷ` whisper cam, `Δʷ` differential, `f_shoe` (W_shoe := 1⁄3·δ_node), node plan CT‑1.
- Working points: `E_Cam[f]`, clutches `c_cam`, `c_w`.
- Show signs: `β ⟂κ₃ δ · ⊳c_cam Cᵖ@CT‑1 + ⊳c_w Δʷ(1:10@10:1) → f_shoe→⌶ [Settle]`.
- Margin: “Equal‑ripple ε_cam ≤ 3×10⁻⁴ with whisper.”

Plate F — Printing & Audits
- Letter: `type_wheel[k]`, `impression_lever`, `paper_carriage`, `double_strike_detent`, audits ⑨ ⑪, `proof_gate`, `ink_bar`.
- Working points: `tw[k].pick`, `impress.p`, `paper.advance`, `audit.tick9/11`.
- Show signs: `β ⟂κ₄ · S[sel]→typewheels → decode(−5…+4 → 0…9 with borrow) → impress → paper→advance → ⑨,⑪`.
- Margin: “Late figure & double‑strike detained by γ; dry trials with ink lifted.”

## 8) Period Tables (P‑series — Final)

Table P‑1. Twelve‑Tick Latin Schedule with Phases — as earlier (A/B/C over t0…t11; S1…S4 per κ).

Table P‑2. Temporal‑Majority & Reset Windows — as earlier (2‑of‑3 over sub‑ticks; Reset_Window[1·τ]).

Table P‑3. Settle & Reconcile Cadence — as earlier (Settle_Slot[⅓·τ]; κ₁·S2 drizzle).

Table P‑4. Stanza Footprints (exemplars within one 12‑tick block)
- ADD: κ₁·S1 fetch A,B @ t0 → κ₁·S2 reconcile @ t1 → κ₁·S1 restore S @ t4 → κ₄ audit/print @ t4 or t6.
- SINCOS (one scale): κ₃·S2 rotate @ t1 → κ₁ residual update @ t4 → κ₃·S4 rotate @ t3 → … → NORMALISE @ t11.
- CAM seat: κ₃·S1 traverse @ t0 → [Settle] → κ₃·S3 traverse @ t2.

Table P‑5. Polyphase Map (Chains→Phases)
- C₁ Store: A→B→C across {0,1,4,5,8,9}.  
- C₂ Braid: A↔C↔B across {0,2,4,6,8,10}.  
- C₃ Cam: A↔C across {0,2,4,6,8,10}.  
- C₄ Rotation: B↔A across {1,3,5,7,9,11} with NORMALISE at S4.  
- C₅ Print: A↔C↔B across {0,2,4,6,8,10}.

## 9) Train Charts (TC‑series)
> Textual charts for the Foreman; each line is a Tick; couplings explicit; Guards implied by tokens.

TC‑1. ROTATE_STEP(sign,s) + NORMALISE (one lap)
- t1  κ₃:S2  `β ⟂κ₃  L_s  (+α_s/2) → [Settle]`
- t2  — idle or κ₁ work per Latin
- t3  κ₃:S4  `β ⟂κ₃  L_s  (+α_s/2) → (x,y)→(x',y')`
- t11 κ₃:S4  `β ⟂κ₃  N(135:82) → [Settle]` (stanza boundary)

TC‑2. CAM_TRAVERSE(f) with Whisper
- t0  κ₃:S1  `β ⟂κ₃ δ  ⊳c_cam Cᵖ@CT‑1 + ⊳c_w Δʷ(1:10@10:1) → f_shoe→⌶ [Settle]`
- t2  κ₃:S3  optional second traverse, same pattern

TC‑3. CARRY Pipeline (ADD exemplar)
- t0  κ₁:S1  `β ⟂κ₁ ⊳c₁  S[a],S[b]→Mill ; Sum‖Carry ← (A,B)`
- t1  κ₁:S2  `drizzle ±1 → bounds{−5…+4} → [Settle]`
- t4  κ₁:S1  `Mill→S[s]` (decode only at PRINT)

TC‑4. TAPE Step/Read/Write
- t0  κ₂:S1  `β ⟂κ₂ ⊳c₂  head.{l/r} → ⌶ [Settle] → (⑤,⑦,⑨,⑪)`
- t2  κ₂:S3  `KNOT_READ → {SYM0/SYM1/Blank/Error}`
- t4  κ₂:S1  `KNOT_WRITE(SYM) → parity seat → [Settle]`

## 10) Fixed Parameters (Pass 2)

All parameters here fixed are framed as admissions and ratios, not as geometry. Numerical tables live in **Annex A — Parameter Tables (Pass 2)**, cited as PT‑*.

### 10.1 Balanced‑Digit Scheme (PT‑1)
We adopt the **non‑redundant signed‑decimal** set **{−5, −4, −3, −2, −1, 0, +1, +2, +3, +4}**. Reconciliation drizzles carries so that each place lies within this set; at print, a decoding stanza converts any negative digit d to `(10+d)` while **borrowing 1** to the next higher place (e.g., −3→print 7 with a borrow). *Clerk’s marginal note:* This bounds carry propagation to ±1 and keeps reconciliation local.

### 10.2 Braid Residue Lanes (PT‑2)
We fit **four lanes** with moduli **{5, 7, 9, 11}**. These are pairwise coprime; by the Chinese Remainder Theorem the combined residue uniquely fixes absolute position modulo **M = 5·7·9·11 = 3465** steps. A **home word** recurs every M steps to set the epoch. *Note:* Adding lane 5 increases feelers by only one and enlarges the unique span from 693 to 3465 without fresh mechanism.

### 10.3 Palindromic Rotation Strokes (PT‑3)
For **MILL_ROT** the lever scales are **dyadic**, with micro‑rotation angles defined by `tan(α_s) = 2^{−s}` for scale index `s = 0…9`. Each admitted step is a **palindromic micro‑stanza** of order 2: `(+α_s/2 ; settle ; +α_s/2)`, cancelling even‑order defects while netting `+α_s`. *Note:* Ten scales suffice for clerkly precision; more may be added later without altering the ledger.

### 10.4 Single Normalising Ratio (PT‑4)
The rotation chain shrinks magnitude by a fixed factor **K** (for ten scales ≈ constant). We restore scale once per stanza with a **quiet gear ratio** **p:q = 135:82**, a convergent of the continued fraction of `1/K`. This ratio is exact as a train and deviates from `1/K` by ~**2.54×10⁻⁴** of full scale—well within audit tolerance and removable by one‑time calibration if desired. A tidy train is `45:41 × 3:2 = 135:82`.

### 10.5 Cam Nodes & Whisper (PT‑5)
The principal cam is fixed at **N = 9 nodes** placed by **Chebyshev spacing** over its lawful sweep; a small **whisper‑cam** superposes a residual at **amplitude 1:10** and **speed 10:1** (relative to the principal), cancelling equal‑ripple error without heroic cutting. *Note:* Nodes are indexed by rational abscissae; no angles are committed here.

> Cross‑references inserted in §1 (Apparatus), §2 (Periods), and §3 (Trains) where these constants are consumed; see footnotes “PT‑*”.

## 11) Iteration Plan (PASS 2 & 3)

- **Pass 2:** Fix parameters in §10; fill Period Tables; complete Train Charts; provide exemplar *ADD*, *MULTIPLY(Log‑Cam)*, *SINE/COSINE* with audited Tables of the Work.
- **Pass 3:** Flesh Draughtsman’s Plates; publish full Proof ledger; introduce calibration rites; add barrel subroutines and printing formes.

> *Clerk’s Note:* This scaffolding admits immediate drafting of specimen stanzas without binding us to gauge. Where ambiguity might breed fresh iron, we have preferred mathematics—orderings, residues, palindromes, and partial orders—so the Engine may grow in truth rather than in bulk.



## Annex A — Parameter Tables (Pass 2)

> *All tables are canonical admissions and ratios; no geometry is fixed. Values may be extended in later passes without upsetting the ledger.*

### PT‑1. Balanced‑Digit Scheme & Decoding at Print

| Stored digit d | Print digit | Borrow to next place |
|---:|---:|---:|
| −5 | 5 | +1 |
| −4 | 6 | +1 |
| −3 | 7 | +1 |
| −2 | 8 | +1 |
| −1 | 9 | +1 |
|  0 | 0 |  0 |
| +1 | 1 |  0 |
| +2 | 2 |  0 |
| +3 | 3 |  0 |
| +4 | 4 |  0 |

*Note.* Reconciliation ensures each place remains in {−5…+4}; carries drizzle as ±1 only.

### PT‑2. Braid Residue Lanes & Absolute Position

| Lane | Modulus m | Mark cadence | Feeler | Note |
|:--:|:--:|:--:|:--:|:--|
| L1 | 5 | every 5th step | lane[5].f | sparse, robust |
| L2 | 7 | every 7th step | lane[7].f |  |
| L3 | 9 | every 9th step | lane[9].f |  |
| L4 | 11 | every 11th step | lane[11].f |  |

**Product:** M = 3465 unique positions modulo M. **Epoch:** a home word printed every M steps resets the count. **Reconstruction:** staged CRT (Garner form) from residues (5→7→9→11).

### PT‑3. Palindromic Rotation Strokes (Dyadic Scales)

Let `s` be the scale index and define `tan(α_s) = 2^{−s}`. Each stroke is admitted as a palindrome: `(+α_s/2 ; settle ; +α_s/2)`.

| s | Lever scale | tan(α_s) | Micro‑stanza (symbolic) |
|:--:|:--:|:--:|:--|
| 0 | 1:1 | 1 | (+α₀/2 ; settle ; +α₀/2) |
| 1 | 1:2 | 1/2 | (+α₁/2 ; settle ; +α₁/2) |
| 2 | 1:4 | 1/4 | (+α₂/2 ; settle ; +α₂/2) |
| 3 | 1:8 | 1/8 | (+α₃/2 ; settle ; +α₃/2) |
| 4 | 1:16 | 1/16 | (+α₄/2 ; settle ; +α₄/2) |
| 5 | 1:32 | 1/32 | (+α₅/2 ; settle ; +α₅/2) |
| 6 | 1:64 | 1/64 | (+α₆/2 ; settle ; +α₆/2) |
| 7 | 1:128 | 1/128 | (+α₇/2 ; settle ; +α₇/2) |
| 8 | 1:256 | 1/256 | (+α₈/2 ; settle ; +α₈/2) |
| 9 | 1:512 | 1/512 | (+α₉/2 ; settle ; +α₉/2) |

*Clerk’s marginal note:* Ten scales suffice for clerkly sines and cosines; add more rows if greater nicety is desired.

### PT‑4. Normalising Ratio for Rotation Scale

**Chosen ratio:** p:q = **135:82** (train `45:41 × 3:2`).

| Quantity | Value |
|:--|:--|
| Decimal value p/q | ≈ 1.6463414634 |
| Target 1/K (ten‑scale) | ≈ 1.64676… |
| Absolute deviation | ≈ 4.19×10⁻⁴ |
| Relative error | ≈ 0.025% |

*Note.* Applied **once** at stanza boundaries by `NORMALISE(135:82)`; never per tick.

### PT‑5. Cam Nodes & Whisper Parameters (Chebyshev)

**Node count:** N = 9. **Abscissae:** `s_k = (2k−1)/(2N)` for k = 1…9 (pure rationals). Cam fixing points are taken at these `s_k` along the lawful sweep of the cam; the whisper‑cam overlays residual with **amplitude 1:10** and **speed 10:1** relative to the principal.

| k | s_k (rational) |
|:--:|:--:|
| 1 | 1/18 |
| 2 | 3/18 |
| 3 | 5/18 |
| 4 | 7/18 |
| 5 | 9/18 |
| 6 | 11/18 |
| 7 | 13/18 |
| 8 | 15/18 |
| 9 | 17/18 |

*Marginal:* Equal‑ripple error is thereby bounded; follower shoe width will be set in a later pass (governance only here).



## Annex C — Cam Tables & Seats (CT‑series)

> All quantities are admissions/ratios. Angles are given as node indices; radii are **normalised seats** relative to mid‑sweep (unit = full‑scale seat). Final gauge is a workshop affair; the ledger fixes only the **plan** and **bounds**.

### CT‑1. Chebyshev Node Plan (N = 9)
Let `A_k = (2k−1)·π/(2N)` for k=1…9 (Chebyshev abscissae). Define `χ_k = cos(A_k)`.

| k | A_k (index) | χ_k ≈ | Normalised target radius R̄_k |
|:--:|:--|:--:|:--:|
| 1 | (1·π)/(18) | 0.985 | 0.070 |
| 2 | (3·π)/(18) | 0.940 | 0.170 |
| 3 | (5·π)/(18) | 0.866 | 0.285 |
| 4 | (7·π)/(18) | 0.766 | 0.415 |
| 5 | (9·π)/(18) | 0.643 | 0.550 |
| 6 | (11·π)/(18) | 0.500 | 0.685 |
| 7 | (13·π)/(18) | 0.342 | 0.815 |
| 8 | (15·π)/(18) | 0.174 | 0.930 |
| 9 | (17·π)/(18) | 0.000 | 0.980 |

*Notes.* (i) The `R̄_k` are shaped to equalise ripple over the sweep; (ii) follower shoe width `W_shoe := 1⁄3·δ_node` where δ_node is the least spacing between consecutive `R̄_k` along the sweep.

### CT‑2. Residual Cancellation (Whisper Recipe)
- Engage `WHISPER_ON` during `CAM_TRAVERSE`. The whisper cam is cut as the **first Chebyshev residual mode**; summing at **amplitude 1:10** and **speed 10:1** relative to the principal cancels the dominant ripple.
- Phase: align whisper maxima to principal minima on first calibration; thereafter fixed by a detented phase plate.
- Bound: pre‑whisper equal‑ripple error **ε_cam,pre ≤ 3×10⁻³**; post‑whisper **ε_cam,post ≤ 3×10⁻⁴** of full‑scale seat.

### CT‑3. Two‑Seat Exemplars (Product & Quotient via Seats)

**Product (X·Y → P) by seats.**
1) κ₁·S1 — `DECIMAL_FETCH(x…)` → κ₃·S1 — `CAM_TRAVERSE(log)` → latch `Seat_logX`.
2) κ₁·S1 — `DECIMAL_FETCH(y…)` → κ₃·S3 — `CAM_TRAVERSE(log)` → latch `Seat_logY`.
3) **MILL_DIFF** — sum seats (`Seat_sum := Seat_logX + Seat_logY`).
4) κ₃·S2 — `CAM_TRAVERSE(exp)` (reverse train) → magnitude from `Seat_sum`.
5) κ₁·S1 — `DECIMAL_RESTORE(p…)`; κ₁·S2 — `CARRY_RECONCILE`.

**Quotient (X÷Y → Q) by seats.**
1) Fetch X,Y as above; obtain `Seat_logX`, `Seat_logY`.
2) **MILL_DIFF** — difference (`Seat_diff := Seat_logX − Seat_logY`).
3) κ₃·S2 — `CAM_TRAVERSE(exp)` → magnitude from `Seat_diff`.
4) Restore to Store; reconcile; audit.

*Guards.* All traverses honour `Clutch_Interlock_δ` and `Block_γ` (settle); κ₃ exclusivity by `Opposed_β(κ₃)`.



## Annex D — Index of Operations (by Section & Chart)
- Primitives (§3.1): BRAID_STEP, KNOT_READ, KNOT_WRITE, PLATE_TEST, DECIMAL_FETCH/RESTORE, CARRY_SAVE_ACCUMULATE, CARRY_RECONCILE, CAM_TRAVERSE, ROTATE_STEP, NORMALISE(135:82), AUDIT_CONGRUENCE, PRINT_ISSUE.
  Charts: TC‑1 (ROTATE/NORM), TC‑2 (CAM), TC‑3 (CARRY), TC‑4 (TAPE).
- Combined (§4.1): ADD, SUB, MULTIPLY(Log‑Cam), MULTIPLY(Rotation), DIVIDE, RECIPROCAL, ROOT.
  Tables: P‑4 footprints; Plates: B, E, D, F respectively.
- Trig Annex (§4.1A): SINCOS, ATAN.
  Tables: TT‑1, TT‑2; Charts: TC‑1; Plate: D.
- Universality (§§3.2, 4.2): Two‑Counter library; Braid‑Head clerk.
  Plate: C; Chart: TC‑4.

## Annex E — Gloss of Signs (Recap for Lettering)
- Couplings: `⟂κ₁` Store, `⟂κ₂` Braid, `⟂κ₃` Mill, `⟂κ₄` Print.
- Guards: `α` (Escapement), `β` (Opposed detent), `γ` (Block by predicate), `δ` (Clutch interlock).
- Unions & Motions: `‖` (permanent union), `⊳/⊣` (engage/release), arrows `→ ← ↑ ↓ ↺ ↻`.
- Mill tokens: `L_s` (lever scale), `N(135:82)` (bring‑to‑standard), `Cᵖ`/`Cʷ` cams, `Δʷ` whisper diff., `f_shoe`.
- Braid tokens: residues ⑤ ⑦ ⑨ ⑪, `head.{l,r}`, `feeler_read`, `pawl_write`.
- Store tokens: `S[i]`, `Sum‖Carry`, `decode_bar`, `Reset_Window`.
- Print tokens: `type_wheel[k]`, `impress.p`, `paper.advance`, audits ⑨, ⑪, `proof_gate`, `ink_bar`.
- Proof marks: `⟦Φ⟧` potential check; `≺` precedence; `{…}` alternatives; `⌶` seat/latch; `[Settle]` slot.

*For the canonical legend consult MA‑0…MA‑4. This recap is for swift lettering at the bench.*

