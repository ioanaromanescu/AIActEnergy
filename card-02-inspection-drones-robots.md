# CARD 02 — Autonomous inspection drones and robots

*AI in Energy Operations: An EU AI Act Guide · [all cards](../README.md) · a guide and general information, not legal advice*

## What it is

Drones, crawlers, and legged robots that inspect flares, storage tanks, pipelines, and offshore and subsea structures, with computer vision reading the imagery for corrosion, leaks, deformation, and coating failure. Operators across the sector publicise these programmes, usually on the argument that they take people out of confined spaces, off ropes, and away from height.

## AI Act status

**Generally minimal risk, with two boundaries and one regime that sits alongside.**

- Detecting the condition of an asset is not a prohibited practice, and inspection of equipment does not correspond to an Annex III category. On its own, this is the low end of the scale.
- The classification can change where the AI acts as a **safety component of a product covered by EU harmonisation legislation** listed in Annex I, for example machinery. Systems that only report findings for human review sit outside that; systems that stop, steer, or intervene deserve a closer look. This route applies from August 2027.
- Separately, the flying itself is governed by **EU drone rules** (Regulations 2019/947 and 2019/945), which are their own regime with their own operator categories, authorisations, and pilot requirements. Compliance there is not evidence of compliance under the AI Act, and the reverse is equally true.

## If you deploy it

- Record the intended purpose in writing with the vendor, and note whether the system recommends or acts.
- Article 4 applies to every AI system: the inspectors and engineers reading the outputs should understand the model's limits, particularly what it tends to miss.
- Confirm the aviation and product-safety side separately, with whoever owns those questions in the organisation.
- Agree in advance what happens when the model misses a defect that a human inspector would have caught, and who reviews the imagery in that case.

## GDPR overlay

**Medium.** The inspection target is an asset, but the footage very often is not only the asset. Site imagery captures workers going about their day, and aerial routes can cross neighbouring land, roads, and housing. Purpose limitation is the discipline: the footage was collected for asset integrity, and reusing it for anything else is a new purpose that needs its own analysis. Practical measures worth putting in place from the start are blurring of faces and plates, tight retention, narrow access, and clear information for people on site.

## Red flags

- Inspection footage reused for a purpose nobody agreed at the outset.
- Flight paths over housing or public roads planned without anyone asking the privacy question.
- The contract is silent on false negatives: a missed defect is a maintenance failure with a legal tail.
- Growing autonomy around people, with no one revisiting the original assessment.
- Aviation compliance assumed because the vendor "handles it", with nothing in writing.
