# Nathan's Revision Tool

An open-source, auto-saving GCSE Higher Maths revision planner built around 106 linked 1st Class Maths topics. YES I KNOW IT CAN BE OPTIMIZED

## Features

- Change the target finish date from the home screen or Maths tracker
- Automatically redistribute unfinished topics across the days remaining
- Keep completed topics, confidence ratings, notes and scores when the plan changes
- Search all 106 topics and open the matching video
- Focus timer, weak-topic queue, mistakes, paper scores and backup/restore
- Calm one-topic-at-a-time sessions with a cleaner glass-and-card interface
- Move a topic to tomorrow without losing it, plus one-tap undo
- Automatic spaced reviews: red tomorrow, amber in 3 days and green in 14 days
- Revision streak, 14-day activity history and focused minutes
- Maths exam countdown with a target grade
- Installable phone/computer app with offline access to the main planner
- Friendly backup reminders that can be postponed
- Device-local auto-save using the stable `gcse-revision-dashboard-v2` storage key

## Use or download it

Open the published website in a modern browser. To use it offline, download
`Nathans_Revision_Tool.html` from the public repository. In a full source checkout,
the same file is also stored under `standalone/`. You can also use GitHub's
**Code -> Download ZIP** option.

## Update the dashboard

Edit `source/gcse-revision-dashboard.html`, run `npm run sync:dashboard`, then build and publish. The permanent website address stays the same and existing browser progress remains available.

## Licence

MIT. Video content remains the property of its creators; this project only links to external videos.
