# Standardized Analysis Report Template & Data Contract

Every multimodal analysis produced by the Deep Analyst must adhere to this standardized output contract.

## Report Markdown Schema

```markdown
# Forensic Intelligence Dossier: [Reel Shortcode] - @[Creator Handle]

**Audit Timestamp**: [YYYY-MM-DD HH:MM UTC]
**Metrics at Audit**: [Views] Views | [Likes] Likes | [Comments] Comments | Velocity Multiplier: [R]x

---

## 1. Executive Summary & Virality Diagnosis
[Dense 3-4 sentence distillation of why this video achieved outlier status. Explain the intersection of visual prime, psychological tension, and algorithmic amplification.]

---

## 2. Multimodal Hook Deconstruction (0-3s Boundary)
- **Exact Millisecond Hook Boundary**: [0.0s to X.Xs]
- **Verbatim Spoken Hook**: "[Exact words spoken]"
- **Text Banner Hierarchy**: "[Headline text overlay]" (Font, Color, Screen Position)
- **Opening Frame Visual Prime**: [Detailed description of t=0.0s frame, prop, gaze, lighting]
- **Single-Chute Attentional Prime**: [How Pre-Suasion channels attention into a single hypothesis]
- **Acoustic Cadence**: [Hook WPM, vocal pitch, inflection, audio sound effects]

---

## 3. Script Persuasion Sequence & Slippery Slide
[Beat-by-beat chronological breakdown of the cognitive journey]
- **Beat 1: The Hook & Pattern Interrupt (0.0s - X.Xs)**: [Analysis]
- **Beat 2: Agitation & Emotional Mirroring (X.Xs - X.Xs)**: [Analysis]
- **Beat 3: Villain Exposure & Root Cause (X.Xs - X.Xs)**: [Analysis]
- **Beat 4: The Remedy & Physical Protocol (X.Xs - X.Xs)**: [Analysis]
- **Beat 5: Call to Action & Infinite Loop (X.Xs - End)**: [Analysis]

---

## 4. Psychological Levers & Compliance Mechanics
- **Life-Force 8 Desire**: [LF8-X: Name] - [Explanation of biological tension created]
- **Primary Weapon of Influence**: [Reciprocity / Authority / Scarcity / etc.] - [Tactical execution]
- **Sugarman Triggers Activated**: [List 3-4 specific triggers with timestamps]
- **Perceptual Contrast**: [How the bad option is contrasted with the simple remedy]

---

## 5. Audience Psychographic Profile & Persona Tagging
- **Assigned Persona Archetype**: [Name of Archetype]
- **Confidence Rating**: [Confidence: High / Moderate / Speculative]
- **Behavioral Schema**:
  - `trigger`: [Acute catalyst]
  - `functional_job`: [Tangible task]
  - `emotional_job`: [Emotional relief/status]
  - `solution_bias`: [Beliefs and skepticism]
  - `root_cause`: [Systemic physical reality]
- **Top Comment Verification**:
  1. "[Verbatim Comment 1]" - [Psychological signal]
  2. "[Verbatim Comment 2]" - [Psychological signal]
  3. "[Verbatim Comment 3]" - [Psychological signal]

---

## 6. Structural DNA & Content Factory Adaptation
- **Format Chassis**: [Format Name, e.g. Automotive Doctor Confession]
- **Replicability Score**: [1-10] / 10
- **Adaptation Blueprint for Content Factory**:
  - Proposed Hook Variation: "[Hook for synthetic avatar]"
  - Staging & Props: [Required props and environment]
  - Funnel / ManyChat Keyword: "[Keyword]"
```

## JSON Database Persistence Contract

For insertion into `factory.db` `analyses` table:

```json
{
  "video_shortcode": "SHORTCODE",
  "format_id": "FORMAT_SLUG",
  "persona_tag": "PERSONA_SLUG",
  "confidence": "High",
  "hook_boundary_seconds": 2.45,
  "hook_spoken": "Verbatim hook text",
  "hook_visual": "Visual frame description",
  "hook_text_overlay": "On-screen banner text",
  "persuasion_sequence_json": [
    {"timestamp": "0-3s", "beat": "Hook", "tactic": "Single-Chute Prime"},
    {"timestamp": "3-12s", "beat": "Agitate", "tactic": "LF8-3 Pain Avoidance"},
    {"timestamp": "12-28s", "beat": "Root Cause", "tactic": "Authority Proof"},
    {"timestamp": "28-42s", "beat": "Protocol", "tactic": "Simplicity Trigger"},
    {"timestamp": "42-48s", "beat": "CTA", "tactic": "Reciprocal DM Trigger"}
  ],
  "psychological_triggers": ["LF8-1", "Authority", "Curiosity", "Contrast"],
  "remixability_score": 9.2
}
```
