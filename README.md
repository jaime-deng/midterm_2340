# midterm

## Section 1

Pulling pulls down from a remote and immediately merges the content onto the branch you are currently on. Pulling essentially runs a fetch command then a merge command by default. 

Pulling differs from fetch as fetch will not merge branches by default. 

Cloning differs from both pulling and fetching as it will clone a repository into a newly created directory. When using clone, a new remote origin is created for the repository that is cloned, sets up a local branch, and creates remote tracking for all the branches in the repository.

An example of git clone would be when a developer clones another developers repository, then makes changes, and finally passes it on as their own.

Git fetch would be used when working in a team and you create features which are not on the master branch, since a developer would most likely not be working on the master branch. Fetching here will pull the most up to date version of the master then move your work on to it.

Following the theme of working in a team, git pull would be used to retrieve and copy all the remote changes that other members in your team created. Doing this would keep the branch you are working on up to date.


## Section 2 

| Trello                    | Asana                        |
|------------------------------|---------------------------|
|Card-based management tool    | Task- orientated          |
|Limited availible features    | Broader feature arsenal   |
|Simple to use                 | More difficult to use     |
|Difficult to maintain workflow| Based to ease flow process|


## Section 3

1. The .git folder contains all the necessary information for your project such as information regarding commits and other similar information.
The object database is the objects folder within the .git folder. 

2. The git hash-object function takes in the content handed to it and returns a unique key that is stored inside of the git database. If the parameter "type" is not specified, it will automatically default to "blob".

3. When commiting, git stores the commits as an object. From there you can look at the objects which will give the name of the files. Tree objects are related to this since part of each commit is a tree object. This is where the paths for the files are stored. 