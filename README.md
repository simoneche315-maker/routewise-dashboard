RouteWise Dashboard

CS399 Innovating with AI, Bentley University, Fall 2026. Group 6.
A prototype for handling delivery problems at RouteWise Distribution.

index.html is version 4. Drivers tap a button to report a problem. The urgency score uses hard facts
(deadline, GPS delay, key account, the button tapped, waiting time) plus at most 20 points from the
driver's note, read by the open model LiquidAI/LFM2.5-2.6B from Hugging Face.

The AI runs on the team laptop with server.py, because no Hugging Face host serves this model and this
free static site has no server. Here the list uses rule points, and notes we scored on the laptop
(notes-cache.json) still show their AI points.

v2/index.html is version 2 with the person switcher. v1/index.html is the first version.

This is a static site. Nothing to build. Render serves the files as they are.
