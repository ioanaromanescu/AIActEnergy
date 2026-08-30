# CARD 01 — Predictive maintenance on rotating equipment

*AI in Energy Operations: An EU AI Act Guide · [all cards](../README.md) · general information, not legal advice*

## What it is

Machine-learning models watch sensor data from pumps, compressors, and turbines, vibration, temperature, pressure, and predict failure before it happens. The most mature AI use case in the industry; the largest programs monitor over 10,000 pieces of equipment worldwide.

## AI Act status

**Minimal risk, with two boundaries to watch.** Predicting equipment failure is not a prohibited practice and does not appear in Annex III. But the classification changes if:

1. **The model becomes a safety component of regulated machinery** (Article 6(1) with Annex I). Advisory tools that flag a failing seal are one thing. A model that automatically trips equipment covered by EU product-safety legislation, such as the Machinery Regulation, can be high-risk once that legislation requires third-party conformity assessment. The compliance date for this category is August 2027.
2. **The equipment sits in critical infrastructure.** AI used as a safety component in the management of critical energy infrastructure, electricity, gas networks, is high-risk by name under Annex III point 2.

## If you deploy it

- Confirm which side of the advisory/control line the system sits on, in writing, with the vendor.
- AI literacy under Article 4 applies to every AI system, including this one: the people acting on the predictions need to understand what the model can and cannot tell them.
- If it crosses into high-risk territory: deployer duties under Article 26 apply, human oversight by trained staff, control over input data, monitoring, and keeping the automatically generated logs.

## GDPR overlay

Light, because the data is about machines. But watch the edges: control-room logs tied to operator IDs, and shift data linked to equipment events, can quietly turn a maintenance tool into an employee-monitoring tool. That changes the legal analysis entirely (see [Card 02](card-02-computer-vision-site-safety.md)).

## Red flags

- The vendor offers to "extend" the model to score operator behaviour.
- Autonomy creep: the tool that used to recommend now acts, and nobody re-ran the legal analysis.
- The contract is silent on who retrains the model after a false negative, and who pays for the downtime it caused.
- Alarm fatigue: so many predictions that operators stop reading them. Human oversight that nobody performs is not oversight.
