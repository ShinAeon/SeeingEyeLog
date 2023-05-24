# SeeingEyeLog
This product is intended as a disability aid for people with time blindness. People with time blindness can use the Seeing Eye Log to increase their awareness of the last time they performed a non-routine hygiene task, or spoke to specific friends and family, or saw the sun like, really saw the sun.

- [SeeingEyeLog](#seeingeyelog)
- [Requirements By Version](#requirements-by-version)
  - [Version 0.1](#version-01)
  - [Version 0.2](#version-02)
  - [Version 0.3](#version-03)
  - [Version 0.4](#version-04)
  - [Version 0.5](#version-05)
  - [Version 0.6](#version-06)
  - [Version 1.0](#version-10)
- [Software Design](#software-design)
  - [Features and requirements traceability](#features-and-requirements-traceability)
    - [Event interval tracking list](#event-interval-tracking-list)
      - [Description](#description)
      - [Requirements satisfied](#requirements-satisfied)
    - [Hamburger Menu](#hamburger-menu)
      - [Description](#description-1)
      - [Requirements satisfied](#requirements-satisfied-1)
    - [Help Menu](#help-menu)
      - [Description](#description-2)
      - [Requirements satisfied](#requirements-satisfied-2)
    - [Press-and-Hold menu](#press-and-hold-menu)
      - [Description](#description-3)
      - [Requirements satisfied](#requirements-satisfied-3)
    - [Undo state change](#undo-state-change)
      - [Description](#description-4)
      - [Requirements satisfied](#requirements-satisfied-4)
    - [Log entry recording](#log-entry-recording)
      - [Description](#description-5)
      - [Requirements satisfied](#requirements-satisfied-5)
    - [Log entry recording configurability](#log-entry-recording-configurability)
      - [Description](#description-6)
      - [Requirements satisfied](#requirements-satisfied-6)
    - [Log entry recording purgability](#log-entry-recording-purgability)
      - [Description](#description-7)
      - [Requirements satisfied](#requirements-satisfied-7)
    - [Table Viewing](#table-viewing)
      - [Description](#description-8)
      - [Requirements satisfied](#requirements-satisfied-8)
    - [Ordinal selection](#ordinal-selection)
      - [Description](#description-9)
      - [Requirements satisfied](#requirements-satisfied-9)
    - [Graph Viewing](#graph-viewing)
      - [Description](#description-10)
      - [Requirements satisfied](#requirements-satisfied-10)
    - [Sync Menu](#sync-menu)
      - [Description](#description-11)
      - [Requirements satisfied](#requirements-satisfied-11)
    - [Google sheets integration](#google-sheets-integration)
      - [Description](#description-12)
      - [Requirements satisfied](#requirements-satisfied-12)
    - [Apple cloud integration](#apple-cloud-integration)
      - [Description](#description-13)
      - [Requirements satisfied](#requirements-satisfied-13)
    - [Office 365 Excel OneDrive integration](#office-365-excel-onedrive-integration)
      - [Description](#description-14)
      - [Requirements satisfied](#requirements-satisfied-14)
    - [Issue reporting and tracking system](#issue-reporting-and-tracking-system)
      - [Description](#description-15)
      - [Requirements satisfied](#requirements-satisfied-15)
    - [Donation service integration](#donation-service-integration)
      - [Description](#description-16)
      - [Requirements satisfied](#requirements-satisfied-16)
  - [Implementation infrastructure](#implementation-infrastructure)
  - [Backend design considerations](#backend-design-considerations)
    - [Technologies under consideration](#technologies-under-consideration)
    - [Final decisions](#final-decisions)
  - [UI/UX Design](#uiux-design)
    - [Mockups by feature](#mockups-by-feature)
    - [Storyboards by feature](#storyboards-by-feature)
- [Help Menu Text by Version](#help-menu-text-by-version)
  - [Version 0.2](#version-02-1)
  - [Version 0.3](#version-03-1)
  - [Version 0.4](#version-04-1)
  - [Version 0.5](#version-05-1)
  - [Version 0.6](#version-06-1)
  - [Version 1.0](#version-10-1)

# Requirements By Version
## Version 0.1
1. Column of text fields the user may put words in
1. Corresponding column of buttons on which are written the last date and time that button was pressed in ISO8601 format

## Version 0.2
1. Add burger for menus 
1. Help menu

## Version 0.3
1. Press-and-hold menu for the date and time buttons
1. Undo Functionality (press-and-hold menu)

## Version 0.4
1. Record log entries locally
1. Disable logging on burger menu
1. Purge logs on burger menu
1. Table viewing (press-and-hold menu)

## Version 0.5
1. Configure button to allow ordinal selection (press-and-hold menu)
1. Create list of values in addition to date and time (press-and-hold menu)
  1. This value is displayed along with the date and time
1. Choose ordinal or between values that were added to that list (press-and-hold menu)
1. Graph viewing (press-and-hold menu)

## Version 0.6
1. Synch menu
1. Synch with a Google Sheet in the user’s Google Drive
1. Synch with whatever’s appropriate on the user’s Apple Cloud thing
1. Synch with an Office Online Excel Document on the user’s OneDrive, happenstance help you

## Version 1.0
1. Contact information for bug reporting
1. Donation button

# Software Design
## Features and requirements traceability
### Event interval tracking list
#### Description
#### Requirements satisfied
- [0.1.1](#version-01)
- [0.1.2](#version-01)

### Hamburger Menu
#### Description
#### Requirements satisfied
- [0.2.1](#version-02)

### Help Menu
#### Description
#### Requirements satisfied
- [0.2.2](#version-02)

### Press-and-Hold menu
#### Description
#### Requirements satisfied
- [0.3.1](#version-03)

### Undo state change
#### Description
#### Requirements satisfied
- [0.3.2](#version-03)

### Log entry recording
#### Description
#### Requirements satisfied
- [0.4.1](#version-04)

### Log entry recording configurability
#### Description
#### Requirements satisfied
- [0.4.2](#version-04)

### Log entry recording purgability
#### Description
#### Requirements satisfied
- [0.4.3](#version-04)

### Table Viewing
#### Description
#### Requirements satisfied
- [0.4.4](#version-04)

### Ordinal selection
#### Description
#### Requirements satisfied
- [0.5.1](#version-05)
- [0.5.2](#version-05)
- [0.5.3](#version-05)

### Graph Viewing
#### Description
#### Requirements satisfied
- [0.5.4](#version-05)

### Sync Menu
#### Description
#### Requirements satisfied
- [0.6.1](#version-06)

### Google sheets integration
#### Description
#### Requirements satisfied
- [0.6.2](#version-06)

### Apple cloud integration
#### Description
#### Requirements satisfied
- [0.6.3](#version-06)

### Office 365 Excel OneDrive integration
#### Description
#### Requirements satisfied
- [0.6.4](#version-06)

### Issue reporting and tracking system
#### Description
#### Requirements satisfied
- [1.0.1](#version-10)

### Donation service integration
#### Description
#### Requirements satisfied
- [1.0.2](#version-10)

## Implementation infrastructure
- Python 3.8 or newer (Because programming)
- Kivy (Because it's easy)
- KivyMD (Because it's pretty)

## Backend design considerations
### Technologies under consideration
- SQL Lite
- Pure JSON
- Encryption
- Push notifications

### Final decisions

## UI/UX Design
### Mockups by feature

### Storyboards by feature

# Help Menu Text by Version
## Version 0.2
- “This product is intended as a disability aid for people with time blindness. People with time blindness can use the Seeing Eye Log to increase their awareness of the last time they performed a non-routine hygiene task, or spoke to specific friends and family, or saw the sun like, really saw the sun.”

- “Write activities you perform or things that happen to you in the text fields on the left. Press the button on the right to update the date and time on that button to the last time you did that thing or the last time that thing happened.”

- “Like any disability aid, the Seeing Eye Log relies on us the users to make use of it. The Seeing Eye Log can only add value to our lives as we use it. We will need to form the habit of pulling out our hand-brains, opening the Seeing Eye Log, and clicking on the button when we do the activities or experience the events we want to track.”

## Version 0.3
- “Press and hold the button to access the menu for that button.”
- UNDO HELP TEXT

## Version 0.4
- “Seeing Eye Log keeps your logs on your phone. You can disable logging. You can purge existing logs.”

## Version 0.5
- ORDINAL CONFIGURATION HELP TEXT
- “Tables and graphs have been added to your press-and-hold button menu”

## Version 0.6
- “Use the Synch menu to connect Seeing Eye Log to your cloud storage account. Seeing Eye Log will create a file in your cloud storage thing, writing your existing log to that file, and update the file from this device as connectivity allows.”

## Version 1.0
- CONTACT INFORMATION FOR BUG REPORTING
- DONATION MESSAGE TEXT