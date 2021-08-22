# Everyone Learns a Little Differently.

Some people learn quickly; some people learn slower than others. I'm a firm believer that *anyone can learn anything*.

The *hardest* part of learning (often) is understanding something that's *new* and *different* and isn't accounted for by any of the stuff that you've managed to pack into your head.

Maybe you've experienced this: "X wasn't doing well, until they met Y, who was a brilliant mentor and guided X."

Hopefully that sounds familiar; personalized attention from someone who deeply understands a concept and *also understands how you learn* can make the difference between you learning, or not.

What if I told you that you could have that personalized attention? What if I told you that it could be free?

## IEP For Everyone

Everyone learns a little bit differently, and I'm saying that *anyone can learn anything* and I can help make that happen.

The way we're going to do that is:

1. Build a dataset of educational content (lots of these exist.)
2. Produce an embedding space for this dataset.
3. Use a KD-Tree from this space to produce content samples for students learning about particular topics.
4. Measure those students.
5. Allow a reinforcement learning algorithm to guide back-propagation in this embedding space as a function of the measurements.
6. Repeat.

The reinforcement learning agent is deciding how best to nudge the embedding vectors to maximize *performance* of the student learners.

So, what's done, what needs to be done, and what's the status?

## Major Project Milestones

### Adaptive KD-Trees (In progress)

This is a Python package which can construct a KD tree and associated embedding space for a dataset representing a collection of educational content.

I just started this; considering my availability I'm expecting to see this done, with implemented testing, sometime late 2021.

### Reinforcement Learning Environment.

This wraps the class above in an OpenAI API compatible learning environment that it also compatible with RLLib.

This will be done after the KD Tree construct is available for use; reasonable movement is likely to be sometime mid 2022.

### Control Experiments

These experiments, using machine learning constructs as learners in a controlled environment, are intended to serve as proof of concept.

Late 2022 is a reasonable time-frame to expect movement on this.

## Can I Help?

You know what, yes! I would love a project manager; if you're interested in the technical aspects there's certainly more room for hands to be put on.

Questions are welcome.
