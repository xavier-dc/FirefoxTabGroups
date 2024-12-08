# Firefox Tab Groups

I created functionality for tab groups in Firefox Nightly.
This allows users to create tab groups using varying methods such as:
- Creating a master group from a specific tab
- Adding tabs to an existing tab group
- Open/closing all tabs related to said group



# Some notable features
## Tab group color
- Tab group color is auto-generated based on the logo of the tab. For example, if you create a tab group on a tab with Youtube, the tab group will be red and all tabs that are part of that group will also become red.

## Auto group similar tabs
- This option will automatically group all tabs that have the same host, for example if you have several tabs on Youtube and you select this option, all of your Youtube tabs will automatically be part of the same group

# Other notes
Tabs may not all be next to eachother, if you pull a tab away from the group, it can still be a part of that group while being elsewhere on your window. It will still open and close along with the group.

# TODO/Known bugs:
- There is no way to remove groups from the list of selectable groups once they are made. This is something I'm still fixing.
- Drag/dropping tabs for some reason is a nightmare. I haven't been able to reliably get this working and is extremely buggy. You can still try if you hold "Shift" on your keyboard while dragging a tab ontop of another but it may not work. 😥
- There is a new button on the far right of the tabs, between the dropdown carrot and the minimize button should be a "refresh" looking icon. This is actually a placeholder for the "Auto organize" button which when pressed will organize all of your tabs automatically via common hosts. However, this is currently bugged and not working properly since I added the option to create tabs by right-clicking on them. I am currently fixing this as well.
