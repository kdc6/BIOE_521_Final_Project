###Macro (MT_FocusStacking.ijm)
- Need to figure out how to change stack filepath/folder names/saved image names (bolded below) for subsequent stacks
- How to run ImageJ from the pi command terminal?

run("Image Sequence...", "open=C:\\Users\\Melody\\Desktop\\Stacks\\Stack001\\Image001.jpg sort use");
run("Stack Focuser ", "enter=20");
selectWindow("Focused_Stack001");
saveAs("Tiff", "C:\\Users\\Melody\\Desktop\\Stacks\\Focused\\Beautiful001.tif");

###Manual steps
- Select: File / Import / Image Sequence
- Navigate folders: Stacks / Stack001 / Image001
- For next stack, will be: Stacks / Stacks002 / Image001)
- Sequence Options window: check ‘Use virtual stack’ / click ‘Ok’
- Select: Plugins / Stacks / Stack Focuser
- Options window: enter ‘20’ for kernel / click ‘Ok’
- Select ‘Focused_Stack001’ image / File / Save As / Tiff
- Click up 1 folder level / click on ‘Focused’ folder / click ‘Save’ 
