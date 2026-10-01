# Behavioral Persona Classification: Deterministic 5-Field Schema

The objective, anti-hallucination classification engine for profiling target audiences based on behavioral causality rather than empty demographics.

## 1. The Failure of Demographic Profiling

Traditional marketing classifications like 'Women 25-45, interested in wellness' are useless for video engineering. Two 35-year-old mothers can have completely opposite psychological profiles:
- One is an anxious hypochondriac seeking instant relief from chronic bloating.
- The other is a skeptical biohacker testing heavy-metal chelation protocols.

To build replicable video formats, you must classify audiences by their behavioral and cognitive states.

## 2. The Deterministic 5-Field Behavioral Schema

Every audience profile must be constructed using these exact five behavioral fields:

```json
{
  "trigger": "The acute real-world catalyst or physical symptom that forces immediate action",
  "functional_job": "The practical, tangible, measurable outcome the viewer needs to achieve",
  "emotional_job": "The internal emotional transformation or relief from shame/fear sought",
  "solution_bias": "The viewer's pre-existing worldview, skepticism, and past failed remedies",
  "root_cause": "The true underlying systemic, biological, or psychological condition"
}
```

### Detailed Field Definitions

1. **Trigger (`trigger`)**:
   - What just happened? (e.g. 'Woke up with painful stomach distension after eating salad', 'Felt embarrassed by bad breath during a meeting', 'Saw a terrifying video about parasites in sushi').
2. **Functional Job (`functional_job`)**:
   - What physical job does the remedy perform? (e.g. 'Empty bowels within 30 minutes without cramping', 'Remove yellow tartar from lower front teeth at home', 'Find a cereal without BHT or food dye for children').
3. **Emotional Job (`emotional_job`)**:
   - What anxiety is silenced? What status is gained? (e.g. 'Relief from the terrifying thought that something is medically wrong with me', 'Feeling like an enlightened, protective mother', 'Reclaiming bodily dignity in public spaces').
4. **Solution Bias (`solution_bias`)**:
   - What does this person already believe? Who do they mistrust? (e.g. 'Distrusts conventional doctors who prescribe laxatives', 'Believes supermarket food is poisoned by corporations', 'Prefers 2-ingredient natural remedies over supplements').
5. **Root Cause (`root_cause`)**:
   - What is the actual underlying reality? (e.g. 'Gastrocolic reflex hypersensitivity exacerbated by social anxiety', 'Microbiome dysbiosis from antibiotic overuse', 'Chronic dehydration and mineral deficiency').

## 3. The 6 Canonical Health & Wellness Behavioral Archetypes

| Archetype Name | Dominant Trigger | Primary Solution Bias | Core Emotional Job |
| :--- | :--- | :--- | :--- |
| **The Desperate Reliever** | Acute, embarrassing, or painful physical flare-up (bloat, constipation, migraine) | Needs immediate action; tired of waiting for appointments | Escape from acute distress and public shame |
| **The Anxious Symptom Solver** | Mysterious bodily quirk (eye twitch, cold feet, shopping-induced bowel urges) | Fosters secret hypochondria; fears undiagnosed rare disease | Reassurance of normalcy and validation that they are not crazy |
| **The Skeptical Optimizer** | Chronic low-grade fatigue, brain fog, sub-optimal gym recovery | Biohacking, lab tests, quantifiable mechanisms, ancestral protocols | Attaining cognitive dominance and physical superiority |
| **The Protective Purist (The Gatekeeper Mother)** | Learning that everyday family items contain toxins, microplastics, or dyes | Naturalism, folk herbs, sovereign parenting, distrust of corporate food | Moral pride in shielding loved ones from corporate harm |
| **The Chronic Exhaustion Seeker** | Waking up exhausted, burnout, adrenal crash, afternoon brain slump | Disillusioned by caffeine and standard blood tests ('Everything is normal') | Reclaiming vital energy without harsh pharmaceutical crashes |
| **The Taboo / Hygiene Insecure** | Socially mortifying symptoms (bad breath, body odor, parasite fears, skin flakes) | High stigma; unwilling to discuss openly with friends or doctors | Restoration of basic interpersonal confidence and cleanliness |

## 4. Decision Tree: Assigning Personas from Reel Evidence

Follow this deterministic sequence when evaluating an outlier video:

```
[Start with Reel & Comment Section]
                |
                v
Does the hook highlight an embarrassing, taboo, or sudden physical bodily reaction?
      |                                           |
     YES                                          NO
      |                                           |
      v                                           v
Is it a sudden symptom (bowel/quirk)?     Does it expose hidden toxins in food/home?
      |                         |                 |                           |
     YES                        NO               YES                          NO
      |                         |                 |                           |
[The Anxious             [The Taboo /       [The Protective             Does it focus on
Symptom Solver]          Hygiene Insecure]    Purist]                   energy / optimization?
                                                                              |
                                                                             YES
                                                                              |
                                                                        [The Chronic
                                                                        Exhaustion Seeker]
```

## 5. Mandatory Anti-Hallucination Rules

- Never declare a persona without citing at least 3 verbatim comments confirming the psychological state.
- Always provide a confidence rating: `[Confidence: High / Moderate / Speculative]`.
