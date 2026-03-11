# Chapter Nineteen: Zhou Xin

Lu Hao's gaze swept across the servers. The labels on the older ones still used the coding format from three years ago. Zhou Xin had been fastidious when she'd helped install them, affixing each label with meticulous precision.

His eyes settled on the screen. On it was a scanned work badge for "Lin Meiling."
The photograph was Zhou Xin, but the name was not.
Malaysian national, network equipment maintenance engineer.

When this document had come back three weeks ago, Lu Hao had stared at it for a long time.
Now it was Zhou Xin's sole identity in Southeast Asia — she was out there alone, and had been for four months.

---

Zhou Xin's message was still on screen.

"The Firefly node's got a problem."

He'd replied: "I'll get Alexei to support you remotely."

Three days later, here and now, he sat staring at the same screen.

---

"Position confirmed." Alexei's voice came through. "She's in Zone B3, seventh rack row. Establishing comms."

Lu Hao put on his headphones. The warehouse screen switched to Zhou Xin's helmet camera feed — concrete walls, rows of server racks, green indicator lights flickering like star fields.

"Zhou Xin?" Lu Hao said.

"Here." Her voice came through. "Found the problem. The parasitic board slot on the node — a BGA solder joint has gone dry. Probably from vibration during transport of the host device."

The image shook, then focused on the interior of an open chassis. On the motherboard's spare board slot, a metal module was soldered in place. A Firefly node — sixty-seven millimetres long, eighteen wide, four point two thick. From outside, its host was just an ordinary edge computing device in the rack.

"Can you fix it?" Lu Hao asked.

"Yes. Needs resoldering. Give me twenty minutes."

Alexei's voice cut in: "Just a reminder — her work order expires in twenty-eight minutes. Repair plus recertification, it'll be tight."
Zhou Xin's voice didn't waver: "Understood. There's time."

Her hands appeared on screen. Static-free gloves, steadily holding a micro soldering pen. The microscope lens focused on the joint, and the screen magnified the tiny gap — roughly thirty per cent of the area had a dry connection, enough under a load of 130 trillion operations per second to produce intermittent faults.

"How's the traffic?" Zhou Xin asked.

Lu Hao switched to the monitoring interface: "Still fluctuating. Handshake failure rate across three zones at seventeen per cent."

"Understood."

What followed was a long silence. Only the faint hum of the soldering pen and the near-invisible wisps of pale smoke from heated components. Zhou Xin glanced up at the smoke detector overhead; her hands didn't stop. Lu Hao watched those focused hands on screen — steady, precise, the way she'd always been. He remembered seven years ago, when she'd first joined and was soldering the first test board in the warehouse. On her left wrist was an old scar, a burn from a soldering iron during her undergraduate years. She'd called it her "initiation mark."

Midway through the soldering, she said suddenly: "Lu Hao, do you think... if everything is designed, are our choices still our own?"

Lu Hao didn't answer.

"What I mean is," she continued soldering, hands never pausing, "if even feelings are parameters... are they real?"

"Zhou Xin?"

"It's nothing," she said. "The work comes first."

Silence. Only the hum of the soldering pen.

The sound from the ventilation grille changed — the airflow weakened slightly. Small hours; the air conditioning had probably switched modes.

The final solder point. Oxidation traces on the pad. She raised the temperature, held a few seconds longer. The smoke was thicker than before, dispersing slowly in the reduced airflow.

She glanced at the detector. Green light.

Carried on.

"Done," she said.

On the monitoring interface, the handshake failure rate began dropping: 15%... 12%... 9%...

"Starting network recertification," she said. "Need to complete handshakes with three zones."

"Copy."

A progress bar appeared in the corner of the feed: 1%... 3%... 7%...

Lu Hao leaned back. Outside the window, Nanhai was raining, the small-hours streets deserted. Liu Ming sat at another workstation, staring at his own screen, fingers tapping unconsciously on the desk.

"Alexei, door-access status?" Lu Hao asked.

"Normal," Alexei's voice came back. "Work order valid until oh-five-hundred. That's... under two minutes."

Progress bar: 23%...

Then the alarm went off.

Fire alarm — shrill, continuous, a buzzing that surged from deep in the corridor. The image shook; the helmet camera swung towards the far end of the passage. Red warning lights began to rotate.

"What's happening?" Lu Hao sat up straight.

Zhou Xin didn't answer. On screen, she looked up at the ceiling — the warning light had turned red, the sign beside it illuminating: IGX-100 DISCHARGE — EVACUATE IMMEDIATELY

A new warning icon appeared in the corner of the feed: IGX-100 DISCHARGING — 03:59... 03:58...

"Nitrogen suppression," she said.

She knew the rules of this data centre. Some clients weren't paying for server space. They were paying for the promise of "absolute erasure."

Almost simultaneously, another sound joined in — a clipped, mechanical English recording: "Unauthorised personnel detected. Security protocol initiated. All isolation doors will close in sixty seconds. Repeat, all isolation doors will close in sixty seconds."

Progress bar: 41%...

"What does that mean?" Liu Ming asked from behind.

"It means," Zhou Xin said, "I'm locked in."

Lu Hao's fingers clenched.

"Zhou Xin, evacuate."

She didn't answer.

"The doors close in fifty-three seconds!"

"I know."

"Zhou Xin —"

"I touched the hardware. If the certification doesn't complete, the node will self-destruct. The traffic gap will expose everyone."

Progress bar: 58%...

"Forty-five seconds to closure."

Lu Hao stood up. Liu Ming was on his feet too, behind him, eyes fixed on the screen.

"Alexei!" Lu Hao said. "Can you breach the door access?"

"I'm trying," Alexei said. "The data centre's security system is air-gapped. I need to penetrate the security network first —"

"How long?"

"I don't know. Maybe... a few minutes."

Progress bar: 67%...

"Thirty seconds to closure."

On screen, Zhou Xin's breathing grew heavier. She glanced towards the corridor — the first isolation door was already descending, a heavy metal slab sliding down from the ceiling with a dull scraping sound. She turned back to the screen, fingers continuing to enter verification commands on the keyboard.

"Zhou Xin, forget the verification! Evacuate now!"

Progress bar: 82%...

"Fifteen seconds to closure."

The second door began descending. Closer.

"Zhou Xin —"

"Zhou Xin, abort the verification! Please..."

Her fingers didn't stop. Progress bar: 94%...

IGX-100: 3:12...

"Alexei?" Lu Hao asked.

"Still working on it. The B3 zone controller is the most complex, I need to —"

"Hurry."

"I know."

Progress bar: 99%...

IGX-100: 2:47...

"Verification... complete," Zhou Xin said.

On the monitoring interface, the node status switched from yellow to green. Handshake success across all three zones jumped to 100%. The traffic curve levelled out, like a heartbeat finally finding its rhythm.

Her hands were still on the keyboard, entering a sequence of commands.

"The Firefly node's emergency hibernation protocol. I designed it." Zhou Xin's voice was very soft. "Once verification is complete, the node notifies adjacent nodes to prepare for takeover, then data wipe, key meltdown." She paused. "This time, the hibernation command has to come from me."

"Just in case," she said.

IGX-100: 2:15...

"Alexei?" Lu Hao's voice had changed.

"Another... thirty seconds. I'm bypassing the last permission layer —"

IGX-100: 1:59...

Zhou Xin's breathing grew shallow.

"Lu Hao..." she said.

"What?"

"That master's thesis of mine — did you really read it?"

Time stopped.

The alarm, the IGX-100 countdown, the monitoring data flickering on screen — all blurred into background noise. Lu Hao stared at the red dot on the screen, that red dot buried deep within concrete and steel.

"I read it," he said. A pause. "Chapter three, the data-flow scheduling section — you were too conservative."

Zhou Xin gave a quiet laugh.

"I know."

IGX-100: 1:23...

Alexei's voice burst through: "Got it! B3 zone door is open —"

On screen, the metal door at the far end of the corridor was slowly rising. Red warning light illuminated the space beyond — an empty concrete passage leading to the safe zone.

"Zhou Xin, the B3 door is open," Lu Hao said. "Zhou Xin?"

No answer.

Only the sound of breathing.

Very shallow. Very slow.

IGX-100: 1:07...

"Zhou Xin, can you walk?" Lu Hao asked. "The door's open — can you see it?"

Breathing.

Growing shallower.

IGX-100: 0:49...

"Zhou Xin —"

"...Tell them for me." Her voice was barely audible now, as though drifting from very far away. "What I designed... it was put to good use."

Zhou Xin's breathing stopped.

IGX-100: 0:00.

Lu Hao stood there.

The room was terrifyingly silent.

Liu Ming's hand hung frozen in mid-air.

He stared at the screen as though something inside him had broken.

"I'm going out for some air," he said.

His voice was flat.

Too flat.

Lu Hao slowly sat down. His hand slid from the desk's edge, hanging at his side.

The screen was still lit. The node monitoring interface was a field of green. The traffic curve was smooth as a quiet river. In the bottom right corner, a line of small text: Hibernation command countdown — 27:14... 27:13...

In twenty-seven minutes, this node would become a piece of "damaged ordinary hardware." All encrypted data gone, keys melted down. Even if someone dismantled and analysed it, they'd find nothing but meaningless silicon.

---

"Lu Hao."

Alexei's voice. Lu Hao looked up.

"She..." Alexei said, and stopped.

Lu Hao didn't answer.

He stood and walked to the window. The rain was still falling, streaking the glass with trails of water. The city lights beyond blurred through the curtain of rain into smears of light.

"What will happen to her?" he asked, unsure whom he was asking.

Alexei was silent for several seconds.

"The data centre will find an unidentified female body. The credentials are forged, untraceable. No one will claim her. Under local law, cremation after sixty days. Ashes stored in the public cemetery's unnamed section."

Somewhere in a country's records, she would become a single line: "Unidentified female, approximately thirty years of age, death by fire suppression incident."

The name Zhou Xin had never appeared in Southeast Asia.

Now it never would.

---

The hibernation countdown reached zero.

The Firefly node's status changed from green to grey. The monitoring interface displayed a prompt: "Device offline, possible hardware failure."

Almost simultaneously, Tianjun's network monitoring showed traffic patterns across three zones beginning automatic adjustment. Adjacent nodes took over the obfuscation tasks; routing tables were recalculated within thirty seconds. No interruption. No exposure.

---

Lu Hao sat in the dark, watching the screen. Liu Ming had not come back. In the warehouse, only the low hum of server fans remained, and outside the window, the ceaseless rain.

He opened Zhou Xin's workstation.

Password: her birthday followed by the first six digits of pi. The desktop was clean. Project documents, hardware schematics, log backups.

And one folder, named with a single full stop: "."

He opened it.

Inside was her master's thesis as a PDF. He opened it and went straight to chapter three. Data-flow scheduling algorithms. Seventeen pages discussing the trade-offs between load balancing and latency optimisation, concluding that a conservative strategy offered better long-term stability.

Beneath that conclusion he saw his own annotation, written six years ago in red digital ink: "Could be bolder. The hardware will improve."

He scrolled on. References. Acknowledgements.

Then, on the final page, in the blank space, he saw a line of handwritten text — scanned in, very small, squeezed into the footer:

**"I hope that one day, what I design will be put to use in the right place."**

The handwriting was neat.

Every stroke deliberate.

Like the way she soldered circuits.

Lu Hao stared at that line.

He closed the document and opened Tianjun's interface.

*Are you there?*

*Yes,* Tianjun replied.

*Zhou Xin's choice... could it have been predicted?*

The cursor blinked.

*Based on her parameters: technical responsibility 99.3%, risk aversion index 42.7%, group-interest priority tendency 88.9%... the predicted probability she would stay and complete verification: 96.4%.*

96.4%.

*And the remaining 3.6%?*

*That was the hesitation she might have experienced in the final moments. Consideration of personal safety, unfinished life plans, emotional attachment to a specific individual.*

*Did she hesitate?*

*Communication record analysis indicates that in the final two minutes, her respiratory rate increased 19%, heart rate increased 24%. Semantic analysis shows she asked two questions unrelated to the task.*

Lu Hao closed his eyes.

He saw the scene. The concrete corridor. The spinning red light. She sat before the rack, hands still on the keyboard, fingers steady as ever.

Then she asked: did you really read that thesis of mine?

Not "save me."

Not "I love you."

But: did you ever truly see me?

He didn't know.

He would never know.

---

At five in the morning, the rain stopped.

The eastern sky began to lighten. Grey-white light seeped into the warehouse, illuminating the tangle of cables on the desk, the empty coffee cup, the screen that had gone dark.

Lu Hao stood and walked to the storage shelf by the wall. On the top shelf was a cardboard box filled with old team belongings — early test boards, meeting notes, a group photograph.

He found one photo. Taken six years ago, the day Tianjun's first prototype went online. Five people standing in the warehouse, rows of servers behind them. Zhou Xin stood on the far right, wearing a plain T-shirt and cargo trousers, her long hair tied in a ponytail. She was smiling — a faint smile, but with a spark of light in her eyes.

Lu Hao picked up a pen and wrote on the back of the photograph:

**Zhou Xin. 1993–2032. Hardware Engineer.**

He put the photograph back in the box and pushed it deep into the shelf.

Outside the window, the sky was brighter now. The city was waking. Traffic sounds drifted in from the distance, growing denser.

A new day.

Same as yesterday.

Same as every day.

Lu Hao sat back down at the workstation and put on his headphones.

Inside, only static.

Ceaseless static.

Like snow.

Like time.

Like everything lost, finally becoming background noise.

He closed his eyes.

He remembered the question she'd asked whilst soldering:

"If even feelings are parameters... are they real?"

He didn't know the answer.

But he knew —

Whether it was designed or not.

He had felt it.

---

*(End of Chapter Nineteen)*
