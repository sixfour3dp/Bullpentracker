Pocket Bullpen — Game Chart V1

Built from the current Pocket Bullpen direction as a standalone game-charting page.

Features:
- Pitcher, opponent, and opposing batter setup
- Add batters to a lineup
- Large BALL and STRIKE buttons
- Live count
- Total pitches
- Overall strike %
- Rolling Last 10 Strike % (shows — until 10 pitches)
- 3 strikes / 4 balls auto-advance to next batter
- Next Batter button for balls put in play
- Undo last pitch
- Change Pitcher keeps the same batter and count
- Strike % and Last 10 are calculated for the active pitcher only
- Every pitch is tagged to the pitcher who threw it
- Saves the active game in browser localStorage so leaving/reopening does not immediately lose it
- Export Backup downloads the entire current game as a JSON backup file
- Import Backup restores a previously exported game backup

Files:
- game-chart.html — complete working V1 game chart page

Integration into the main Pocket Bullpen index.html:
Add a "Chart Game" button in the Team section that opens game-chart.html.
For the quickest safe deployment, keep this feature in its own page first. It can be merged into the main single-file UI later.

Recommended Codex prompt:
"Use the current main branch as the source of truth. Add game-chart.html from this ZIP to the repo. In the Team section of index.html add a Chart Game button that opens game-chart.html. Match the existing Pocket Bullpen styling. Do not change unrelated functionality. Show me the diff before committing."
