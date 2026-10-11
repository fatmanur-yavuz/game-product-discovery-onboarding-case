# Onboarding User Flow (Hypothetical Case)

This document visualizes the player journey and progression logic during the first-session experience.

---

## 1. User Progression Flow

* *[Step 1] Start Game:* Player opens the game and starts the first session.
* *[Step 2] Action Completed:* Player completes the first meaningful action/level.
* *[Step 3] UI Feedback:* Progress Indicator and "Next Goal" pop up on the main UI.
* *[Step 4] Decision Point (Progress Check):*
  * *If Progress Made:* Update Progress Bar -> Check Milestone.
  * *If Struggling / No Progress:* Trigger optional subtle hint -> Player retries.
* *[Step 5] Milestone Decision:*
  * *If Milestone Reached:* Display & Claim Reward -> Continue Gameplay.
  * *If Milestone Not Reached:* Return to Main Gameplay loop.

---
## 2. Key Considerations

* *Trigger Point:* The progress indicator appears only after the first meaningful action to prevent cognitive overload.
* *Friction Check:* Offer an optional, non-intrusive hint when a player appears to struggle, helping them continue without interrupting gameplay.
* *Goal:* Help new players understand their next goal and recognize early progress, while keeping first-session friction low.
