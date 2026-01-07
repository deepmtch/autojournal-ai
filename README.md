# AutoJournal AI (Release Builds)

Welcome! This page is for end users who want to download and use AutoJournal AI on macOS.

## What AutoJournal AI does
AutoJournal AI tracks your active windows and apps, then shows simple analytics:
- Daily activity summary
- Top apps and windows
- Time estimates (approximate, based on sampling)
- CSV export
- Optional AI analysis (Pro)

All data is stored locally on your Mac.

## Download
Go to the latest GitHub Release in this repo and download the `.dmg` file.

## Install
1. Open the `.dmg`
2. Drag **AutoJournal AI** into **Applications**
3. Launch the app from Applications

## Required macOS permissions
AutoJournal AI needs these permissions to read window titles correctly:
- **Screen Recording**
- **Accessibility**
- **Automation** (allow AutoJournal AI to control **System Events**)

You can grant them in:
**System Settings → Privacy & Security**

After changing permissions, **quit and relaunch** the app.

## Updates
The app checks for updates on launch.
You can also use **Help → Check for Updates...** in the menu bar.

## Data and privacy
- Data is stored locally in your user profile
- No data is sent to external servers unless you enable AI analysis

## Pro features
Pro unlocks:
- AI analysis of usage data
- MCP Server integration

## Troubleshooting
If you see empty data:
- Make sure the app has permissions (Screen Recording + Accessibility)
- Make sure tracking is enabled in Settings
- Keep the app running; it samples every few seconds

If updates are not showing:
- You must be using the packaged app (not `npm start`)
- Check **Help → Check for Updates...**

## Support
If you need help, open a GitHub issue in the source repo or contact the author.
