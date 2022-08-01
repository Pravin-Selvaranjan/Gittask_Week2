# _**GIT INSTRUCTIONAL TUTORIAL**_

![Flowcharts (2)](https://user-images.githubusercontent.com/110179866/182137462-52b662d8-1976-4273-a137-51785226833e.jpeg)


## Creating a repo on Github

- Once you have logged into your Github go to repositories and select _New_
- From there fill in the relevant details as shown in the image below
  


![week2 task image 1](https://user-images.githubusercontent.com/110179866/182137500-08b3874c-9d57-481b-93db-bc971f3d2577.jpeg)



- You do not need to create a README.md file at this point if you do not want to
- Once you have created your repository you will be taken to the following page where the steps below will assist you
  


![week2 task image 2](https://user-images.githubusercontent.com/110179866/182137520-5763d085-2d9e-4797-828a-d1623cf3a934.jpeg)


- This tutorial will utilise the SSH protocol so ensure you have created a key using the following tutorial [SSH key tutorial](https://github.com/Pravin-Selvaranjan/Spartalearning/blob/main/Github%20setup%20using%20HTTPS%20and%20SSH.md)
- Open your terminal (Gitbash etc) as **_ADMIN_**
- Ensure you create a new directory/folder using the same name as your repo, in the case of the above example this would be "```mkdir test```"
- Once created ensure you change to the relevant directory "```cd test```"
- You may then use "```git init```" in order to initialise an empty repo in said folder
- using "```nano README.md```" you can create an md file
- then use "```git add .```" 
- You must then commit using "```git commit -m "whatever you wish to call it"```"
- You can then use "```git branch -M main```"
- You may then paste the remote add origin that is shown on the Github repo page, mine looks like this "``` git remote add origin git@github.com:Pravin-Selvaranjan/test.git```"
- If you receive an error to do with your public key follow the steps at [key agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- Finally you may use "```git push -u origin main```"

You should then be able to refresh your repo on Github and see that the md file you created locally is viewable.

## Essential Git commands for use with your terminal

- ```git init (initialise)``` - This command is used to start a new depository (be sure to only complete this task once you have created the correct folder on your localhost using mkdir)
- ```git add``` - This command adds a file to the relevant area (using an * or . adds all of the files available)
- ```git commit``` - This command records the file in the version history
- ```git push -u origin main``` - This command sends the committed changes of master branch to your depository
- ```git pull``` - This command fetches and merges changes on the server to your local directory

## Deleting a folder

Sometimes you may initialise a git folder in the wrong location ie allowing your entire machine contents to be uploaded. 
If you see (master) after your default command line - this is most likely the case.

- Delete the git folder by using rm - rf .git 
- Be sure to have created a folder using the exact name of the folder you made on Github!!
