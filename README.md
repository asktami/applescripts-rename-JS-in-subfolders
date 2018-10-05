# applescripts-rename-JS-in-subfolders
Applescripts to Rename JS in SubFolders Up to 2 Levels Deep for Import into Quiver

Created this combination of Applescripts and Automator workflows to rename Javascript files created with Visual Studio Code as .txt files so I could import them into the [Quiver](http://happenapps.com/) notetaking app.


These scripts assume you have a folder, let's call it **_'Test-First-Part-2'_** that has inside it Javascript files and other folders that contain Javascript files, and some of those folders also have folders that contain Javascript files.

First put your **_'Test-First-Part-2'_** folder inside a **_'FilesToImport'_** folder. 

Then manually run these scripts against that **_'FilesToImport'_** folder, one at a time.

(Folder names are optional and for example purposes only.)

The scripts:
![1](https://github.com/asktami/applescripts-rename-JS-in-subfolders/blob/master/Screenshots/0.%20Applescripts.png "1")

Inside the **_'FilesToImport'_** before running the scripts:
![2](https://github.com/asktami/applescripts-rename-JS-in-subfolders/blob/master/Screenshots/1.%20Before%20Scripts.png "2")

Inside the **_'FilesToImport'_** after running the scripts:
![3](https://github.com/asktami/applescripts-rename-JS-in-subfolders/blob/master/Screenshots/2.%20After%20Scripts.png "3")

Files in Quiver after manually importing and changing each cell to a code cell; each file = 1 note with 1 cell:
![4](https://github.com/asktami/applescripts-rename-JS-in-subfolders/blob/master/Screenshots/3.%20Inside%20Quiver.png "4")
