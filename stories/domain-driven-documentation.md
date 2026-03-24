# Domain-Driven Documentation: Documentation was never the problem

**Author:** David Boyne
**Read time:** 5 min

---

Documentation is this weird thing in software.

Nobody really wants to do it, but everyone feels like they have to. I've been there. We look for ways to automate it, generate it, or avoid it entirely. And when we do write it, it can quickly becomes outdated or just isn't read by anyone anyway.

It's a cycle most teams go through, but many teams come back to documentation.

But after spending years working in this space, building tools, talking to many companies, I've started to think…

Maybe documentation isn't the problem.

## It's not documentation, it's how we use it

I don't think the issue is that we don't document enough.

I think the issue is how we represent documentation, how we access it, and whether it actually provides value at the moment we need it.

Most documentation tools follow the same pattern. You create pages, organise them in a sidebar, and expect people to navigate through them. It's all very linear. You click around, search a bit, and hope you eventually find what you're looking for.

Sometimes you do. A lot of the time, you don't.

And even when you do, it's often missing the context you actually care about.

## Documentation is back (and we didn't expect it)

What's interesting is that documentation is becoming important again, whether we like it or not.

Over the past year, markdown has basically become the interface for working with AI. Prompts, tools, agent instructions, knowledge bases… it's all documentation.

The same thing we've been trying to avoid is now something we depend on.

But this shift is also exposing a deeper problem.

AI can read what we write, but it doesn't understand our systems in the same way we do. It doesn't know why something exists, what it means to the business, or how it has evolved over time.

And if you're unlucky a lot of that information isn't written down anywhere anyway.

## The real problem is context

The value of documentation isn't just in what it contains. It's about when and how that information is presented.

If you look at something like the C4 model, the value isn't just the diagrams. It's the idea of showing the right level of information at the right time.

Too much detail and you lose people. Too little and it becomes meaningless.

What's useful is always relative to the person reading it. Or now, the AI consuming it…

Most documentation doesn't handle this well. It's static. It's linear. It assumes everyone will read it the same way.

But that's not how people actually understand systems.

## We already have the building blocks

Spending time working with event-driven architectures really changed how I think about this.

You start to realise how important events and data are, and how closely tied they are to the business. There's a constant tension between technology and the domain it serves…

And when you look at Domain-Driven Design, we already have a lot of the pieces we need.

- Bounded Context
- Domains/Subdomains
- Ubiquitous language
- Domain events

We use these to model systems, but we don't really use them to structure our knowledge.

We run EventStorming/Event Modeling sessions, have great conversations, uncover important insights… and then most of that context just disappears.

Even when we do try to capture it, it often ends up scattered.

We write architecture decision records (ADR) to capture decisions and reasoning. We document schemas. We create diagrams. But all of this information lives in different places, disconnected from the actual domain concepts they relate to.

So while the information exists, it's hard to access, hard to navigate, and even harder to use when you actually need it.

## Domain-Driven Documentation

This is where I've been exploring something I've started calling domain-driven documentation (bad name? Not sure…)

At a simple level, I think of it like this:

> Domain-driven documentation is about capturing and organising domain knowledge around the concepts that actually matter in your system, not as pages, but as part of the domain itself.

Not just documentation as static pages in a tool, but a more flexible approach where documentation can evolve, connect, and surface the right information when it's needed either to humans or AI.

Static pages still have a place. They're useful for capturing knowledge, decisions, and explanations. But on their own, they don't give us the full picture.

What we really need is a hybrid approach. One where we can combine static knowledge with more dynamic, contextual information. Pulling together data, decisions, and domain concepts across bounded contexts, and presenting them in a way that reflects what's actually happening at a point in time.

Documentation then becomes less about reading pages, and more about accessing context.

That might look like:

- Events that capture intent, not just schemas
- Concepts tied to real business meaning
- Decisions and history connected to the system

Including things like ADRs, but instead of them living in isolation, they are connected to the domain concepts they relate to, within the right bounded contexts and teams.

The goal isn't to write more documentation.

It's to bring together the context we're already creating, and make it accessible in the right place, at the right time, to the right people (and AI).

## Looking ahead

I don't really know what the future of this looks like yet.

AI will keep evolving. Teams will automate more. New tools will come along.

But I think the core problem stays the same.

We need to share context.

We need to preserve meaning.

And we need to make that meaning accessible, not just for the people building our systems, but for the AI that's starting to shape them as well.

This is also a big part of why I've been leaning into these ideas with EventCatalog.

I've been exploring how we can use Domain-Driven Design practices to structure and present information differently. Thinking more in terms of boundaries, attaching meaning to schemas, and providing the right level of context at the right time.

It's far from perfect, and I'm still figuring a lot of this out. But it feels like an important area to explore.

I have a feeling the future of documentation is going to look very different from what we have today, and I'm excited to keep diving deeper into it.
