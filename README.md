# Nathan's Revision Tool

An open-source, auto-saving GCSE Higher Maths revision planner built around 106 linked 1st Class Maths topics.

## Features

- Change the target finish date from the home screen or Maths tracker
- Automatically redistribute unfinished topics across the days remaining
- Keep completed topics, confidence ratings, notes and scores when the plan changes
- Tuesday tutor preparation and a full-paper day after the chosen finish date
- Search all 106 topics and open the matching video
- Focus timer, weak-topic queue, mistakes, paper scores and backup/restore
- Device-local auto-save using the stable `gcse-revision-dashboard-v2` storage key

## Use or download it

Open the published website in a modern browser. To download an offline copy, save `standalone/Nathans_Revision_Tool.html`, or use GitHub's **Code -> Download ZIP** option.

## Update the dashboard

Edit `source/gcse-revision-dashboard.html`, run `npm run sync:dashboard`, then build and publish. The permanent website address stays the same and existing browser progress remains available.

## Licence

MIT. Video content remains the property of its creators; this project only links to external videos.
