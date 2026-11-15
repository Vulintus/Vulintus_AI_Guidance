# Vulintus AI Policy & Guidance

### "May you live in interesting times"

Working with AI tools at the end of 2025, we at Vulintus largely echoed the opinion that LLMs were "stochastic parrots", useful perhaps for writing inelegant text or creating oddly composed images, but not to be trusted with anything you wouldn't want to be considered "slop". Now, a year or so later, we have been thoroughly converted. Every day we're using AI tools, to review and troubleshoot engineering plans, to help write documentation, and to create customized software and firmware. The improvement in accuracy and functionality of those outputs from month to month has been shocking. We imagine that our customers have experienced the same shift.

From our vantage point, the biggest impact of AI tools so far seems to be the personalization of software. AI technology has reached a point where the average layman, with no computer science background, can use these tools to create and implement their own complex programs from scratch, without having to understand or review a single line of code. Within the field of biomedical research, already we can see a new explosion of niche, purpose-built software made to solve problems that only a handful of labs face.

If Vulintus was in the business of selling software, this moment of democratization would perhaps be unsettling. Fortunately for us, even though it has probably been up-to-now commercially unwise, we've always provided the software that controls and connects to our devices for free. In fact, most of the control and analysis software we provide for our systems are open-source, and we've always encouraged our customers to take and modify our code however they can. In practice, however, only a few labs have had the bandwidth to explore customization on their own. More often, Vulintus software engineers work with labs to help implement the special features they want into our software. But we, too, have a limited bandwidth, and there has always been a bottleneck in how quickly we can respond to customers' customization requests. Now that every lab may effectively have access to teams of virtual expert software engineers, we want to throw open the floodgates to ensure that bottleneck disappears completely.

---

## Getting started With AI agents

To better enable customers to use AI tools to work with Vulintus devices, we've created this [Vulintus AI Guidance](https://github.com/Vulintus/Vulintus_AI_Guidance) repository, a starting point for agents (and humans!) to navigate and understand all of the open-source projects that Vulintus provides. If you have a Vulintus system and you want to see how you can use AI agents to customize it to meet your exact needs, just point your agent to this repository, tell it what Vulintus equipment you have (or what equipment you might need), and set it to work.

Repositories and markdown files are the forum and language of AI agents, and so from [Vulintus AI Guidance](https://github.com/Vulintus/Vulintus_AI_Guidance) you will find links to an expanding web of Vulintus open-source repositories, each focused on a particular device or behavioral task. In each repository, look for an 'AGENTS.md' markdown file (like this [one](https://github.com/Vulintus/Vulintus_AI_Guidance/blob/main/AGENTS.md)) for all the background and context information you, or your agent, need to get started.

---

## How Vulintus Uses AI Tools

### Software Development

As you might expect from how we'd like to encourage your use of AI coding tools, we're embracing them quite thoroughly ourselves. If you use Vulintus devices or software for your research (and we hope you do!), hearing that AI is used in development might make you understandably wary. Data collection for biomedical research absolutely has to be deterministic to be replicable. When your mouse pulls on a Vulintus isometric pull handle, the force that’s measured needs to be calibrated and recorded the same way every single time. Our software can never be allowed to “hallucinate.” At the same time, Vulintus works every day to figure out ways to reduce costs to make our products accessible to more researchers, and AI tools are an unignorably powerful way we can increase the value we offer to our customers. A good compromise comes from the admission that not all code is critical. In fact, of the code we write, maybe more than 90% of it is concerned with aesthetics such as buttons, selections, graphics, and presentation. We can let the AI tools run wild with those aspects, where the worst that can happen is the user interface is uglier than it might otherwise be. Meanwhile, we humans will focus on verifying that data flows through our systems, from sensor to data files, in exactly the steps that we expect it to, and that any transformation is consistent, repeatable, and documented.

---

### Documentation

It’s unlikely anyone outside of Vulintus would notice, but we feel like our documentation has been improving quite a bit over this last year. You might notice that a repository we recently updated has a much more developed README file, or that our connection guides now have simplified diagrams instead of pictures. While we’ve always aspired to be more thorough with our documentation, our use of AI tools is the one big reason why it’s finally getting better. Whatever you may think of their artistic or literary pursuits, the AI tools we use seem quite adept at creating coherent how-to guides from software code and diagrams from poorly-composed smartphone photos. You can be sure, however, that a human reviews and edits every word of our documentation for accuracy, and that where AI was used, we'll disclose it right at the top with a note (like [this one](https://github.com/Vulintus/MotoTrak_Treadmill_Walking_Task/blob/main/README.md)) saying _"This guide was AI-generated, but checked for accuracy by a human."_

---

## Going Forward

After living through a year of blisteringly fast AI advancement, we couldn't dare to guess what the next year will bring. We can promise, though, that whatever new capabilities AI develops, we'll remain open and transparent about how we're using them.  What new value and advantages they bring to us, we'll do our best to pass on them to our customers. Finally, and most importantly, we promise that when you reach out to Vulintus, you'll always reach a human first.

And, for the record, all of this was written by a human.


