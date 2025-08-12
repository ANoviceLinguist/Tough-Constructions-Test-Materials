# Codebook — Tough to Learn Tough Constructions: Test Materials

This codebook documents the structure, columns, and labels for all CSV files in this repository.

---

## 1. `exp1.csv` — Experiment I

**Purpose**  
The test materials test syntactic well-formedness judgments for *Tough* constructions and related control items.

**Columns**

| Column | Type | Description |
|--------|------|-------------|
| `NUM` | Integer | Unique numeric ID for the item. |
| `SET` | String/Integer | Experimental set/group identifier. |
| `TYPE` | String | Condition type (e.g., `tough`, `non-tough`, `control`). |
| `GAP` | String | Gap position/feature (e.g., `subject`, `object`). |
| `GRAMMATICALITY` | String | Gold standard grammaticality judgment (`acceptable` / `unacceptable`). |
| `SENTENCE` | String | Full test sentence in English. |

**Example Rows (Set 1)**

| NUM | SET | TYPE              | GAP | GRAMMATICALITY | SENTENCE |
|-----|-----|-------------------|-----|----------------|----------|
| 1   | 1   | Tough             | `+` | Grammatical    | John is easy to please. |
| 2   | 1   | Subject-Control   | `+` | Grammatical    | John is eager to please. |
| 3   | 1   | Tough             | `-` | Ungrammatical  | John is easy to please his friends. |
| 4   | 1   | Subject-Control   | `-` | Grammatical    | John is eager to please his friends. |

---

## 2-1. `exp2_object.csv` — Experiment II (Object-Focused)

**Purpose**  
The test materials evaluate semantic interpretation in contexts where the focus is on the **object** affected by the action.

**Columns**

| Column | Type | Description |
|--------|------|-------------|
| `SET` | String/Integer | Experimental set/group identifier. |
| `SENDER` | String | Speaker producing the utterance. |
| `RECEIVER` | String | Addressee/recipient of the utterance. |
| `CONTEXT` | String | Scenario context for interpreting A/B/C. |
| `A` | String | Option A (test sentence). |
| `B` | String | Option B (test sentence). |
| `C` | String | Option C (test sentence). |

**Example Row (Set 1)**

| SET | SENDER | RECEIVER | CONTEXT | A | B | C |
|-----|--------|----------|---------|---|---|---|
| 1 | John | Tom | John has to send a very heavy box to Tom, who lives right next door. John complains to his friend about this. | This box is tough to send to Tom. | Tom is tough to send this box to. | It is tough to send this box to Tom. |

---

## 2-2. `exp2_goal.csv` — Experiment II (Goal-Focused)

**Purpose**  
The test materials evaluate semantic interpretation in contexts where the focus is on the **goal** of the action.

**Columns**

| Column | Type | Description |
|--------|------|-------------|
| `SET` | String/Integer | Experimental set/group identifier. |
| `SENDER` | String | Speaker producing the utterance. |
| `RECEIVER` | String | Addressee/recipient of the utterance. |
| `CONTEXT` | String | Scenario context for interpreting A/B/C. |
| `A` | String | Option A (test sentence). |
| `B` | String | Option B (test sentence). |
| `C` | String | Option C (test sentence). |

**Example Row (Set 1)**

| SET | SENDER | RECEIVER | CONTEXT | A | B | C |
|-----|--------|----------|---------|---|---|---|
| 1 | John | Tom | John has to send a lightweight box to Tom, who lives alone in a remote island far away. John complains to his friend about this. | This box is tough to send to Tom. | Tom is tough to send this box to. | It is tough to send this box to Tom. |

---

## 2-3. `exp2_event.csv` — Experiment II (Event-Focused)

**Purpose**  
The test materials evaluate semantic interpretation in contexts where the focus is on the **event** itself.

**Columns**

| Column | Type | Description |
|--------|------|-------------|
| `SET` | String/Integer | Experimental set/group identifier. |
| `SENDER` | String | Speaker producing the utterance. |
| `RECEIVER` | String | Addressee/recipient of the utterance. |
| `CONTEXT` | String | Scenario context for interpreting A/B/C. |
| `A` | String | Option A (test sentence). |
| `B` | String | Option B (test sentence). |
| `C` | String | Option C (test sentence). |

**Example Row (Set 1)**

| SET | SENDER | RECEIVER | CONTEXT | A | B | C |
|-----|--------|----------|---------|---|---|---|
| 1 | John | Tom | John has to send a lightweight box to Tom, who lives right next door. However, John recently hurt his back and has trouble bending or lifting anything. John complains to his friend about this. | This box is tough to send to Tom. | Tom is tough to send this box to. | It is tough to send this box to Tom. |

---

## Notes for All Files

- **Encoding:** All CSV files are UTF-8 encoded with comma separators.
- **License:** TBD
- **Citation:** TBD

---
