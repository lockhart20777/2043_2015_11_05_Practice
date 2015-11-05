Notes for starting git in 2043

Step 1, get an online github.com account.
Your user name for reference: jeremy.evert@swosu.edu

Step 2, Use a machine that has git installed.

Step 3, go to the command prompt and lets get started.

Big idea: Get to your folder.

use *dir* to find out what is in the directory.
```
C:\Users\LAB>dir
 Volume in drive C is OS
 Volume Serial Number is 864D-605F

 Directory of C:\Users\LAB

06/21/2012  01:13 PM    <DIR>          .
06/21/2012  01:13 PM    <DIR>          ..
05/14/2015  08:11 AM    <DIR>          Contacts
11/05/2015  08:12 AM    <DIR>          Desktop
05/14/2015  08:11 AM    <DIR>          Documents
05/14/2015  08:11 AM    <DIR>          Downloads
05/14/2015  08:11 AM    <DIR>          Favorites
05/14/2015  08:11 AM    <DIR>          Links
05/14/2015  08:11 AM    <DIR>          Music
05/14/2015  08:11 AM    <DIR>          Pictures
05/14/2015  08:11 AM    <DIR>          Saved Games
05/14/2015  08:11 AM    <DIR>          Searches
05/14/2015  08:11 AM    <DIR>          Videos
               0 File(s)              0 bytes
              13 Dir(s)  406,076,936,192 bytes free		  
```
Change directory to the Desktop using *cd* and your file name.
```
C:\Users\LAB>cd Desktop
```
Look in the directory for our file using *dir*
```
C:\Users\LAB\Desktop>dir
 Volume in drive C is OS
 Volume Serial Number is 864D-605F

 Directory of C:\Users\LAB\Desktop

11/05/2015  08:12 AM    <DIR>          .
11/05/2015  08:12 AM    <DIR>          ..
11/05/2015  08:13 AM    <DIR>          2043_git_Practice
06/21/2012  02:16 PM             1,553 Report Problems-ITS.lnk
               1 File(s)          1,553 bytes
               3 Dir(s)  406,076,936,192 bytes free
```
Change directories to our folder using *cd*
```
C:\Users\LAB\Desktop>cd 2043_git_Practice
```
And now we are ready to begin.
```
C:\Users\LAB\Desktop\2043_git_Practice>
```

Big idea 2: Set up your git folder.
1. Go to github.com
2. Sign in
3. Create a new repository 
(this is usually a big green button with a + mark)
4. Name the new repository
5. Provide a meaningful description in the repository.
This should try to answer 5 questions:
Who?
What?
Where?
When?
Why?

Step 6: Do not select the button
to initialize the folder with a readme file.

Step 7: Follow the instructions on Github.com for:
…or create a new repository on the command line
echo # 2043_2015_11_05_Practice >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/jeremy-evert/2043_2015_11_05_Practice.git
git push -u origin master

Now I will show those instructions and their results 
inside the command prompt.
I will copy and paste one line at a time
from github.com into my command prompt and then 
execute it.
After I have finished executing these lines, 
I will copy the command prompt over and comment it.

Hello, Singh did something.


