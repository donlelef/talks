# How Does AI Watermarking Work? A Close Look at SynthID

Watermarking is the most reliable way we have to spot AI-generated text, and it took researchers several failed attempts to get there. This talk retraces that path: post-hoc classifiers that degrade as models write more like humans, invisible Unicode characters that are trivial to strip, and green/red-list watermarks that either break on low-entropy text or bend the model's output distribution. It ends at SynthID, the scheme DeepMind built for Gemini and that Anthropic now uses for Claude.

The core idea is tournament sampling: at each generation step, candidate tokens drawn from the model's distribution compete on pseudorandom, keyed scores, and the winner is emitted. Configured correctly, it is non-distortionary, so watermarked text reads like unwatermarked text. In DeepMind's evaluation it added 0.57% latency per token and caused no measurable quality drop across 20 million Gemini responses. Attendees will leave knowing exactly how the algorithm embeds and detects its signal, and where it breaks.

## Where it was held

- Codemotion, Milan, Italy, 2026
- ML Prague, Prague, Czech Republic, 2027

## Slides

[How Does AI Watermarking Work - A Close Look at SynthID.pdf](How%20Does%20AI%20Watermarking%20Work%20-%20A%20Close%20Look%20at%20SynthID.pdf)
