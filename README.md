# boatdock
A simple Bash script to take all the folders in the home directory that have docker-compose in them, and copy them to back them up into a Github repository.
If no local git repo exists (or docker-backups doesn't exist) it will make a new directory, initiate a new local Git repository, and ask the user for a Git server URI.

## How to use
1. Setup a Github (or any sort of Git server) repository.
2. Clone the repository
3. Go into the directory, and do the following command to allow executable permissions `chmod +x boatdock`
4. Run the command `./boatdock`
5. When prompted, enter the Git link from the remote repository you made.

## Prerequisites
git
bash
