Script does what the name implies. ReaEQ and ReaComp on the folder. Tracks are also set to have random colors.

Customization options (acording to claude.ai):

To change plugins on the folder track, modify these lines:
reaper.TrackFX_AddByName(folder_track, "Your Plugin Name", false, -1)

To add plugins to child tracks, uncomment and modify:
reaper.TrackFX_AddByName(child_track, "Your Plugin Name", false, -1)

To change the number of tracks, modify the loop:
for i = 1, 5 do  -- Change 5 to your desired number

Not in this version of the script, but I beat claude's skull in until it made the random colors match my specific color scheme using custom colors.
