These scripts part of making a custom action to setup lots of regions for multilayered SFX very quickly.
Make a custom action in this order

1. Script: FolderItems.lua
2. Item: Select all items in track
3. Script: DeselectChildrenFolderItems.lua
4. Markers: Insert separate regions for each selected item

I ran into trouble when attempting to disable folder tracks as a part of the custom action. But there is no issue if you manually turn them off after. I personally wouldn't advise working with that script on 100% of the time. Not super reliable. But for this purpose, it works great.
