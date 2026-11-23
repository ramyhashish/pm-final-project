# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** A three-year delivery driver who completes dozens of stops a day, often in bad weather with his hands full (UXR-01).
- **Goal , what this user is ultimately trying to achieve:** Confirm a delivery and receive route changes quickly, with minimal interaction with the app.
- **Friction / moment of misery , the specific pain blocking their goal:** Marking a stop delivered takes three taps across three screens (BUG-2055), so he texts his dispatcher instead.
- **Current workaround , the external tool or manual process they rely on (M2):** Text messages to the dispatcher (documented): Diego’s substitute for the in-app “Mark delivered” action.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** Complex and inefficient shipment coordination is consuming valuable internal resources while driving customers toward competitors offering faster, simpler digital experiences.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** The new value is to a chatter to group all the stakeholders with notifications and actions tracker to engage all the stockholders timely.

## Read your data snapshots
- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** _(not filled in)_
- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** _(not filled in)_
- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** _(not filled in)_
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** Drivers are in the app constantly, but the most frequent actions are buried and slow, so they work around them. That is supported. “Burdened by tools they don’t use” is a bigger claim than the data backs. The Compliance Checklist’s “high friction” note is worth following up, since it’s a heavily used driver feature. Coordinators use the Live Dispatch Board (91%) and Route Optimizer (85%) heavily, yet they still run coordination through WhatsApp and phone calls (UXR-02) because they can’t trust the board (UXR-09, BUG-2072). The tools are used but not relied on, and that is the misery the hook describes.
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** I would say "may be". If the compliance checks is a step before marking a stop delivered, this step has delay/gap of 11.6 minutes, and so this directly relates to the persona avoids the tool and use direct texting with the dispatcher. And the 23% drop-off percentage also support this match.
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** Drivers' rating to reporting 1.1 is the most cell directly maps to the persona friction. Considering that the reporting is somewhat related to the task of "marking the stop delivered".

One other option can be weak "compliance" rating by drivers, building on the assumption that the three screens include a compliance check.

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** 1- Route changes don't reflect spontaneously causing delays in updates and consequently delivery delays.
2- UX/UI makes users life harder rather than easier, a lot of enhancements are needed for quicker actions (marking delivered, start route)
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** 1- Avg daily time lost (manual workarounds)
2- Log Compliance Checks 11.6 minutes gap.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Role, who are you solving for? (the specific user segment or profile): A three-year delivery driver who completes dozens of stops a day, often in bad weather with his hands full (UXR-01).
Goal, what is this user ultimately trying to achieve?: Confirm a delivery and receive route changes quickly, with minimal interaction with the app.
Friction, the main barrier (moment of misery) stopping them from succeeding: Marking a stop delivered takes three taps across three screens (BUG-2055), so at a rainy doorstep with a package in hand he “just texts” his dispatcher instead, creating the off-platform coordination your hook describes.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Marking a stop delivered takes three taps across three screens (BUG-2055), so at a rainy doorstep with a package in hand, The driver texts his dispatcher instead, pushing status updates off-platform and into manual coordination.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Workflow drop-off rate decrease, i.e. higher application adoption.
Faster delivery times and daily dispatch workflow completion/lower drop-off in the daily dispatch workflow completion..
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Log Compliance Checks gap decrease.
Avg daily time lost (manual workarounds) decrease.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Live dispatch board feature adoption rate by drivers and coordinators.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** A week.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on lengthy "marking a delivered" feature leading to high average daily time lost -per delivery- in the manual workarounds. I believe solving this problem for Diego (the driver) will result in Faster delivery times and "lower drop-off in the daily dispatch workflow completion" measured by 30% change in Avg daily time lost (manual workarounds) and 20% less drop-off in the tasks workflow completion. I will protect the "Live dispatch board feature adoption rate by drivers and coordinators" and will make a go/no-go decision after a week.
