# The effectiveness of moderating harmful online content

**Authors:** Philipp J. Schneider, Marian-Andrei Rizoiu
**Published:** 2023, Proceedings of the National Academy of Sciences (PNAS), Vol. 120, No. 34
**DOI:** 10.1073/pnas.2307360120
**Link:** https://www.pnas.org/doi/10.1073/pnas.2307360120

## Abstract

In 2022, the European Union introduced the Digital Services Act (DSA), a new legislation to report and moderate harmful content from online social networks. Trusted flaggers are mandated to identify harmful content, which platforms must remove within a set delay (currently 24 h). Here, we analyze the likely effectiveness of EU-mandated mechanisms for regulating highly viral online content with short half-lives. We deploy self-exciting point processes to determine the relationship between the regulated moderation delay and the likely harm reduction achieved. We find that harm reduction is achievable for the most harmful content, even for fast-paced platforms such as Twitter. Our method estimates moderation effectiveness for a given platform and provides a rule of thumb for selecting content for investigation and flagging, managing flaggers' workload.

## AI Summary

This PNAS study applies mathematical modeling to quantify the effectiveness of content moderation timing, providing one of the first rigorous analyses of how moderation speed relates to harm reduction across different platforms. The research is framed in the context of the European Union's Digital Services Act (DSA), which mandates that online platforms remove illegal and harmful content within specified timeframes (currently 24 hours) once flagged by "trusted flaggers."

The methodology is computational and analytical. The researchers deploy self-exciting point processes (specifically Hawkes processes) — a class of statistical models originally developed for seismology — to model how harmful content spreads on social media. These models capture a key property of viral content: each piece of harmful content can trigger additional harmful content (replies, reshares, reactions), creating cascading chains of harm. The "self-exciting" property means that the probability of future harmful interactions increases after each observed interaction.

The critical innovation is the concept of "content half-life" — the time it takes for a piece of content to generate half of its total direct offspring (replies, shares, etc.). The researchers empirically measured content half-lives across major platforms: Twitter (24 minutes), Facebook (105 minutes), Instagram (20 hours), LinkedIn (24 hours), YouTube (8.8 days), and Pinterest (3.75 months). These dramatically different half-lives have direct implications for moderation effectiveness: on platforms with short half-lives (Twitter), most harm occurs within minutes of posting, meaning that a 24-hour moderation window allows the vast majority of harm to occur before content is removed. On slower platforms (YouTube, Pinterest), the same 24-hour window captures a much larger fraction of potential harm.

The study finds that harm reduction is achievable even on fast-paced platforms, but only if moderation resources are targeted at the most harmful content. The researchers provide a mathematical framework for optimizing flagging priorities — essentially a rule of thumb for which content to investigate first given limited enforcement resources. Their model estimates the percentage of harm that can be prevented as a function of moderation delay, allowing platforms and regulators to make informed trade-offs between speed and coverage.

Key conclusions: the DSA's 24-hour removal requirement is effective for slower platforms but insufficient for fast-moving ones like Twitter; harm reduction requires prioritizing the most harmful content rather than attempting comprehensive coverage; and the relationship between moderation delay and harm reduction is non-linear — small improvements in response time can yield disproportionate harm reduction for viral content.
