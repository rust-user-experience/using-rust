# Introduction

"Using Rust" is a living document describing what it's like to use Rust. Each
story narrates the challenges encountered by [one of our characters][cc] as they
try (and typically fail in dramatic fashion) to achieve their goals.

[cc]: ./characters/characters.md

Writing the stories helps us to compensate for the [curse of knowledge][cok]: the folks working on Rust tend to be experts in Rust. We've gotten used to the workarounds required to be productive, and we know the little tips and tricks that can get you out of a jam. The stories help us gauge the cumulative impact all the paper cuts can have on someone still learning their way around. This gives us the data we need to prioritize.

[cok]: https://en.wikipedia.org/wiki/Curse_of_knowledge

### Based on a true story

These stories may not be true, but they are not fiction. They are based on real-life experiences of actual people. Each story contains a "Frequently Asked Questions" section referencing sources used to create the story. The "Frequently Asked Questions" section also contains a summary of what the "morals" of the story are (i.e., what are the key takeaways), along with answers to questions that people have raised along the way.

### The stories provide data we use to prioritize, not a prioritization itself

**Just because a user story is represented here doesn't mean we're going to be able to fix it right now.** Some of these user stories will indicate more severe problems than others. As we consider the stories, we'll select some subset to try and address.

## Metanarrative

*What follows is a kind of "metanarrative" of using Rust that summarizes the challenges that are present today. At each point, we link to the various stories; you can read the full set in the table of contents on the left. We would like to extend this to also cover some of its glories, since reading the current stories is a litany of difficulties, but obviouly we see great promise in Rust. Note that many stories here appear more than once.*

Rust strives to be a language that brings together performance, productivity, and correctness. Rust programs are designed to surface bugs early and to make common patterns both ergonomic and efficient, leading to a sense that "if it compiles, it generally works, and works efficiently". Rust aims to extend that same feeling to an async setting, in which a single process interweaves numerous tasks that execute concurrently. Sometimes this works beautifully. However, other times, the reality falls short of that goal.
