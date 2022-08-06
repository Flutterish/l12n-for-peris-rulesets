Localisation for all of my rulesets

There are 2 programs you will need to translate this project:
* Git (if you know how to use it) or Github Desktop
* [o!f-l12n (Localisation generator for osu!framework)](https://github.com/Flutterish/l12n-generator-for-osu-framework/releases)

First, fork and clone this repository.
Forking creates a copy independent of this repository that we will edit and later merge back into this repository. Cloning does the same, but to your machine rather than on github.

![image](https://user-images.githubusercontent.com/40297338/183265969-c6e45dd0-8709-411f-822c-1923351e511b.png)

![image](https://user-images.githubusercontent.com/40297338/183265674-b4a434e1-e9e9-4327-a27f-a4b691d85dfc.png)

Open the folder you cloned it to (Repository -> Show in Explorer) and find a file called `l12nConfig.json`.
There are different config files for each ruleset in a folder with their name (except rurusetto addon - its localisation is in its own project)

Run the [o!f-l12n](https://github.com/Flutterish/l12n-generator-for-osu-framework/releases) program 
and select [Select path] - choose the path to the folder containing the `l12nConfig.json` file

Everything else will already be set up for you by the developer, you can now simply add or edit a locale.

Before finishing run the [Summary] option to see if there are any issues with the locales you edited.

Add a commit message, click Commit and Push.
Commiting creates a list of changes you made, and pushing sends that to your fork on github.
You can view all the changes ever made to the repository in the `History` tab

![image](https://user-images.githubusercontent.com/40297338/183266057-b9faf5e6-8764-4c61-aec4-cfc8ed4fccb7.png)

![image](https://user-images.githubusercontent.com/40297338/183266334-7186b743-0377-4b7c-b9c3-0d0506cd798f.png)

Now you can create a pull request, so your changes can be merged into this repository.
A pull request is the same thing as pushing from one repository to another, but with authorization from
the owner of the latter. We need to do this because you're not the owner of this repository, or just to verify that everything is okay with the changes you made

![image](https://user-images.githubusercontent.com/40297338/183265928-e1cd84e0-9ac3-4ec9-b5d7-47786120c563.png)

If you want to contribute again after that, you might find that the fork of the repository
you made is outdated. To fix this, you will need to open the fork on github and click "Sync fork"

![image](https://user-images.githubusercontent.com/40297338/183266241-6c0321c4-65ef-42ca-8a2f-35a7bf63e34b.png)

Then, you will need to Fetch (if it hasn't happened automatically) and Pull.
Fetching is simply checking if there are any changes made to the main repository (your fork),
while pulling is downloading them

![image](https://user-images.githubusercontent.com/40297338/183266309-a0060528-4666-4dd5-a0dc-29e081d00899.png)

![image](https://user-images.githubusercontent.com/40297338/183266319-ed26dad5-2967-4ed8-966d-f0fd6093645b.png)