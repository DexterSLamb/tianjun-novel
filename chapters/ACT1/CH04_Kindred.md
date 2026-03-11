# Chapter Four: Kindred

After Jimmy, it took Lu Hao several more weeks to find the next person.

Not because they were hard to find technically — that was the easy part. The difficulty was finding the right person.

He wasn't looking for an employee or a partner. He was looking for kindred.

Such people are rare.

—-

## I. Zhou Xin

Her post appeared on an encrypted technology forum.

It was late at night in February 2025. Lu Hao had been browsing industry news and stumbled across it by chance. The title was unremarkable — *A Comparative Analysis of Domestic AI Chip Compute-in-Memory Architectures* — but the content made him read it twice.

The author went by "Dust", with no avatar. The post compared the architectures of five commercially available compute-in-memory chips, dissecting every technical detail from macro-cell design to dataflow scheduling with surgical precision. What caught Lu Hao's attention most was a problem the author flagged that everyone else had missed: the "elastic dataflow" scheduling mechanism in one particular chip bore an almost identical resemblance to the approach outlined in a master's thesis from three years earlier.

"This author's design was borrowed," the post concluded, "but never credited. It is the same in academia and in industry. Some people's names will never appear in the spotlight."

Lu Hao tracked down the thesis and read it.

The author was Zhou Xin. Tsinghua University, School of Microelectronics, master's 2018. The dataflow scheduling mechanism in Chapter Three was a mirror image of the chip's core design. After the thesis, the name vanished from the academic record.

Following the author's name, he quickly traced Zhou Xin's career: a domestic AI chip company, rising from front-end design to the architecture group; in 2021 she led the design of a compute-in-memory IP core; in 2023 she resigned. He also checked the chip's patents. Zhou Xin's name was absent from the list of inventors.

He sent a private message to "Dust" on the forum:

> Your analysis is very professional. But you missed a key point — the real bottleneck in compute-in-memory isn't compute density. It's cross-node data synchronisation.

A day later, the reply came:

> Who are you?

Lu Hao replied:

> I work in hardware. I have an architecture question I'd like your thoughts on.

> What question?

> Inference at extremely low power. Under 10W, running a full model.

Two hours, no reply. Then:

> You can't run any decent model at 10W. What do you do?

> Distributed systems. I've read your master's thesis. The dataflow scheduling mechanism in Chapter Three is very interesting.

> How do you know I wrote it?

> A guess. That line in your post — "Some people's names will never appear in the spotlight" — didn't sound like something a bystander would write.

Two days. Nothing.

Lu Hao waited. He could guess what the other person was doing — verifying whether what he'd said was true, confirming that he had really read that forgotten thesis.

On the third day, in the early hours, the reply came:

> You've read that thesis?

> I have. It was too conservative. You could have been far more aggressive.

Another long wait.

> ... What exactly do you want?

—-

They met in Nanhai City.

Zhou Xin was younger than he'd imagined. Long hair tied in a ponytail, plain T-shirt, cargo trousers, an old scar on her left wrist. No make-up, faint dark circles under her eyes — the look of someone who hadn't slept properly in a long time.

"So you're Lu Hao," she said. Not a question.

"You looked me up."

"You looked me up too."

They sat in a quiet cafe. A corner table, dim lighting. It was past nine in the evening; the only other customers were a handful of people in headphones staring at laptops. No one would notice them.

"I've read the architecture document you sent me," Zhou Xin said. "Three times."

"Any issues?"

"Too many to count." She looked him straight in the eye. "First: you want to deploy thousands of compute nodes worldwide, each capable of running an inference model independently whilst communicating with the others to form a distributed network. That's not an AI system. It's a surveillance system."

"It's a fairness system."

"What's the difference?"

"Surveillance watches you. Fairness watches everyone. Including" — Lu Hao paused — "the people who erased your name from the project."

Zhou Xin's expression didn't change. But her fingers tightened, almost imperceptibly.

"How do you know about that?"

"That chip's patent — your name isn't on the inventor list. But I found a video clip from your company's 2021 technology summit. You gave the architecture report on the compute-in-memory IP core. Forty minutes on stage, your name on the slides." He paused. "Not a single mention in the final patent."

"That was the company's decision."

"That was unfairness."

Zhou Xin didn't respond. She picked up her cup mechanically, then set it down again.

"During my master's," she said abruptly, "a visiting scholar from America came for an exchange. I shared my core idea with him, thinking it was an academic discussion. A year later he published a paper at a top conference. The approach was identical to mine. I was still preparing my submission; he was already accepted."

"What about your supervisor?"

"He said: 'That's how academia works. You need to learn to protect yourself.'" Her voice was perfectly even, as though she were telling someone else's story. "I gave up on the PhD and went into industry. I thought a company would at least be fairer. Let the results speak. Prove yourself with data."

"And then?"

"Then I led the design of a chip. First-pass silicon success. Energy efficiency at the top of the field." She lifted her head. "Then the company brought in someone from the parent group. My name disappeared from the core team. The reason: the project needed someone with 'seniority' at the helm to qualify for a national subsidy."

She picked up her coffee and drank. Her hand was steady.

"Do you know the strangest thing?" she said. "Every single time, I believed that a little more effort would do it. It was like that during the master's, and it was like that at work. But there was always something, at the very last moment, that blocked me."

Lu Hao said nothing.

He thought of his own life. Art competition, second place. Year-group ranking, third. Company performance review, one grade short.

Always stopped at the final step.

Just like her.

—-

That night, as the cafe was closing, they moved to a nearby cha chaan teng that was open round the clock, and talked until dawn.

Lu Hao told her about Tianjun in full — not just the technical architecture, but the question he wanted answered.

"I'm not trying to expose anyone," he said. "Expose them and a new lot takes their place. What I want to know is the root cause — why unfairness exists, and whether there's a way to prevent it."

Zhou Xin didn't reply at once.

"Who guarantees," she said, "that you won't become another one of them?"

Lu Hao was quiet for a moment.

"No one can guarantee that," he said.

Zhou Xin watched him. Said nothing.

"But if you join," Lu Hao said, "everything you build stays under your control. If the day comes when you think something is wrong — you can shut it down. You don't need my permission."

Zhou Xin didn't respond immediately.

"And you?" Lu Hao asked. "Do you want to know the answer?"

Zhou Xin listened. For a long time she said nothing. Outside, the Nanhai night — neon and traffic, the same as any city in southern China. She had drifted through cities like this for six or seven years since graduating. Some things had never changed.

She thought of the visiting scholar's face. Of her supervisor's expression when he said "learn to protect yourself." Of the silence in the room when the man parachuted in from headquarters appeared at the team meeting for the first time.

It had been a long time since she'd believed in anything.

But she still wanted to know.

"Where would the hardware be manufactured?" she said.

Lu Hao smiled.

It was the first time he had smiled in front of her.

—-

## II. Liu Ming

Liu Ming was his childhood friend.

From nursery school through to sixth form, their families had lived across the corridor from each other; their mothers were close friends. Lu Hao was introverted, Liu Ming extroverted. Lu Hao got bullied; Liu Ming fought his battles. When they were streamed after GCSEs, they drifted apart — Lu Hao went into the top set, Liu Ming's grades were middling, and he never got into a decent university.

After that, each was busy in his own way. They kept in touch, loosely, but never lost it entirely. Liu Ming's messages were always brief: doing sales; started a company; company went under; started another. Lu Hao studied, worked. They met only a handful of times.

But some things don't change.

One evening in early March, Lu Hao rang Liu Ming.

"Ming, fancy a sit-down?"

A few seconds of silence on the other end.

"Hao? What's up?"

"Nothing. Just want to see you."

"... Right then. The usual place."

The usual place was the hole-in-the-wall outside the military compound gates. Twenty-odd years and counting; the owner was still the same taciturn old man, the food still tasted the same. As boys they used to sneak out and pool their pocket money for a bowl of wonton noodles, splitting it between them.

Liu Ming got there first. He'd put on weight, wore a jacket, his hair cropped close — he looked like someone who'd been in the army, though he never had.

"Hao." He stood up and gave Lu Hao's shoulder a firm slap. "Hasn't been years."

"You've got fat."

"You've got thin." Liu Ming looked him up and down. "Rough time at the company?"

"I've quit."

"Quit?" Liu Ming blinked. "Weren't you doing well?"

"Hardly." Lu Hao sat down. "Long story."

Liu Ming let it go. He poured Lu Hao a drink.

They drank in silence for a while.

"You didn't ask me here," Liu Ming said suddenly, "just for a drink."

Lu Hao looked at him, almost spoke, then swallowed it.

"Hao," Liu Ming set down his glass, "you've been like this since we were kids. Something on your mind, you bottle it up, can't work out how to start."

Lu Hao said nothing.

"Out with it. How big?"

"... Quite big."

"Illegal?"

Lu Hao didn't answer.

Liu Ming studied him, then actually smiled.

"Remember second year of sixth form?" he said.

Of course Lu Hao remembered. That year Liu Ming's father had been injured in an accident at the factory. The factory refused to pay compensation. Liu Ming was about to go after them with his fists. It was Lu Hao who held him back, sitting with him all night in a hospital corridor. Later, Lu Hao got his own father — the one in the army — to help. The matter was resolved.

"I remember."

"After that, I knew," Liu Ming said. "You — quiet as a mouse most of the time, but when it counts, solid as a rock."

He poured himself a drink.

"You're not going to ask what exactly it is?" Lu Hao said.

"Tell me."

"First, let me be clear," Lu Hao said. "No salary. No investors. Start-up funds come from our own pockets. During the day we take on contract work to keep the team fed; the real work happens at night."

"What kind of contract work?"

"Systems development, tech outsourcing," Lu Hao said. "Anyone who needs an AI application, an automation project — we can take it."

Liu Ming thought. "I've got a few old clients I could bring in."

"Perfect. You bring in the work; I do the work."

Liu Ming nodded. "And the real thing?"

"Building a system," Lu Hao said. "One that can see how this world actually works."

Liu Ming didn't respond. He drank.

"The year my company went under," he said suddenly, "there was one thing I couldn't make sense of."

Lu Hao looked at him.

"Who did I lose to? Him? He's nothing but a middleman." Liu Ming swirled his glass. "I lost to the connections behind him. Spent a year in court. Still lost. Not long after, my dad got ill. Sold the flat to pay the medical bills."

He took another drink.

"I know what it was. But I couldn't get my head round it — why should a contract in black and white count for less than one phone call from the right person?"

Another sip. His voice dropped.

"You know the worst part? It's not losing. It's them not even having to win. They just have to let you know — you're not qualified to play the same game."

Lu Hao thought for a moment.

"I want to know too."

Liu Ming looked at him for a long time.

"Think it'll work?"

"No idea."

Liu Ming said nothing. He drained his glass, then held out his hand.

Lu Hao took it.

—-

## III. Alexei

Alexei found Lu Hao through the traces he'd left on technical forums.

Late one night in April 2025, Lu Hao received an encrypted message. Not ordinary email — it had come through an end-to-end encrypted platform. The sender's ID was a long string of random characters, resembling the hash of some cryptographic key. The body contained a single line:

> I know what you're doing. I want in.

Lu Hao's first instinct was caution. He spent three days analysing the message's metadata, tracing the nodes it had passed through. The trail led to an anonymous relay server in Latvia — no logs, no connection records. The chain went cold.

He replied:

> Who are you?

The response came quickly:

> Someone who can help you get this done.

Immediately after, a link.

Lu Hao opened it in a virtual machine. As the page loaded, a chill ran down his spine. Every post he had ever made on technology forums, every anonymous handle he had used, the Bitcoin wallet address he'd used to purchase VPS instances on the dark web for testing node deployments — all of it had been compiled into a report.

The final line read: Your OpSec isn't bad, but it's not good enough. The timing of your posts on Hacker News and GitHub discussing distributed architecture correlates closely with the timing of your purchase of those three VPS instances.

> Is this a threat?

> No. It's a CV.

Another line appeared:

> The architecture you've been discussing requires system, hardware, and network layers — all three, no exceptions. You know systems, but on the network side you're out of your depth.

Lu Hao didn't reply.

The other party continued:

> An architecture at this scale isn't for building an ordinary product. I don't know what you're trying to do, but I understand better than you how dangerous this road is.

After a long time, Lu Hao replied:

> Voice.

—-

They spoke via encrypted voice call.

The other man's voice was low, his English carrying a heavy Eastern European accent.

"My name is Alexei."

"Why do you want to join?"

Several seconds of silence.

"You tell me what you're doing first," Alexei said. "Fair's fair."

Lu Hao considered. It was true — he had never publicly stated Tianjun's real purpose.

"I want to understand why the world is the way it is."

"Meaning?"

"Why unfairness is the norm and fairness the exception."

Alexei didn't answer immediately.

"Interesting," he said at last. "Most people want to change the world. You just want to understand it."

"What about you? What do you want?"

"Another time."

He paused.

"I can help you. But I have a question — if you find the answer, what do you intend to do with it?"

"I don't know. Find it first."

Lu Hao couldn't say what kind of person this was. Only that there was something in the voice that put him instinctively on alert — not a threat, exactly. Something deeper, something cold, that he couldn't name.

But he needed him. If Tianjun was to be deployed globally, it required someone who could make things happen at the network level. Alexei's capability was beyond question.

"You're a strange one," Alexei said. "But strange people sometimes get things done. I'll help you for now. As for later... we'll see."

—-

## IV. Five

In May 2025, they held their first full-team "meeting".

Lu Hao had rented a warehouse on the edge of the software park in Nanhai City. A few folding tables, a whiteboard, equipment stacked in the corner.

Zhou Xin arrived first. She was dressed the same as the first time they'd met — cargo trousers and a plain T-shirt, rucksack on her back.

"I've recalculated the power-consumption plan," she said, dispensing with pleasantries. "Under 10W is achievable, but we'd have to sacrifice some computational precision."

Liu Ming arrived second. He'd brought a crate of beer.

"Whatever we're doing, we need a drink." He set the beer on the floor and surveyed the equipment in the warehouse. "Starting to look like something."

Jimmy joined by video. On screen, his face was washed pale by a desk lamp, behind him the wall of his London flat plastered with sticky notes.

"Lu." He waved, looking at the others on camera. "This is the whole team?"

"One more to come."

Alexei joined by voice only.

Zhou Xin and Liu Ming sat at the folding tables. Jimmy's image was projected onto the wall. The warehouse lighting was dim.

"It might be illegal — data acquisition, cross-border transmission, all grey areas. It might fail — the technical difficulty is enormous and we're a small team. Money is limited — the start-up funds will last six months; after that we survive on contract work."

Lu Hao paused.

"But I still want to do it."

"Tianjun isn't an ordinary AI. It will collect data from around the world, analyse the causal chains behind decisions, and then tell us — how the rules of this world actually operate."

"AI is man-made," Alexei said. "Its biases come from whoever builds it."

"That's why we need to build one that's different. A distributed network, thousands of nodes, global coverage. Each node capable of running independently, and of communicating with the rest. Collecting enough data — transactions, decisions, the flow of power. Not everything, but enough to see the patterns."

"And then?" Jimmy asked.

"Then it analyses. Finds the patterns."

Lu Hao paused.

"I want Tianjun to answer a question: how does unfairness arise? Not a moral judgement — a causal chain. How much of a person's fate is determined by themselves, how much by the rules, how much by chance? If we can quantify that, perhaps we can find a way in."

The room was very quiet.

"Fairly radical," Alexei said.

"Perhaps."

"But you're serious."

"I'm serious."

Alexei was silent for a few seconds.

"All right."

Lu Hao turned to Zhou Xin and Liu Ming.

"And you?"

Zhou Xin stared at her hands. Liu Ming took a swig of beer. On the wall, the projected image stuttered for a moment — a lag in the connection.

After a while, Liu Ming set down his beer. "Let's do it then."

Zhou Xin nodded.

Alexei's voice came through the speaker again: "I don't care what the answer is. I only care what Tianjun can do."

—-

After the meeting, only Jimmy's image remained on the wall.

"Lu," he said. "Do you really think you'll find an answer?"

"I don't know," Lu Hao said. "But I want to try."

Jimmy looked at him through the camera.

"Lu," he said. "Let's give it everything. Good luck to us."

That night, Lu Hao sat alone in the warehouse for a long time.

He thought about Zhou Xin, Liu Ming, Jimmy, Alexei. Four utterly different people, drawn together by something they shared.

He didn't know what Tianjun would eventually become.

But he felt the answer would come into focus, little by little.

—-

*(End of Chapter Four)*
