This file is a summary of major git commands. 

## Set configuration options for the current user:

--global flag 

## Configuring author and email:

#### list all global configuration at user level

git config --global --list   

#### define the author name to be used for all commits by the current user

git config --global user.name <your name>

#### define the author email to be used for all commits by the current user

git config --global user.email <your email>

## Initializing an empty repository: 

mkdir {repo name}

cd {repo name}
   
## Notice the creation of .git directory and scratch or convert an existing unversioned code base to a git repository:            

git init   
                       
## "ls -al" command lists all objects, including hidden: 

ls -al  
      
## Edit a file without using any editor:                                                               

echo "this is my first file in empty repository" >> {file name.txt}     

cat {file name.txt}

## Create the file and enter some content:

vi  {file name.txt}                                        

cat {file name.txt}

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

git help <command>

#### read about a specific concept

git help <concept>

## Copy/Clone a GitHub repository:

cd <project_directory>

git clone https://github.com/<user>/<project name>

cd example_project

## Commiting changes:

#### create a file and add some content

vi {file name}                    

cat {file name}

#### to check the status of changed or added files

git status

#### adding or staging changes of a particular file

git add {file name}

#### adding or staging changes of all files

git add .

#### committing changes

git commit -m "<commit message>"



