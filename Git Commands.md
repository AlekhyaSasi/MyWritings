This file is a summary of major git commands. 

## Set configuration options for the current user:

--global flag 

## Configuring author and email:

#### list all global configuration at user level

git config --global --list   

#### define the author name to be used for all commits by the current user

git config --global user.name {your name}

#### define the author email to be used for all commits by the current user

git config --global user.email {your email}

## Initializing an empty repository: 

mkdir {repo name}

#### change path to the intialized repo 

cd {repo name}
   
## Notice the creation of .git directory and scratch or convert an existing unversioned code base to a git repository:            

git init   
                       
## "ls -al" command lists all objects, including hidden: 

ls -al  
      
## Edit a file without using any editor:                                                               

echo "this is my first file in empty repository" >> {file name.txt}  

#### view the file

cat {file name.txt}

## Create the file and enter some content:

vi  {file name.txt}                                        

## Existing unversioned project to repository

#### copy the downloaded file

cp {folder name.zip}

#### unzipping will create a folder called "initilizr"     

unzip {folder name.zip}                                      

ls -al

#### remove copied file

rm {folder name.zip} 

#### rename directory                                          

mv initializr/ {directory name}    
              
#### now we need to add source control to the unversioned repo

cd {directory name}   
         
#### initializing existing source                        

git init            
  
## Accessing Git Help system: 

#### general help

git help

#### lists sub-commands

git help -a

#### lists concept guides

git help -g

#### read about a specific sub-command

git help {command}

#### read about a specific concept

git help {concept}

## Copy/Clone a GitHub repository:

cd {project_directory}

git clone https://github.com/{user name}/{project name}

cd {project name}

## Commiting changes:

#### create a file and add some content

vi {file name}                    

#### to check the status of changed or added files 

git status 

#### to check the status with short messages 

git status -s 

?? - status for untracked files 

A - added files 

M - modified files 

D - deleted files 

#### adding or staging changes of a particular file

git add {file name}

#### adding or staging changes of all files

git add .

#### committing changes

git commit -m "{commit message}"

## Check Commit history: 

#### displays the entire commit history using the default formatting

git log     

#### oneline condensed view of each commit history                      

git log --oneline

#### only display commits that include the specified file                             

git log {file}
   
#### show only commits that occur between {since} and {until}. 
   
both arguments can be either a commit ID, branch, name, HEAD, or any other kind of revision reference.                    

git log {since}..{until}                     

#### limit the number of commits by {limit}. 
   
git log -n {limit}                      
   
For example, git log -n 3 will display only 3 commits.  
