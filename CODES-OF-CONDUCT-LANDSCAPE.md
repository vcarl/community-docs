# Codes of Conduct in Online and Open Source Communities: A Landscape Analysis

A survey of commonly adopted Codes of Conduct, with emphasis on scope — who the code applies to, what spaces it covers, and how it addresses members beyond direct contributors.

---

## The Core Problem of Scope

Most early Codes of Conduct in open source were framed around "contributors" — people submitting code, documentation, or other direct project artifacts. But open source communities include many other participants: users asking questions in forums, attendees at meetups and conferences, people discussing the project on social media, sponsors, and people who claim affiliation with the community without being core members. A Code of Conduct that only covers "contributors" leaves the majority of community interactions unaddressed.

Since roughly 2020, newer CoC versions and original codes have trended toward broader scope language. Three mechanisms are commonly used to extend coverage beyond contributors:

1. **Space-based scope**: The code applies in all community-managed spaces (repos, forums, chat, events), covering anyone who participates in those spaces regardless of their role.
2. **Representation clauses**: The code applies whenever someone is "representing the project or its community" — using official channels, social media accounts, or acting as a representative.
3. **Impact clauses**: The code applies to behavior outside community spaces when it negatively impacts the project or its members. This is the broadest formulation but the hardest to enforce.

---

## Widely Adopted Codes

### Contributor Covenant

- **Maintainer**: Coraline Ada Ehmke; now managed by the Organization for Ethical Source
- **License**: CC-BY-4.0
- **Adoption**: The most widely adopted CoC in open source by a large margin. Used by thousands of projects including Go, Ruby, Rails, Swift, Kubernetes, and many others.
- **Current version**: 2.1 (2021)
- **Scope**: Version 2.0 (2020) significantly broadened scope from "contributors" to "community." The current version applies within "all community spaces" and extends to public spaces "when an individual is officially representing the community." Examples of representation include using an official email address, posting via an official social media account, or acting as an appointed representative.
- **Notable features**: The most templated and adoptable code — designed to be dropped into any project. Includes a structured enforcement guide. Defines a "Community Impact" ladder with four levels (Correction, Warning, Temporary Ban, Permanent Ban) with specific triggers for each.
- **Limitations**: Despite broadening in v2.0, the framing still centers on project spaces. It does not include an impact clause covering behavior outside community spaces. Enforcement depends entirely on the adopting project's capacity.
- **URL**: https://www.contributor-covenant.org/

### Citizen Code of Conduct

- **Maintainer**: Stumptown Syndicate
- **License**: CC-BY-SA-3.0
- **Adoption**: Moderately adopted, particularly by meetup groups, user groups, and community organizations rather than code repositories.
- **Scope**: Designed from the start as a community code, not a contributor code. Applies to all community members, organizers, sponsors, and anyone interacting in community spaces. Oriented toward in-person and hybrid communities.
- **Notable features**: Frames participation as "citizenship" in a community, which inherently broadens scope beyond contribution. Addresses both online and offline spaces. Includes specific guidance for event organizers. Provides a model focused on community belonging rather than project contribution.
- **Limitations**: Less structured enforcement guidance than the Contributor Covenant. Less widely adopted in software projects specifically.
- **URL**: https://github.com/stumpsyn/policies/blob/master/citizen_code_of_conduct.md

### Geek Feminism Community Anti-Harassment Policy

- **Origin**: Ada Initiative (now defunct); maintained on the Geek Feminism Wiki
- **License**: CC0 (public domain)
- **Adoption**: The template behind most conference and event CoCs. PyCon, JSConf, and many other tech conferences use derivatives. Available in short, medium, and long versions.
- **Scope**: Explicitly covers attendees, speakers, sponsors, vendors, exhibitors, staff, and volunteers. Applies at all event venues and event-related social activities. The long version extends to online communities, official communication channels, and social media.
- **Notable features**: The earliest widely-adopted anti-harassment policy in tech communities. CC0 licensing makes adoption frictionless — no attribution required. Provides specific examples of unacceptable behavior and specific enforcement procedures (warning, expulsion from event, contacting security). The template approach (fill in your event name) made mass adoption practical.
- **Limitations**: Primarily designed for events; online community adaptations require modification. Enforcement guidance is event-specific (escorting out of venue, contacting hotel security).
- **URL**: https://geekfeminism.fandom.com/wiki/Community_anti-harassment/Policy

### TODO Group Open Code of Conduct

- **Maintainer**: TODO Group (a Linux Foundation project). Originally created by a consortium including GitHub, Facebook, Twitter, and Google.
- **License**: CC-BY-4.0
- **Adoption**: Used by corporate-backed open source projects, particularly those affiliated with TODO Group member companies.
- **Scope**: Applies to all community spaces managed by the project. Includes a representation clause covering public spaces when representing the project. Specifically names official project email, social media, and events.
- **Notable features**: Designed for corporate-backed open source, where the project has institutional backing and resources for enforcement. Includes guidance on how to handle reports and a commitment to confidentiality.
- **Limitations**: Less widely adopted than the Contributor Covenant. Oriented toward projects with corporate sponsors and paid staff, which doesn't match the dynamics of volunteer-run communities.
- **URL**: https://github.com/todogroup/opencodeofconduct

---

## Foundation-Level Codes

These codes are notable because they cover entire ecosystems — not just individual projects, but all projects, events, and community spaces under a foundation's umbrella.

### Mozilla Community Participation Guidelines

- **Maintainer**: Mozilla Foundation
- **Scope**: One of the broadest in open source. Explicitly covers Mozilla employees, contractors, volunteers, event attendees, and anyone participating in Mozilla community spaces. Extends to behavior outside Mozilla spaces when it affects community safety. Notably covers people "claiming affiliation" with Mozilla — if you represent yourself as part of the Mozilla community, the CPG applies.
- **Notable features**: The "claiming affiliation" clause directly addresses peripheral members. The impact clause extends beyond project spaces. Includes a detailed enforcement ladder and a trained team for handling reports. Distinguishes between behaviors that are "disrespectful," "unexpected," and "not tolerated" with different response levels for each.
- **URL**: https://www.mozilla.org/en-US/about/governance/policies/participation/

### Python Software Foundation Code of Conduct

- **Maintainer**: Python Software Foundation
- **Scope**: Applies to all PSF-managed spaces: PyCon, regional Python conferences, mailing lists, IRC/Discord, forums, GitHub organizations, and in-person events. Covers all participants in these spaces — attendees, speakers, sponsors, volunteers, community members — not just CPython contributors.
- **Notable features**: Backed by a dedicated PSF Conduct Working Group with defined procedures. One of the earliest foundation-level codes. PyCon's specific implementation (derived from this) has been influential as a model for conference CoCs globally.
- **URL**: https://www.python.org/psf/conduct/

### Django Code of Conduct

- **Maintainer**: Django Software Foundation
- **Scope**: Applies to all Django community spaces: forums, mailing lists, IRC, official events, and code repositories. Covers anyone interacting in these spaces.
- **Notable features**: One of the earliest CoCs in open source (2013). Established the DSF Code of Conduct Committee model — a standing committee with defined membership, terms, and procedures — that many other projects have replicated. The committee model provides institutional continuity rather than depending on individual maintainers.
- **URL**: https://www.djangoproject.com/conduct/

### Apache Software Foundation Code of Conduct

- **Maintainer**: Apache Software Foundation
- **Scope**: Foundation-wide, covering all 350+ ASF projects. Applies to all participants in ASF community spaces. ASF explicitly describes itself as "a community of communities."
- **Notable features**: Scale — governing conduct across hundreds of projects with different cultures and norms under one umbrella. The ASF model demonstrates how a shared code can work across a large, diverse ecosystem.
- **URL**: https://www.apache.org/foundation/policies/conduct.html

### Linux Foundation / LF Projects Code of Conduct

- **Maintainer**: Linux Foundation
- **Scope**: Covers all LF-hosted projects (including Kubernetes, Node.js, Hyperledger, and many others). Applies to all participants in project and community spaces.
- **Notable features**: Institutional backing of the Linux Foundation provides enforcement resources that individual projects lack. Adopted as a default by many LF-hosted projects.
- **URL**: https://lfprojects.org/policies/code-of-conduct/

---

## Professional Association Codes

These codes apply based on membership in a profession or association, not participation in a specific project or space. They are relevant as models for communities where affiliation is the basis of membership rather than contribution to a shared artifact.

### ACM Code of Ethics and Professional Conduct

- **Maintainer**: Association for Computing Machinery
- **Scope**: Applies to all ACM members — students, practitioners, educators, researchers — regardless of role or where they are. Membership in ACM constitutes agreement to the code. This is a condition-of-membership model rather than a space-based model.
- **Notable features**: Organized around seven general ethical principles and specific professional responsibilities. Covers ethical obligations beyond interpersonal conduct: responsibility for the impact of computing systems, honesty in professional claims, respect for privacy, fairness and non-discrimination. Includes guidance for organizational leaders, not just individual practitioners.
- **Relevance**: The condition-of-membership model is directly applicable to communities where people claim affiliation or identity ("I'm a member of X community") rather than contributing to a specific project. Anyone who self-identifies as an ACM member is bound by the code regardless of context.
- **URL**: https://www.acm.org/code-of-ethics

### IEEE Code of Ethics

- **Maintainer**: Institute of Electrical and Electronics Engineers
- **Scope**: Applies to all IEEE members as a condition of membership.
- **Notable features**: Shorter and more principles-based than the ACM code. Focused on professional conduct in engineering: honesty, avoiding conflicts of interest, treating all persons fairly, assisting colleagues in professional development.
- **Relevance**: Like ACM, uses a membership-based rather than space-based model. Less directly applicable to online community governance but relevant as a model for professional peer groups.
- **URL**: https://www.ieee.org/about/corporate/governance/p7-8.html

---

## Codes with Distinctive Scope Features

### The Carpentries Code of Conduct

- **Maintainer**: The Carpentries
- **Scope**: Applies to everyone participating in Carpentries activities: workshops, email lists, GitHub, Slack, social media, and events. Explicitly names *learners* alongside instructors and organizers as covered.
- **Why it matters**: Most open source CoCs implicitly assume participants are peers (fellow developers). The Carpentries explicitly covers people in an asymmetric relationship — learners who are there to receive instruction, not to contribute. This is a useful model for communities where many members are users or consumers rather than co-creators.
- **URL**: https://docs.carpentries.org/policies/coc/

### Elastic Community Code of Conduct

- **Maintainer**: Elastic
- **Scope**: Covers all community spaces (forums, wikis, repos, Slack channels), all events and event venues, and — unusually — private communications between members when the communication involves harassment, threats, or behavior affecting community members' safety.
- **Why it matters**: The private communications clause is rare. Most CoCs only cover community-managed spaces. Elastic's code acknowledges that harassment often happens in DMs and private channels, and asserts jurisdiction over those interactions when they affect community safety.
- **URL**: https://www.elastic.co/community/codeofconduct

### Google Open Source Code of Conduct

- **Maintainer**: Google
- **Scope**: Applies within project spaces and in public spaces when representing the project. Also includes an impact clause: applies "outside the project spaces when the Project Steward has a reasonable belief that an individual's behavior may have a negative impact on the project or its community."
- **Why it matters**: The impact clause is the broadest scope formulation in common use. It doesn't require the person to be in a community space or representing the community — only that their behavior affects the community. This addresses the gap where someone's conduct on personal social media or at unrelated events creates harm for community members.
- **URL**: https://opensource.google/conduct

### Red Hat Open Source Participation Guidelines

- **Maintainer**: Red Hat
- **Scope**: Distinct from a traditional CoC — these are guidelines for Red Hat employees participating in upstream open source communities. They address how employees should conduct themselves in communities Red Hat doesn't control.
- **Why it matters**: This inverts the typical model. Rather than a community setting rules for its members, an organization sets expectations for how its members should behave in other people's communities. Relevant for communities that include employees of companies with a commercial interest in the project.
- **URL**: https://www.redhat.com/en/about/open-source/participation-guidelines

---

## Gaps in Existing Codes

Most current codes still assume one of two models:

1. **Space-based**: You're in our space (forum, repo, event), so our rules apply.
2. **Representation-based**: You're representing us (official email, social media, appointed role), so our rules apply.

Neither model fully addresses people with **peripheral affiliation** — someone who attended one event, uses the software, occasionally posts about the community on personal social media, or self-identifies as part of the community without holding any official role. The Mozilla CPG's "claiming affiliation" language and Google's impact clause come closest, but this remains genuinely under-addressed.

The professional association model (ACM, IEEE) offers a different paradigm: membership-as-agreement. If you claim membership, you accept the code. This could be adapted for open source communities — "if you identify as a member of this community, you agree to this code" — but enforcement mechanisms for this model are underdeveloped in the open source context.
