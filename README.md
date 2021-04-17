# Password-Protect-folder-windows10
*_Password Protect a Folder in Windows 10 Without Any Additional Software<br>_*

I will tell you a trick that will help you lock and hide any folder without installing any third-party software. With just a simple .bat file, you can protect your folders easily. Whenever you want to open the protected folder, a password will be required before the folder becomes visible and accessible. So, without further delay, follow the steps given below to password protect a folder :<br><br>


1. First of all, open the folder you want to secure with a password. You can see in the below animation that I’ve created a folder named “Demo,” which consists of an image and an HTML file.<br><br>
2. Now, create a new text file inside the same folder. You can name the text file according to your choice. I’m naming it “LockedFolder.txt.”<br><br>
3. [Click here](https://github.com/Brodevil/Password-Protect-folder-windows10/blob/main/FolderLock.bat), and you’ll be redirected to a My GitHub Repo file name FolderLock.bat. Copy the code given on the repo and paste it into the text file that you’ve created in the last step.<br><br>
4. Star this GitHub repository otherwise this will not work<br><br>
5. Now, open the text file and move your cursor to line number 21(if NOT %pass%== YOUR-PASSWORD goto FAIL). Replace YOUR-PASSWORD with the password of your choice. In the below animation, you can see that I’ve used “DemoPass” as my password.<br><br>
6. Now, click on the File option in the top left corner. Click on the Save as button and save the file as “LockedFolder.bat.”<br><br>
7. Now, double click on the “LockedFolder.bat,” and a folder named “Private” will be created automatically.<br><br>
8. Move all the files you want to hide inside the Private folder that we’ve just created in the last step.<br><br>
9. Again double click on the “LockedFolder.bat” A command prompt window will open asking you that “Are you sure you want to lock this folder?”. Type Y<br><br>
10. Once you hit enter, your Private folder will be automatically hidden, and only LockedFolder.bat will be visible to you.<br><br>
11. To open your secured folder, double click on the LockedFolder.bat file. A command prompt window will open asking you the password of the secured folder.<br><br>
12. Type the password and hit enter. Once you do that, your hidden folder will be displayed to you successfully.<br><br>
13. If you want to hide your Private folder again, all you need to do is double-click on the “LockedFolder.bat” file again.<br><br>
14. For Editional Security you can just hide the `LockedFloder.bat` File
<br><br><br>
## So that’s how you can easily hide your private files without using any additional software. Every Steps are important plz follow those and 5th Step is most important one
