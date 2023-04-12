## End to End ML Project
All the codes need to be pasted in the terminal section cmd in local machine so that eveything works properly.
### Created an Evnivronment 
```
create -p venv python==3.8
```
### Process of creating an environrment 
Open New Terminal and Then change it to command prompts then use this code
```
conda activate venv/
```

### Next Step - Install all Libraries 
create a requirements.txt file in the folder "House_Price_Prediction" 
and write the libraries that is necessary for the project..such as 
Numpy,Flask,Seaborn,Pandas,Matplotlib
```
pip install -r requirements.txt
```
### Creating a Setup.py file - Making a folder into pakages. 
Inside the setup.py we need to import some of the pakages. 

```
### What does -e. means in the Requirements.txt file which is used in setup.py file. 
```
numpy 
pandas 
flask 
seaborn
-e. 

-e. is used for triggering the setup.py file when we run the code. -e. is used for package building of the corresponding libraries. 

### How to run setup.py file without requirments.txt -e . ?
```
python setup.py install
```

### Life cycle of Machine Learning Project needs to be made in a Folder 
Suppose the name of the folder is 'src' inside the 'src' folder we need to build __init__.py file. 

## How to commit the code in to the Github - In Neuro Labh Bash is being used.
Remember in Neuron Lab we are using BASH not COMMAND PROMPTS. Command Prompts is used in local machine.  
```
ls -a
```
This command is used to see the git repository which is in default mode. This is used to check the path of git or origin 
```
git init
```
abc@31f67e965e5d:~/workspace$ git remote -v
origin  https://github.com/iNeuron-Pvt-Ltd/neurolab-flask (fetch)
origin  https://github.com/iNeuron-Pvt-Ltd/neurolab-flask (push)

As it can bee seen when ever i am opening the git remote -v it in inbuild fetch towards the iNeuron repository. 
For which we have to remove the github linked with ineuron and add out own repository for fetching the data. 

In order to remove the origin we need to write this code in the new terminal # Process of Removing 

```
git remote rm origin
```
Again after cheking it has shown blank as the git remote rm origin has removed the previous ineruon path. 

```
clear
```
This is used to clear the terminal. 

After claerning the termininal it is necessary to add the new git repository link.

```
git add . 
``` 
is used in the bash terminal to add the link. 

```
git status . 
```
This is used to find the current status of directory. 

```
git commit -m "first commit"
```

This is the output 
```
** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'abc@31f67e965e5d.(none)')
abc@31f67e965e5d:~/workspace$ 
```

In these phase we have to commit the changes with the templete which has beeen provided to me. 
```
git config --global user.email "joyjitd@gmail.com"
git config --global user.name "Joyjit Dhar"
```
The next two steps has been done to add the git repostition into the vscode. 
```
abc@31f67e965e5d:~/workspace$ git branch -M main
abc@31f67e965e5d:~/workspace$ git remote add origin git@github.com:joyjitd/FSDSRegerssion.git   
```
In order to check the git reposition as being the origin  we need to paste 
```
git remote rm origin
```
Now my git hub repositiry can been seen. 

In order to see the location where we want to push the repository
```
git remote -v
```








