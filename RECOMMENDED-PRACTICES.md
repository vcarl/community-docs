# Recommended Practices for Online Community Governance

Synthesized from 22 research papers on Code of Conduct efficacy and enforcement mechanisms.

---

## 1. Write specific, high-quality rules — not boilerplate

The presence of a code of conduct is not enough. The quality, specificity, and comprehensiveness of the rules predict whether they actually influence behavior.

- Codes with specific behavioral standards and clear enforcement procedures are significantly associated with better outcomes. Companies with high-quality codes are overrepresented in top ethical performance rankings across multiple independent systems. Boilerplate codes adopted without customization show little measurable effect. (Erwin 2011)
- A meta-analysis of 79 studies found that the wide variance in whether codes "work" is largely explained by differences in code content, implementation depth, and enforcement — not by whether a code exists. (Kaptein & Schwartz 2008)
- Fewer than 10% of F/OSS project websites surveyed had any behavioral rules at all, and among those that did, there was enormous variation in specificity and enforcement. (Singh et al. 2021)

**Practices:**

- Define specific unacceptable behaviors with examples, not just aspirational values
- Specify enforcement procedures: who handles reports, what the process looks like, what consequences exist
- Designate responsible enforcement parties by role, not just "the maintainers"
- Tailor rules to the community's specific context rather than adopting a template unmodified

## 2. Actively communicate rules at the point of participation

Rules that exist in a document nobody reads have little effect. Proactive, visible communication of norms at the moment people are participating is one of the most cost-effective interventions available.

- In a pre-registered experiment across 2,190 Reddit discussions, posting community rules at the start of a discussion increased newcomer participation by 38.1% and decreased rule-violating behavior — without any enforcement action at all. (Matias 2019)
- Codes serve as a "screening signal" for prospective contributors evaluating whether a community is safe to join. Potential contributors from marginalized groups actively look for these signals during "reconnaissance work" before participating. (Frluckaj & Howison 2024)
- Mathematical modeling demonstrates that lack of moderation can trigger "death spirals" where extreme voices drive away moderate participants. Making norms visible helps prevent this by attracting and retaining moderate voices. (Dwork et al. 2024)

**Practices:**

- Post rules visibly where participation happens — not just in a linked document
- Surface rules to newcomers at the point of their first interaction
- Frame rules as community norms ("this is how we interact here") rather than legal prohibitions
- Recognize that rule communication serves double duty: it sets expectations and signals community values to prospective members

## 3. Enforce consistently — unenforced rules erode trust

Across multiple studies and contexts, enforcement is the single most important factor separating effective governance from performative governance. Unenforced codes are worse than no code at all because they signal that leadership doesn't take its own stated values seriously.

- Contributors from marginalized groups report that observing how leadership responds to violations is a stronger safety indicator than the existence of a CoC document. Unenforced codes are compared to "greenwashing." (Frluckaj & Howison 2024)
- Women in OSS forums identified inconsistent enforcement, lack of designated enforcement contacts, and lack of transparency in handling reports as primary failures. (Singh et al. 2021)
- CoC adoption without clear violation-handling processes is common; the enforcement gap is the most challenging aspect of governance. (Tourani et al. 2017)
- When community rules are formalized clearly enough to be operationalized in automated systems, moderation becomes more consistent and more aligned with community expectations. (Xin et al. 2024)

**Practices:**

- Treat enforcement capacity as a prerequisite for adopting a code, not an afterthought
- Establish clear processes for receiving and handling reports before they're needed
- Apply rules consistently across community members regardless of status or contribution level
- Document enforcement actions (appropriately anonymized) to demonstrate that the code is active

## 4. Respond quickly — timing matters more than you think

The speed of enforcement has outsized effects on harm reduction. Delayed enforcement allows harmful content to spread and signals that violations are tolerated.

- Content spreads at very different rates across platforms. On fast-moving platforms (Twitter: 24-minute half-life), a 24-hour response window allows the vast majority of harm to occur before action. On slower platforms (YouTube: 8.8-day half-life), the same window captures most spread. Small improvements in response time yield disproportionate harm reduction for viral content. (Schneider & Rizoiu 2023)
- In competitive gaming, quick moderation is more effective than delayed moderation at both reducing the moderated player's disruptive behavior and discouraging disruptive players from continuing to participate. (Li et al. 2024)

**Practices:**

- Prioritize response speed for the most harmful content rather than processing all reports in order
- Set internal response time targets calibrated to how fast your community moves
- Use automated tools for initial triage to reduce time-to-first-response on clear violations
- Recognize that even acknowledging a report quickly (before resolution) signals that enforcement is active

## 5. Use graduated consequences — calibrate severity to the situation

Research consistently shows that consequence severity matters, but the relationship is not linear. Different enforcement tools achieve different goals, and the most severe option is not always the most effective one for a given situation.

- A large-scale quasi-experiment at Meta found that suspensions (full platform lockout) are the most effective consequence for reducing recidivism, while warnings are the least effective. Longer suspensions work better than shorter ones, but with diminishing marginal returns — the jump from 1 to 7 days matters much more than from 23 to 30 days. (Gleason et al. 2025)
- Quarantining (restricting access and visibility without outright banning) reduced new member recruitment to toxic communities by 58-79.5%, but did not change existing members' behavior. Different tools serve different purposes: containment vs. reform. (Jhaver et al. 2022)
- The relationship between punishment severity and behavioral change is non-linear; severity should be calibrated to violation type and frequency. (Li et al. 2024)

**Practices:**

- Implement a clear escalation path: notice/warning → temporary restriction → temporary suspension → permanent ban
- Apply lighter interventions first; escalate for repeated violations
- Calibrate suspension lengths thoughtfully — a 7-day suspension captures most of the behavioral benefit of longer ones
- Recognize that different tools serve different goals: warnings educate, restrictions limit reach, suspensions change behavior, bans protect the community

## 6. Explain enforcement decisions — transparency changes behavior

How you communicate enforcement matters as much as what you enforce. Explanations improve compliance among sanctioned users and prevent chilling effects on the broader community.

- Users who receive explanations for content removal have lower future violation rates. Explanations perceived as "fair" by the community are most effective. Explanations perceived as "unfair" produce no improvement over silence. (Jhaver et al. 2019)
- Bystanders who witness unexplained content removal become less willing to participate themselves — a chilling effect that suppresses the behavior of rule-following community members. Longer, polite explanations counteract this effect. (Jhaver et al. 2024)
- Suggestive evidence that inclusive language ("we") and sufficient explanation length improve outcomes. (Jhaver et al. 2019)

**Practices:**

- Always provide an explanation when taking enforcement action, even if brief
- Reference the specific rule that was violated — don't just say "this was removed"
- Use a respectful, professional tone — politeness in enforcement explanations measurably improves community outcomes
- Make enforcement visible (appropriately) to the community so bystanders understand that rules are applied fairly and predictably
- Avoid terse, unexplained removals — they harm community participation more than doing nothing

## 7. Involve the community in governance

Codes imposed without community input create a "participation paradox" where quiet adoption is followed by contested enforcement. Governance perceived as legitimate — because the community had a voice in shaping it — is more effective than governance imposed top-down.

- CoC adoption typically involves minimal community discussion, but enforcement decisions trigger enormous backlash. This asymmetry creates governance problems: the community never collectively agreed on the norms being enforced. (Li et al. 2021)
- Moderators who build relationships with community members — not just enforce rules — create more effective governance. Moderation perceived as fair and consistent has different effects than identical actions perceived as arbitrary. (Seering et al. 2019)
- Community consensus in code creation produces stronger buy-in and more sustainable governance. (Frluckaj & Howison 2024, Tourani et al. 2017)

**Practices:**

- Involve the community in creating or adopting behavioral standards — don't just post a document
- Provide forums for discussing rules and enforcement, especially during and after contentious incidents
- Invest in moderator-community relationships, not just moderator-violator interactions
- Recognize that moderators serve as community builders, not just rule enforcers — support both roles

## 8. Banning works — but understand what it achieves and what it doesn't

Community-level bans are among the most studied enforcement interventions. The evidence is clear that they reduce harm on the platform that does the banning, but the effects across the broader ecosystem are more complex.

- Banning hate communities from Reddit reduced hate speech across the platform. Users who migrated to other subreddits did not bring significant increases in hate speech to their new communities. This directly challenges the "whack-a-mole" objection. (Chandrasekharan et al. 2017)
- Reddit's 2020 mass ban of ~2,000 subreddits reduced activity among affected users and produced a small but significant decrease in toxicity among users who remained. (Cima et al. 2024)
- However, communities that migrate to alternative platforms rather than dispersing become smaller (58-83% user loss) but more internally toxic. Banning reduces reach and exposure but may concentrate toxicity elsewhere. (Ribeiro et al. 2021)
- Permanent bans of individuals may construct a "most toxic player" narrative useful for deterrence, but may not address root causes of the behavior. (Kou 2021)

**Practices:**

- Don't hesitate to ban communities or individuals that consistently violate rules — the evidence supports this as effective at the platform level
- Understand that banning primarily reduces reach and exposure, which is the main source of harm
- Recognize that some displaced users will seek less moderated spaces — this is an acceptable tradeoff when the alternative is tolerating harm in your community
- For individual permanent bans, be direct about the reason and finality — ambiguity creates false hope and repeat appeals

## 9. Consider restorative approaches alongside punitive ones

Purely punitive enforcement has well-documented limitations. A growing body of work argues for complementing removal-and-ban approaches with mechanisms focused on accountability, repair, and victim support.

- Current platform governance mirrors punitive criminal justice: it asks "did this violate a rule?" and punishes the violator, while neglecting the person harmed. Reframing governance around "who was harmed and how can it be repaired?" opens different intervention options. (Schoenebeck & Blackwell 2021)
- Permanent bans in gaming communities function partly as symbolic messaging rather than genuine behavioral intervention. The restorative lens suggests that addressing root causes of toxic behavior — through mediated conflict resolution, structured rehabilitation, or community-based accountability — may produce more durable change. (Kou 2021)

**Practices:**

- For interpersonal conflicts (as opposed to clear policy violations), consider mediation before punishment
- Develop mechanisms for violators to acknowledge harm and make repair — not just serve time
- Center the experience of the person harmed in the response, not just the rule that was broken
- Reserve purely punitive approaches for cases where restorative options have failed or where the severity of harm demands immediate protective action

## 10. Moderate to build, not just to police

Moderation is often framed as a cost center — the necessary work of removing bad content. The evidence reframes it as a community design tool that shapes participation, diversity, and culture.

- Mathematical modeling demonstrates that moderation can increase total participation by making the platform hospitable to groups that would otherwise leave. Removing content that drives away larger populations is a net positive for community size. (Dwork et al. 2024)
- The overall moderation environment affects even users who are neither particularly disruptive nor particularly well-behaved. Moderation shapes the behavior of the entire community, not just the people being moderated. (Li et al. 2024)
- A systematic comparison of 43 platforms found enormous variation in policy design. Platforms that specify clear enforcement consequences, provide appeals processes, and distinguish severity levels create more predictable environments. (Schaffner et al. 2024)

**Practices:**

- Frame moderation internally as community investment, not overhead
- Recognize that every enforcement action sends a message to the entire community about what's valued here
- Design for the participants you want to attract, not just the ones you need to remove
- Provide appeals processes — they improve perceived legitimacy and catch errors
