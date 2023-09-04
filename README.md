# Metrodata Academy SIBKM DevSecOps Task 3: Versioning

## Objective

- Establish a team.
- Simulate the implementation of the following Git commands (each member's individual implementation):
	- `git help`
	- `git init`
	- `git add <filename>`
	- `git status`
	- `git commit`
	- `git config`
	- `git log`
- Simulate the following events with each team member as the player/code contributor:
	- Fast-Forward Merging 
	- Three-Way Merging 
	- Resolving a Merge Conflict

## Solution

### 1. The Team

Our team consists of three members:
1. Lareza Farhan Wanaghi (Reza)
2. Indra Wicaksono (Indra)
3. Lesti Oktasari (Lesti)

We utilize "Google Meet" as our online communication platform to accomplish the task.

![Screenshot 2023-09-04 at 12.26.27.png](_resources/Screenshot%202023-09-04%20at%2012.26.27.png)

### 2. Individual Code Implementations
**1. Reza**
1. Before Reza began his implementation, he refreshed his memory by using Git's `help` subcommand:

	![Screenshot 2023-09-03 at 15.09.43.png](_resources/Screenshot%202023-09-03%20at%2015.09.43.png)

2. Reza first created a folder and initialized a repository in that folder.

	![Screenshot 2023-09-03 at 15.01.45.png](_resources/Screenshot%202023-09-03%20at%2015.01.45.png)
	
3. Reza then created a file in the repository, added it to the staging area, and checked the status before committing the change:

	![Screenshot 2023-09-03 at 15.15.26.png](_resources/Screenshot%202023-09-03%20at%2015.15.26.png)

4. Reza then finally committed the change:

	![Screenshot 2023-09-03 at 15.21.20.png](_resources/Screenshot%202023-09-03%20at%2015.21.20.png)
	
5. Reza then checked the history of his commits.

	![Screenshot 2023-09-03 at 15.27.39.png](_resources/Screenshot%202023-09-03%20at%2015.27.39.png)

**2. Indra**
1. `git help`: Viewing Git documentation to see the available commands.

	![f44fa8d93ed992850ac3f913ee9db292.png](_resources/f44fa8d93ed992850ac3f913ee9db292.png)

2. `git init`: Initializing a repository in a new folder to start a project with the repository name "indra-repo."

	![fae960ae7e9ac6b886190a29f87edd5c.png](_resources/fae960ae7e9ac6b886190a29f87edd5c.png)

3. `git add .`: Adding files to the repository to include them in the staging area.

	![a41411b0b322e32d641ccc752c609efb.png](_resources/a41411b0b322e32d641ccc752c609efb.png)

4. `git status`: Checking the status to verify if the desired files are in the staging area.

	![4eebbae22b377db407459501ab2c9ec9.png](_resources/4eebbae22b377db407459501ab2c9ec9.png)

5. `git commit`: Committing the changes to record project progress in the history.

	![7ec67bcc457979ba3ab2bc54ec5d991d.png](_resources/7ec67bcc457979ba3ab2bc54ec5d991d.png)

6. `git log`: Viewing all the commit history with `git log`.

	![d33fc4e5119a30ffb0c8d70aa608c9eb.png](_resources/d33fc4e5119a30ffb0c8d70aa608c9eb.png)

7. `git remote`: Integrating the local Git repository with a GitHub repository.

	![23385824a91c236e3b9d6d96eec6cd5a.png](_resources/23385824a91c236e3b9d6d96eec6cd5a.png)

8. `git push`: Pushing local source code to the GitHub repository.

	![71554d8415cc8391b6f17a6a8d00517a.png](_resources/71554d8415cc8391b6f17a6a8d00517a.png)

**3. Lesti**
1. `git help`: Displaying the list of Git commands available.

	![ec7ccd5e8249673fac4b1cc2a141ed0a.png](_resources/ec7ccd5e8249673fac4b1cc2a141ed0a.png)
	
2. Creating a folder and initializing a repository using `git init` to begin a project with the repository named "lesti-repo."

	![b890bad82d02671a9bbb6e6a174d7824.png](_resources/b890bad82d02671a9bbb6e6a174d7824.png)

3. Using `git add` to stage files in the repository and checking the status with `git status` to ensure the desired files are in the staging area.

	![fdcc269acbf4867861642808b88b7f78.png](_resources/fdcc269acbf4867861642808b88b7f78.png)

4. Committing the changes with `git commit` to record project progress in the commit history and using `git log` to view all commit history.

	![08c92d7d420684ec8cdf39c4a9977b6f.png](_resources/08c92d7d420684ec8cdf39c4a9977b6f.png)

5. Integrating the local Git repository with a GitHub repository using `git remote`.

	![Screenshot 2023-09-04 at 11.56.30.png](_resources/Screenshot%202023-09-04%20at%2011.56.30.png)

6. Switching branches to the main branch and merging it with her branch using Git commands.

	![Screenshot 2023-09-04 at 12.02.38.png](_resources/Screenshot%202023-09-04%20at%2012.02.38.png)

### 3. Fast-Forward Merging Simulation

1. Reza first created a remote repository on GitHub and invited his team members to collaborate with the repository.

	![Screenshot 2023-09-03 at 15.39.03.png](_resources/Screenshot%202023-09-03%20at%2015.39.03.png)
	
	![Screenshot 2023-09-04 at 09.37.47.png](_resources/Screenshot%202023-09-04%20at%2009.37.47.png)

2. Reza then set up a repository and added the remote repository's address to the repository.

	![Screenshot 2023-09-03 at 17.42.44.png](_resources/Screenshot%202023-09-03%20at%2017.42.44.png)

3. Reza created a branch called "reza."

	![Screenshot 2023-09-03 at 17.41.58.png](_resources/Screenshot%202023-09-03%20at%2017.41.58.png)

4. Reza created a new file and pushed it to the repository.

	![Screenshot 2023-09-03 at 18.00.29.png](_resources/Screenshot%202023-09-03%20at%2018.00.29.png)

5. Reza then switched to the main branch, merged it with his branch, and pushed the merge.

	![Screenshot 2023-09-03 at 18.00.54.png](_resources/Screenshot%202023-09-03%20at%2018.00.54.png)

	![Screenshot 2023-09-03 at 18.10.56.png](_resources/Screenshot%202023-09-03%20at%2018.10.56.png)

6. Indra cloned the repository on his machine.

	![4b083a0d3544d42989da640d3e4498c8.png](_resources/4b083a0d3544d42989da640d3e4498c8.png)

7. Indra then created a branch.

	![ac0de9373c829a55ab33a3db06e82ac1.png](_resources/ac0de9373c829a55ab33a3db06e82ac1.png)

8. Indra created a new file and pushed it to the repository.

	![ebcb47b5cb332fdea06e933f58ad1056.png](_resources/ebcb47b5cb332fdea06e933f58ad1056.png)

	![3994c954af6c68c95b4c8d47b59ba38a.png](_resources/3994c954af6c68c95b4c8d47b59ba38a.png)

9. Indra then merged his branch into the main branch.

	![3b7bdefe69a49d3cefad46d09803ed7f.png](_resources/3b7bdefe69a49d3cefad46d09803ed7f.png)

10. Lesti cloned the repository on her machine, added a file, and pushed it.

	![9101524183177c6cf821e44b758b0bef.png](_resources/9101524183177c6cf821e44b758b0bef.png)

	![Screenshot 2023-09-04 at 11.56.30.png](_resources/Screenshot%202023-09-04%20at%2011.56.30.png)

11. She switched to the main branch and merged it with her branch.

	![Screenshot 2023-09-04 at 12.02.38.png](_resources/Screenshot%202023-09-04%20at%2012.02.38.png)

### 4. Three-Way Merging Simulation

1. Each member pushed a file containing their favorite number using their own branch.

	![Screenshot 2023-09-03 at 18.29.38.png](_resources/Screenshot%202023-09-03%20at%2018.29.38.png)

	![60367443529ed4efe79800f7a437db57.png](_resources/60367443529ed4efe79800f7a437db57.png)

	![Screenshot 2023-09-04 at 12.00.32.png](_resources/Screenshot%202023-09-04%20at%2012.00.32.png)

2. Now, each member wanted to fetch each other's branches.

	![Screenshot 2023-09-03 at 20.16.24.png](_resources/Screenshot%202023-09-03%20at%2020.16.24.png)

	![29764428e6c1b270c87ca35a7d3c74aa.png](_resources/29764428e6c1b270c87ca35a7d3c74aa.png)

	![Screenshot 2023-09-04 at 12.01.50.png](_resources/Screenshot%202023-09-04%20at%2012.01.50.png)

3. At this point, Reza wanted to merge Indra's branch into his branch.

	![Screenshot 2023-09-03 at 20.15.26.png](_resources/Screenshot%202023-09-03%20at%2020.15.26.png)

4. Similarly, Indra wanted to merge Lesti's branch into his branch.

	![3a79c7850188b8f2dabc661a9553f43c.png](_resources/3a79c7850188b8f2dabc661a9553f43c.png)

5. Meanwhile, Lesti wanted to merge her branch into Reza's branch.

	![Screenshot 2023-09-04 at 12.05.36.png](_resources/Screenshot%202023-09-04%20at%2012.05.36.png)

### 5. Conflict

1. Now, each member changed the `readme.md` file to include each member's name. Reza updated the file with the following content and pushed it:

	![Screenshot 2023-09-04 at 09.34.53.png](_resources/Screenshot%202023-09-04%20at%2009.34.53.png)

2. At the same time, Indra also updated the same file and pushed it.

	![a33fa37eb5f59647f517ad97482d418f.png](_resources/a33fa37eb5f59647f517ad97482d418f.png)

3. Meanwhile, Lesti also changed the `readme.md` file.

	![Screenshot 2023-09-04 at 12.09.23.png](_resources/Screenshot%202023-09-04%20at%2012.09.23.png)

	![Screenshot 2023-09-04 at 12.09.59.png](_resources/Screenshot%202023-09-04%20at%2012.09.59.png)

4. At this point, Lesti wanted to merge with Reza and encountered a conflict.

	![Screenshot 2023-09-04 at 12.10.42.png](_resources/Screenshot%202023-09-04%20at%2012.10.42.png)

	![Screenshot 2023-09-04 at 12.11.20.png](_resources/Screenshot%202023-09-04%20at%2012.11.20.png)

5. Similarly, Indra wanted to merge with Lesti and encountered a conflict.

	![ab5e677f5d28adb57c172dfeb81c505a.png](_resources/ab5e677f5d28adb57c172dfeb81c505a.png)

	![8af66de28a300a0bb2a55b1bc1971007.png](_resources/8af66de28a300a0bb2a55b1bc1971007.png)

6. At this point, Reza and Lesti updated their `readme.md` file again and pushed it.

	![7d4eddaf0f6af2e7690e42c4efb88160.png](_resources/7d4eddaf0f6af2e7690e42c4efb88160.png)

	![Screenshot 2023-09-04 at 09.32.37.png](_resources/Screenshot%202023-09-04%20at%2009.32.37.png)

7. Reza then wanted to merge with Lesti and encountered a conflict.

	![Screenshot 2023-09-04 at 09.32.53.png](_resources/Screenshot%202023-09-04%20at%2009.32.53.png)
