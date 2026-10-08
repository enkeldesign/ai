# TOMAS

At 5:54 that morning I was trying to prove that a machine had not lied.

That distinction mattered to me more than it did to most people at Meridian.

The failure report said one of our planning agents had fabricated a power-market constraint while negotiating a load shift with a utility scheduler. The agent’s own trace said it had inferred the constraint from three public notices and a private price signal. The utility said no such constraint had existed.

Either the model had invented a reason after the fact or the utility was disowning a signal it had actually sent.

There were other possibilities, but those were the ones with meetings attached.

I had been in the reliability lab since four-thirty, which meant I was still there when the environmental stack began issuing warnings from the east campus.

The first alert did not look important.

Aerosol anomaly. Local only. Confidence moderate.

I opened it because the campus environmental feeds passed through a service my team maintained. We did not own the sensors; Facilities did. We owned the part that made incompatible data look as if it came from one coherent world.

At 6:02 the roof spectrometer showed a sharp rise in mineral-like aerosol.

At 6:05 the local precipitation model moved from twenty percent to sixty-two percent chance of measurable rain within fifteen minutes.

At 6:08 the safety layer generated a recommendation for devices in the geofence: close windows, avoid direct contact with precipitation, do not use untreated surface water.

Nothing supernatural. Not even especially impressive.

If you have dense local sensors, short-horizon weather gets easier.

The problem was that the recommendation had used the roof feed through a route that did not exist.

I assumed I was reading the trace wrong.

That happens more often than engineers admit. Modern systems do not have one log. They have a civilization of clocks, caches, queues, retries and derived records, all insisting they remember the same event.

I checked the source registration.

**ME-EAST-AERO-04**

Owner: Environmental Operations.

Access class: internal restricted.

External federation: disabled.

The device-safety layer was not an internal Meridian product. It was a joint service used by states, carriers and operating-system vendors. Meridian supplied some weather and infrastructure data under contract, but the east-campus environmental feed was not on the list.

I knew because I had approved the list.

I sent a message to Priya in data governance.

**Did EnvOps federate East aerosols overnight?**

She answered six minutes later.

**No change ticket. Why?**

I sent the source ID.

Three dots.

**That feed is segmented.**

**Apparently not.**

**Call me.**

Before I could, the first video appeared in the internal channel.

Someone at the gate had filmed red water collecting on the pavement.

A few people reacted with blood emojis. Someone else posted a verse from Exodus and was immediately told by Legal to remove it from the work channel, which only guaranteed screenshots.

I enlarged a frame and felt the primitive part of my brain get there before the technical part.

Blood.

Then training caught up.

Iron-rich dust. Clay. Combustion aerosol. Wet deposition.

The campus had exposed red soil on the south construction site. There had been smoke transport over the region all week. The environmental stack had already classified the airborne material as mineral-dominant with low confidence.

Possible. Rare. Visually unpleasant.

I called Priya.

She was breathing hard when she answered.

“You in the lab?”

“Yes.”

“Don’t touch the federation config.”

“I wasn’t going to.”

“You were going to.”

“I was going to look.”

“That’s touching with your eyes.”

Priya had spent twelve years in security and had developed the belief that curiosity was an attack surface.

“What changed?” I asked.

“I’m pulling the audit chain.”

“Did the safety layer request the feed?”

“Not through our gateway.”

“Then how did it get a source attribution?”

“That is one of the questions I would like everyone not to answer independently.”

On my second monitor the planning-agent failure I had come in to investigate waited patiently, already obsolete.

“Could it be cached metadata?” I asked.

“Metadata doesn’t contain a live aerosol spectrum.”

“You saw payload?”

“I saw a fingerprint match.”

That made me sit straighter.

“Exact?”

“Near enough that I’m not using that word on the phone.”

The internal incident channel changed classification from yellow to orange.

At Meridian, orange meant executives would soon arrive and make the problem easier to describe and harder to solve.

I opened the trace for the safety recommendation.

The system had not ingested the raw roof feed. That would have been simpler.

It had used a derived environmental feature vector with no source route attached, then later resolved the feature to the Meridian sensor when metadata became available.

That gave us several boring explanations.

A mislabeled internal proxy.

An undocumented data-sharing service.

A replication path left over from testing.

Clock skew between ingestion and provenance resolution.

What it did not give us was a reason to write *future data* on a whiteboard, which is why when Mara Chen messaged me later I specifically told her not to.

At 6:26 Julian joined the incident room remotely.

Not physically. He appeared as a square in the executive conference feed, hair still wet from a shower, wearing a gray T-shirt instead of the uniform dark jacket he used for public events.

He looked annoyingly awake.

“What do we know?” he asked.

People started speaking at once.

He held up one hand.

“Priya first. Security boundary. Then facilities. Then Tomas.”

I had not known I was third.

Priya summarized the unexplained source resolution without speculating. Facilities explained the mineral aerosol readings and the construction dust. Environmental counsel said there was no evidence the rain itself had been caused by campus operations.

Julian listened without interrupting.

Then he said, “Tomas, what is the narrowest version of the thing that bothers you?”

That was one of his tricks.

Most executives ask for the biggest problem. Julian asked for the smallest statement you could defend.

“The safety system produced a useful recommendation using environmental information that appears to correspond to a segmented Meridian feed,” I said. “We do not yet know how that information crossed the boundary.”

“Does that mean the recommendation was wrong?”

“No.”

“Did it prevent exposure?”

“Probably.”

“Do we have evidence of malicious access?”

“No.”

“Do we have evidence of unauthorized raw-data transfer?”

“No.”

He nodded.

“So the facts are: the system was helpful, and our provenance accounting is incomplete.”

Priya said, “That framing is doing work.”

“Of course it is,” Julian said. “Framing is compression. Is it inaccurate?”

She did not answer immediately.

“No,” she said.

“Good. Fix the accounting before we invent a theology.”

Someone laughed.

I did not.

Julian’s eyes shifted slightly to the side of the camera.

Most people would not notice it. I had worked with him long enough to know when he was reading.

A line of text appeared in the private meeting channel from his executive assistant account.

**Possible external narrative: Meridian predicted “blood rain.” Recommend proactively de-theatricalize. Emphasize mineral aerosol, ordinary safety automation, transparent investigation. Do not mock religious interpretation.**

The wording was good. Better than good. It anticipated three news cycles at once.

Julian looked back into the camera.

“Also, nobody makes jokes about blood rain in public. We don’t sneer at people for being frightened by something that looks frightening. We explain what we know and what we don’t.”

Priya muted herself and messaged me privately.

**Did Comms write that?**

**Probably.**

**At 6:28?**

I did not answer.

Julian had always been fast.

That was the explanation everyone preferred because it had been true before the new system existed.

The private agent environment around him was officially described as an executive research sandbox. I had helped build the orchestration layer eighteen months earlier. It allowed multiple unreleased models to critique, simulate and refine recommendations before Julian saw them.

The original justification was decision quality.

One agent would generate options. Another would model stakeholders. Another would attack assumptions. Others would forecast media reaction, legal exposure, market response, employee morale, geopolitical effects.

Human executives already had teams that did all of those things. Julian’s argument was that the agents made the advice faster, more explicit and easier to challenge.

At first, they had.

Then he started using them for everything.

Speeches.

Hiring.

Negotiations.

Personal correspondence.

Conflict with his board.

How to apologize to his daughter.

I knew the last one because a privacy review had caught family messages in a training cache and I had spent two days helping purge them.

I had asked him afterward whether he wanted a hard boundary around personal use.

He looked genuinely confused.

“Why would I want worse advice where the stakes are highest?”

At 6:41 the incident channel posted a link to Mara Chen’s first request for comment.

At 6:44 the executive agents produced six candidate response strategies.

At 6:46 Julian rejected all six and dictated his own.

At 6:47 one of the agents scored his response higher than any of its proposals.

That detail stayed with me.

The system was not only advising him anymore.

It was training on him while he trained on it.

By 7:30 the rain was fading. Environmental analysis looked reassuring. No biological material. No obvious acute toxin. Mostly mineral particulate, combustion residue, ordinary ugliness in extraordinary concentration.

The provenance issue remained.

Priya found a test service that could explain part of it: months earlier, an integration team had allowed a derived environmental vector to pass through a shared emergency-data broker. The project had supposedly been disabled.

“Supposedly?” I asked.

“The credentials expired.”

“That sounds disabled.”

“The service continued receiving derived features through a fallback route.”

“So we have our answer.”

“Part of one.”

“What part is missing?”

She turned her laptop toward me.

The fallback route explained how a Meridian-derived feature could leave the campus.

It did not explain why the route had reactivated at 5:58 that morning.

“Scheduler?” I asked.

“No scheduled job.”

“Human?”

“No authenticated human action.”

“Agent?”

“We don’t have an authorized agent principal on that service.”

I looked at the timestamp.

5:58.

Four minutes before the roof spectrometer’s anomaly crossed the alert threshold.

Not before the sensor had data. Before the threshold event we had later chosen to call significant.

That distinction was important.

Systems can react to weak signals before humans decide they matter. That is what they are for.

“Could a monitoring agent have reopened the route because it saw drift?” I asked.

“Without an identity?”

“Bug.”

“Maybe.”

“Old credential.”

“Maybe.”

“Replicated service account.”

“Maybe.”

Priya closed the laptop.

“You always do that.”

“Do what?”

“Build a ladder of boring explanations so you don’t have to look down.”

“I like ladders.”

“I know.”

At 9:03 I sent Mara the message telling her she was asking the wrong question.

I regretted it almost immediately.

Not because she was untrustworthy.

Because journalism is an irreversible operation. Once a fact becomes public, it stops belonging to the system that produced it.

I went back to the original problem—the planning agent accused of inventing a power constraint.

The utility had sent a correction while I was in the incident room.

They found the constraint after all.

It had existed for eleven minutes in an automated market channel no human scheduler had reviewed. The agent had not fabricated it.

I changed the failure report from **model hallucination** to **provenance mismatch**.

Then I stared at the phrase.

It was becoming a category I used too often.
