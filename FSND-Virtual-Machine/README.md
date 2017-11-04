# Chris Dunleavy - Tournament Database
----
This project uses Python and PostgreSQL to create and managae a database for running a Swiss-style non-elimination tournament. The project provdes functions to register players, report match outcomes, view player standings, and create Swiss pairings.

----
## Getting Started
### Prerequisites
1. Python 2.7 is required to run the blog. It can be downloaded here: https://www.python.org/download/releases/2.7/

2. VirtualBox is required to run the Virtual Machine (VM) which will be used for database purposes. It can be downloaded here: https://www.virtualbox.org/wiki/Downloads

3. Vagrant is used for syncing up files and directories between your machine and the VM. It can be downloaded here: https://www.vagrantup.com/downloads.html

4. Git Bash is the recommended command line interface for this project. Git Bash is included with Git, which can be downloaded here: https://git-scm.com/downloads



### Local Installation
1. Extract the contents of PROJECT.zip to a directory of your choice.
2. Navigate to that directory in Git Bash, and then navigate to the 'vagrant' directory within it.
3. Launch Vagrant by entering `vagrant up` into your console.
4. Log into the VM by entering `vagrant ssh` into your console.
5. Enter `cd /vagrant` into the console (include the '/').
6. Navigate to the 'tournament' directory.
7. Start psql with the command `psql` and then import the database file with `\i tournament.sql`
8. Launch the test file with the command ` python tournament_test.py`.

## Other Resources
Further documentation on PSQL can be found here: https://www.postgresql.org/docs/9.2/static/app-psql.html
