#  Contributing Guideline

### Follow these steps to make your first pull request:

## Step-1 : Forking
First **Fork** this repository in your github account. 

<img width="450" src="howto/fork.png" alt="fork this repository" align="center"/>

## Step-2 : Cloning
Now you need to clone your forked repository to your local machine. <br>
Head back to your **GitHub account**, open the forked repository, click on the *clone* button, click **clone with HTTPS** and then click the *copy to clipboard* icon.

<br>
<img width="450" src="howto/clone.png" alt="clone this repository" /> <br>

<img width="450" src="howto/copy-to-clipboard.png" alt="copy URL to clipboard"/>

Open **Git Bash** (or some other terminal) and type the following git command:

```
git clone "URL"
```
Replace *URL* with the copied link.It should look like the following -
```
git clone "https://github.com/JU-Computer-Club/JU-ForkMe.git"
```
You will see a new folder named *JU-ForkMe* has been downloaded to your machine on the **directory** that *Git Bash* is on.

## Step-3 : Local Changes
From your machine, your need to edit the necessary changes to some files. <br>

First, goto **Images** folder and place your portrait image titled "Your-Name.png" or "Your-Name.jpg" (replace Your-name with your fullname without space).
<br><br>Secondly, goto **Contributors** folder and create a file named "Your-Name.md" (replace Your-name with your fullname without space).
<br> Copy the contents of the file *example.md*, paste it to your newly created file. 
<br> Make sure that the first line looks like the following (replace *Your-name.jpg* with your image file name with proper extension) 
```
<img src="../Images/Your-name.jpg" alt="your full name" width="200"/> <br>
```
Then make other changes according to your own information and save the file.
<br><br>Finally, head back and open *README.md* and change the following table by adding a row of your own on the bottom of the table. Save it when your row looks like the following. (Of course replace Your-name.md with your one) -

```
| **NAME**           | **PROFILE**                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------|
| JU Computer Club | [Click me](Contributors/example.md) |
| Meraj al Maksud | [Click me](Contributors/example2.md) |
| Your-Name | [Click me](Contributors/Your-name.md) |
```
Great! Now you have finished all the edits. <br>
Recheck all the steps twice to make sure that everything is okay. <br>

## Step-4 : Push To Github
Next you need to push your local repository to your github repository. Write these commands on your terminal:

    ```
    git add -A
    git commit -m "your name"
    git push origin master
    git status
    ```
## Step-5 : Verification
Go back to your **Github forked Repository** and check if you see your new files.<br>
If everything goes right, you will see your name on *Contributors* list on the *README* file and clicking on *Click Me* will open up your own **profile card**! <br>
Check your profile image if it shows up correctly.If not, look into *Your-Name.md* code and cross check it with your *Your-name.jpg* image on the *Images* folder. 

## Step-6 : Create PR

Now you are ready to create your first pull request! <br>
Click on **Create Pull Request**.

<img style="float: right;" src="howto/compare.png" alt="create a pull request" />

Make sure to double check everything.
<br>See if your github repository is on the the *head-repository* and it is pointing to the base repository (which is *JU-Computer-Club/JU-ForkMe*).
<br> Replace the pull request **title** with "Your-Name" and in the **description**, you may write anything you want.(optional) 
Click on **Create Pull Request**
<img style="float: right;" src="howto/pull-request.png" alt="submit pull request" />

### Congratulations! Your pull request has been successfully created!

## Step-7 : Ping & Connect
Star this repository! :star: <br>
Email us at info@jucomputerclub.org to and wait patiently till we review changes! <br>
You will be notified if your pull request needs any revision or else it will be merged and you will find your **profile card** displayed here.

Till then, you can follow our socials mentioned at the [Credits section](https://github.com/JU-Computer-Club/JU-ForkMe#credits) 

