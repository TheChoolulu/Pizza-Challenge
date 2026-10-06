# Agent Christa: The Great Pizza Challenge — v7

V7 expands replayability and presentation.

- 40+ city-level pizza/flatbread cases across multiple continents
- Junior Agent location solving is fully multiple choice with complete City + State/Country answers
- Pizza identification remains multiple choice at every level, scaling from 2 to 6 choices
- Recent destinations are remembered locally and avoided on the next mission when possible
- New versioned Agent Christa artwork prevents old-image browser caching
- Redesigned vintage travel-dossier opening screen
- More realistic two-page end-of-mission passport with ID page, visa stamps, score, rank, date and Print/Save PDF
- Higher levels retain open-ended location deductions and Kids spelling support

Deploy all root files and the assets folder to GitHub Pages.


## v8
- Agent Christa's opening dialogue is now dynamic instead of repeating the same generic line.
- Dialogue combines destination-specific lines with pursuit-state reactions.
- Christa changes tone across Cold Trail, On Her Trail, Closing In, Hot Pursuit, and Visual Contact.
- Recently used Christa lines are suppressed to reduce immediate repetition.
- Arrival dialogue also reacts to the current pursuit state.
- Canonical Christa artwork is versioned as `agent-christa-v8.png` to avoid stale browser image caching.


## v9
- Rebuilt gameplay around the supplied tactile investigation-board design reference.
- Physical clue objects, translation interaction, evidence board selection, evidence-theory pursuit bonus.
- New investigations: Ask a Local, Translate Clue, Check Map, Inspect Photo, Research Landmark, Check Menu, and Adult Taproom intel.
- Dedicated deduction desk with Narrow the Region, Reveal Map Area, Show Possible Locations, and Another Pizza Clue. No neighborhoods.
- Junior Agent location deduction remains fully multiple choice using complete City + State/Country answers.
- Correct-location arrival is now an event with arrival stamp and live passport progress.
- Pizza investigation now exposes selectable crust/topping/preparation observations before the multiple-choice identification.
- Passport stamp progress is visible during the mission.
- Stronger dossier/tactile styling throughout gameplay.


## v10
- Global guard suppresses literal undefined/null in UI.
- Investigation sources are single-use per destination and visibly stamped USED.
- No investigation returns “no intel available”; exhausted pools return a useful synthesis.
- Adult Mode adds Taproom Intelligence with destination-specific and regional beer clues. Kids Mode has no alcohol content.
- Agent and harder pizza deductions hide giveaway pizza names and use crust/topping/preparation descriptions.
- Higher-level distractors are selected for clue similarity.
- One-use investigation state resets at every destination.
