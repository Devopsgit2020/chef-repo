<<<<<<< HEAD
# Overview

Every Chef Infra installation needs a Chef Repository. This is the place where cookbooks, policyfiles, config files and other artifacts for managing systems with Chef Infra will live. We strongly recommend storing this repository in a version control system such as Git and treating it like source code.

# Repository Directories

This repository contains several directories, and each directory contains a README file that describes what it is for in greater detail, and how to use it for managing your systems with Chef.

- `cookbooks/` - Cookbooks you download or create.
- `data_bags/` - Store data bags and items in .json in the repository.
- `roles/` - Store roles in .rb or .json in the repository.
- `environments/` - Store environments in .rb or .json in the repository.

# Configuration

The config file, `.chef/config.rb` is a repository-specific configuration file for the knife command line tool. If you're using the Hosted Chef platform, you can download one for your organization from the management console. You can also generate a new config.rb by running `knife configure`. For more information about configuring Knife, see the Knife documentation at https://docs.chef.io/knife.html

# Next Steps
=======
Deprecated
==========

Use of this repository is deprecated. We recommend using the `chef generate repo` command that comes with [ChefDK](http://downloads.chef.io/chef-dk/).

Overview
========

Every Chef installation needs a Chef Repository. This is the place where cookbooks, roles, config files and other artifacts for managing systems with Chef will live. We strongly recommend storing this repository in a version control system such as Git and treat it like source code.

While we prefer Git, and make this repository available via GitHub, you are welcome to download a tar or zip archive and use your favorite version control system to manage the code.

Repository Directories
======================

This repository contains several directories, and each directory contains a README file that describes what it is for in greater detail, and how to use it for managing your systems with Chef.

* `cookbooks/` - Cookbooks you download or create.
* `data_bags/` - Store data bags and items in .json in the repository.
* `roles/` - Store roles in .rb or .json in the repository.
* `environments/` - Store environments in .rb or .json in the repository.

Configuration
=============

The repository contains a knife configuration file.

* .chef/knife.rb

The knife configuration file `.chef/knife.rb` is a repository specific configuration file for knife. If you're using Hosted Chef, you can download one for your organization from the management console. If you're using the Open Source Chef Server, you can generate a new one with `knife configure`. For more information about configuring Knife, see the Knife documentation.

https://docs.chef.io/knife.html

Next Steps
==========
>>>>>>> 0d4d00990353fa0aeb9f356e8ca8d436ece4252f

Read the README file in each of the subdirectories for more information about what goes in those directories.
