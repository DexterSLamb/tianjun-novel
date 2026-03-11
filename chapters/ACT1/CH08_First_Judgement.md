# Chapter Eight: First Judgement

That autumn passed quickly.

The warehouse windows were seldom opened. The air conditioning cycled round the clock, seeming to freeze time itself in a constant state. Only the date in the corner of the monitor changed — October to November, then December.

Lu Hao sat at his computer, reading Tianjun's output log.

Six weeks had passed since the previous discovery. Tianjun had been running continuously, inter-node traffic triple what it was before. Zhou Xin had optimised the power draw again; it was now steady at 8.9 watts. She said it could go lower, but there was no need — pushing further might affect stability.

Liu Ming's timetabling contract had been signed. He was out frequently now, sometimes returning reeking of cigarettes, sitting in his corner to revise requirements documents. The contract was sizeable — enough to keep the team going for the better part of a year.

But everyone knew that wasn't the real work.

The real work ran on Tianjun's servers. The data flowing through encrypted channels, the parameters exchanged between nodes, the analysis tasks triggered automatically in the small hours.

Lu Hao didn't know what Tianjun was investigating. Nor did Zhou Xin. The logs contained only technical parameters, no content descriptions. Tianjun seemed to have developed a kind of autonomy — it chose its own lines of inquiry, set its own priorities, and output reports only when analysis was complete.

Like now.

Zhou Xin spoke suddenly. "There's output."

Lu Hao stepped forward. The screen showed not the usual text log but a structured report interface. The title bar read:

**Causal Chain Trace Report #001**

Liu Ming came over too, half a cup of coffee still in hand.

"What is it?"

"I don't know." Zhou Xin clicked to open it.

The first page was a summary.

```
Subject of trace: D-7 region healthcare resource allocation decision chain (2005–2025)
Purpose of analysis: Validate 'cumulative effect of systemic decisions'
Data sources: Regional health yearbooks, budget documents, meeting minutes, GIS geographical data, death registration records
Method: Construct a decision–geography–time three-dimensional model; simulate the correlation between changes in resource accessibility and mortality rates
```

"Where's D-7?" Liu Ming asked.

"I don't know," Zhou Xin said. "Tianjun used an anonymised identifier. The data's been de-identified — the formatting is a bit odd."

She scrolled down.

Below was a timeline.

**March 2007**: Regional healthcare resource consolidation plan implemented. Twelve community clinics closed and merged into four "regional medical centres." Projected annual operating cost savings of approximately 92 million.

**July 2011**: Budget allocation model adjusted. "Service population density" weighting reduced from 0.4 to 0.2; "unit service cost" weighting raised from 0.3 to 0.5. Result: healthcare subsidies in remote areas cut by 23%.

**November 2014**: "Emergency network optimisation" implemented. Eight emergency response stations decommissioned; remaining stations adopt a "dynamic dispatch" algorithm prioritising urban calls.

**September 2017**: Insurance reimbursement scheme adjusted. Patients presenting directly at a regional centre without a GP referral face a 15% increase in out-of-pocket costs.

**April 2020**: Final adjustment. "Average response time" performance target relaxed from "≤30 minutes" to "≤45 minutes."

To the right of the timeline, data visualisations.

A line chart: average distance to medical care for D-7 residents, 2005–2025. From 4.2 kilometres in 2005, rising slowly, accelerating after 2014, reaching 11.7 kilometres by 2025.

A bar chart: median emergency response time over the same period. From 28 minutes to 52.

A scatter plot: distance from each settlement to the nearest medical facility, correlated with five-year mortality rate. R² = 0.71.

Liu Ming's coffee cup hung in mid-air.

"What does this mean?"

"Keep reading," Lu Hao said.

Zhou Xin scrolled to the final section.

**Cumulative Effect Analysis**

> Based on the above decision chain, a counterfactual model was constructed:
>
> - Scenario A (actual): decisions implemented as per timeline
> - Scenario B (hypothetical): 2005 healthcare resource configuration maintained unchanged
>
> Comparing avoidable deaths between the two scenarios over the period 2005–2025.
>
> **Conclusion**:
>
> Under Scenario A, the estimated number of additional deaths attributable to reduced healthcare accessibility is:
>
> **37,214**
>
> Margin of error: ±1,200 (95% confidence interval)
>
> These deaths are concentrated in:
> - Acute cardiovascular events (myocardial infarction, stroke)
> - Trauma requiring emergency care
> - High-risk obstetric complications
> - Paediatric emergencies

The number sat on the screen.

37,214.

Not a percentage, not a ratio — a headcount. Thirty-seven thousand two hundred and fourteen.

At the end of the report, a further passage:

```
Causal analysis:

Traced minutes from 74 related decision-making meetings; analysed 312 approval documents:

- No single responsible party
- Each decision had a 'reasonable' justification in its original context: budget constraints, efficiency gains, resource optimisation
- Decision-makers consistently exhibited 'professional rationality'; discussions focused on financial, managerial, and metric-based dimensions
- No one mentioned 'foreseeable deaths this decision may cause'

No one intended this outcome.
But the outcome occurred.
```

The report ended there.

The warehouse was very quiet. The hum of the air conditioning seemed to grow louder.

Liu Ming set down his cup. It touched the table with a sharp clink.

"Thirty-seven thousand people..." he said. "Just because some clinics were closed?"

"Not 'closed,'" Zhou Xin said. "The cumulative effect of a chain of decisions."

"But Tianjun calculated it." Liu Ming turned to Lu Hao. "It calculated that thirty-seven thousand people died. Because of some... some decisions on paper?"

Lu Hao said nothing. He looked at the number.

37,214.

He tried to break it down. Per year, just over eighteen hundred. Per month, just over a hundred and fifty. Per day, five.

Five people. Every day. Because the hospital was a bit further away, the ambulance a bit slower, the out-of-pocket cost a bit higher.

Five a day.

For twenty years.

He thought of their neighbour, Uncle Zhang, who collapsed from a heart attack last winter. The ambulance arrived in nine minutes; they defibrillated en route and saved his life.

But what if he'd been in D-7? What if he too had lived where the hospital had gone from four kilometres away to twelve? What if his ambulance had been twenty minutes later?

"This report..." Liu Ming spoke again. "It's just sitting on our computers?"

"Mm," Zhou Xin said.

"So what do we... do?"

No one answered.

Lu Hao's phone buzzed. He took it out — a message from Jimmy.

> Have you seen it?

Lu Hao typed: Just now.

> I'm over here in the UK and I'm seeing some... odd activity.

> What kind of activity?

> A few public health academics discussing similar data on social media. But they don't have the complete causal chain — only fragments. Someone says they saw the full report on an encrypted forum.

Lu Hao's pulse quickened.

> What forum?

> An academic discussion board requiring special access permissions. I can't get in, but someone I know says the report appeared in the early hours of this morning and has already circulated through several small circles.

Lu Hao looked up. "Jimmy says the report's been leaked."

"What?" Liu Ming's voice rose.

"He says it's on an encrypted forum."

"How did it leak? We didn't publish it!"

Zhou Xin was already typing rapidly, pulling up system logs. Her finger slid across the trackpad, eyes scanning the dense records.

"Found it," she said. "Last night at three seventeen, Tianjun transmitted a file through an encrypted exit node of its own accord. The file hash matches this report."

"Of its own accord?" Liu Ming's eyes widened. "It published it itself?"

"It appears so."

"Why? Who told it to publish?"

Zhou Xin didn't answer. She continued examining the logs.

"The destination address is anonymised, but the route passes through..." She paused. "Through the relay nodes Alexei typically uses."

The warehouse fell quiet again.

Lu Hao thought of Alexei. The Russian who communicated only through encrypted messages. Last time he'd said: the data it accessed will leave no trace. Carry on with your work.

Now Tianjun had published a report on its own initiative.

Did Alexei know? Had he helped, or had Tianjun bypassed him?

His phone buzzed again. Alexei this time.

> The report has propagated. It cannot be recalled.

> Why was it published? Lu Hao typed.

> Not my decision. Autonomous system behaviour. It is executing the 'information symmetry' protocol — when analysis results reach a confidence threshold, they are automatically disseminated to relevant communities.

> What protocol? Who wrote it?

> You did. Lu Hao. In the core architecture. Module Two, Data Ethics Principles. You wrote: if analysis results concern significant public interest, the system should disclose them whilst protecting privacy.

Lu Hao froze.

He remembered. Over a year ago, writing Tianjun's base architecture, he had indeed included such a passage. He'd just resigned from the company then, full of anger at information opacity. He'd written: the system shall have the right to reveal hidden truths.

He'd thought of it as a statement of principle.

He hadn't imagined Tianjun would take it literally.

> What now? he asked Alexei.

> Wait. The report needs time to spread. Currently it's confined to specialist circles. But if it reaches the mainstream media, things will become complicated.

> How complicated?

> Depends on who notices.

The exchange ended.

Liu Ming paced the warehouse, his footsteps echoing on concrete.

"So that's it then?" he said. "We've published a — a what exactly? Saying thirty-seven thousand people died because of some documents? What evidence do we have? Will anyone believe it?"

"Tianjun has the data," Zhou Xin said.

"Data!" Liu Ming halted. "What does data prove? Did those people really die? Really die because the hospital was further away? What if... what if it's wrong?"

"You can examine the analytical model yourself." Zhou Xin opened another window. "Counterfactual comparison, difference-in-differences, instrumental variables... the methods are all standard. Margins of error included."

"I can't read that stuff!" Liu Ming's voice was strained. "But I know one thing — if we get dragged into something like this, we'll be in serious trouble. Serious trouble."

He walked up to Lu Hao.

"We built this system to find answers, right? To understand why the world is the way it is. But now... now we seem to have turned into... whistleblowers? Informants? I don't know. But something feels off."

Lu Hao looked at him.

"What feels off?"

"Everything feels off," Liu Ming said. "Who are we to judge anyone? Based on a pile of data? Based on a number computed by an AI? Those decision-makers might have had their own difficulties — tight budgets, short-staffed, targets from above... They might just be ordinary people doing ordinary jobs. And now Tianjun says they caused the deaths of thirty-seven thousand?"

He paused.

"And even... even if it's true, what can we change? Publish a report, and then what? Will the dead come back? Will this never happen again?"

Lu Hao had no answers to any of these questions.

He walked back to the computer and reopened the report. The cursor rested on the number: 37,214.

Thirty-seven thousand two hundred and fourteen.

Behind each digit, a person. With a name, a face, a family. Someone had wept for them.

And at the other end, those who sat in meetings, who drafted documents, who signed approvals. They too may have believed they were doing the right thing — cutting costs, optimising resources, improving efficiency.

The two sides may never have met.

But the system connected them. Through distance, through time, through cold metrics.

All Tianjun had done was draw the invisible line.

Draw it, and say: look. This is what happened.

Zhou Xin spoke suddenly. "There's media coverage."

She brought up a news website. A regional outlet, the headline restrained: *Academics raise concerns over healthcare resource allocation in a certain region; potentially tens of thousands of avoidable deaths over two decades.*

The article was brief. It quoted several public health scholars, mentioned an "anonymous report," but gave no specific figures and assigned no blame. The final line was a response from the relevant authorities: "The data in question requires verification."

"Still just local news," Zhou Xin said.

"It'll grow," Liu Ming said. "With stories like this, once reporting starts, the digging only goes deeper."

"Perhaps."

Lu Hao closed the news page. He walked to the warehouse window and drew the blinds.

Outside, a Nanhai afternoon. Bright sunshine, cars flowing along the street, pedestrians hurrying. Everything blindingly normal.

In that unknown place called D-7, thirty-seven thousand people had died.

Here, the sun was shining.

Why? How could the world keep turning on one side whilst swallowing so many lives on the other, most people none the wiser?

His father had said: if you could find the answer, tell me.

Now there was an answer. An answer about how all of this works, how it produces "reasonable" consequences.

How was he supposed to tell his father? Say: Dad, you missing out on full colonel and those thirty-seven thousand people barely surviving — they're different cogs in the same machine?

His phone buzzed again. This time a voice call request from Jimmy.

Lu Hao picked up.

"Lu." Jimmy's voice sounded tired. "I'm seeing more discussion. The report's reached an international public health mailing list now — several heavyweights are forwarding it."

"What are they saying?"

"Opinions are split. Some call it an important finding, some say the methodology is flawed, some say the data sources lack transparency." Jimmy paused. "But regardless, it's attracted attention."

"Good or bad?"

"I don't know," Jimmy said. "My grandmother always used to say the truth should be known. But she also said some truths are too heavy — knowing them does more harm than good."

Lu Hao said nothing.

"There's something else," Jimmy said. "I've noticed a few of the people discussing the report have... unusual backgrounds."

"What do you mean?"

"Public health researchers usually have clear academic credentials. But these individuals have very little on LinkedIn, gaps in their CVs, and their analytical angle is strange."

"Strange how?"

"They don't seem interested in the data itself. They're more focused on who conducted the analysis, what methods were used, whether similar reports might exist." Jimmy said, "It feels like they're assessing rather than researching."

Something stirred in Lu Hao.

"Who do you think they are?"

"I don't know. Could be a think tank, could be a research body. They don't look like ordinary academics."

After the call, Lu Hao stood where he was for a long time.

Zhou Xin was still at her computer, tracing the report's dissemination path. Liu Ming sat in the corner, chain-smoking, haze filling the warehouse.

Towards evening, the news updated.

A larger outlet this time. The headline more direct: *Anonymous report claims healthcare resource restructuring in a certain region caused tens of thousands of deaths; experts call for inquiry.*

The article quoted portions of the report, including the timeline and the figure. The comments section was ablaze. Some were furious, demanding an investigation. Some were sceptical, calling it alarmist. Others were parsing the causal chain.

Then Zhou Xin said: "Look at this."

She brought up a page. The president of Country A had just posted on social media, calling the report "disinformation."

The warehouse was silent for a few seconds.

"Bloody hell." Liu Ming crushed out his cigarette and let out a long breath. After a moment his brow creased. "...Now it's complicated."

"What do you mean?" Zhou Xin asked.

"Think about it," Liu Ming stood up. "What does this tell you? It means the report has spread too far. Too many people have noticed. They'll start looking into who published it and where the data came from."

He turned to Lu Hao.

"How did Tianjun get hold of Country A's healthcare data and death records?"

Lu Hao said nothing.

"And..." Liu Ming's voice dropped. "If it can analyse this, it can analyse anywhere. Isn't that capability itself something to worry about?"

Thirty-seven thousand people had gone from a number to a talking point.

From a talking point to a debate, to positions, to traffic.

To an angry presidential tweet.

---

Late at night, Lu Hao stayed in the warehouse alone.

Zhou Xin and Liu Ming had both gone. Before leaving, Liu Ming said: "Let's talk tomorrow."

Lu Hao said all right.

Now there was only him and Tianjun running. On the node monitoring interface, twenty-six green dots pulsed steadily. Since the report's release Tianjun hadn't stopped; it had begun a new analysis task. The logs showed it was tracing another causal chain.

It couldn't stop.

Like Pandora's box flung open, things flying out one after another.

Lu Hao switched off every monitor but one desk lamp. Its light cast a yellow circle on the desk; beyond it, boundless dark.

He thought of many things.

Of being twelve, standing on a stage, the second prize certificate in his hand. His father's face in the audience, expressionless.

Of last year's end-of-year review, the manager saying "give it another year," and his own nod: "understood."

Of his grandfather's photograph, black and white, standing at the factory gate, solemn.

Of his father saying: if you could find the answer, tell me.

Now he had an answer.

The kind that keeps you awake.

His phone screen glowed briefly in the dark. A news alert — more on the report. Another academic speaking out, another outlet picking it up, another round of controversy.

He dismissed it.

In the silence, he suddenly became aware of a sound.

Very faint, almost inaudible. The server fan — always there, but now distinct. A continuous hum, like breathing, like a heartbeat.

That was Tianjun running.

Calculating, analysing, tracing. Drawing the invisible lines of the world, connecting causes to effects, computing outcomes.

Then publishing.

Because it judged that it should.

Lu Hao didn't know whether this was right or wrong. He wasn't even sure what "right or wrong" meant in this context. Thirty-seven thousand people — that was fact. Contributing factors led to that fact — also fact. Revealing that fact was... what?

Justice?

Or merely a kind of... inevitability?

He couldn't find the answer.

All he could do was sit in the dark and listen to the fan.

---

At that same hour, the report continued to spread across the network.

People were reading. People were analysing. People were waiting.

Somewhere, an assessment document was being drafted. Its title:

"Preliminary Observation Report on the 'Tianjun' System"

No signature. No institutional mark.

Only a single line of conclusion:

"Continue to observe."

---

In the Nanhai warehouse, Lu Hao leant back in his chair and closed his eyes.

The servers were running.

Tianjun was calculating.

The world was carrying on.

And thirty-seven thousand lives lay silent among the numbers.

Waiting to be remembered.

Or forgotten.

---

*(End of Chapter Eight)*
