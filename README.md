# DevOpsDays Zürich 2023
2023-05-03 to 2023-05-04

[Programme](https://www.devopsdays.ch/program)

## Building High-Performing Teams through Psychological Safety
95% of the employees feel that their wings are pinned (like the expression)

Disagreement doesn't have to be conflict.

Manual of Me

Tip for smaller teams: Rely on structured feedback, not just the coffe break talk.

## Reporting on Reliability
@rmedranollamas

 - What the hell? &lt;- Incident status
 - What was that? &lt;- Postmortem
 - How's it going? &lt; Periodic Reviews

### What the hell
Real-time incident management. Don't phone. Live docs.

### What was that?
Postmortem. Make it blameless.

Action items - track, and the incident is not really over until all the action items are completed.

### How's it going?
How is the team doing? (Toil). Forecast demand. Forecast work to be done.

Do we name names? Yes, but the blameless part is really "so what".

## From Backend Developer to DevOps
@Ladymeyy

Documentation - write How to's

Advantage of teaching early on - you still have fresh eyes for the stuff other people already forgot.

## Bridging dev and ops with eBPF
[Slides](https://www.slideshare.net/raphink/devopsdays-zurich-2023-bridging-dev-and-ops-with-ebpf-extending-observability-upwards-and-downwards)

Before: stupid

goal: expertise-driven

Adjust privileges to expertise

Dashboards *that actually make sense* - pointing to actual stuff that happens in the application.

Example: IP logs - that doesn't even, like, make sense, in a container-based world.

## Saying No
Eisenhower matrix: does this work if you're not the one deciding?

## Developer productivity
Citation needed: Happy developers write better code. Maybe it's our suffering that is the secret ingredient.

Build cache: if the inputs stay the same then we can reuse the output.

[Predictive Test Selection](https://research.facebook.com/publications/predictive-test-selection/)

[Test Parallelization with vstest](https://learn.microsoft.com/en-us/azure/devops/pipelines/test/parallel-testing-vstest?view=azure-devops)

## CIA
These three buckets - confidentiality, integrity, availability

https://www.wiktoriadalach.com

## Development process of Cloud native applications
Feature toggles: they really tried for a unified set of features, no per-customer toggles.

## Effective Observability in Microservice Architecture
You shouldn't have to do data transformation just to follow the trace.

## Continuous Compliance
https://www.beautifulabstraction.com/compliance-by-design/

Example: Release notes

