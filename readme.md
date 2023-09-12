## Metrodata Academy SIBKM DevSecOps Task 3: Versioning

- Establish a team.
- Simulate the implementation of the following Git commands on each team member's machine (include screenshots):
	- `git help`
	- `git init`
	- `git add`
	- `git status`
	- `git commit`
	- `git config`
	- `git log`
- Simulate the following events with each team  member as the player/code contributor (include screenshots):
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

<img src="_resources/Screenshot%202023-09-04%20at%2012.26.27.png" width="75%"/>

### 2. Individual Code Implementations
1. Each team member initiated the implementation process by executing the `git help` command in the following order: Reza, Indra, and Lesti.

	<img src="_resources/Screenshot%202023-09-03%20at%2015.09.43.png" width="75%"/>

	<img src="_resources/f44fa8d93ed992850ac3f913ee9db292.png" width="75%"/>

	<img src="_resources/ec7ccd5e8249673fac4b1cc2a141ed0a.png" width="75%"/>

2. Subsequently, they created a folder and initialized a Git repository within that folder using the `git init` command.

	<img src="_resources/Screenshot%202023-09-03%20at%2015.01.45.png" width="75%"/>

	<img src="_resources/fae960ae7e9ac6b886190a29f87edd5c.png" width="75%"/>
	
	<img src="_resources/b890bad82d02671a9bbb6e6a174d7824.png" width="75%"/>

3. Next, they created a file within the repository, added it to the staging area using the `git add` command, and checked its status before committing the changes using the `git status` command.

	<img src="_resources/Screenshot%202023-09-03%20at%2015.15.26.png" width="75%"/>

	<img src="_resources/a41411b0b322e32d641ccc752c609efb.png" width="75%"/>

	<img src="_resources/4eebbae22b377db407459501ab2c9ec9.png" width="75%"/>

	<img src="_resources/fdcc269acbf4867861642808b88b7f78.png" width="75%"/>

4. By using the `git commit` command, they finally proceeded to commit the changes.

	<img src="_resources/Screenshot%202023-09-03%20at%2015.21.20.png" width="75%"/>

	<img src="_resources/7ec67bcc457979ba3ab2bc54ec5d991d.png" width="75%"/>

	<img src="_resources/08c92d7d420684ec8cdf39c4a9977b6f.png" width="75%"/>
	
5. Following the commits, they reviewed the commit history using the `git log` command.

	<img src="_resources/Screenshot%202023-09-03%20at%2015.27.39.png" width="75%"/>

	<img src="_resources/d33fc4e5119a30ffb0c8d70aa608c9eb.png" width="75%"/>

	<img src="_resources/Screenshot 2023-09-04 at 17.04.35.png" width="75%"/>

	


### 3. Fast-Forward Merging Simulation

1. Reza first created a remote repository on GitHub and invited his team members to collaborate with the repository.

	<img src="_resources/Screenshot%202023-09-03%20at%2015.39.03.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2009.37.47.png" width="75%"/>

2. Reza then set up a repository and added the remote repository's address to the repository.

	<img src="_resources/Screenshot%202023-09-03%20at%2017.42.44.png" width="75%"/>

3. Reza created a branch called "reza," put a new file into the branch, and then pushed the branch to the remote repository.

	<img src="_resources/Screenshot%202023-09-03%20at%2017.41.58.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-03%20at%2018.00.29.png" width="75%"/>

4. Reza then switched to the main branch, merged it with his branch, and pushed the merge.

	<img src="_resources/Screenshot%202023-09-03%20at%2018.00.54.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-03%20at%2018.10.56.png" width="75%"/>

5. Indra cloned the repository on his machine. He then created a branch called "indra", put a new file into the branch, and pushed the branch to the remote repository.

	<img src="_resources/4b083a0d3544d42989da640d3e4498c8.png" width="75%"/>

	<img src="_resources/ac0de9373c829a55ab33a3db06e82ac1.png" width="75%"/>

	<img src="_resources/ebcb47b5cb332fdea06e933f58ad1056.png" width="75%"/>

	<img src="_resources/3994c954af6c68c95b4c8d47b59ba38a.png" width="75%"/>

6. Indra then merged his branch into the main branch.

	<img src="_resources/3b7bdefe69a49d3cefad46d09803ed7f.png" width="75%"/>

7. Lesti cloned the repository on her machine. She then added a new branch, put a file into it, and then pushed it.

	<img src="_resources/9101524183177c6cf821e44b758b0bef.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2011.56.30.png" width="75%"/>

8. She then switched to the main branch and merged it with her branch.

	<img src="_resources/Screenshot%202023-09-04%20at%2012.02.38.png" width="75%"/>

### 4. Three-Way Merging Simulation

1. Each member pushed a file containing their favorite number using their own branch.

	<img src="_resources/Screenshot%202023-09-03%20at%2018.29.38.png" width="75%"/>

	<img src="_resources/60367443529ed4efe79800f7a437db57.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2012.00.32.png" width="75%"/>

2. Now, each member wanted to fetch each other's branches.

	<img src="_resources/Screenshot%202023-09-03%20at%2020.16.24.png" width="75%"/>

	<img src="_resources/29764428e6c1b270c87ca35a7d3c74aa.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2012.01.50.png" width="75%"/>

3. At this point, Reza wanted to merge Indra's branch into his branch.

	<img src="_resources/Screenshot%202023-09-03%20at%2020.15.26.png" width="75%"/>

4. Similarly, Indra wanted to merge Lesti's branch into his branch.

	<img src="_resources/3a79c7850188b8f2dabc661a9553f43c.png" width="75%"/>

5. Meanwhile, Lesti wanted to merge her branch into Reza's branch.

	<img src="_resources/Screenshot%202023-09-04%20at%2012.05.36.png" width="75%"/>

### 5. Conflict

1. Now, each member changed the `readme.md` file to include each member's name. Reza updated the file with the following content and pushed it:

	<img src="_resources/Screenshot%202023-09-04%20at%2009.34.53.png" width="75%"/>

2. At the same time, Indra also updated the same file and pushed it.

	<img src="_resources/a33fa37eb5f59647f517ad97482d418f.png" width="75%"/>

3. Meanwhile, Lesti also changed the `readme.md` file.
	
	<img src="_resources/Screenshot%202023-09-04%20at%2012.09.23.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2012.09.59.png" width="75%"/>

4. At this point, Lesti wanted to merge with Reza and encountered a conflict.

	<img src="_resources/Screenshot%202023-09-04%20at%2012.10.42.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2012.11.20.png" width="75%"/>

5. Similarly, Indra wanted to merge with Lesti and encountered a conflict.

	<img src="_resources/ab5e677f5d28adb57c172dfeb81c505a.png" width="75%"/>

	<img src="_resources/8af66de28a300a0bb2a55b1bc1971007.png" width="75%"/>

6. At this point, Reza and Lesti updated their `readme.md` file again and pushed it.

	<img src="_resources/7d4eddaf0f6af2e7690e42c4efb88160.png" width="75%"/>

	<img src="_resources/Screenshot%202023-09-04%20at%2009.32.37.png" width="75%"/>

7. Reza then wanted to merge with Lesti and encountered a conflict.

	<img src="_resources/Screenshot%202023-09-04%20at%2009.32.53.png" width="75%"/>