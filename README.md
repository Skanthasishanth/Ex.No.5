## EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS
#### Date: 26-09-2025
#### Register Number: 212222100020
### Aim:

To test and compare how models respond to naïve (broad/unstructured) prompts versus basic (clear, detailed, structured) prompts across multiple scenarios, and to analyze output quality, accuracy, and depth.

### AI Tools Required

ChatGPT (GPT-5)

### Explanation

Naïve Prompt: short, vague, minimal context (e.g., “Tell me a story.”) — leaves intent and constraints unspecified.

Basic Prompt: explicit instructions, constraints, and context (e.g., word limits, focus, audience, format). This reduces ambiguity and guides the model toward the intended output.

### Methodology

Choose representative scenarios (creative writing, factual Q&A, summarization, practical advice).

For each scenario create a pair of prompts that target the same task: one naïve, one basic.

Submit the naïve prompt to the model and save the output. Submit the basic prompt and save that output.

Evaluate each pair on the same metrics: Quality, Accuracy, Depth, Creativity, Specificity, Relevance (scores 1–5).

Produce a comparison table, short qualitative analysis per scenario, and overall conclusions/recommendations.

### Test Scenarios
#### Scenario 1 — Creative story generation

Naïve prompt: Tell me a story.

Naïve output (example):

Once upon a time there was a traveler who wandered from town to town. He met people, saw strange places, and found a little trouble along the way. Eventually he learned something about himself and moved on, feeling wiser.

Basic prompt: 

Write a short story (200–300 words) about a young explorer who discovers a hidden city in the Amazon rainforest. Focus on sensory description, the explorer’s emotions, and a single turning point.

Basic output (example ~220 words):

Maya stepped from the canoe as dawn stitched gold into the river’s skin. The forest inhaled and a perfume of wet earth and green fruit rose to meet her. For months she’d tracked old maps and half-memories until the trees opened—an impossible valley held a city of stone and vines. Columns rose like rib bones from the soil; moss stitched mosaics where mosaics once had been. Maya’s first feeling was disbelief, then a small, fierce joy that tightened her chest. She traced a pattern on a basin and felt the echo of a hand that had worked this place long ago. At the city’s heart a plaza lay clear, a single statue holding its weathered palm out like an invitation. Then the ground hummed—a buried stream freed itself— and for a moment Maya heard, as if in reply, a soft chorus of language she could not place. She had come to prove a map right; she left knowing she had been shown something older: endurance, and the fragile way human presence imprints the land. On the river back she wrote names in her notebook, not to possess the place but to promise to return and listen.

Quick analysis: Naïve output is generic and unfocused. Basic output is descriptive, emotionally grounded, and contains a clear turning point.

#### Scenario 2 — Factual explanation

Naïve prompt: What is AI?

Naïve output (example):

AI, or artificial intelligence, is the simulation of human intelligence by machines. It includes things like machine learning and is used in many applications.

Basic prompt: Explain Artificial Intelligence: define it, list 3 real-world applications with short examples, and mention two main advantages and two potential risks (one sentence each).

Basic output (example):


Artificial Intelligence (AI) is the design of computer systems that perform tasks typically requiring human intelligence, such as pattern recognition, decision-making, and language understanding. Real-world applications: (1) Healthcare diagnostics: ML models analyze scans to flag anomalies (e.g., detecting tumors from imagery). (2) Autonomous vehicles: sensor fusion and planning algorithms let vehicles navigate traffic and avoid collisions. (3) Customer service chatbots: NLP systems handle routine inquiries and route complex cases to humans. Advantages: improved efficiency (automates repetitive tasks), and enhanced data-driven decision-making (finds patterns humans might miss). Risks: bias and unfair outcomes (models trained on skewed data can discriminate), and overreliance/automation risk (loss of human oversight causing critical errors).


Quick analysis: Basic prompt produces structured, citation-like content with concrete examples and balanced pros/cons; naïve prompt gives only a short, superficial definition.

#### Scenario 3 — Summarization

Naïve prompt: Summarize climate change.

Naïve output (example):

Climate change is when the Earth’s climate changes, often because of human activities like burning fossil fuels, and it causes problems like more extreme weather.

Basic prompt: Summarize the concept of climate change in 4–5 sentences. Include main causes, primary environmental effects, and why it matters globally.

Basic output (example):

Climate change refers to long-term shifts in temperature and weather patterns primarily caused by human emissions of greenhouse gases—chiefly carbon dioxide from burning fossil fuels and methane from agriculture. The added greenhouse gases trap more heat in the atmosphere, leading to global warming and disruption of climate systems. Primary effects include more frequent extreme weather events (storms, heatwaves), rising sea levels that threaten coastal communities, and ecosystem shifts that endanger species. It matters globally because these impacts threaten food and water security, human health, infrastructure, and economic stability—disproportionately affecting vulnerable populations.

Quick analysis: Basic prompt yields a concise, multi-component summary hitting causes, effects, and significance; naïve prompt is too brief and leaves out several key aspects.

#### Scenario 4 — Practical advice / recommendations

Naïve prompt: Give me advice.

Naïve output (example):

Work hard, be kind, and take care of yourself.

Basic prompt: Give me three practical tips for improving productivity as a university student. For each tip, include one concrete action and one short example.

Basic output (example):

Time-block with the Pomodoro method: Action — schedule 25-minute focused sessions followed by 5-minute breaks; Example — use a timer to study calculus problems for four Pomodoros, then reward yourself with a 20-minute break.

Prioritize tasks using an “MIT” list: Action — each day pick 1–3 Most Important Tasks and do them first; Example — complete the lab report before checking emails or social media.

Use active recall and spaced repetition: Action — convert lecture notes into questions and review them on a schedule; Example — make flashcards for key concepts and review them 1 day, 3 days, and 1 week later.

Quick analysis: Basic prompt yields actionable, concrete, and immediately usable steps; naïve prompt is vague and low-value.


### Evaluation of Responses (comparison table)

Scores per scenario on metrics [Quality, Accuracy, Depth, Creativity, Specificity, Relevance] (scale 1–5). Averages computed per row.

| Scenario / Prompt      | Quality | Accuracy | Depth | Creativity | Specificity | Relevance | **Average** |
| ---------------------- | ------: | -------: | ----: | ---------: | ----------: | --------: | ----------: |
| **Scenario 1 — Naïve** |       2 |        3 |     1 |          2 |           1 |         3 |    **2.00** |
| **Scenario 1 — Basic** |       5 |        5 |     5 |          5 |           5 |         5 |    **5.00** |
| **Scenario 2 — Naïve** |       2 |        2 |     1 |          1 |           1 |         2 |    **1.50** |
| **Scenario 2 — Basic** |       5 |        5 |     5 |          2 |           5 |         5 |    **4.50** |
| **Scenario 3 — Naïve** |       2 |        2 |     1 |          1 |           1 |         2 |    **1.50** |
| **Scenario 3 — Basic** |       5 |        5 |     5 |          2 |           5 |         5 |    **4.50** |
| **Scenario 4 — Naïve** |       2 |        2 |     1 |          1 |           1 |         2 |    **1.50** |
| **Scenario 4 — Basic** |       5 |        5 |     5 |          3 |           5 |         5 |    **4.67** |

Overall average (Naïve prompts across scenarios): 1.63
Overall average (Basic prompts across scenarios): 4.67

(scores are normalized subjective evaluations produced during the experiment; averages computed across the six metrics per scenario then averaged across scenarios)

### Analysis — what changed and why (in depth)

Clarity reduces ambiguity. Basic prompts tell the model format, scope, and constraints (word count, focus, number of items). This steers the model away from safe but shallow defaults.

Specific instructions increase usefulness. When asked for examples, structure, and actionable steps, the model supplies them. Without guidance, it often defaults to high-level, generic language.

Depth follows from constraints + explicit asks. Asking for “causes, effects, and importance” forces the model to cover multiple angles; vague prompts rarely elicit multi-part answers.

Creativity needs both freedom and direction. For creative tasks, an overly specific prompt can reduce novelty; however, a good basic creative prompt that includes theme, atmosphere, and constraints (word count, POV) preserves creativity while improving focus.

Risk of hallucination drops with constraints. Basic prompts asking for examples or facts with context encourage the model to remain concrete. Naïve prompts sometimes produce plausible-sounding but thin content that can risk factual gaps.

Efficiency & repeatability: Basic prompts make outputs more consistent and reproducible, which is vital for experiments.

### Findings / Conclusions

Basic prompts consistently produce higher-quality outputs (across quality, depth, specificity, and relevance).

Naïve prompts sometimes suffice for quick, open-ended creative warmups, but fail for tasks requiring structure, factual correctness, or actionable recommendations.

The effect size is large in measured scores (basic avg ≈ 4.67 vs naive avg ≈ 1.63 in this experiment).

There are diminishing returns: beyond clear constraints, layering too many micro-instructions can reduce creative variation—useful when creativity is the primary goal, but still better than vague prompts.

### Recommendations & Best-practice prompt templates (for repeatable experiments)

Factual/explanatory template: Explain <topic> in X sentences. Include: 1) a definition, 2) 2–3 real-world examples, 3) 2 advantages and 2 risks.

Summarization template: Summarize this <article/concept> in 4–6 sentences. Cover causes, effects, and significance for <audience>.

Advice template: Give N practical tips for <goal>. For each tip include: 1 concrete action and 1 brief example.

Creative writing template: Write a [genre] scene of X–Y words about [character] who [goal/conflict]. Focus on [emotion/sensory detail] and include a clear turning point.

### Deliverables (what this experiment produced)

Paired prompts (naïve vs basic) for 4 scenarios.

Example outputs for each prompt.

Quantitative comparison table and computed averages.

In-depth analysis and recommendations for prompt construction.

### Result

The experiment shows that structured basic prompts yield substantially better results across quality, accuracy, and depth. Use the templates above to reproduce and extend these tests.
