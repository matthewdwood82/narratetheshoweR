# narratetheshoweR

“... really he can have chemistry with a pebble.” _-Phoebe Waller-Bridge, regarding working with Andrew Scott on "Fleabag"_

NFL pundits often refer to the role of chemistry in describing the coordinated performance and shared situational awareness of teammates on the football field. The goal of this project is to develop methods and analyses that allow for users to identify those NFL players who show great chemistry (1) with specific other players, and (2) tend to elevate the play of others in general. 

This package will use [snap count data](https://cloud.r-project.org/web/packages/nflreadr/vignettes/dictionary_snap_counts.html) or similar to provide functions that return such information as:
- pairs of players on active rosters by game week (both NFL and CFB)
- summary of number of games where the pair of players played on the field for the same team at the same time (NFL & CFB)
- boxscore statistics for the pair (e.g., how much target share for QB/WR combos, how much of total offense for WR/WR, ...) - FOCUS ON NFL FIRST
- plot on where the pair falls on a per-game basis in distribution(s) on those boxscore measures relative to other arbitrary pairs/games, and the NFL average

Thanks to the folks at Establish the Run, especially Evan Silva and Adam Levitan, whose comedic use of the "shower narrative" label that NFL and fantasy football fans use to reference this chemistry had inspired this work.

