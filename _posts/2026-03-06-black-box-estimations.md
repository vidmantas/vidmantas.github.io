---
layout: post
title: "Black Box Estimations"
tags: [ai, industry, estimations, stakeholders]
featured_image_thumbnail: assets/images/posts/2026/black-box-estimations_thumbnail.jpg
featured_image: assets/images/posts/2026/black-box-estimations.jpg
---

Software estimation has always been hard — a running joke in the industry for so long the joke stopped being funny. And yet, with enough discipline, decomposition, and calibration, we got into a *vicinity* of truth. Close enough to plan a quarter, set a customer expectation, or make a reasonable staffing decision. The underlying assumption in all our tools — story points, t-shirt sizes, velocity baselines — is that engineers are roughly predictable actors. Given similar context, a similar task takes a similar amount of time.

That assumption is now under serious pressure.

### Enter the Black Box

AI coding tools have become a real part of how engineers work. Cursor, Copilot, Claude, Codex. The productivity gains are real and visible. Engineers regularly report that certain tasks which used to take hours are now done in minutes. Some classes of problems that required senior knowledge to approach are now accessible with a well-crafted prompt.

But here's the catch: essentially, these tools are **non-deterministic black boxes**.

What that means in practice: the same engineer, with the same AI tool, working on two superficially similar tasks, can have wildly different experiences. One task — writing a straightforward CRUD endpoint with familiar patterns — might be done in a quarter of the usual time. Another — integrating with a poorly documented third-party API or working in a legacy codebase the model has never seen anything like — might end up *taking longer* than doing it manually, because you're now debugging AI-generated code that looks plausible but introduces subtle bugs you have to hunt down.

The multiplier is unknowable upfront. It could be 10x. It could be 2x. It could be 1x. It could, in some cases, be 0.8x.

### The Volatility Problem

This is where estimation gets into genuinely new territory. Before AI tools, the variance in execution time for a well-understood task was fairly bounded. A mid-level engineer estimating a task in their domain of expertise wouldn't be wildly off — maybe 1.5x, maybe 2x in bad cases. That's manageable.

With AI tools in the mix, the variance explodes. Virtually the same task, the same engineer, on a different day could now take 20 minutes or 3 days. And crucially, you often don't know *which* until you're already in it.

Now imagine building a sprint plan, a roadmap, or a customer commitment on top of estimates with this kind of range baked in. What does a "two-day task" even mean anymore if the honest confidence interval is "somewhere between two hours and two weeks"?

An estimate with that kind of spread is not an estimate. It's a shrug with a number attached.

### Does This Make Estimation Useless?

Not entirely — but it might retire some of the tools we've relied on. Story points as a proxy for effort assume that effort is at least somewhat stable as a concept. Velocity as a planning baseline assumes your team's throughput from last quarter tells you something about next quarter. Both assumptions become significantly shakier when a core ingredient in the work — AI assistance — is this unpredictable.

What might still hold: **relative estimation**. If Task A and Task B are both AI-assisted in similar ways (similar codebase familiarity, similar documentation quality, similar problem domain), comparing them to each other still carries some signal. The absolute number might be nonsense; the ratio might still be meaningful.

What I suspect will emerge as more valuable: **leading indicators other than time**. Things like: is the AI generating confident, clean output for this task, or is it hedging and hallucinating? Has this type of work been done in this codebase before, so the tool has patterns to latch onto? Is this a greenfield problem or a legacy archaeology expedition? These don't give you a number — but they give you a *risk profile*.

My wild guess: estimations will be done only after the first AI-only pass on the problem.

### What This Means for Leaders

If you're managing teams or communicating commitments upward, I think this deserves an honest conversation — perhaps before the next planning cycle rather than after the first one blows up.

A few things worth putting on the table:

Acknowledge the new source of variance. It's not that engineers are estimating poorly. The tool they're using has genuine uncertainty baked in at a level we haven't dealt with before. Treating blown estimates as a calibration failure misdiagnoses the problem.

Consider time-boxing over estimating. For high-AI-leverage work, "we'll spend three days on this and see how far we get" might be a more honest contract than "this will take three days." The former is a commitment you can keep. The latter might just be fiction.

And have the conversation with stakeholders now. The teams that will handle this best are the ones that proactively reframe how they communicate uncertainty — not the ones that keep using the old vocabulary and hope nobody notices when the numbers stop adding up.

### Closing Thought

We spent decades learning to be better at estimation despite the inherent difficulty of the craft. We got better because we understood the variables. The arrival of AI tools has introduced a variable we don't yet understand well enough to model — and that's the honest state of things.

The worst response is to keep estimating as if nothing has changed, and then explain the misses later. Altough everybody will accept the work that took 5x shorter time than estimation, next time your own integrity and knowledge will be at risk. The more useful response is to start figuring out, now, what estimation even means in this new environment — and to be transparent with everyone around us while we work that out.

<small>Photo by [Photo by Ann H](https://www.pexels.com/photo/tape-measure-on-blue-surface-10895045/)</small>