# Folder Backup Automation — Microsoft Power Automate Desktop

## Project Overview

This is a personal automation project developed using Microsoft Power Automate Desktop.

The project demonstrates how a repetitive file-backup task can be automated using a simple, user-friendly desktop workflow.

**Technology:** Microsoft Power Automate Desktop, Windows File System

**Project Type:** Independent hands-on learning project

## Business Problem

Administrative staff often need to copy working folders into backup locations manually. This repetitive process can consume time and may be overlooked.

## Automation Solution

I developed a desktop automation that allows a user to select a folder and automatically creates a copy in a designated backup directory on the Windows Desktop.

### Workflow

1. **Get special folder:** Identifies the user's Desktop directory.
2. **Display select folder dialog:** Prompts the user to select the source folder.
3. **Create folder:** Creates a backup directory on the Desktop.
4. **Copy folder:** Copies the selected folder into the backup directory.

## Flow Screenshot

![Power Automate Desktop flow](screenshots/Flow-Design.png)

## Example Output

![Backup folder created](screenshots/Backup-Result.png)

## Testing

Successfully executed the desktop flow using a test folder and verified that its contents were copied to the backup location.

## How to Reproduce

1. Install Microsoft Power Automate Desktop.
2. Create a new desktop flow.
3. Open the `Folder-Backup-Flow.txt` file from this repository.
4. Copy its contents.
5. Paste the actions into the Main subflow in Power Automate Desktop.
6. Save and run the flow.
7. Select a sample folder and verify the copied contents in the Desktop backup directory.

Compatible Power Automate Desktop versions may be required.

## Skills Demonstrated

- Desktop workflow automation
- File and folder operations
- Working with variables and user input
- Basic workflow testing and validation
- Technical documentation
- Sharing a reproducible automation project

## Limitations and Future Improvements

This is a manually initiated desktop automation rather than a scheduled enterprise backup system.

Possible future enhancements include:

- Timestamped backup folders
- Error handling and execution logs
- Validation of source and destination folders
- Notifications of successful or failed backups

**Disclaimer:** This is an independent educational project using sample data. It is not a clinical system or a production hospital backup solution.
