Soham
=====

Collective Ideas of,

Soham Naik
Dr.George Alber Cook


Initial Setup
============
1. Set the directory you want to use using the commands cd and ls
      example: 
             HC-Lab-5:~ hcstudent$ ls
             Applications	Documents	Library		Music		Public
             Desktop		Downloads	Movies		Pictures	Sites
             HC-Lab-5:~ hcstudent$ cd Desktop
             HC-Lab-5:Desktop hcstudent$ ls
             DigisparkArduino.app	Student Files
             GitHub			heli
             HC-Lab-5:Desktop hcstudent$ cd GitHub
             HC-Lab-5:GitHub hcstudent$ ls
             RocksAndRobots	RocksNRobots	Soham
             HC-Lab-5:GitHub hcstudent$ cd Soham
             HC-Lab-5:Soham hcstudent$ ls
             Programs	README.md 

2. Create a copy of the repository on your computer using the command git clone and paste the url in 
      example:
            git clone 
There will now be a folder on your computer that is linked with the repository


Commands
========
cd                (Changes folders)
ls                (Lists folders in the folder you are currently in)
git status        (Checks status of your files compared to the cloud)
git add           (Adds new files to repository)
git commit -a -m  (Commits changes or additions to permanent record)  (-a selects all) (-m sets a message)
git push          (Updates cloud from your files)
git pull          (Updates your files from cloud)


Add New Files
============
1. Place the file in the folder you created earlier. You can check to see it is there by using the command git status it will be listed under untracked files

2. Use the command git add followed by the file name.

3. To commit the changes you the command git commit followed by the file name. By also adding -m and a note in quotations a message will be added to the commit.


4. Finally to upload your changes to the master repository (hosted on github) by using the command git push

Now if you check the GitHub your files should be added
```
More Help
=========
This youtube video has a very good example of how to use all the basic commands: https://www.youtube.com/watch?v=0fKg7e37bQE&list=WL&index=14
