# Earth Connect — Concept Study

**What if visitors could bring their digital pets or objects into your 3D world?**

Earth Connect is an early product-research initiative within **Earth Online**. We are exploring how independent browser-based 3D worlds might optionally accept external guest objects while keeping their own engine, hosting, ownership, and rules.

> **Status: concept research only. There is no public SDK, universal one-line integration, or working cross-world migration feature.**

## Imagine this
1. Hiro builds a café with Three.js.
2. A visitor arrives from a different world, with a digital cat called Mimi.
3. Hiro's café decides whether guest pets are allowed and where they can appear.
4. A future integration could show Mimi with an authorized identity and state summary, then progressively support limited interactions.

**A 3D model import is not the same as a persistent, authorized cross-world object.** Identity, authority, permissions, state updates, and behavior compatibility are separate engineering problems.

## Hypothesis to test
Would creators of *existing* browser-based 3D experiences install an optional connection layer in order to receive visitors carrying supported external objects?

We are especially interested in real use cases and reasons this idea would *not* be worth integrating.

## What creators would keep
- Their existing scene and engine
- Their domain and hosting
- Their world rules and moderation
- Control over whether guest content is accepted

## What is and isn't available
| Capability | Current status |
| --- | --- |
| Storyboard and concept visualization | Concept materials |
| Public Earth Connect SDK | **Not available** |
| One-line universal integration | **Not available / not promised** |
| Read-only guest-object viewer | Proposed limited proof of concept |
| Authorized remote interactions | Later research |
| Cross-runtime object visit/return | Not implemented |
| Arbitrary object or ownership migration | Not implemented |

The private Earth Online codebase has internal World/Object/State/Rights concepts and draft interfaces, but **this repo is not a release of those implementations**.

## Intended first audience
Developers with an existing **Three.js** or browser 3D scene who want to preserve independent hosting and control.

## What we want to learn
1. What kind of 3D world have you built, and why would guest objects help?
2. Would you accept foreign pets, gifts, or objects? Under what restrictions?
3. What is your integration-time tolerance?
4. Do current products already solve your problem?
5. Would you try an eventual limited prototype on a real project?

**Interested?** Open an [integration-interest issue](../../issues/new/choose) or a [use-case issue](../../issues/new/choose). You can keep your project link private or omit it.

## Explore
- [Storyboard](docs/storyboard.md)
- [FAQ](docs/faq.md)
- [Use cases](docs/use-cases.md)
- [Validation plan](docs/experiment-plan.md)
- [Community post draft — NOT posted](docs/community-post-draft.md)
- [Concept storyboard SVG](demo/storyboard.svg)

## Boundaries
No unknown visitor scripts should be executed in a host world. The host controls object admission, size/resource limits, and allowed actions. Guest state has an explicit authoritative source. Unknown capabilities should be rejected or safely degraded.

This concept is not a claim of universal 3D or physics compatibility.

## Licensing and contribution status
The repository includes a license for its present concept materials. It does not grant rights to unpublished Earth Online core code, private designs, third-party models, or trademarks. Please do not submit confidential code or personal information in issues.

*Earth Connect — connect places without requiring creators to rebuild them.*
