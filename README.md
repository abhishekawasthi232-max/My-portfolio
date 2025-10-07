# My-portfolio
My projects
 
Rapido Product Strategy: Reducing Ride Cancellation and Boosting Trust
Project Contributor: Abhishek Awasthi
Status: Strategy & Proposal (Ready for A/B Testing)

Project Overview
This product case study outlines a comprehensive feature proposal designed to address critical issues of trust and safety within the Rapido platform, primarily focusing on Captain (driver) driven ride cancellations. The core solution, branded as the Captain TrustScore & Smart-Cancel Shield, is engineered to realign the financial incentives of Captains with Rapido's platform policy compliance. By doing so, the feature aims to drastically improve service reliability and enhance the safety standards for all riders.

I. The Core Problem Statement
Rapido is currently facing a systemic failure in both service reliability and passenger safety, rooted in Captain behavior that prioritizes immediate personal gain over platform integrity. This issue manifests in two critical ways:

Safety and Commission Fraud: Captains frequently coerce riders into canceling booked trips post-pickup. This practice removes Rapido's commission and, more dangerously, bypasses essential safety features like real-time tracking and post-ride safety checks required for late-night commuters. This exposes riders, particularly women (as highlighted in Divya's story), to high-risk, untracked journeys.

Service Unreliability: The platform suffers from high rates of driver-initiated cancellation after rider wait-time. This typically occurs when a Captain secures a more lucrative ride, leaving the original rider stranded and forcing them into a disruptive re-booking cycle (as seen in Shivam's experience). The cumulative effect of these behaviors is a direct threat to Rapido's brand equity and customer retention.

 II. Solution and Core Hypothesis
Hypothesis
Our strategy hypothesizes that by creating a transparent, incentive-based mechanism—the Captain TrustScore—which rewards compliant behavior with commission discounts and priority matching, and simultaneously implementing a system-level financial barrier—the Smart-Cancel Shield—to penalize off-platform attempts, we will achieve a quantifiable reduction. Specifically, we aim to reduce post-pickup rider-initiated cancellations by 30% and Captain-initiated mid-wait cancellations by 15% within the first quarter.

Core Mechanism: The Dual-Action Solution
The solution uses a dual-action approach: Incentive Alignment and Fraud & Safety Barrier.

1. Captain TrustScore (CTS): This is designed for Incentive Alignment to address the issue of mid-wait abandonment (Shivam's Problem). It is a dynamic score based on ride completion rate, acceptance rate, and negative feedback. The primary Reward is that high-score Captains will receive priority matching to lucrative long rides (like airport trips) and also qualify for commission discounts.

2. Smart-Cancel Shield (SCS): This serves as a Fraud & Safety Barrier to combat commission fraud (Divya's Problem). The Logic dictates that if a rider cancels a GPS-anchored ride (i.e., after the Captain has arrived), a financial penalty is immediately deducted from the Captain's ledger, effectively eliminating the profit from the attempted fraud. Crucially, it includes a Safety Nudge—an in-app micro-survey that allows the rider to report coercion instantly, providing critical data for penalty enforcement.

 III. Key Logic and Implementation Changes
Protecting Genuine Cancellations
The system is designed with safeguards to protect Captains in genuine situations. A Dynamic Penalty Logic ensures a cancellation fee is deducted only if the pattern is highly suspicious (Driver Accepts → Driver Arrives → Wait Time > 1 min → Rider Cancels). The Genuine Protection mechanism waives or reduces the penalty if chat history or movement data indicates a legitimate, unavoidable issue (e.g., Captain reported a vehicle breakdown). Furthermore, as a safety measure, if a cancellation occurs at the pickup location, the Rider App initiates a Safety Re-Engagement prompt: "Safety Alert: Would you like to share the ride details with a trusted contact?"

Combating Mid-Wait Abandonment (Captain Incentives)
To influence Captain behavior, the Matching Algorithm uses the TrustScore as a multiplier, granting Prioritization Weight to high-scoring Captains for high-value trips. A Financial Nudge is built into the Driver App: when a Captain navigates to the 'Cancel' screen, a small pop-up warns: "Cancelling this ride will decrease your TrustScore by X, potentially costing you Y in priority earnings next week." This provides a final, transparent warning about the value of reliability before the Captain commits to cancellation.

 IV. Key Metrics and Validation Plan
The success of this feature set will be measured through a clear hierarchy of metrics focusing on both immediate and long-term impact.

Success Metrics (Lagging Indicators)
The primary goal for the Smart-Cancel Shield is to reduce the Post-Pickup Rider Cancel Rate by 30%. For the TrustScore incentive, the goal is to reduce the Captain-Initiated Mid-Wait Cancel Rate by 15%. The Overall Ride Completion Rate serves as the North Star metric, which is expected to increase (Absolute Value), validating the feature set's success in boosting reliability.

A/B Test Plan (MVP Focus)
The rollout is planned in two distinct phases to accurately isolate the impact of different levers:

Phase 1 (MVP Focus): Launch only the Smart-Cancel Shield penalty logic on a small, high-churn segment of riders to measure its specific effect on fraudulent commission elimination.

Phase 2 (Incentive Test): Roll out the Captain TrustScore and priority matching to a control group of Captains and measure its specific impact on the mid-wait cancellation rate.

 Project Details
Project Type: Product Feature Design, Incentives & Trust Strategy

Target Platform: Rapido Rider & Captain Mobile Applications

Skills Demonstrated: Problem Definition, Hypothesis Generation, Incentive Design, Metric Definition, A/B Testing Strategy.
