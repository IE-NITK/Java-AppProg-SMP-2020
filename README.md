# IE Java AppProg SMP 2020
A repository of task submissions by the mentees who are a part of the 'IE Application Programming Using Java and MySQL' SMP in the year 2020.

### Steps to be followed during the submission of tasks:

1. Click the Fork button (top right corner) and then click on your username in the box which opens up. This creates a copy of this repository (called a fork) in your account. You'll get redirected to this copy.

2. Click the 'Clone or download' button (green button on the right). Copy the URL which appears in the box which opens up.

3. Now, open Command Prompt. Enter the following command to enter Documents:
```
cd Documents
```
4. Now, enter this command to create a local version of your fork:
```
git clone paste-link-here
```
Paste the link you'd copied in step 2 in the place shown above.

5. Enter the following command to enter the local fork copy you've just created:
```
cd Java-AppProg-SMP-2020
```
6. Enter the following command to specify the original repository (the one which you forked at the beginning) as the upstream repository i.e. you'll use this upstream repository to keep your fork up-to-date.
```
git remote add upstream https://github.com/IE-NITK/Java-AppProg-SMP-2020.git
```
7. Make your local fork in sync with the original repository by entering these commands:
```
git fetch upstream
git checkout master
git merge upstream/master
```
8. Next, enter the Task-n directory, create a folder with your name, and enter that folder with these commands:
```
cd Task-n
mkdir Name_Surname
cd Name_Surname
```
9. Using the File Explorer, copy the file(s)/folder(s) you've created for Task-n (e.g. ABC Car Rentals or task2.txt) and paste inside the above Name_Surname folder.

10.  Commit the changes to you've made in your local fork by using the following commands:
```
git add .
git commit -m "Add files for task n"
```
11. Make your local fork in sync with the original repository by entering the commands in step 7.

12. Push the changes you've made to your online forked repository by entering this command:
```
git push origin master
```
13. Go to your online fork on GitHub. You'll be able to see the changes you've made. Now, if you feel like making some more changes to the files you're submitting for Task n, repeat steps 9 to 11. Otherwise, if you're ready to submit the files, click the 'Pull request' button (right under the big green 'Clone or download' button).

14. On the page which opens next, click the big green 'Create pull request' button. Enter a different title if you don't like the one already present, and click the big green 'Create pull request' button.

15. For further task submissions, repeat steps 3, 5 and 7 to 14.

#### Mentors
```
Manas Trivedi (181CO231)  
Omanshu Mahawar (181CO237)  
Sasidhar Swarangi (181CO245)
```

#### Super Mentors
```
Shrinidhi Anil Varna (171CO145)  
Shreyansh Shrivastava (171CO244)
