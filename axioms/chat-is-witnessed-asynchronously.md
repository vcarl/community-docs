# Chat is witnessed asynchronously

## Claim

Messages posted in a chat environment are read by more people over more time than the sender anticipates. Every post is a small act of broadcasting, even when it feels like conversation.

## Justification

Chat interfaces present as ephemeral — a running river of real-time talk. The actual social reality is different. Messages are read later by members who join the channel, scroll back, follow links from elsewhere, or receive notifications hours after posting. In large communities the asymmetry is extreme: a message typed for the three people present in the moment may be read by a hundred over the following week, and indexed permanently in search and logs. Bernstein et al. (2013) measured this directly on Facebook and found that users consistently and dramatically underestimate the size of their actual audience — the audience they imagine is a small fraction of the audience they reach.

This has consequences for what chat *is* as a medium. It is not a conversation, though it looks like one. It is closer to a continually appended public record, experienced as conversation by those present at the moment of posting. Marwick and boyd (2011) describe this condition as "context collapse" — the flattening of distinct audiences (friends, colleagues, strangers, adversaries) into a single undifferentiated readership, with the speaker unable to tailor utterances to each. Chat inherits this property. The social rules that apply to small-group talk and the social rules that apply to broadcast don't fully apply. Chat occupies an ambiguous middle where senders write for the present audience and are read by a much larger absent one.

Members often reason about their posts as if the present audience were the whole audience. The platform reinforces this illusion by presenting chat as conversational UI. Designing community norms around the conversational framing alone misses most of what actually happens.

## Implications

- Behavior that would be appropriate in private conversation can be harmful when read by the wider audience that eventually witnesses it.
- Community norms must account for the reading population, not just the participating one.
- Mechanisms like searchable history, linkability, and cross-channel mentions make this asymmetry more severe, not less. They are not neutral features.
- "This was meant in the moment" is not, on its own, a defense against the record the moment produced.

## References

- Bernstein, M. S., Bakshy, E., Burke, M., & Karrer, B. (2013). Quantifying the Invisible Audience in Social Networks. *Proceedings of CHI 2013*. https://doi.org/10.1145/2470654.2470658
- Marwick, A. E., & boyd, d. (2011). I tweet honestly, I tweet passionately: Twitter users, context collapse, and the imagined audience. *New Media & Society*, 13(1), 114–133. https://doi.org/10.1177/1461444810365313
