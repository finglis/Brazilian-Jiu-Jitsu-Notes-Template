Hopefully this page covers the logic behind the structure and function of these notes and can provide a little help so others can start using them.

** Little note, this derived knowledge from a blue belt brain. This information could be very wrong :) I am not responsible for any injuries related to trying out these moves (particularly those moves requiring some flexibility...) or migraines from obsidians graphing logic **
# Useful Keyboard Shortcuts
Crtl + o = find note (creates a new one if title doesn't exist)
Ctrl + p = run a command (eg run graph view)
Ctrl + t = apply template (requires setting change)
# View
Although a personal preference, I've found the following view to be useful:
![[Pasted image 20260201193644.png]]
The contents of the folders and all the notes can be found on the left. Select one and you will see the default note view (read on to improve). 

## Over-complicated Graph
Before we sort the note viewing bit, the graph viewing needs to be sorted (as it will overwrite the rest if done last). I find it useful to get an overview graph by opening the far right section by selecting this:
![[Pasted image 20260201194248.png]]
Select the map view to open a new tab by selecting the map icon in the top left corner:
![[Pasted image 20260201194516.png]]
You can then click and drag that tab into the toolbar in the top right pane so it looks like this: 
![[Pasted image 20260201194909.png]]
The big over complicated graph will show on the right. This can be hidden using 
![[Pasted image 20260201194248.png]] 
There is a bunch of settings that will improve the viewing experience which can be edited by selecting the cog and can be seen below:
![[Pasted image 20260201200450.png]]

The "Forces" can be toggled here but I cant say I've found actually useful setting, only made it worse.
## Actually Useful Notes
Try selecting a note within the "Position" folder if you haven't already from the very left of the screen and it will fill the main view. This tab can be pinned in place if you want to always have access to this note. Just right click on the tab and select "pin". 
![[Pasted image 20260201195926.png]]
But this is a personal preference, I'm not using it here and just have the note open.

To see the graph related directly to the note you are currently on (eg seeing all the options from full mount), right click on the tab and select the following near the bottom:
![[Pasted image 20260201193924.png]]

This will open a new tab that *should* split the main view in two. Whatever note you click on in the folders should be synced with the graph view. Please note this graph will show the direct options from the position. They can be expanded using the depth slider in settings below:
![[Pasted image 20260201201111.png]]
But I've found this to be too chaotic.. hence the development of my own plug in (still brewing).

To see the links coming and going from the note in a separate tab, you can select the "open outgoing links" and "open backlinks" from right clicking on the tab again:
![[Pasted image 20260201201241.png]]And then just drag and drop the new tabs where you want them. 
# Notes and Folders
There are 3 templates which match the 3 folders within the vault of notes. 
1. Position
2. Submission 
3. Transition
## Positions & Submissions
Assume all notes on positions are from the advantage position unless otherwise stated. For example "Mount" alone would be notes on the perspective from when you are in the top position and where you can go from there, submission or transition to another non-submission position.

## Linking
Only link forwards to positions or submissions and not backwards unless that path would be intentionally done when rolling. For example, the Full Guard note would link to the Triangle note, but the Triangle note wouldn't link back to the Full Guard note. To link, just type "[["
then the name of the next position/submission followed by "]]" which may of automagically already been added so selecting enter may just be required to wrap it up.

When linking to a position, I'm currently just noting the transition in an unlinked form if there is a known name to it (eg giggle sweep). This is because the overcomplicated graph got even more overcomplicated and I haven't figured out a fix for the flow yet.

We have "backlinks" which shows all the notes that link to the current one you are. Activate backlinks to be shown on each note via Settings (cog in lower left corner of screen):
![[Pasted image 20260201191954.png]]

# Tags
To create a tag, just type # followed by the tag you want to use. These are particularly useful in organizing your notes and displaying on the graph.
## Tags for Note status
I've been using these for marking the level I understand the technique (or if its any good). 
#New 
#Testing
#Confirmed
#Trash
These can be later filtered so you can see all the ones that perhaps need worked on (new) or ones that can be part of your arsenal (confirmed). Or ones you want to spam when your coach is watching (trash) :).
## Tags for groupings
Few examples of grouping I have found useful: 
1. Marking moves from specific series so that you can view them on their own (or exclude) in the graph later. Eg. #10pRubberGuard
2. Saving specific flows you want to view in the graph later. Eg. #GetTheGogo

# Settings probably worth setting
In the Obsidian settings (lower left cog), it may be useful to change the following...
## Files & links
![[Pasted image 20260201202908.png]]

##  Core Plugins
Make sure backlinks is turned on
![[Pasted image 20260201203024.png]]

## Community Plugins
This would be where I'd love for you to select the BJJ Graph Viewer if it was actually in a complete and sharable form... So in the meantime there are 2 other plugins that may provide some usability. 

Journey 
Will give you the shortest single path between two nodes in a list form

Path Finder 
This will give you the shortest path in list form, all of the paths in list form or ALL OF THE PATHS IN LIST FORM. If only it went one way.... it currently will include backlinks... eg. going from a locked up triangle to guard to then go back to another submission. 

Extended Graph
Seems to have useful features (like images on the nodes in the graph). I just haven't fully explored them yet. 