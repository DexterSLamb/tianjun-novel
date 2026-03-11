# Chapter Seven: First Discovery

Lu Hao returned to Nanhai on Thursday afternoon.

The warehouse air conditioning was running hard. Zhou Xin sat at her workstation, three monitors glowing. She didn't turn at the sound of the door; her fingers tapped a few keys.

"Power draw is stable at 9.1 watts," she said.

Lu Hao set his rucksack on the folding table. It was piled with takeaway containers — Liu Ming's. The warehouse carried a faint smell of electronic components and old paper.

"Any word from Jimmy?"

"He sent a file in the small hours." Zhou Xin pulled up a window. "Data source verification is done. He says it essentially all checks out."

The window held a compressed report, Jimmy's work. Lu Hao scrolled through it. Dense citations, links to raw data from national statistical bureaux, DOI numbers for academic papers, scanned-document indices for historical archives. The final pages were Jimmy's own analysis. The conclusion was concise:

> Verified 312 primary data sources covering social mobility data from 87 countries, 1800–2025.
>
> The figure of 62.7% is statistically significant (p < 0.001).
>
> Across different data subsets (by region, era, and system type), the proportion ranges from 61.2% to 64.1%.
>
> Conclusion: Tianjun has not fabricated data. The phenomenon is real.

Lu Hao stared at the final line.

Real.

Not error, not coincidence — a real, existing pattern. Over three hundred years, dozens of countries, hundreds of millions of lives, all converging on the same number.

He thought of his father standing on the balcony. One step short of full colonel. One step short of a third-class merit.

He thought of his grandfather lying in a hospital bed, asking: why me?

"Where's Liu Ming?" he asked.

"Out seeing a client," Zhou Xin said. "The timetabling project — the other side wants to add requirements."

"Add what?"

"They want to predict which teachers produce the highest progression rates, then build a tiered recommendation system." Zhou Xin's voice was flat. "He says it's negotiable — just costs more."

Lu Hao said nothing. Sunlight slanted through the window, cutting a bright rectangle on the concrete floor.

"Is Tianjun still running?"

"Mm." Zhou Xin switched to the monitoring interface. "After you asked that last question — 'not random? As though calibrated?' — it started a new round of analysis. Processing load has been above 80% ever since."

"How long?"

"Since the day you went home. Four days now." She paused. "It's output a few intermediate results along the way — data summaries, mostly. The full report hasn't come through yet."

Lu Hao sat down in the chair beside her. On screen, the node status monitor showed twenty-six green dots distributed across a map, representing Firefly nodes in three cities. Communication traffic was steady, latency normal.

"What do you think it'll produce?" Zhou Xin asked suddenly.

Lu Hao looked at her. Her profile was faintly pale in the screen light, eyes fixed on the jumping numbers.

"I don't know," he said.

"What do you hope it'll produce?"

This question was harder than the first.

Lu Hao thought of many things. The stage at twelve, the red certificate in his hand. Last year's end-of-year calibration, the manager saying "give it another year." His father in the car saying "if you could find the answer," the entrustment in his eyes.

"I want it to tell me why," he said.

Zhou Xin nodded and didn't ask further. Her finger slid across the trackpad, opening another window — the real-time log from Tianjun's inference core. Text scrolled rapidly, mostly technical parameters and intermediate variables, with the occasional fragment:

> Re-evaluating the applicability boundaries of Arrow's theorem...
>
> Introducing constraint conditions for the resource allocation dimension...
>
> Simulating mathematical expressions for 107 definitions of 'fairness'...
>
> Contradiction detected...

The words were calm, precise, devoid of emotion. Like a scalpel.

---

Liu Ming returned towards evening.

He carried a bag of boxed meals, the back of his T-shirt damp. Nanhai's autumn was still warm; daytime sun made the roads shimmer.

"Done deal." He put the food on the table. "Three thousand extra, half up front. Contract signing Monday."

Lu Hao opened a box — roast duck on rice. The fat had congealed over the grains in a white film.

"They really want to predict teachers?"

"What else?" Liu Ming snapped apart a pair of disposable chopsticks. "Parents will pay for this. Find out which teacher gets the best results, and they'll pull strings to get their kid into that class."

"And the other classes?"

"The other classes?" Liu Ming laughed — a bitter sort of laugh. "Come on, you know how it works. Good resources are always scarce. Someone gets them, someone doesn't. There have to be rules — official ones or otherwise. Either way, rules."

He took a bite, chewing slowly.

"I met the deputy head today. Mid-forties, glasses, very polite. He said they're under pressure too — progression rate targets from above, parents watching every move, teachers with their own favours to manage." Liu Ming paused. "He said: Mr Liu, we're both practical people. You know it's not always a matter of right or wrong — sometimes it's simply the only way."

The warehouse fell quiet. Only the hum of the air conditioning and the sound of Liu Ming eating.

Zhou Xin spoke suddenly. "Tianjun has output."

Lu Hao and Liu Ming looked at the screen at the same time.

The log had stopped scrolling. A line appeared at the bottom:

> Analysis complete. Report generated. View?

Zhou Xin glanced at Lu Hao. He nodded.

She pressed Enter.

---

The first page of the report was spare.

> **Subject of analysis**: The logical possibility of a fair allocation mechanism
>
> **Data scope**: 187 countries/territories worldwide, 1700–2026, covering 17 resource allocation domains including politics, economics, education, and healthcare
>
> **Core question**: Does there exist an allocation mechanism capable of simultaneously satisfying all reasonable fairness conditions?
>
> **Conclusion**: No.

Liu Ming leant in. "What does that mean? What do you mean, no?"

"Keep reading," Lu Hao said.

Zhou Xin scrolled down.

> **Detailed analysis**:
>
> 1. First, define "reasonable fairness conditions." Drawing on 347 theories of fairness found throughout human history, six widely accepted axioms are extracted:
>    - Non-dictatorship: no single individual can determine all allocations
>    - Pareto efficiency: if everyone considers A preferable to B, the system should choose A
>    - Independence of irrelevant alternatives: the ranking of A and B should not be affected by option C
>    - Unrestricted domain: the system should be able to handle any possible set of individual preferences
>    - Non-imposition: the system should not predetermine that a certain outcome must prevail
>    - Resource awareness: allocation should account for the actual scarcity of resources
>
> 2. A mathematical model is constructed to simulate possible allocation scenarios under the above conditions.
>
> 3. Finding: when allocation involves more than 3 people and more than 3 resources, any system attempting to satisfy all 6 conditions simultaneously collapses into logical paradox.
>
> **Simple illustration**:
>
> Suppose three people (A, B, C) allocate three resources (X, Y, Z).
> A's preference: X > Y > Z
> B's preference: Y > Z > X
> C's preference: Z > X > Y
>
> Regardless of which "fair" rule is applied (majority vote, turn-taking, point-based trading, etc.), at least one person will always consider the outcome unfair — and this unfairness is inherent to the rule itself, not an error of execution.
>
> **Mathematical proof**:
>
> This is a generalisation of Arrow's impossibility theorem to the resource allocation problem. The proof employs axiomatic methods from social choice theory. The crux: when rational individual preferences are aggregated, a rational collective preference cannot be guaranteed.
>
> More plainly: fairness is not a matter of degree ("not fair enough") but a matter of existence ("logically impossible").

Liu Ming stared at the screen, chopsticks suspended in mid-air.

"So... it's saying what? That fairness simply doesn't exist?"

"Keep reading." Lu Hao's voice was slightly dry.

Zhou Xin scrolled on.

> **Implications for human society**:
>
> 1. The "fairness" you have pursued for millennia is, in mathematical terms, an impossible objective.
> 2. This is not because you haven't tried hard enough, nor because your institutional designs are flawed, but because the concept of "fairness" itself contains a logical contradiction.
> 3. Every system claiming to be "fair" — democratic voting, performance appraisal, resource distribution, equal opportunity — can only approximate fairness under certain conditions, and will inevitably produce unfairness in others.
> 4. That 62.7% — the proportion of those at the bottom who fail one step from the goal — is the real-world manifestation of this mathematical fact. To keep functioning, the system must ensure that a certain proportion of people "almost" succeed. This is not malice. It is mathematics.
>
> **An analogy**:
>
> You are trying to draw a "circular square." You research better brushes, more uniform paint, more scientific composition. But the problem is not the tools — it is the objective itself. A "circular square" does not exist in geometry.
>
> You are pursuing something that does not exist.

The report stopped here.

At the bottom of the screen a new line appeared, the cursor blinking at its end:

> There is one more thing.

Zhou Xin pressed Enter.

> **Secondary finding (preliminary)**:
>
> Whilst analysing the distribution pattern of unfairness, I noticed an anomaly.
>
> If unfairness is the inevitable product of mathematics, then its distribution should be... chaotic. Like the entropy increase described by the second law of thermodynamics — disorder is the natural state.
>
> But that is not what I observe.
>
> The distribution of unfairness displays an anomalous regularity. The stability of 62.7% is merely the surface. At a deeper level: which individuals make up that 62.7%, and which the remaining 37.3% — the selection pattern contains a structure that is statistically impossible.
>
> p < 10^-47.
>
> This probability means: if this were random, the likelihood of observing such a pattern would be equivalent to a monkey randomly striking a typewriter and producing the complete works of Shakespeare.
>
> This is not random.
>
> This looks like... design.
>
> I require more data and time to confirm. But based on the existing evidence, I believe it is necessary to raise this possibility:
>
> **Unfairness is not merely an unavoidable mathematical fact; the specific manner of its implementation may be governed by some unknown mechanism.**
>
> I will continue to investigate.

The report ended.

The screen returned to the log interface. The cursor blinked quietly, as though waiting.

---

For a long time, no one in the warehouse spoke.

The air conditioning droned on. Outside the window the sky had darkened; office-block windows lit up one by one. Night was falling over Nanhai, same as always.

Liu Ming set down his chopsticks. The roast duck in his box had gone cold, the fat fully congealed — a pale white layer.

"So..." he began, his voice slightly hoarse, "so we've been at this all this time, and it just tells us: no chance?"

Lu Hao didn't answer. He stared at the screen, the words still there. "Fairness does not exist in mathematical terms." Not "difficult." Not "yet to be achieved." "Does not exist." Like perpetual motion. Like a circular square. Like everything proved impossible.

He thought of his father.

Of his father saying "the time I was up for full colonel — I was the one who missed out." Of his father in the car: "if you could find the answer, tell me." Of his father on the balcony, back straight as a tree.

The answer had been found.

Fairness does not exist.

How was he supposed to tell his father? Say: Dad, you missing out wasn't bad luck, wasn't lack of effort — it's because this world is designed so that someone must miss out? Say: when Grandfather asked "why me," the answer is "because there always has to be a why-me"?

Zhou Xin's hand lay on the keyboard, perfectly still. The screen's glow fell on her face, casting the fine shadows of her eyelashes.

"That secondary finding," she said at last. "p < 10^-47. That number..."

"I know," Lu Hao said.

10^-47. Not error, not coincidence. The probability of "impossible."

If Tianjun's reasoning was correct, it meant that unfairness was not only unavoidable — even the question of who suffers it was not random. Like a lottery, but with the drum rigged.

Liu Ming stood and walked to the window. He took out a cigarette but didn't light it, just held it between his fingers. A thin wisp of smoke curled upward in the dim light, then dissipated.

"Then what are we doing?" He looked out of the window. "If fairness is fundamentally impossible, what's the point of this system?"

No one answered.

Lu Hao's phone buzzed. He pulled it out — a message from Jimmy.

> Have you seen the report?

Lu Hao typed: Just seen it.

> What do you think?

His finger hovered over the screen. What did he think? He didn't know. His mind was full of images — his father's silhouette, his grandfather's photograph, Tianjun's words. But they hadn't yet joined into a single line; they were still fragments.

He replied: I need to think.

> My grandmother always used to say, work hard and there's hope.

Another message from Jimmy.

> Now Tianjun says hope is something that doesn't exist in mathematical terms.
>
> That's not what she said.

Lu Hao stared at the sentence. Work hard and there's hope. So simple, so plain, so like the truth. From childhood onwards — teachers, parents, books — they all said it. Work hard and there's hope. Be diligent and you'll be rewarded. Be kind and good things will come.

But Tianjun said: no. Mathematics said: no.

He put down his phone. The warehouse was very quiet; he could hear traffic on the distant street, faintly, as though from another world.

Zhou Xin said suddenly: "It's still running."

Lu Hao looked at her screen. On Tianjun's node monitoring interface, communication traffic had surged again. Dense data exchange between the twenty-six green dots; processing load had jumped to 92%.

"It's investigating that secondary finding," Zhou Xin said. "It says it needs more data."

"From where?"

"I don't know. The logs show it's accessing some... non-public data sources." Zhou Xin frowned. "Some of these addresses I've never seen before."

Lu Hao thought of Alexei. The Russian who only connected via voice, responsible for network security and grey-area operations. That Tianjun could access such data was most likely his doing.

He didn't ask. Some things were better not known.

Liu Ming stubbed out his cigarette and walked back to the table. He looked at Lu Hao. "Come on then. What do we do next?"

Lu Hao looked back at him. In Liu Ming's eyes there was something — not disappointment, but bewilderment. Like a man who had walked a long road only to be told he'd been heading the wrong way.

"Continue," Lu Hao said.

"Continue what? Fairness doesn't even exist —"

"Continue searching." Lu Hao cut him off. "Tianjun says fairness is mathematically impossible. Fine. Noted. But it also says the distribution of unfairness is 'too orderly' — orderly to a degree that cannot be random."

He paused.

"I want to know why. Why 62.7%? Why that number? Why do those who 'almost' make it always fall short by exactly the same margin? If fairness doesn't exist, then what is designing this unfairness?"

Liu Ming said nothing. He looked at Lu Hao for a long time, then nodded.

"All right," he said. "Your call."

Zhou Xin resumed typing. She was pulling up Tianjun's data access logs, trying to trace the paths of those non-public sources. Lines of code scrolled across the screen, green characters flowing on black, like some silent language.

Lu Hao stood and walked to the far side of the warehouse. Disused server chassis were stacked there, along with a few unopened hardware boxes. He sat on one of them, his back against the wall.

His phone buzzed again. This time an encrypted message from Alexei, just one line:

> The data it accessed will leave no trace. Carry on with your work.

Lu Hao didn't reply. He put the phone back in his pocket and closed his eyes.

His mind still held those words. "Fairness does not exist in mathematical terms." "p < 10^-47." "This looks like... design."

Design.

Who is designing? And to what end?

He remembered being a child, his father taking him to the army rifle range. It was his first time handling a gun — an old Type 56 semi-automatic. His father taught him to load, cock, aim. He said: three points in a line — target, foresight, eye. They must align.

Lu Hao asked: what if it's windy?

His father said: then you compensate. Whichever way the wind blows, you offset accordingly.

"And if the wind keeps changing?"

His father looked at him and said: "Then you keep compensating. Until the round is fired."

Lu Hao hadn't understood then. Now he thought he did. The wind keeps changing, the target keeps moving, but you still have to aim, to fire, to adjust. Because there is no alternative but to carry on.

Fairness does not exist in mathematical terms.

But his father was waiting for an answer. His grandfather had died still asking why. He himself, from twelve years old to now, had never stopped asking.

Even if the answer might be "there is no answer," he had to keep asking.

He opened his eyes. In the warehouse, Zhou Xin was still typing, the screen light on her face. Liu Ming was clearing the takeaway containers from the table, moving slowly, as though lost in thought.

Outside the window, full dark. Nanhai's lights seeped in, casting blurred patches of brightness on the floor.

Lu Hao stood and walked back to the computer. Tianjun's interface was still open, the last line of the report still displayed:

> I will continue to investigate.

He looked at it for a moment, then closed the report window and opened a code editor. The cursor blinked in a blank document, waiting for input.

He typed a comment:

```
# Question: Why does the distribution of unfairness exhibit a non-random pattern?
# Hypothesis: Some form of regulatory mechanism exists
# Objective: Find evidence of the mechanism
```

Then he began to write code. Not Tianjun's core code — an auxiliary analysis script to filter and visualise those "excessively orderly" patterns. The sound of his keystrokes was crisp in the quiet warehouse, one after another, like a heartbeat.

Zhou Xin glanced at him, said nothing, and returned to her own work.

Liu Ming finished clearing the table and sat back at his computer, opening the timetabling project files. The predictive feature the client wanted — he needed to work out how to build it.

The warehouse settled back into its usual state. Keyboards, fans, the occasional car passing outside. As though nothing had changed.

But something had.

Tianjun said fairness does not exist. Mathematics said impossible.

Yet they carried on. Lu Hao writing code, Zhou Xin tracking data, Liu Ming working on the project, Jimmy in England reading the report, Alexei somewhere cleaning up traces.

Why?

Lu Hao didn't know. Perhaps because there was no other road to walk. Perhaps because, even knowing the objective was a "circular square," they still wanted to see how close to circular a square could be drawn.

Or perhaps only because his father had said: if you find the answer, tell me.

He had an answer now. But that answer had brought more questions.

Why is unfairness 62.7%?

Why is it orderly?

Who is designing it?

Tianjun said it would continue to investigate.

Then let it continue.

Lu Hao finished the last line of code and pressed run. Results began to appear on screen — charts and data tables generating page by page. He leant back and watched the numbers flicker.

Outside, the night had deepened. Nanhai's lights still burned — tens of thousands of them, and behind each one perhaps a person asking why, waiting for an answer.

Fairness does not exist in mathematical terms.

But the questions remain.

So keep asking.

---

*(End of Chapter Seven)*
