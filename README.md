# HW0
Home work assignment 0 for the Software Engineering Course 510.


> ## My name is Khantil Choksi. 
> ## My Unity ID is khchoksi.  
> ## My student id is 200200287.


**1. Complete moodle and slack profile:**
* Moodle Profile: ![img](/screenshots/MoodleProfile.png)  
* Slack Profile: ![img](/screenshots/SlackProfile.png)

**2. Completed Git Tutorial:**
![img](/screenshots/CompletedGitTutorial.png)  

For my reference I have also pushed the advance topic solutions.  
![AdvancedTopic1](/screenshots/AdvancedTopic1Solution.png)  
![AdvancedTopic2](/screenshots/AdvancedTopic2Solution.png)  
![AdvancedTopic3](/screenshots/AdvancedTopic3Solution.png)

**3. Hook Script:**  
`#!/bin/bash`  
`open https://android.com`

*I have done the following steps to implement the hookscript.*

* 1. git init .            // This will create a local repository in the present working directory.
* 2. nano ./.git/hooks/post-commit    //This will create a post-commit file in the hooks.
* 3. #!/bin/bash   //It’s written so that Unix/Linux shell knows what kind of interpreter to run the following commands, here it is Bourne Again Shell.  Then command open https://android.com
* 4. chmod u+x post-commit   //chmod is used to change the permission of the files like read, write and executable
* 5. Myfile.txt //To add something in the local repo so that we can commit and test our post-commit hook.
* 6. git add Myfile.txt //Add the file to local repo
* 7. git commit -m “New File” //Committing the changes to repo
* 8. This will open the link given in the post-commit executable file due to post-commit hook.


**4. Screencast:**

![My Screencast](/HooksScreencastCompressed.mov)
or   

[![ScreenCast](https://img.youtube.com/vi/kUO9cr0g3kE/0.jpg)](https://www.youtube.com/watch?v=kUO9cr0g3kE)



**Thank you for taking your valuable time and I hope that I had put my all efforts to understand the concepts of HW0.**

