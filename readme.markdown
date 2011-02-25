What
===

This is a simple tool to help you out when creating repos in Beanstalk that follow a set template.

This isn't a general command line tool, to access all of the features of Beanstalk.

How
===

`$ beanstalk create test_repo green`

Installation
=======

Download the file and make it executable

`chmod a+x beanstalk`

Either place it in your path, or add to your path.

`PATH=/Users/user_name/bin:$PATH`

Add a beanstalk_cli.config to your home directory containing: \n

[account_settings]
account = 
username = 
password =

Type `beanstalk help` check your settings

Methods
=====


create - will create an SVN repo and add the staging and production release servers (update the script with your details for this to work)

list - return a list of repos

create-empty - will create an SVN repo without any release servers

create-git - will create an empty GIT repo

changes - will list the most recent changes, grouped by date then ordered by time, with the revision and author

releases - will list the most recent releases, grouped by date then ordered by time, with the revision and author

repo - will show info, and server environments for a repo

Thanks
=====

Thanks to https://github.com/AzizLight/fire for inspiration (and code) to create the script!