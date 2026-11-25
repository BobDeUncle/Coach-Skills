# Phase 1 topics

Run in order. Each topic's completion criterion is the bar for marking it `Done`.

## 1. Business context

- Number of active clients, and how that changes (intake waves, seasonal).
- Check-in cadence: which day, weekly or other, and the deadline clients submit by.
- Who replies: only him, or other coaches too? If others, who handles which colour.
- Programme types or client groups that are judged differently (e.g. fat loss vs. muscle gain, comp prep, new vs. long-term clients).

**Done when** the doc states client count, cadence, who replies, and every client group that needs different rules.

## 2. Data

Ask him to **show** you, step by step, how he gets client data into Claude today. Then do it yourself, here, with real data.

**Google Drive (client list)**
- Find the client list or folders through the Drive connector. Open them.
- Record: file or folder names and location, the structure (one sheet? one doc per client? folders?), every field or heading, how a client is identified, and anything stale or inconsistent.

**Fitness app (check-ins)**
- Ask which app it is and how he gets check-ins out today: a connector, export (CSV, PDF), copy-paste, screenshots, or reading on his phone.
- Get a real sample into this chat by that route. If there's a quicker route (an export, a connector), try it too.
- Record: the app name, the route and how many clicks or minutes it takes, every field in a check-in with type and units (weight, measurements, photos, adherence, sleep, steps, energy, free-text answers), which fields clients often skip, and anything that only exists on the phone or in photos.

**Linking**
- How does a check-in match a Drive client (name, email, ID)? Try matching the sample. Note every mismatch.

**Done when** both sources have been opened in this chat with real data, every field is listed with type and units, the fetch route for each is written step by step, and the linking method has been tested on the sample.

## 3. Traffic-light rules

Build these from his reasoning, then test them against the data from topic 2.

- For **red**, **orange** and **green**: what puts a client there? Get thresholds and specifics ("weight up more than 1 kg", "missed 2+ workouts", "sounds flat in the comments"), not adjectives.
- Which signals matter most? When signals conflict (great adherence, weight up), which wins?
- Free-text and tone: what in a client's written answers moves the colour? Collect real phrases that would.
- Missing data: a missed check-in, no photos, half a form. What colour, and why?
- Gut-feel overrides: when does he overrule the rules? Push until each override becomes a rule or an explicit "coach's call" case.
- **History**: should last week's colour, his notes, or a trend change this week's colour (e.g. orange two weeks running becomes red)? What history would he want kept, and for how long? (It would live in a Drive file.)
- Different rules for the client groups from topic 1.

**Done when** every colour has concrete, checkable criteria; conflict, missing-data and history rules are written; and you've applied the rules to two or three clients from the topic 2 sample and he agrees with the result.

## 4. Review queue and green message

Check-in day output: every green client gets the same message, which he picks that day. Every orange and red client comes up one at a time for him to reply to personally. He replies himself; Claude does not write replies.

**The queue**
- Order: red before orange? Worst first? Alphabetical? Grouped by client type?
- The **client card**: exactly which fields he needs on screen to reply well. This week only, or alongside last week or a trend? Photos? The client's own words in full?
- The reason for the colour: shown on the card? How detailed?
- Ticking off: what he types to mark a client done; whether a note is saved for next week, and what it holds.
- Overrides mid-queue ("actually this one's green"): allowed? Logged with his reason? (Logged overrides are how the rules get better over time.)
- End of run: what summary he wants (counts per colour, overrides, clients who didn't check in).

**The green message**
- How he chooses it each week: writes it fresh, picks from past ones, asks Claude for options?
- How it's sent: through the fitness app, one by one, in bulk, or something else? How long does that take today?
- Is a client's name or any detail merged in, or is it identical for everyone?

**Done when** the queue order, every client card field, the tick-off and override behaviour, the end-of-run summary, and the green message's choice and sending are all written.

## 5. The run itself

- Walk through a real check-in day from start to finish: what he opens, in what order, what he copies where.
- Time each part (roughly). Where does the time go?
- What's manual today that he'd most like gone?
- What must stay manual?

**Done when** the doc has a numbered start-to-finish walkthrough with rough times, and the manual steps he wants gone and wants kept.

## 6. Pain points, success, and review

- What goes wrong on check-in day now? Missed clients, inconsistent calls, burnout, slow replies?
- What does a good check-in day look like? How long should it take?
- **After each run**, what would he want reviewed so the system improves: overrides he made, colour calls that felt wrong, clients that took too long, missing data? How often would he do that review?

**Done when** pain points, a measurable "good day", and what to review after each run are written.

## 7. Current Claude setup

He already runs part of this in Claude.

- Ask him to paste, **word for word**, everything he uses: project instructions, saved prompts, rule lists, example messages. Remove only client names. Put it in the appendix as-is.
- What does he dislike about it? What does he keep correcting? What does it get wrong?
- What does it do well that must survive?

**Done when** the appendix holds his current setup word for word (or he's confirmed there's nothing more), plus what to keep and what to fix.

## 8. Parking lot

Anything outside check-in day that came up (onboarding, programming, billing, marketing). One line each. Don't explore them.

**Done when** he's confirmed the list is complete.
