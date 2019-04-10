# Latency Numbers Every Programmer Should Know

## Learning Goals

- Recognize the latency contributions of different levels of the computing stack

## Introduction

We want computers to feel fast. As engineers, we learn lots of tricks and cheats for speeding things up (or at least making them _feel_ like they are sped up).

In order to reason effectively about _why a program is slow_, you need to have some background knowledge about computers. In particular, you need to have an intutition for how fast different operations will take.

[Latency Numbers Every Programmer Should Know](https://people.eecs.berkeley.edu/~rcs/research/interactive_latency.html) is an interactive explorer of the latency of different operations over time. It can help you answer questions like "How long did it take to send a packet around the world in 1995?"

At this point, many of the terms on this page are still mysterious to you. Your task is to demystify the jargon on this page using google and wikipedia, until the terms are no longer quite as mysterious. You don't need to know everything about computers (yet!), so timebox each exploration, leaving yourself some loose threads to check out later.

> Note: You might start with this [explainer on memory sizes (Bytes, KB, MB, GB, TB)](http://myrepono.com/faq/4)

After you have figured out what the basic terms mean, answer the following prompts to deepen your mental picture of latency.

- How many bytes could you compress with Zippy in the time it takes to make a roundtrip within a datacenter?
- What is a 'gigahertz'?
- How large is this text file (the current one, that you are reading)?
- How many operations can your laptop do in the time that it takes to read this file from memory?
- Why are N+1 queries so bad in Rails?

Check out this blog post on [human perception of speed and latency](https://www.pubnub.com/blog/how-fast-is-realtime-human-perception-and-technology/).

- What is the 'refresh rate' of the human eye? Where would it fit on the latency chart?
- How many operations can a computer perform before a human notices?
