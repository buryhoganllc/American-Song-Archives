# AV06 - Music Bar

Version Control / Change Log
---
Use semantic versioning (X.Y.Z):  
Given a version number MAJOR.MINOR.PATCH, increment the:
1. MAJOR version release with incompatible API changes
2. MINOR version releasing adding functionality in a backward compatible manner
3. PATCH version releasing backward compatible bug fixes

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format, e.g.. "2.6.0-alpha"

ALL Intuiface builds start at version 0.1.0  
Initial production release = 1.0.0

#### Interface Assets  
- Random Number
- HCMS

Layout: 1920 x 1080 LANDSCAPE

#### STYLE SHEET  
__Font(s):__  
- Arial Normal
- Arial Normal Bold
- Arial Italic
- Color: FFFFFF

__Other colors__  
- Orange: DA6F1A
- Light Gray: ADADAD
- Dark Gray: 404040

__Details window__  
- 5” width x 3.25” height  

__Music Bar header__   
- 2.75” off top, 3 ⅜” L/R, 2 ⅛” tall  

__Controls__   
- 2.25” off bottom

__Song Title__   
- ⅞” below Music Bar header

__L/R scroll__ 
- 9 ⅞” wide (w/o arrows) 3.5” up from bottom, ⅜” thick


#### HCMS Content

__Static Colors:__  
- Font Name
- Font Color
- Background Color

__Static Graphics:__

__Song Assets (Collection):__
- Song Title (plain text)
- Song Art (image)
- Song File (audio)
- Song Text (long text)

Background Helpers  
Audio Watcher (toggle)


##### AT LAUNCH:  
- Move Asset Flow to random index point
- Inactivity timer (90 seconds) begins
    - No activity - pick random index number and shuffle player
    - Restart timer

### UX:  
Visitor scrolls through Asset Flow collection to choose a song (set items to interactive)  
ON RELEASE - grow/restore selection to indicate choice
Set Audio Player to selection, PLAY  
Forward/Back "jump" arrows move scroll index +3/-3 from current index

Add "Now Playing" text field - show only when Audio Player is active?


---
## CHANGE LOG
