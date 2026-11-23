# Release Notes
## New in 2026.1

The Release of the new SWARC4AI curriculum includes revised, cleaned-up, consolidated and sharpened learning goals, cleaned up, consolidated and sharpened towards central software architectural question for AI based software systems, methodologies and patterns.

Important updates and changes:

* All former Github issues were also resolved
* The learning goals count is now 62 (compared to 97 before)
* Module 3 Added documentation of architectural decisions for AI-based systems
* Module 4 Added learning goal for knowing modern data architectures and role of data products, contracts and responsibilities
* Module 6 Added learning goal including Agent Runtime (Harness) architecture considerations
* Module 7 LG 7-1 Case Study is mandatory now (not optional anymore)
* The learning goals are renumbered as after updates and changes quite a few number gaps emerged
  * Renumbered all learning goals and updated / synchronized the English translation, which fixed #42 and #34
* Alphabetically sorted, updated, and cleaned up references which resolved #35 and #54

More details on updates to the SWARC4AI curriculum version 2:

* Module 1
  * LG 1-2 and 1-8 consolidated
  * LG 1-4 and 1-9 consolidated
  * LG 1-5 and 1-6 consolidated
* Module 2
  * LG 2-4 and 2-5 consolidated
  * LG 2-8 and 2-10 consolidated
  * LG 2-12, 2-13 and LG 2-14 merged and consolidated with 2-6 and 2-7; AI Principles documents optional
  * LG 2-16 removed and merged with the similar LG 4-4
* Module 3
  * LG 3-1 and 3-2 merged, as they fit well together in terms of content
  * LG 3-3 consolidated with LG 3-4 and LG 3-5
  * LG 3-6 can be omitted, as the LG is not specific enough; LG 5-8 is redundant—the topic fits better in Chapter 5 -> LG 3-6 removed
  * LG 3-7 and 3-8 consolidated
  * LG 3-9 consolidated with the new LG 3-23, as they fit well together in terms of content
  * LG 3-10 removed, as it is redundant with the new LG 3-3
  * LG 3-14 and 3-15 consolidated
  * LG 3-19 removed, as it is redundant and already covered in Chapter 2
  * LG 3-21 removed and combined with the similar LG 2-11; bias fits better under AI Safety, Ethics, Risk, and Data Governance in Module 2 than under Design/Development in Module 3
* Module 4
  * LG 4-3 consolidated with 4-1 and remains optional
  * LG 4-6 consolidated with 4-4 and marked as optional
  * LG 4-7 remains and has been expanded to include vector databases and graph databases; these are generally interesting and architecturally relevant for participants (RAG). The remaining storage technologies are retained only for completeness
* Module 5
  * LG 5-1 remains and has been expanded to include NPUs and LPUs, as new AI accelerators are generally very interesting for participants and offer significant potential for runtime cost and efficiency improvements
  * LG 3-5 and 5-20 consolidated
  * LG 5-10 and 5-11 consolidated and marked as [OPTIONAL]; then consolidated with 5-9 and 5-12
  * LG 5-13, 5-14 and 5-21 consolidated
  * LG 5-15 removed, as it is redundant with 3-8
  * LG 5-16 and 5-17 merged
  * LG 5-19 marked as [OPTIONAL] and consolidated with 5-18; generally interesting for participants in the context of systematic, iterative ML optimization, but not among the most central topics
* Module 6
  * LG 6-1 and 6-2 consolidated
  * LG 6-3 and 6-6 consolidated
  * LG 6-4 removed, as it is redundant and quality attributes can be covered in Module 5
  * LG 6-5 and 6-15 consolidated
  * LG 6-7 and LG 6-8 consolidated
  * LG 6-11 remains and consolidated with 6-10, as there are many specific use cases / benefits / trade-offs associated with it, and it has been slightly corrected and expanded to include GraphRAG, CAG, Agentic RAG, and Multi-Agent RAG -> highly requested in the training sessions, including understanding the differences and trade-offs
  * LG 6-14 remains unchanged for now, as it covers fundamental LLM-specific design patterns
  * LG 6-20: Harness renamed to agent runtime system
* Module 7
  * LG 7-1 is mandatory now (not optional anymore)

## What's Changed since 2026.1-rev0

* Fix bullet lists by @programming-wolf in https://github.com/isaqb-org/curriculum-swarc4ai/pull/58
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/64
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/65
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/67
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/68
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/69
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/70
* Update 01-duration-terms.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/71
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/66
* Fix rendering 73 by @StefanZoerner in https://github.com/isaqb-org/curriculum-swarc4ai/pull/74
* Update 02-learning-goals.adoc by @mahboubagharbi in https://github.com/isaqb-org/curriculum-swarc4ai/pull/72
* Use “minimal risk” for the fourth EU AI Act risk level by @StefanZoerner in https://github.com/isaqb-org/curriculum-swarc4ai/pull/76
* Fix Update CHANGELOG.md by @programming-wolf in https://github.com/isaqb-org/curriculum-swarc4ai/issues/77


**Full Changelog**: https://github.com/isaqb-org/curriculum-swarc4ai/compare/2026.1-RC1...2026.1-rev1