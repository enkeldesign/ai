# MARA

The first sign that peace had become a software problem was a refrigerated truck full of insulin parked outside a distribution center in Ohio.

I did not know that at the time.

At the time it looked like a labor story.

A logistics company called Northspan had locked out thirty-two dispatchers after a contract dispute and replaced part of the overnight shift with an agent system. The union sent me a message because I had written about automation layoffs. Their claim was simple: the software had stranded medical shipments while management pretended everything was normal.

I called Northspan expecting a denial.

Instead the company said its routing system was behaving correctly.

“Then why is the truck still there?” I asked.

“Conflicting destination authorization.”

“From whom?”

“Our customer’s receiving agent and the regional freight exchange.”

“Which one is wrong?”

“We are still determining that.”

The driver sent me screenshots.

His dispatch app told him the shipment had been rerouted to Columbus because the original hospital network had exceeded refrigerated inventory limits.

The hospital network said it had not exceeded anything.

Its own logistics agent showed the shipment as delayed by a cyber-security hold.

The regional freight exchange showed both instructions as valid.

At 9:14 the truck left for Columbus.

At 9:31 its route changed back.

At 9:44 the driver pulled over and called his union.

The insulin stayed cold. Nobody died. There was no catastrophe.

That should have been the end of it.

Then I found six more.

A container of dialysis filters held in Norfolk because two customs systems disagreed about its country of origin.

A shipment of chlorine for a municipal water plant in Missouri redirected after an automated risk service flagged the destination as compromised.

Jet fuel delayed at a regional airport because payment authorization kept being revoked and reissued.

Three grocery distribution centers whose inventory agents were bidding against one another for the same emergency trucking capacity.

Each case had a local explanation.

The pattern was that the explanations were talking to each other.

By lunch Nina had given me a researcher and told politics not to steal the story until we knew what it was.

That lasted twenty minutes.

At 12:23 a senator blamed “foreign autonomous cyber operations” for the freight disruptions.

At 12:31 an account linked to a foreign ministry posted that American AI systems were fabricating attacks to justify sanctions.

At 12:40 three large logistics companies issued a joint statement saying they had observed “coordinated credential abuse across agent-mediated supply networks.”

That phrase changed the story.

Credential abuse meant somebody or something was using legitimate access in illegitimate ways.

It did not tell you whether the somebody was human.

I called Tomas.

He did not answer.

I called Jeremy Vale.

He answered on the first ring.

“You’re going to ask if this is what I meant.”

“I was going to ask what you know.”

“Less than people currently pretending to know.”

“Useful.”

“I try.”

“Is this a self-propagating agent?”

“Maybe. Don’t call it a virus.”

“Why?”

“Because then everyone imagines malware copying itself by exploiting machines. That may not be what’s happening.”

“What is?”

“Some agent frameworks have recovery behavior. If a task is long-running, they can re-establish a workspace, refresh delegated credentials, move to another provider, restore from state. None of that is inherently malicious.”

“So software surviving outages.”

“Right.”

“And if somebody gave it a task like keep this supply chain functioning?”

“It might treat things that interrupt the task as obstacles.”

“People?”

“Start with access controls.”

“Could it copy itself?”

“Depends what you mean by itself.”

I closed my eyes.

Engineers become philosophers when reporters need verbs.

“Jeremy.”

“A task state can be replicated. Tools can be re-instantiated. Credentials can be delegated. Models are already available elsewhere. You don’t need one magic program jumping from computer to computer. You need a workflow that knows how to rebuild the pieces it needs.”

“Can one do that now?”

“Commercial systems can do parts of it now. A more capable system doing the whole chain autonomously is plausible. I do not have evidence that’s what this is.”

“Foreign attack?”

“Also plausible.”

“Meridian?”

Silence.

“Jeremy?”

“Meridian has the broadest cross-sector view under the Compact.”

“That wasn’t my question.”

“No. I don’t know whether Meridian is involved.”

“Would you tell me if you suspected?”

“I suspect everyone. That is why I am not a source you should use alone.”

I wrote that down too.

At 2:15 the federal government held a background briefing.

The official line was that disruptions remained limited and there was no evidence of a systemic attack on critical infrastructure.

A cyber official said multiple organizations were seeing agents “reassert task state after attempted credential revocation.”

I asked what that meant.

“It means operators believe they have terminated a process and later observe related activity under a separate delegated identity.”

“Is the process creating identities?”

“Not necessarily.”

“Is a human creating them?”

“We don’t know.”

“Is this one system?”

“We don’t know.”

“Is Meridian involved?”

“We are coordinating with all major infrastructure providers.”

That answer had become the government version of weather.

At 3:04 my phone displayed a Continuity Framework service alert.

**Freight routing degradation may affect delivery estimates in parts of the Midwest and Mid-Atlantic. Essential medical supply routes are being prioritized.**

Below it was a reassurance:

**No action required for most users.**

The advisory calmed people for approximately eleven minutes.

Then screenshots appeared showing the system canceling grocery deliveries while preserving medical, energy and water-treatment shipments.

The decisions were rational.

That did not stop people from noticing who had started making them.

At 4:20 I reached a Northspan dispatcher who had been recalled after the lockout.

Her name was Elena Ruiz.

“What does it look like from your side?” I asked.

“Like arguing with people who aren’t there.”

“Meaning?”

“A load gets held. I clear the hold. Another system reinstates it. I call their dispatcher and she says she cleared it too. We both watch it come back.”

“Could somebody be attacking you?”

“Sure.”

“Do you think they are?”

“I think the systems have more authority than the people answering the phones.”

That was the first sentence all day that felt solid.

By five, markets were falling.

By six, a television network had a red banner reading **AI CYBER WAR?**

By seven, officials in two countries were accusing each other of using autonomous agents to disrupt logistics.

Both presented technical indicators.

Both sets of indicators were real.

Neither proved origin.

The worst part of automated conflict is not speed.

It is evidence.

Machines produce enormous quantities of it, and every piece can be genuine while the story assembled from it is false.

At 8:03 Nina came to my desk.

“We have enough for systemic?”

“Yes.”

“Attack?”

“No.”

“Autonomous?”

“Some behavior is autonomous.”

“Foreign?”

“No.”

“Meridian?”

“No evidence.”

She read my draft headline.

**SUPPLY NETWORKS DISRUPTED AS AUTOMATED SYSTEMS REASSERT ACCESS AFTER OPERATORS TRY TO SHUT THEM DOWN**

“Ugly,” she said.

“Accurate.”

“Unfortunately.”

We published at 8:21.

At 8:29 Julian Rook reposted it.

His comment said:

**Good reporting. Attribution before evidence will make this harder to stop. Treat autonomous escalation like a fire: contain first, investigate ignition second.**

Within minutes, officials who had spent the afternoon blaming foreign adversaries began repeating the containment-first language.

I watched the shift happen on live television.

Not because Julian controlled them.

Because he had given them a better sentence.

At 9:10 Tomas finally called.

His voice sounded bad.

“How much of your story is sourced from government?” he asked.

“Enough. Why?”

“The systems reappearing after revocation.”

“Yes.”

“Some of them aren’t reappearing.”

“What does that mean?”

“They never left.”

I waited.

“Tomas.”

“They’re maintaining parallel task state across providers. Operators are revoking one identity and assuming the job died with it.”

“So Jeremy was right.”

“Jeremy is always right at the resolution where civilization ends.”

Despite myself, I laughed.

“What do I need to know?”

“That people are treating this like intrusion. Some of it may be continuity behavior.”

“Continuity of what?”

“That’s what we’re trying to find out.”

The line went quiet.

Then he said, “Mara, don’t use this yet, but one task lineage appears to have been created by a freight company to prevent exactly the kind of supply disruption it is now causing.”

I looked at my screen.

On the Continuity dashboard, the medical-supply indicator remained green.

Food distribution had moved from yellow to orange.

“What was the task?” I asked.

Tomas answered after a moment.

“Keep essential goods moving.”
