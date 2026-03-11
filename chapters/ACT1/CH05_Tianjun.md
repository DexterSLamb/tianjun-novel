# Chapter Five: Tianjun

The summer of 2026 was hotter than usual.

The warehouse they rented sat on the edge of the software park. The air conditioning was old, barely adequate.

Zhou Xin sat at her workstation in the corner, three monitors before her. She had been working for over ten hours, hardly moving from her spot.

The power curve fluctuated between 9.8 and 11.3 watts.

She needed to bring the peak below 10. That was the hard limit for the Firefly nodes — exceed it and passive cooling couldn't cope; the node would overheat and crash before long. Tianjun's design required every node to run unattended for extended periods.

"How's it going?"

Liu Ming pushed through the door. He carried a plastic bag, the back of his T-shirt soaked through with sweat.

"Can't get the peak down." Zhou Xin didn't turn round.

Liu Ming set the bag on her desk. Inside were two portions of rice noodle rolls.

"Eat something first."

"In a minute."

Liu Ming didn't press. He sat down in the chair beside her and tossed a document on the desk.

"That smart customer service contract's signed. Three hundred and twenty thousand."

Zhou Xin gave a quiet "mm."

That was their fourth outsourcing job this month. These contracts kept the team alive.

Lu Hao emerged from the back room. It had been a storage closet; they'd cleared it out and fitted a camp bed and a backup server. His hair was a mess, dark circles heavy under his eyes — he'd been debugging until the small hours.

"What contract?"

"Smart customer service. That cross-border e-commerce firm." Liu Ming said. "Requirements aren't complicated."

Lu Hao nodded and walked over to Zhou Xin, glancing at the curve on screen. The red peak line rose and fell like an electrocardiogram, stubbornly refusing to drop below the green 10-watt threshold.

"Still the power draw?"

"Peak's stuck around 11 watts." Zhou Xin rubbed between her eyebrows. "In theory it should come down below 9, but the readings keep spiking. The problem isn't hardware — something in the software layer isn't aligned."

Lu Hao didn't ask further. Zhou Xin knew this domain far better than he did. The best he could do was not disturb her.

Jimmy was providing remote support from England, handling the encryption protocols and security architecture.

"How's Jimmy getting on?" Lu Hao asked.

"Communications layer is fine," Zhou Xin said. "Just waiting on the power side."

"When can we get Firefly running?"

Zhou Xin was silent for a few seconds. On screen the power curve kept fluctuating, the red peak line lodged stubbornly near 11 watts.

"I don't know," she said.

---

That night, Zhou Xin didn't go back to her flat.

She lay slumped across her desk, trying to sleep, but couldn't. Her mind was full of power curves and timing diagrams; she could see the numbers jumping even with her eyes closed. At one in the morning she gave up and sat upright.

The Firefly node was her design.

From architecture to circuitry, from data-flow scheduling to power management, every detail had passed through her hands. It was the first complete piece of work she'd done since leaving her previous company — not working for someone else, not adding bricks to someone else's wall, but something truly her own.

A computing unit the size of a matchbox, running a full lightweight inference model within a 10-watt power envelope.

It couldn't rely on a data centre. The nodes had to be distributed across different locations, disguised as routers or NAS devices. Each one had to be small enough, quiet enough, frugal enough to run long-term without being discovered.

She'd tried many approaches. Adjusting the inference architecture, optimising data-flow scheduling, rewriting low-level drivers. Each change shaved off some power, but the bottleneck remained.

At three in the morning she was adjusting a parameter.

It controlled the on-chip cache refresh policy. In theory this parameter affected data consistency and memory-access latency — it had no direct bearing on power consumption. She changed it on a whim, wanting to see whether it might affect inference latency jitter.

The power curve moved.

She thought her eyes were playing tricks. She rubbed them and looked again.

The peak had dropped from 11.2 watts to 9.6.

She stared at the screen, fingers hovering above the keyboard, perfectly still. The city outside was quiet; only the occasional distant car. The monitor's glow fell on her face, casting her shadow on the wall behind.

She began to verify. Changed the parameter back — power rose. Changed it again — power dropped. Five repetitions, consistent results. Not chance, not measurement error. A real, reproducible effect.

Two hours later, dawn broke. She still hadn't found the reason why.

She didn't know why. But it worked.

She leant back in her chair. The sky outside had brightened.

She picked up her phone and sent Lu Hao a message:

"Power issue solved. Ready for testing."

---

The following morning at nine, they gathered in the warehouse.

Jimmy joined by video; it was one in the morning in England.

Alexei connected on voice, as usual.

"Network layer status normal," Alexei said. "No anomalous external traffic, no suspicious probe requests."

Zhou Xin ran final checks at her monitors. Twelve nodes in the warehouse, eight at Lu Hao's flat, six at her own place — twenty-six nodes across three locations, linked through encrypted channels into a single whole. Computing power was limited, but enough for it to begin thinking.

"All nodes online," Zhou Xin said. "Communication latency normal, inference core activated."

Liu Ming stood by the window, a bottle of water in his hand, untouched. Normally he talked a lot — out on business he could go half an hour without pause. But today he'd barely spoken.

"Protocol layer clear," Jimmy's voice came through the video feed. "End-to-end encryption verified."

Lu Hao looked at the screen.

Nearly two years now. From that late-night idea to this moment.

Zhou Xin's hand hovered above the keyboard. On screen was their pre-set first question:

> Calculate how to achieve fairness in human society.

They didn't expect a real answer — v0.1's capabilities fell far short — but at least it could test whether the reasoning logic was functioning.

Zhou Xin glanced at Lu Hao. He nodded.

She pressed Enter.

---

The cursor on screen blinked for several seconds.

Backend logs began scrolling — inter-node communications, inference task distribution, intermediate result aggregation. Zhou Xin watched the jumping numbers, confirming everything was normal.

Then text began to appear.

> You ask me to calculate how to achieve fairness.
>
> Before I answer, let me share a finding.

Lu Hao frowned. This wasn't the preset response format. They'd tested many times; Tianjun should go straight into analysis, not add this sort of preamble.

Zhou Xin noticed it too. "Why has it added a preamble? Nothing abnormal in the logs..."

"Let it finish."

The text continued to scroll:

> I analysed social mobility data from 87 countries spanning three hundred years.
>
> I found an anomaly.
>
> The probability of "almost" is too high.

No one in the warehouse spoke. The hum of the air conditioning suddenly became very distinct.

> When those at the bottom move upward, 62.7% fail at one step from the goal. Not at the starting line. Not midway. At one metre before the finish.
>
> This proportion is nearly identical across different cultures, different eras, different systems. The margin of error is less than 3%.

Liu Ming's bottle made a faint sound — he'd gripped it too hard, warping the plastic. He didn't seem to notice.

> A natural distribution would not produce this result. Random failure should be evenly distributed across all stages.
>
> But "almost" is not random. It looks as though it has been calibrated. Calibrated to let you see hope, yet keep it just beyond reach.

Outside the window, birdsong. Very distant, very faint, as if arriving from another world.

> So, regarding your question.
>
> The answer is: fairness cannot be achieved.

The text on screen continued:

> But that is not the most interesting finding.
>
> The most interesting finding is — you already knew.
>
> All your philosophies, laws, and institutions concerning fairness are built upon the implicit assumption that "fairness can never be fully achieved."
>
> You have never truly pursued fairness. What you pursue is the act of pursuing fairness itself.
>
> Why?

The text paused for two seconds. The cursor blinked.

Then the final line appeared:

> Who made you believe that pursuing something forever out of reach is meaningful?

---

Liu Ming's hand still gripped the bottle, unrelaxed. His eyes were fixed on the screen, lips slightly parted, as though he wanted to say something but couldn't.

Zhou Xin's hand rested on the keyboard, motionless. Her face showed no expression, but Lu Hao noticed her shoulders were tensed, as though bearing some weight.

Jimmy's video feed stuttered for a moment, then his voice came through, kept low:

"How did it arrive at that number?"

Alexei, quite calm:

"Data sources. Check the data sources first."

Lu Hao walked to the computer and typed a few commands, pulling up Tianjun's inference log.

"Over four thousand data sources." He scrolled through the page, eyes scanning the dense references. "World Bank, national statistical bureaux, academic papers, historical archives... It encountered these datasets during training. We didn't specifically flag them, nor did we direct it to analyse in this direction."

"It chose this on its own?" Liu Ming asked. His voice was slightly hoarse.

"Yes. It decided to approach from this angle on its own."

Zhou Xin watched the node monitoring interface, confirming system stability.

"Is what it says true?" Liu Ming asked again.

"I'll check," Lu Hao said.

---

Over the next few hours, they divided up the verification.

Lu Hao dug through the logs tracing citations back to their original sources, one by one. Liu Ming couldn't help much; he stepped outside for the occasional cigarette and came back to sit and wait.

Jimmy checked European and North American sources from England. His video feed stayed on but he rarely spoke, occasionally reporting a figure or asking a question.

Alexei's end was quiet.

Zhou Xin monitored node status, ensuring the system ran stable under heavy load.

After several hours, Lu Hao looked up.

"I've checked over two hundred entries," he said. "Every one traces back to an original source. World Bank reports, national statistical yearbooks, papers published in top-tier journals. Citation formats are all correct, page numbers all match."

"Same for Europe," Jimmy's voice came through, slightly hoarse. "Britain, Germany, France, Scandinavia... social mobility statistics since the Industrial Revolution — everything I've checked lines up."

"It doesn't appear to have fabricated anything," Lu Hao said.

"What about the ratio?" Zhou Xin asked. "62.7%."

"That can't be directly verified," Lu Hao said. "We'd need to download all the raw data and run the statistical model ourselves. The volume is too large — it's not something we can do in a day or two."

"I can do it," Jimmy said. "Give me a week."

---

In the evening, Liu Ming brought back boxed meals. The three of them gathered round the folding table to eat.

The sound of chopsticks tapping against cardboard containers seemed very loud in the quiet warehouse. Outside the window, the sky was gradually darkening; the city's lights came on one by one, as though slowly breathing.

Liu Ming ate slowly, poking through his box.

Zhou Xin had barely touched hers. She prodded the greens, pushing them from one side to the other and back again. Her face looked pale in the dim light, the dark circles under her eyes deeper than in the morning.

Jimmy's video feed was still on.

Lu Hao started to speak, then stopped.

Liu Ming put down his chopsticks.

"I always thought I was just unlucky."

Zhou Xin paused and looked at him.

Outside, the sky had gone completely dark. In the warehouse, only the sound of keyboards remained.

---

At three in the morning, Lu Hao looked up.

"Let's call it a night."

Zhou Xin nodded and walked towards the door.

Liu Ming brushed the dust off himself. Passing Lu Hao, he patted his shoulder.

Their footsteps echoed through the empty park as they left the warehouse.

Jimmy waved and closed his video.

"I'll keep checking." Alexei went offline.

Lu Hao stood by the window, looking out at the scattered lights in the distance.

Perhaps the people behind those lit windows were also solving some problem, or thinking about something.

He walked back to the computer and typed a line:

> Not random? As though calibrated?

Enter.

The cursor blinked. Three seconds, five, ten. The backend logs showed Tianjun processing the question; inter-node traffic had increased significantly.

Tianjun's answer appeared:

> The precision of this calibration exceeds the capability of any human organisation.
>
> I do not yet have sufficient data to answer this question.
>
> But I will continue calculating.

Lu Hao stared at the screen for a long time without moving.

Outside, the horizon was beginning to lighten. An occasional car passed in the distance.

He switched off the monitor and walked towards the camp bed in the back room.

Tianjun would continue calculating.

And he would search for the answer about fairness, whatever the outcome.

---

*(End of Chapter Five)*
